---
title: "Custom Roles and Permissions"
metaTitle: "sensenet - Custom Roles and Permissions"
metaDescription: "sensenet Custom Roles and Permissions"
---

# Custom Roles and Permissions

Sense/Net comes with a built-in permission system with the most common permission types. The pre-defined permission type set is adequate in most of the cases, but there might be some situations when it is desired to define custom permissions on content 

# Creating a new role

-> group creation

sensenet offers special and built-in groups and users by default. All users and almost all groups are stored in the /Root/IMS folder. It is possible to create groups outside the IMS folder. These are local groups created for using individual workspaces.
There can be some cases when you need to create a new role, which is actually a new group. You just need to create the group and (as mentioned above), set the proper permission rules of the group, then add the users to the group. This way instead of setting permissions to individual users one by one, they will earn the permissions of the group automaticly. For example, if you would like to create the role "Approval", you create the group "Approval". Then in the subtree you allow the right "approval" and put the users into the group.


# Modifying an existing role

-> editing groups
-> allow or deny permissions for groups

# Permissions

https://wiki.sensenet.com/Permission_settings.html

https://wiki.sensenet.com/Permission_Constraints.html

A group is a content in the Content Repository that cannot have physical children but has a Members Reference Field that can contain users or other groups.

# Using permissions
