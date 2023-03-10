# Template BS5 Project for `FIGMA` conversions

Free Template styled with **Bootstrap** `v5.2.3` using best practices and simple tooling - **Used in projects**:

- 👉 [Web Agency Design](https://github.com/app-generator/design-web-agency) - `free & open-source` project
- 👉 [eCommerce Design](https://github.com/app-generator/design-ecommerce) - `free & open-source` project

<br />

## Features

- 🚀 [Bootstrap 5](https://www.admin-dashboards.com/bootstrap-5-templates/) 
- ⚙️ `Gulp Tooling` (simple usage, no fancy tools)
- ✅ **Easy Customization** (below files are already integrated)
  - `Primary/secondary` colors in [variables.scss](#)
  - `Add your own code` in [custom.scss](#)
- ✅ Sections
  - ✅ [Section_1](#), styled in [#](#)
  - ✅ [Section_2](#), styled in [#](#)

<br />

## How To use it

> Compile the project

```bash
$ yarn       # install modules
$ gulp       # start for development
$ gulp scss  # recompile SCSS
```

The design should be visible in the browser.

<br />

## How To Customize 

> ✅ `Step 1`: Open & Edit `assets\scss\variables.scss`. This file allows to set the primary and seconday colors of the website

```sass
/*
* Global Styling (edit below variables) 
* Warn: once edited, the SCSS needs to be recompiled
*/
$primary:   #FF7A00 !default; // primary color
$secondary: #00D2C4 !default; // secondary
$info:      #17c1e8 !default; 
$success:   #82d616 !default;
$warning:   #fbcf33 !default;
$danger:    #ea0606 !default;
```

> ✅ `Step 2`: Add custom styles to `assets\scss\custom.scss`. This file, initially shipped empty, should contain your own code CSS code.

```sass
.your-awesome-class {
    color: red;
}
```

> ✅ `Step 3`: Recompile SCSS via `GULP`

```bash
$ gulp scss
```

At this point, the new styles should be visible in the website.

<br />

## Section_1

> Section_1 screen here

<br />

## Section_2

> Section_2 screen here

<br />

--- 
Template BS5 Project for `FIGMA` conversions - Open-Source project crafted by [AppSeed](https://appseed.us/).
