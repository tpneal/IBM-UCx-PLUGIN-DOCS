# z/OS Rexx Executor - Overview

---

The z/OS Rexx Executor plug-in allows one to execute REXX statements provided in a zOS Dataset or Inline in the plugin.

## Installation

No special steps are required for installation. See [Installing plug-ins in UrbanCode products](https://community.ibm.com/community/user/wasdevops/blogs/laurel-dickson-bull1/2022/06/13/install-plugins).

## History

### Version 2

* Added new checkbox input to show debug logs in case of any unknown failure.
* Output will now show the elapsed time of the REXX program
* New output property RexxReturnCode will store the return code of the REXX program
* Fixes output buffer issue when output has too much data
* Arguments can now be as big as 248 characters
* Fixed issue with work directory during two or more parallel step execution
* Minor improvements in temporary directory creation 

### Version 1

* Initial release

|          Back to ...          |                                |                                                         Latest Version                                                          | z/OS Rexx Executor  |                   |                   |                           |
|:-----------------------------:|:------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------:|:-------------------:|:-----------------:|:-----------------:|:-------------------------:|
| [All Plugins](../../index.md) | [Deploy Plugins](../README.md) | [2.1161998](https://raw.githubusercontent.com/UrbanCode/IBM-UCD-PLUGINS/main/files/zos-rexx/ucd-plugins-zos-rexx-2.1161998.zip) | [Readme](README.md) | [Steps](steps.md) | [Usage](usage.md) | [Downloads](downloads.md) |