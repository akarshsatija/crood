TODO
----

## Bugs

* Add Humane for error notifications
* The folder input shows and then goes away on page load
* The syntax colors didn't show once, because editor wasn't defined in line:
  if (content !== editor.getValue()) {
* The whole page goes white after showing an empty page first

## Features

* Tests!
* Overwriting file with unmergeable changes should alert user
* Moving away from unsaved file must alert user
* Chrome extension
* Plugin architecture
* List of recent files
* Maintain Undo history correctly across files. Maybe save that to localStorage
* Options menu inside file's li element to rename, copy, etc
* Drag and drop move to different folder
* Run command in local folder's command prompt
* Make an installable component that enables a hosted version of this to save to local
* When moving up a folder, highlight the last folder for a short while
* Real-time updates from server about changes in file system
* Show breadcrumbs below folder path
* Make dragging files on top of windows work
* Make /create create new files as well as folders