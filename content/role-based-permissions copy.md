---
title: "Role based Permissions"
metaTitle: "sensenet - Role based Permissions"
metaDescription: "sensenet Role based Permissions"
---

sensenet offers you a sophisticated permission system, giving you the possibility to apply permission rules according to the logic you prefer.

# Advantages
Within an organization roles are created for various job functions. Using role-based permissions, you can assign users to roles taking advantage of predefined permission settings to that role. Since users are not assigned permissions directly, but only acquire them through their role (or roles), management of individual user rights becomes a matter of simply assigning appropriate roles to the user’s account; this simplifies common operations, such as adding a user, or changing a user’s department.

# Built-in and custom permissions
There is a set of basic built-in permissions, such as See, Open, Save, Delete etc., and it is even possible to add custom ones as well.
•	See: you only have the information that the content exists (content metadata cannot be accessed)
•	Open: you have access to content metadata
•	Save: you can make changes in the content metadata
•	Other permissions for removing or approving a content or managing lists and workspaces.

as mentioned above, the built-in permission set can be extended with custom ones. These permissions are by default hidden from the UI and have no effect on permission checks but a builder or developer can easily bring custom permissions into the set of effective permissions.

# Built-in roles for SNaaS users

- Administrators:

- Editors

- Developers


# Permission inheritance
One of the advantages of the tree based hierarchical content structure in sensenet, is that it ensures permission inheritance, so it is enough to set a permission rule one time and it comes down in lower levels of the tree. This means, if you set a permission on a document library it will be automatically applied to subfolders and contents. Inherited permissions cannot be changed without breaking the inheritance. You may decide to change some permissions inherited from above - e.g. you inherited an Open permission for a user that you do not want to allow in a subtree. In that case you can break permission inheritance on a content. That means all the inherited permission entries will be copied to the current content and from than on you will be able to change them (usually remove one or more). The new permission set (even if it contains less entries than the inherited) will be the one that is used in that subtree. If possible, break permissions in exceptional cases only, because it makes permission administration more complicated.

# How to use
It is possible to manage the role-based permission settings through the admin surface, or with User Management and Permission APIs. Define roles based on the business logic right at the beginning of your project so it will be much easier to handle permission related tasks (like add/remove a user) in the long run.
