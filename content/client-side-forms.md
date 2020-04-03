---
title: "Client Side Forms"
metaTitle: "sensenet - Client Side Forms"
metaDescription: "sensenet Client Side Forms"
---

# Client Side Forms

As you probably heard before, in sensenet everything is a content. This philosophy provides many advantages when working with sensenet because the only difference between contents are the fields they have. This facilitate the way of managing different [type of contents](/concepts/content-types).

Based on this logic, defining a new content type with custom fields, opens the possibility to create client side forms easily.

# Schemas and Forms

You have the newly defined content type (form) but how this will be filled by users, you may ask.
Every time a user fills the fields (questions) of this content and submit it, a new instance is created (filled form) containing all the answers given to the questions in the form (saved to the corresponding fields).

Schemas
???

# Views

The content is there in the repository, but how it will be visible to the users only depends on you. You can get fields and possible values by API calls and display it in your solution based on your taste and needs.

You can define views for different content types, this way you can have a dedicated view for each forms (content type).

# Fields
[illustration of a custom content type with questions as fields]

Every content is built up by fields, so for example a user as content has numerous special fields as well for storing data like their username and password (among others). It is no different with forms but instead of username and password, it consists of questions.
Fields (of a content) can be defined on the content type definition.

# usage (advantages)

It is a handy use case of a custom content type since you don't need to rely on any third party service to create client side forms. All submitted forms will be saved as a new content under a specified location in your repo enabling you to analyze all the answers afterwards.
This versatility enables you to easily define contents based on your business needs, the client side forms (presented above) is just one example of the possibilities content type methodology holds.
