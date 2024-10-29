# Task Board - Obsidian Plugin

![License](https://img.shields.io/github/license/tu2-atmanand/Task-Board)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/tu2-atmanand/Task-Board?style=flat-square)
![Obsidian Downloads](https://img.shields.io/badge/dynamic/json?logo=obsidian&color=%23483699&label=downloads&query=%24%5B%22Task-Board%22%5D.downloads&url=https%3A%2F%2Fraw.githubusercontent.com%2Fobsidianmd%2Fobsidian-releases%2Fmaster%2Fcommunity-plugin-stats.json)

> Inspired from [CardBoard Plugin](https://github.com/roovo/obsidian-card-board) by [roovo](https://github.com/roovo).

**"Document your progress while completing your tasks"**

An Obsidian plugin to view and manage all your task in a much more efficient Kanban Board format. Easily manage your tasks throught your vault.

< need to add two images here with dark and light theme>

The main idea behind this plugin is to able to document all your work from start to end on how you completed the specific task, what all possible solution and resources you collected along with recording the timestamp while you were working on the task.

#### **How Does it work ?**

- It scans tasks from all the Markdown file from your whole vault and show them on a Kanban type Board.
- Edit the task directly from the Task Board, without opening the Markdown file.
- See Real TIme changes in the parent markdown file.
- Add task to currently opened files using a pop-up window.

#### **How to start ?**

**Step 1 :** Install and Enable the plugin.

**Step 2 :** Open Task Board using the Icon from the right side Ribbon Icon Bar. Or there is a command in the Command Pallet.
< Add a Image here to show which ribbon button to click >

**Step 3 :** Click on the Re-Scan Vault button. This will open the Scanning Pop-up window to scan tasks from your file. (This is required to run only for fresh install or in special cases.)
< Add a Image here, where on left show the button to press and on right of this image, show the Scan Modal >

**Step 4 :** There are already two predefined board for your convenience as an example. Feel free to delete or edit the boards and create your own boards from the Configure Board Settings. Enjoy !

---

## Basic Information

> The detailed Documentation on how to use the Task Board efficiently can be found here : [Task Board Documentation]()

### Task Formats

This plugin will only detect and work with the checkbox items/tasks which are in the following format :

```
- [ ]
```

If you dont want this plugin to detect your tasks, you are free to use the below format to define your tasks/checkbox items :

```
* [ ] 
+ [ ] 
```

### Marking as Complete

Marking a Task as complete from the board is real-time, as soon as you will mark or unmark the task, the changes will be instantly made in the parent markdown file.
![Realt Time changes for marking task complete](assets/MarkTaskComplete.gif)

### Editing a Task

Edit task directly from the Edit Task Window. You can add different properties to the task, add more subTask, add or edit description to the task. And the changes will be return to the parent markdown file exactly the way you see it in the preview.

### Deleting a Task

Directly delete unwanted task from the board using the delete Icon. The task will aslo be deleted from the parent markdown file.

### Applying Filters

Apply Board filters to filter out and see the urgent tasks on the board with ease. Filters for Columns coming soon.

---

## Upcoming Features

- **Task Sorting :** Sorting feature for each individual Column.
- **Task Searching :** Search any task from any board.
- **New Column Type :** Similar to the `Dated` and `Tagged` type of columns, a new column type on `priority` will be added.
- **Drag N Drop for Tasks :** User will be able to drag and drop tasks from one column to another for easy editing fields.
- **Temporary Task :** User will be able to add a temporary task which is not required to be saved in any file.
- **New Board Type :** A new type of Board knows as `Markdown` will be added, which will work with a single markdown file, similar to the Kanban Plugin.
- **Comments and Activity :** From the Task Popup window, you can add comments to the task, which will help you to document everything you were doing while working on this task, similar to Github Projects Kanban boards.

---

# How to Contribute

You can contribute to this project by :

**1. Requesting a new feature or suggesting a change :** [How to create a new request]().

**2. Improving the old translated languages or add a new language :** [How to Contribute for Language Translation]().

**3. Contribute to the Development of the plugin Code :** : [How to join the plugin developme]().

---

## Motivation for the Project

I always used the [Kanban Plugin]() to manage my tasks. And it use to work nice for me with all the amazing features. But as soon as I came across the [CardBoard Plugin]() eveything changed. The idea of adding tasks anywhere in your vault and managing them from a single board amazed me. While using kanban plugin the issue was, i wasnt able to add tasks directly to any markdown file, i was required to use the Kanabn Board only to add/edit my tasks, and it use to keep all this tasks in a single markdown file. I immediately switched to the CardBoard plugin after I came across it. But after using it for few days, i realized there are few important features this plugin is lacking and hence I went to first contribute to the main project, but I wasnt familiar with the elm files, hence decided to start my own plugin.

While development I took inspirations from CardBoard and Kanban plugin as well as many feature ideas from [GitHub Project KanBan board](). I hope I am able to give the best of all this three plugins into one, and will be improving this further.

> Note for me :  Dont make this readme so big, so the user will keep scrolling also difficult to load. Only put basic things to get user going, rest everything put in docs/ folder.
