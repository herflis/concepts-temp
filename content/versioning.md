---
title: "Versioning"
metaTitle: "sensenet - Versioning"
metaDescription: "sensenet Versioning"
---

# What is content versioning?
As mentioned above, versioning is the management of changes to documents and other information stored in a file system or repository.
The versioning system of sensenet also provides mechanisms for keeping the published version of a document visible to non-editor users, while you continue to work on the latest, draft version.
In sensenet, versioning is disabled by default. It can be enabled for folders or content lists, by setting the value of the Versioning Mode field. Subfolders inherit versioning settings by default. 
When a new Content is created in the Content Repository with versioning enabled, it is assigned the initial version number, depending on the versioning mode. Changes made to the document will result in a bump of the version number, with old versions tracked for possible rollbacks.

# Does sensenet also version content types or users?
# version types (mayor, minor)
You can set the following Versioning Modes for folders:

- None: the default setting of the Root folder, no versioning.
- Inherited: The folder inherits its versioning mode from its parent. This is the default setting for all other content.
- Major only: Only major versions (1.0, 2.0,…) are preserved.
- Major and minor: Every version is preserved (1.0, 1.1, 1.2,…).

# Versioning and visibility
Visitors in general are only allowed to view the last public versions of a content. This is controlled by the Open minor permissions: a user who does not possess the open minor permission for a content will only see the last public version of a content, and will never see any changes that correspond to a draft version or that are not yet approved. The other important thing here to bear in mind is that if a document gets rejected it does not mean that the document is not visible for the public. It only means that the last version that was rejected will not be visible to the public.
# How do I configure user permissions to work with versioning?
# usage (advantages)
