---
title: "Getting Started"
author: "Andrew Butler"
date: 2018-05-21
---

## Edit the configuration file (config.toml)

1. Change the author name
2. (Optional) Remove the menu item for this getting started guide.

### How to add menu categories
Add entries to config.toml. For example, to add a menu item that contains all entries from a "new-project":

```toml
[[menu.main]]
    name = "New Project"
    identifier = "new-project"
    weight = 200
    url = "/new-project/"
```

When creating the new project, you will also need to create a new subdirectory (through the Addins menu) if you want to have a leading description above the list of entries. Then just add an `_index.md` file to that subdirectory, the contents of which will appear above the list.

## Adding new entries

1. In Rstudio, select "new post" through the Addins menu.
2. Fill out relevant dialogue boxes.
3. Do work.