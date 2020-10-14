# Group Assigner

Simple plugin for [AllianceAuth](https://gitlab.com/allianceauth/allianceauth) to assign groups to users when they change states.

## Installation
1. `pip install allianceauth-group-assigner`
2. add `'groupassign',` to your `INSTALLED_APPS` in the local.py, 
3. run migrations
4. restart auth

## Setup
* Add groups to the required State in admin
* this module will not remove groups
    * you can achieve this with the groups state permissions.

## Contributing
Make sure you have signed the [License Agreement](https://developers.eveonline.com/resource/license-agreement) by logging in at https://developers.eveonline.com before submitting any pull requests. All bug fixes or features must not include extra superfluous formatting changes. If you have an issue with formatting, push it in it's own PR for discussion. 

## Change log
* v0.0.1
  * First release