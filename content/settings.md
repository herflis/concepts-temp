---
title: "Settings"
metaTitle: "sensenet - Settings"
metaDescription: "sensenet Settings"
---

# intro

sensenet has a number of modules and features that provide a way to customize their behavior by offering settings. It is an essential part of an application how it stores and handles settings and we wanted to provide a framework that is easy to use and customize at the same time enabling developers to make custom modules more flexible and easy to configure.

# settings is a content too

In sensenet, settings are stored as content in the content repository. The advantage of this is that changing a setting does not involve site restart and you can manage values in one central place.

Another advantage of storing settings as content is that you are able to provide a rich user interface for administrators to manage settings. It is possible to create or edit settings files on a dedicated ui in your solution or using OData.

In general settings are created for administrators or editors to let them customize the behavior of a certain feature.
Settings on the other hand are readable and writable by the application without restarting it. Settings files are stored in sensenet content repository.

# local and global settings

Settings in sensenet can be either global or local

Global settings: stored in the /Root/System/Settings folder.
Local settings: any folder can contain a system folder named Settings for storing settings files related only to that part of the repository that override or extend global settings.

-------------
# setting inheritance

Settings files can be global or local, as we mentioned above. Local settings files override global ones and they are applied only in that part of the Content Repository.

Every key in a settings file is overridable in another file with the same name under an appropriate position in the subtree. See the following example:

For example there is a custom application that uses MySettings. The request starts this application with Aenean semper.doc as a context node (red arrow). In this case your application's real settings are combined by the ancestor settings chain that contains three items in the following order:

the workspace's settings (green arrow)
the site's settings (blue arrow)
and global settings (black arrow)
The inheritance is realized on the file and key level: if the settings file on a lower level (which has the same name) contains only one key, only this value will be overridden; values in other files in higher levels won't be affected and will remain accessible.

The examples above about accessing setting values contain a path parameter. That is the content path that the settings framework will use as the starting point when discovering the appropriate settings. If no local setting is found with that name or the given property, the fallback is always the global settings file in the /Root/System/Settings folder.


https://wiki.sensenet.com/Settings

https://wiki.sensenet.com/Portal_settings
