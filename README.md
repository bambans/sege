# Semantic Editor with Git-based semantic File System (SEG Editor)

Based on [EditorPP - FNakano](https://github.com/FNakano/CFA/tree/master/projetos/EditorPP)

Its purpose is to make possible:

- Creating a semantic journal;
- Graph based relationship among files;
- Semantic Tagging annotation and quering (SPARQL queries on the system);
- Versioning support for every single change.

## Main objectives:

- **Creating a backend to provide**:
    - Terminal based frontend;
    - TKinter frontend;
    - Web based frontend;
    - `WYSIWYG` - What You See Is What You Get.
- **Using Git as a FUSE (File System in Userspace), featuring**:
    - Semantic support to emulate a semantic filesystem (at first, in files metadata);
    - Versioning for files and folders for the entire scope;
    - Make possible to use semantic queries, as using a SPARQL endpoint;
    - Let possible to login with your Git server account and have a synchronization functionality embedded.
- **Some tool to provide a graph view of the entire filesystem**:
    - Despite a tradicional editor, it will be possible to link everything with everyother thing else;
    - Have some statistical data about tags density, so, in other words, see how tags are often used or what is you write the most.

## First achtechture outline

From top to down:

- **Editor User's frontend**: terminal, tkinter or web;
- **Editor Backend**: that will provides an API for frontend implementations of its features (tagging, git sync, git commiting... ) and editor functionality;
- **Git functionality backend**: providing a backend's API for editor's backend implemetations of its Git features;
- **Semantic support system**: websemantic features for this system.

## Some web links:

- [Semantic Versioning 2.0.0](https://semver.org/)
- [Nakano's EditorPP](https://github.com/FNakano/CFA/tree/master/projetos/EditorPP)
- [Git-SCM](https://git-scm.com/)
- [Semantic File System - Wikipedia](https://en.wikipedia.org/wiki/Semantic_file_system)
- [Tagsistant: tagging semantic file system for Linux Kernel based on FUSE](https://www.tagsistant.net/)
    - [_Tagsistant - Wikipedia_](https://en.wikipedia.org/wiki/Tagsistant)
