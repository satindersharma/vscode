# vsconfig
Visual Studio Code configuration for django

## folder structure be like
`.vscode`
   -  `launch.json`
   -  `settings.json`
   -  `tasks.json`
   


## Shot discription:

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


search    "workbench.editor.enablePreview"




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


### open folder in new window
settings > open folder in new window
dropdown to on 

### Stop closing the non changed tab

workbench.editor.enablePreview

settings > workbench.editor.enablePreview
uncheck to make changes(means set to false)



<a href="https://github.com/satindersharma/django-getting-started"  target="_blank"><h2>Click here to Get Started with Django</h2></a>
