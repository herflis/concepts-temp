---
title: "Role based Permissions"
metaTitle: "sensenet - Role based Permissions"
metaDescription: "sensenet Role based Permissions"
---

sensenet offers you a sophisticated permission system, giving you the possibility to apply permission rules according to the logic you prefer.

# Advantage
Using role-based permissions, you can assign users to roles taking advantage of predefined permission settings.
built-in and custom permissions
There is a set of basic built-in permissions, such as See, Open, Save, Delete etc., and it is even possible to add custom ones as well.
•	See: you only have the information that the content exists (content metadata cannot be accessed)
•	Open: you have access to content metadata
•	Save: you can make changes in the content metadata
•	Other permissions for removing or approving a content or managing lists and workspaces.

# Permission inheritance
One of the advantages of the tree based hierarchical content structure in sensenet, is that it ensures permission inheritance, so it is enough to set a permission rule one time and it comes down in lower levels of the tree. This means, if you set a permission on a document library it will be automatically applied to subfolders and contents.

# How to use
It is possible to manage the role-based permission settings through the admin surface, or with User Management and Permission APIs.

# Pro tip
Define roles based on the business logic right at the beginning of your project so it will be much easier to handle permission related tasks (like add/remove a user) in the long run.

-> built-in roles for SNaaS users (Administrators, Editors, Developers)
