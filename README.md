# RevSkills / Mobile Revelator 16-digit SP code XML

An updated version of **sp.xml** for use with the RevSkills and [Mobile Revelator](https://github.com/bkerler/MR) mobile development and forensics tools.


# How to "install" on RevSkills

Drag and drop this file into the /keys/ folder where RevSkills is installed. By default, this would be ``C:\Program Files (x86)\Revskills\config``.

## Why?
Primarily to aid in dumping the memory contents or filesystem (EFS) of certain obsolete Qualcomm-based mobile phones. Most newer Samsung CDMA feature phones require both the 16-digit SP code **and** 6-digit MSL in order to allow unblocked filesystem access and memory reading (useful for backing up BREW games and extracting other resources). You can read the MSL using RevSkills once you input the correct SP code.

## Issues

If an SP-code in this list doesn't work with your phone, please submit an Issue with your phone model and the SP code you tried.


## Have your own list?

The more complete, the better! Any known working SP codes are appreciated.
