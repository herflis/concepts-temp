---
title: "Trash"
metaTitle: "sensenet - Trash"
metaDescription: "sensenet Trash"
---

# introduction
sensenet has a trash feature. When you delete a document or a folder and the trash feature is enabled (enabled by default), it will not be deleted permanently. You can find it in the Trash Bin, and you can restore it.

The Trash Bin is a central place for deleted documents where you can browse, restore or delete content permanently. It is also possible to provide a local (workspace-level) trash for users.

The size of the trash and the time frame while the contents can be recovered from the trash is set by the administrator. Trash feature can be switched on or off globally.

# Delete operation capabilities
Delete operation allows users to transfer content (documents, folders or whole workspaces) into the Trash Bin - or delete them permanently.

- delete content that go to the trash
- delete content permanently, without using trash
- enable or disable trash locally or globally
- enable or disable trash for a content type

Contents can be deleted through API calls, but these actions are also available on the admin ui:

You can access delete action for basically every content in the doclib by clicking context menu (...) or right click on item.
![delete action](./img/delete_contextmenu.png)


By default configuration, a confirmation popup appears, displaying content name and path, with an additional option to permanently delete the content (skipping trash). 
![confirm delete](./img/confirm.png)

Deleted (trashed) items can be found in a specific folder having some extra parameter like retention time, quota for size and number of content. These limits can be customized.
![trash](./img/trasheditem.png)

Actions can also be performed on a trashed item. It can be moved to a specific location (restore from trash), deleted, edited and so on.
![trash actions](./img/trash_actions.png)

When deleting a trashed item, the content will be permanently deleted
![delete from trash](./img/permanentdelete.png)

If the trash is disabled, the popup informs you that the feature is turned off. Be careful because you may delete a content permanently. Your content can't be restored in this case.


# Trash - for Portal Builders
# Trash - for Developers
# Trash - for System operators

https://wiki.sensenet.com/Trash

és itt a links részben található cuccok
