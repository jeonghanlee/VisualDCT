# Release Notes

## 2.7.1 (not released yet)
[View diff](https://github.com/epics-extensions/VisualDCT/compare/v2.7.0...master)

## 2.7.0 (05 Jan 2018)
[View diff](https://github.com/epics-extensions/VisualDCT/compare/v2.6.1280...v2.7.0)

 * Add support for 64bit integer database fields (introduced in Base 3.16)
 * Bugfix: Handle escaped quotes and backslashed in field values
 * Enhancement: Use Writer for file output to support UTF character encoding in DB files
   (Required for use with EPICS Base 3.16 and EPICS 7.)

## 2.6.1280 (02 May 2016)
[View diff](https://github.com/epics-extensions/VisualDCT/compare/8f714da...v2.6.1280)

 * Resurrect as a Maven project on GitHub, adding CI (CloudBees and Travis)
 * Fix Javadoc errors
 * Enhancement: Read promptgroup (gui_group) choices from DBD.
   (Recommended for use with EPICS Base 3.15.4 and up.)

## 2.6.1279 (08 Jan 2015)
[View diff](https://github.com/epics-extensions/VisualDCT/compare/03889bc...8f714da)

 * Bugfix: When opening multiple dbd files via args, do not overwrite already
   loaded definitions.
 * Bugfix: When removing dbd files via the dialog, remove the file also from the
   loaded dbd vector. Otherwise it is impossible to reload it.
 * Enhancement: Do not use decorated frames and dialogues.
   They are really ugly and non-standard.

## 2.6.1278 (10 Feb 2010)
[View diff](https://github.com/epics-extensions/VisualDCT/compare/61f04240...b21ee0f5)

 * Bugfix: File find
 * Enhancement: Add support for info fields
