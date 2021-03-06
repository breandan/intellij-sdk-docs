---
title: Project Model. Roots and Libraries. Configuring Project from Code.
---

This section considers internal architecture *IntelliJ Platform* projects
and gives overview for classes and packages of the API used to manipulate with projects and their components, such as modules, facets, libraries, SDK.
For general information about the concept of a projects and concepts related to it, refer to
[Project](http://www.jetbrains.com/idea/webhelp/project.html),
[Module](http://www.jetbrains.com/idea/webhelp/module.html),
[Library](http://www.jetbrains.com/idea/webhelp/library.html),
and
[Facet](http://www.jetbrains.com/idea/webhelp/facet.html)
in
[IntelliJ IDEA Web Help](https://www.jetbrains.com/idea/help/intellij-idea.html).


## Project Structure

A project consists of one or several modules.
Each module includes the plugin source code and so called order entries that refer to SDK and libraries the module uses.
By default, all modules uses the project SDK.
In addition, a module can optionally have a set of facets.
This document explains how you can explore and change the structure of projects using API.

Main project structure components are:

* [Project](/reference_guide/project_model/project.html) 
  itself

* [Module](/reference_guide/project_model/module.html)

* [SDK](/reference_guide/project_model/sdk.html)

* [Library](/reference_guide/project_model/library.html)

* [Facet](/reference_guide/project_model/facet.html)


