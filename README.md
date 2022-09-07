# vs code
<p align="center">
<a href="https://github.com/satindersharma/vscode">
<img src="https://github.com/satindersharma/all-images/blob/master/icons/vscodeicon.png" width="30%" height="30%" alt="Vscode icon">
</a>
</p>
# vsconfig

Visual Studio Code configuration for django

## folder structure be like
`.vscode`
   -  `launch.json`
   -  `settings.json`
   -  `tasks.json`
   


## Short discription:

### To create settings.json


`ctrl+shift+p`

`python:Select Interpreter`



### To create launch.json:


`ctrl+shift+p`

`Python` > `Django`


### To create tasks.json:

Run Build Task (Ctrl+Shift+B).

`Ctrl+Shift+B`


### To create project.code-workspace:


`File` > `Add Folder to Workspace...`

`File` > `Save Workspace As...`

choose a name for this file for example `project`


### set shotcut to folders to collapse


click on `Manage` (setting like icon on left lower corner) > `Keyborad Shortcuts`(or press `ctrl+k` and `ctrl+s` consecutively)

search     `workbench.files.action.collapseExplorerFolders`

`+` to add a shortcut


### Prevent closing of previous open window

click on `Manage` (setting like icon on left lower corner) > `Settings`(or press `ctrl+,`)


search    `workbench.editor.enablePreview`




## Long discription:


to create `settings.json`  ---->    just press `ctrl+shift+p` (this will open command pallete)

type `python:Select Interpreter`

This will look for availabel interpreter in your system.

choose one Interpreter and it will gentrate a file  `settings.json` inside `.vscode` directory


Click on `debug` icon(4th one on the left corner) -->   click on `create a launch.json file`
 
 the pop up search bar like will apear which is a `debug configuration bar`
 `Python` > `Django`
 
 (
when there is no Python then

under debug configuration bar click on `more`

(if no other menu appear it means you havn't set your python interpreter)

click on `django`
)

this will create a `launch.json` file




On every startup of vscode if think you virtual env is not working 

then just do 

`ctrl+shift+p` ( to open command pallete)

and

``` ctrl+shift+` ``` ( to open terminal)



### To create project.code-workspace:


`File` > `Add Folder to Workspace...`

`File` > `Save Workspace As...`

choose a name for this file for example `project`


this file contains the settings related to the currunt project

this is helpful incase you want some settings or configuration only for your current folder but not for all vscode global settings.



### format on save

setting > Format on Save 

check this field

Make this to true so the pritter will format the document.

### move the cursor to last working position

`Alt` + &larr;

### move the cursor to last working position bacword or forward

`Alt` + &larr; or `Alt` + &rarr;

settings > open folder in new window


### open folder in new window

settings > open folder in new window

dropdown to on 

### Stop closing the non changed tab

`workbench.editor.enablePreview`

`settings` > `workbench.editor.enablePreview`

uncheck to make changes(means set to false)


### enable emmet after vscode django extenstion

`setting` > click on `Extensions` > click on `Edit in settings.json`

add`"emmet.includeLanguages": {"django-html": "html"},`





### Move back to last cursor position
ctrl + u



### split
ctrl + \


### collapse all code

ctrl + k + 0



### expand all code

ctrl + k + j




### join lines

make selection of the lines which you want in one line

F1

search join lines

hit enter


### Switch between recent tabs

ctrl + Tab


### Run currunt line code

(this will run the code in a new python shell)
shift + enter

### Get out of the qoutes or get cursor out of the string

Ctrl + Shift + \



### Show/Hide panel(the cmd panel)

Ctrl + j



### Scroll Fast

alt + scroll



### move the cursor to error 

f8


### Go to the defination

`crtl+click` or `f12`





# add some cusotm key shortcut

go to 

File > Preferences > > Keyboard Shortcuts


search for Terminal Focus Previous Terminal

`workbench.action.terminal.focusNext`

add shotrcut `ctrl+shift+alt+.`



---


search for Terminal Focus Next Terminal

`ctrl+shift+alt+,`

`workbench.action.terminal.focusPrevious`



search for Tasks: Restart Running task

`ctrl+shift+alt+b`

workbench.action.tasks.restartTask


search for Collapse Folders in Explorer

`ctrl+shift+alt+c`

workbench.files.action.collapseExplorerFolders


```json

{
  "key": "ctrl+shift+alt+oem_period",
  "command": "workbench.action.terminal.focusNext"
}


{
  "key": "ctrl+shift+alt+oem_comma",
  "command": "workbench.action.terminal.focusPrevious"
}


{
  "key": "ctrl+shift+alt+b",
  "command": "workbench.action.tasks.restartTask"
}

{
  "key": "ctrl+shift+alt+c",
  "command": "workbench.files.action.collapseExplorerFolders"
}

```
new changes new changes

<a href="https://github.com/satindersharma/django-getting-started"  target="_blank"><h2>Click here to Get Started with Django</h2></a>
<p align="center">
<a href="https://github.com/satindersharma/django-getting-started">
<img src="https://github.com/satindersharma/all-images/blob/master/icons/django-logo-positive.png"  alt="Django icon">
</a>
</p>

