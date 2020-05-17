# vsconfig
Visual Studio Code configuration for django



## Shot discription:

### To create settings.json


`ctrl+shift+p`

`python:Select Interpreter`



### To create launch.json:


`ctrl+shift+p`

`more`

`Django`


### To create project.code-workspace:


`File` > `Add Folder to Workspace...`

`File` > `Save Workspace As...`

choose a name for this file for example `project`



## Long discription:


to create `settings.json`  ---->    just press `ctrl+shift+p` (this will open command pallete)

type `python:Select Interpreter`

This will look for availabel interpreter in your system.
choose one Interpreter and it will gentrate a file  `settings.json` inside `.vscode` directory


Click on `debug` icon(4th one on the left corner) -->   click on `create a launch.json file`
 
 the pop up search bar like will apear which is a `debug configuration bar`
now under debug configuration bar click on `more`
(if no other menu appear it means you havn't set your python interpreter)

click on `django`

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


<a href="https://github.com/satindersharma/django-getting-started" target="_blank"><h3>Click here to get started with django</h3></a>
