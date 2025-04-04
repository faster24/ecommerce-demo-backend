# Changelog

All notable changes to `color` will be documented in this file

## 1.7.0 - 2024-12-30

### What's Changed

* Extended HSL/HSLA/HSB Handling with Float Support by @danielebarbaro in https://github.com/spatie/color/pull/93

**Full Changelog**: https://github.com/spatie/color/compare/1.6.3...1.7.0

## 1.6.3 - 2024-12-23

### What's Changed

* Test Enhancements for Contrast Calculations (and mini refactor for contrast class) by @danielebarbaro in https://github.com/spatie/color/pull/92

### New Contributors

* @danielebarbaro made their first contribution in https://github.com/spatie/color/pull/92

**Full Changelog**: https://github.com/spatie/color/compare/1.6.2...1.6.3

## 1.6.2 - 2024-12-09

### What's Changed

* Issue #88 Cast return to float instead of string to match Contrast ratio return type by @NiklasBr in https://github.com/spatie/color/pull/91

### New Contributors

* @NiklasBr made their first contribution in https://github.com/spatie/color/pull/91

**Full Changelog**: https://github.com/spatie/color/compare/1.6.1...1.6.2

## 1.6.1 - 2024-11-18

### What's Changed

* Fix wrong Validation Error message for hsla strings by @Afrowson in https://github.com/spatie/color/pull/90

### New Contributors

* @Afrowson made their first contribution in https://github.com/spatie/color/pull/90

**Full Changelog**: https://github.com/spatie/color/compare/1.6.0...1.6.1

## 1.6.0 - 2024-09-20

### What's Changed

* Ignore more file when packaging releases by @andypost in https://github.com/spatie/color/pull/83
* Fix typo in README for Hsl::fromString() in Cast the color to a string. by @agnonym in https://github.com/spatie/color/pull/84
* Added named colors by @vanodevium in https://github.com/spatie/color/pull/87

### New Contributors

* @andypost made their first contribution in https://github.com/spatie/color/pull/83
* @agnonym made their first contribution in https://github.com/spatie/color/pull/84
* @vanodevium made their first contribution in https://github.com/spatie/color/pull/87

**Full Changelog**: https://github.com/spatie/color/compare/1.5.3...1.6.0

## 1.5.3 - 2022-12-18

### What's Changed

- Refactor tests to pest by @AyoobMH in https://github.com/spatie/color/pull/80
- Add PHP 8.2 Support by @patinthehat in https://github.com/spatie/color/pull/81
- Fix rgb to cmyk division by zero bug by @stefanriehl in https://github.com/spatie/color/pull/82

### New Contributors

- @AyoobMH made their first contribution in https://github.com/spatie/color/pull/80
- @patinthehat made their first contribution in https://github.com/spatie/color/pull/81
- @stefanriehl made their first contribution in https://github.com/spatie/color/pull/82

**Full Changelog**: https://github.com/spatie/color/compare/1.5.2...1.5.3

## 1.5.2 - 2022-06-24

### What's Changed

- Add RegEx fix to Validate.php too... by @jcogs-design in https://github.com/spatie/color/pull/73
- Fix typo in Distance::CIE76. by @Angel5a in https://github.com/spatie/color/pull/76

### New Contributors

- @jcogs-design made their first contribution in https://github.com/spatie/color/pull/73
- @Angel5a made their first contribution in https://github.com/spatie/color/pull/76

**Full Changelog**: https://github.com/spatie/color/compare/1.5.1...1.5.2

## 1.5.1 - 2022-04-12

## What's Changed

- Fix rgba opacity by @AstroCorp in https://github.com/spatie/color/pull/67

## New Contributors

- @AstroCorp made their first contribution in https://github.com/spatie/color/pull/67

**Full Changelog**: https://github.com/spatie/color/compare/1.5.0...1.5.1

## 1.4.0 - 2022-01-05

- Added support for PHP 8
- Added support for CMYK & HSB
- Added support for HEX alpha channel
- Added support for 3-digit HEX values

## 1.3.1 - 2021-09-09

- Fix HEX/HSL conversion bug

## 1.3.0 - 2021-09-06

- Added CIELab and XYZ color formats and `Distance` API
- Added `Contrast` API

## 1.2.4 - 2021-02-18

- Fixed division by zero error on pure white/black convertions ([#42](https://github.com/spatie/color/pull/42))

## 1.2.3 - 2020-12-10

- Added support for PHP 8

## 1.2.2 - 2020-11-18

- Fix transform RGB value to HSL : division by zero (#38)

## 1.2.1 - 2020-07-17

- HSL to RGB fixes

## 1.2.0 - 2020-06-22

- Added HSL & HSLA support

## 1.1.1 - 2017-02-03

- Fixed validation when a color contained redundant characters at the beginning or end of the string

## 1.1.0 - 2017-01-13

- All color formats now implement a `Color` interface
- Added a `Factory` class with a `fromString` static method to guess a format
- `rgb` and `rgba` values can now contain spaces (e.g. `rgb(255, 255, 255)`)

## 1.0.2 - 2016-10-17

- `rgbChannelToHexChannel` now also accepts single single-digit hex values

## 1.0.1 - 2016-09-22

- Bugfix (breaking!): Alpha channel values are now a float between 0 and 1

## 1.0.0 - 2016-09-21

- First release
