# Changelog

## Release 0.9.0

[Released on April 13, 2018](https://github.com/adobe/xdm/releases/tag/v0.9)

* Release 0.9 is preview release which updates the `ExperienceEvent` schema to 'stabilizing' status, along with many of the schemas it depends on. This release is intended to get early feedback from implementers and the community before a 1.0 release.

## Release 0.9.1

[Unreleased](https://github.com/adobe/xdm/releases/tag/v0.9.1)

* Renames all `Metric` schemas to `Metric Definition` #254
<<<<<<< HEAD
* Moved web metrics used in ExperienceEvent \\metrics to the webinteraction and webpageview contexts #316
* Moved `Commerce` metrics used in ExperienceEvent `\metrics` to the `\commerce` context #317
* Shortened the URI field name for the web events to `https://ns.adobe.com/xdm/metrics/*` by dropping the 'data'. #317
* `abandons` metric field name change to `cartAbandons` `https://ns.adobe.com/xdm/metrics/cartAbandons`. #317
* Added application and mobile context via `\context\application.schema.json` #318
* Fixed issue where `\context\experienceevent` `xdm:application` referred to the 'application.schema.json' in `\channels` #318
* `xdm:application` in `\context\experienceevent` `@id` renamed to `xdm:id` #318
=======
* Removed the required constraint from `\xdm\external\schema\geo*.schema.json` #315
>>>>>>> Issue-308---Geo-@id-needs-to-be-removed
