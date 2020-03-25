---
title: "User Management"
metaTitle: "sensenet - User Management"
metaDescription: "sensenet User Management"
---

# User Management

# What is it for?
User management is a core function of the business, that includes user creation and assigning roles to the users. Effective user management contains adjusting the access rights of the users who change role, get promoted or leave the company. It is important to close these changes in short time, this way we can increase employee productivity.

# Users and groups as content
sensenet is built around content, so they are also users ang groups. Every content is built up by fields, so for example a user as content has a name field and password field (among others). The type of the content is called content type, and it defines a set of fields a content possesses, and also the behavior of it.

# Built-in groups and users
sensenet offers special and built-in groups and users by default. All users and almost all groups are stored in the /Root/IMS folder. It is possible jto create groups outside the IMS folder. These are local groups created under workspaces.

•	public domain (/Root/IMS/Public) for the users

•	builtin domain (hidden) for technical users and groups that cannot be modified but its capabilities could be used in development

o	Visitor

o	Everyone

o	Owners

o	IdentifiedUsers

o	RegisteredUsers

o	Somebody

https://wiki.sensenet.com/Special_and_built-in_groups_and_users.html

•	built-in public groups/roles for basic tasks -> administrators, developers, editors


# Permission
sensenet offers you a sophisticated permission system, giving you the possibility to apply permission rules according to the logic you prefer.
Using role-based permissions, you can assign users to roles taking advantage of predefined permission settings. Role based access control provides management of users and tasks that they can perform on contents (for example built-in permissions such as See, Open, Save, Delete ect, and it is also possible to add custom ones as well.
Define roles based on the business logic right at the beginning of your project so it will be much easier to handle permission related tasks (like add/remove a user) in the long run.
To learn more go to [role based permission]

# Workspace local groups
In sensenet the default location of users and groups is the IMS folder. However, we can create groups under workspaces too. The main purpose of Workspace local groups is to help permission management inside workspaces. They are located under the Groups system folder in workspaces and workspace permissions can be defined for these groups. If the local group structure is properly configured, the only thing workspace administrators should do when a new user is assigned to a workspace is to add them to the proper local group(s) instead of assigning permissions to individual users. In sensenet there are three predefined local groups (Owners, Members, Visitors) that cover the most important use cases but there are no limitations to add or remove groups or modify the default behavior. Groups are contents too (like almost everything in sensenet), so you can add additional groups to workspaces as easily as you add folders. Populating a group with users is an easy task as well using our group management GUI with instant search capability.

# How to create a new role

