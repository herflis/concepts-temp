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

Built-in groups in sensenet are regular groups, meaning their membership can be freely modified. They are used in the default Content Repository structure extensively, but no hard-coded logic is built on them (except for the Administrators group, please do not delete that one). This means you can freely change or replace these groups with your own custom groups in your permission settings. The best practice however is that you build on them, using the suggested purpose in the following sections.

•	public domain (/Root/IMS/Public) for the users

•	builtin domain (hidden) for technical users and groups that cannot be modified but its capabilities could be used in development

o	Visitor

o	Everyone

o	Owners

o	IdentifiedUsers

o	RegisteredUsers

o	Somebody

# Built-in public groups/roles for basic tasks
Administrators

Administrators considered to be the most powerful users in the system. This may be true for some features but not necessarily for all content. In the default structure administrators have access to everything, but when you build your project and add your custom content, it is perfectly fine if you hide something from the Administrators group. For example you may remove their permissions from confidential documents completely.

By default only the Admin user is a member of this group, but you can add more members as you like. Please use this group for administrative permissions instead of single users.

Editors

We do not have any predefined permissions for this group by default, we consider them as a middle layer between administrators and regular users. For example you can define permissions for the global Editors group for skins and renderers or content types.

IdentifiedUsers
Identified users are what the name implies: users who we know. These can be intranet users synchronized from the Active Directory or users created for your clients or partners. The membership of this group depends totally on you, the system does not add anybody to this group automatically.

Operators

The Operators group is used by the system in cases where an administrative task needs to be completed. For example only the members of the Operators group can modify the CreationDate property of content (e.g. when importing). We created this group to be used as a role in the system and did not add any content permissions for them by default. The Administrators group is a member of this group, but this may be changed if you want to.

Operators see the PRC on pages, they have access to the Content Explorer interface (since this group is the member of the ContentExplorers group), furthermore they are entitled to the monitor pages, like: Task Management and Permission Overview.

RegisteredUsers

The Registered users group is a regular group, you may modify its members freely; the only specialty of it is that the sample public registration workflow adds users to it. They should have slightly less permissions than identified users (see above) because the registration can be very open in a public portal. This is why there are not many permission settings for this group in the default structure.


# Permission
sensenet offers you a sophisticated permission system, giving you the possibility to apply permission rules according to the logic you prefer.
Using role-based permissions, you can assign users to roles taking advantage of predefined permission settings. Role based access control provides management of users and tasks that they can perform on contents (for example built-in permissions such as See, Open, Save, Delete ect, and it is also possible to add custom ones as well.
Define roles based on the business logic right at the beginning of your project so it will be much easier to handle permission related tasks (like add/remove a user) in the long run.
To learn more go to [role based permission]

# Workspace local groups
In sensenet the default location of users and groups is the IMS folder. However, we can create groups under workspaces too. The main purpose of Workspace local groups is to help permission management inside workspaces. They are located under the Groups system folder in workspaces and workspace permissions can be defined for these groups. If the local group structure is properly configured, the only thing workspace administrators should do when a new user is assigned to a workspace is to add them to the proper local group(s) instead of assigning permissions to individual users. In sensenet there are three predefined local groups (Owners, Members, Visitors) that cover the most important use cases but there are no limitations to add or remove groups or modify the default behavior. Groups are contents too (like almost everything in sensenet), so you can add additional groups to workspaces as easily as you add folders. Populating a group with users is an easy task as well using our group management GUI with instant search capability.

# How to create a new role

