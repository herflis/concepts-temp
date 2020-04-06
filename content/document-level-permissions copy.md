---
title: "Document level Permissions"
metaTitle: "sensenet - Document level Permissions"
metaDescription: "sensenet Document level Permissions"
---

In addition to the [role-based permission](/concepts/role-based-permissions) functionality, sensenet offers you the ability of setting permissions even on document level . Managing the accessibility of individual contents is an essential part of working with the repository. Administrators (and all users that have the permission to see and edit security settings) are allowed to change permission settings on content and influence who can see or edit, or perform a particular operation on it.

# Advantages
Using content (or document) level permissions, you can set who has access to an individual content and allow/restrict actions one by one. Since sensenet has a tree based hierarchical content structure it ensures permission inheritance, so it is enough to set a permission rule one time and it comes down in lower levels of the tree. This means, if you set a permission on a document library it will be automatically applied to subfolders and contents. You are able to set a permission for an individual document or on whole libraries and workspaces.
This can be a good solution, for example in case a certain user has the access to a workspace, but not to a certain folder or document in that workspace.

If you want to change the permission settings for one or more identities (or remove it completely), you have to break the permission inheritance, after that you are able to edit the permission settings for the them.

Document level permission is useful when you want to give (or reject) access to an individual document for specific user or group. For example in a document library containing contracts, only those document could be available to open or download for user that are connected to them.

# Built-in and custom permissions

There is a set of basic built-in permissions, such as:
•	See: you only have the information that the content exists (content metadata cannot be accessed)
•	Open: you have access to content metadata
•	Save: you can make changes in the content metadata
•	Other permissions for removing or approving a content or managing lists and workspaces.

It is possible to add custom permissions as well. Besides the built-in permission types (See, Open, etc.) sensenet defines  some custom permission types (named Custom01, Custom02, etc.) that can be used for custom permission settings. A common example would be to allow a user to print a document (or deny it): for this developers could assign the permission type Custom1 and use it consistently in the system to check permissions and allow or disallow printing.

It is possible to manage content (document) level permission settings through the admin surface, or with User Management and Permission APIs.