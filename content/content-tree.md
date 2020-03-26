---
title: "Content Tree"
metaTitle: "sensenet - Content Tree"
metaDescription: "sensenet Content Tree"
---

sensenet content repository is basically a tree structure of the various stored content. A specific content is identified by a unique number (id) and also by its path. The root of the tree is at `/Root` path, all other content is placed somewhere under this root content - for example the users are placed at `/Root/IMS`.

# Structured storage of content

# Content access and url resolution

Every content in the content repository is identified by its unique Id and its path. You cannot change a content Id, but you can move a content to another folder and thus change its path. The tree structure of the repository makes it possible to use the path as a link to the content.

# Advantages of the tree structure
- inheritance (type, permission)
- organize bunch of content in a separate subtree (even for differenciate content for multiple separate apps in one repository)
- handle subtrees separately at once
- search faster in subtree
