## 0.2.5
* Updated libphonenumber and PhoneNumberToCarrierMapper on Android 
* Remove dependency on [libphonenumber](https://pub.dev/packages/libphonenumber)
* Switch from libphonenumber-iOS to PhoneNumberKit on iOS 
* Update libphonenumber.js file 
* Depreciating `getNameForNumber` in future updates

## 0.2.3
* Updated dependencies
* Resolved issue with `RegionInfo.regionPrefix` is always `null`
* Replaced `regionPrefix` with `regionCode` in swift file

## 0.2.2
* Fixed recurring issue, exception caused by `isValidPhoneNumber` on `Web`

## 0.2.1
* Added full support of iOS
* Caught exception caused by `isValidPhoneNumber`
* Updated README.md file
* Added library documentation

## 0.2.0
* Migrated to Null Safety
* Changed `isValidNumber` to `isValidPhoneNumber`
* Added Android Support
* Added iOS support **:warning: :construction:**

## 0.1.0
* Initial implementation of libphonenumber_package