<h1 align="center">angular-mydatepicker</h1>

<h2 align="center">Angular datepicker and date range picker</h2>

<p align="center">
  <a href="https://github.com/sundar-pk/angular-mydatepicker">
         https://github.com/sundar-pk/angular-mydatepicker 
  </a>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@sundar-pk/angular-mydatepicker">
    <img src="https://img.shields.io/npm/v/@sundar-pk/angular-mydatepicker?logo=npm&logoColor=green&style=for-the-badge" alt="NPM Package" />
  </a>&nbsp;

  <a href="https://www.npmjs.com/package/@sundar-pk/angular-mydatepicker">
    <img src="https://img.shields.io/npm/dm/@sundar-pk/angular-mydatepicker?logo=npm&style=for-the-badge" alt="NPM Downloads" />
  </a>&nbsp;

  <a href="https://app.codecov.io/gh/sundar-pk/angular-mydatepicker">
    <img src="https://img.shields.io/codecov/c/gh/sundar-pk/angular-mydatepicker?logo=codecov&style=for-the-badge" alt="Codecov Coverage" />
  </a>&nbsp;

  <a href="https://github.com/sundar-pk/angular-mydatepicker/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/sundar-pk/angular-mydatepicker/npm-publish.yml?logo=github&style=for-the-badge" alt="Build Status" />
  </a>&nbsp;

  <a href="https://github.com/sundar-pk/angular-mydatepicker/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/sundar-pk/angular-mydatepicker?&style=for-the-badge" alt="License" />
  </a>
</p>

---

**Note:** This repository was originally forked from `kekeh/angular-mydatepicker` but the original repository had not been maintained for a year and was then deleted without any notice :confused:. Hence this detached fork.

This updated version uses `"compilationMode": "partial"` for use in Ivy-enabled applications.

If you need a version compatible with an older (View Engine) Angular application, the original package can be found [here.](https://www.npmjs.com/package/angular-mydatepicker)

Credits : kekeh / nodro7

---
## Install

```console
npm install ivy-angular-mydatepicker
```
---

## Changelog

CHANGELOG.md has been deprecated, for recent changes see [GitHub releases](https://github.com/sundar-pk/angular-mydatepicker/releases).

---

## Browser support (tested)

| Chrome | Firefox | Edge | IE11 | Safari | iOS Safari |
| :------------- | :------------- | :----| :---------- | :----| :---------- |
| :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |

---

## Description

Highly configurable Angular datepicker and date range picker.

Basic idea to create this library was to make it as configurable as possible. The library is implemented as a directive. It is done this way, because then there is more choices to configure it.

### Main features

* no dependencies to other libraries
* currently localized to 47 
* datepicker
* date range picker
* popup mode
* inline mode
* supports keyboard
* supports RTL
* animation of calendar (open/close)
* awesome configuration possibilities
  * easily set styles to the component which are in line with your page theme
    * calendar
    * input box and input box controls
  * 50 [options]
    * change value of any option dynamically
* well tested
  * coverage [report]
  * most of the code is from existing libraries which are widely used

## Installation

To install this component to an external project, follow the procedure:

1. `npm install ivy-angular-mydatepicker`

2. Add `AngularMyDatePickerModule` import to your `@NgModule` as follows:

    ```ts
    import { BrowserModule } from '@angular/platform-browser';
    import { NgModule } from '@angular/core';
    import { FormsModule, ReactiveFormsModule } from '@angular/forms';
    import { AngularMyDatePickerModule } from '@sundar-pk/angular-mydatepicker';

    @NgModule({
      declarations: [
        AppComponent
      ],
      imports: [
        BrowserModule,
        ReactiveFormsModule,
        FormsModule,
        AngularMyDatePickerModule
      ],
      providers: [],
      bootstrap: [AppComponent]
    })
    export class AppModule { }
    ```

## License

* [MIT]

## Original Author

* [kekeh](https://github.com/kekeh)

## Fork - I Author

* [Nodro7](https://github.com/nodro7)