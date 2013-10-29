cordova-datepicker-plugin-test-project
======================================

Simple Cordova 3 project to show how my [cordova-datepicker-plugin](https://github.com/DURK/cordova-datepicker-plugin) can be used

## Getting started
To run this demo, you'll need to follow a few steps:
* You need to have the phonegap/cordova-cli installed
* Add cordova's device-plugin: `phonegap local plugin add org.apache.cordova.device`
* Add my plugin: `phonegap local plugin add https://github.com/DURK/cordova-datepicker-plugin`
* Run! `phonegap local run android/ios`


## Notes
* With some small adjustments, `nativedatepicker.js` could be changed to work without jQuery
* I'm setting a custom html5 data-attribute called `iso`, on each picker-field for platform-independent (de)serialization, which can also be useful when submitting these fields
* `LOCALIZED_MONTH_NAMES` can be extended to use different languages, and `getDateString()` can be edited to allow different date-formats per language
