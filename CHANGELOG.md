# Changelog Region Device Count

## Table of Contents
- **[r1.1](#r11)**

**Please be aware that the project will have frequent updates to the main branch. There are no compatibility guarantees associated with code in any branch, including main, until it has been released. For example, changes may be reverted before a release is published. For the best results, use the latest published release.**


# r1.1
## Release Notes

This pre-release contains the definition and documentation of
* region-device-count 0.1.0-rc.1

The API definition(s) are based on
* Commonalities v0.5.0
* Identity and Consent Management v0.3.0


## region-device-count v0.1.0-rc.1

**region-device-count v0.1.0-rc.1 is the first release-candidate version for v0.1.0 of the region-device-count API. The following changes have been made for v0.1.0 through https://github.com/camaraproject/RegionDeviceCount/pull/47**

  * Error model aligment with commonalities, which implies use of normalization values (i.e. enums) for `status` and `code`
  * Removal of 404,405,406,5xx errors
  * Change the validation rule of the `Filter` parameter from `oneOf` to `anyOf`
  * Fix MegaLinter error

 API definition **with inline documentation**:
[[YAML]](https://github.com/camaraproject/RegionDeviceCount/blob/r1.1/code/API_definitions/region-device-count.yaml)
[[View it on ReDoc]](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/camaraproject/RegionDeviceCount/r1.1/code/API_definitions/region-device-count.yaml&nocors)
[[View it on Swagger Editor]](https://editor.swagger.io/?url=https://raw.githubusercontent.com/camaraproject/RegionDeviceCount/r1.1/code/API_definitions/region-device-count.yaml)

**Initial contribution of API definitions for Region Device Count**, including initial documentation and implementation code.

## What's Changed
* Initial yaml file including regionUserCount api in https://github.com/camaraproject/RegionDeviceCount/pull/5
* Change the API name from regionUserCount to regionDeviceCount in https://github.com/camaraproject/RegionDeviceCount/pull/27
* Add startime and endtime parameters to support querying the number of devices within a certain time period in https://github.com/camaraproject/RegionDeviceCount/pull/31
* Added filter parameter in the request parameters to filter the roaming status and type of the device in https://github.com/camaraproject/RegionDeviceCount/pull/38
* Add capability for async response behaviour in https://github.com/camaraproject/RegionDeviceCount/pull/42
* Add test file in https://github.com/camaraproject/RegionDeviceCount/pull/46


