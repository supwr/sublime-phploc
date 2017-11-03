Class created to consume Sebastian Bergmann's PHPLOC from SublimeText. This class was tested using phploc 2.0.4 and Sublime Text 3 in a Windows 7 environment.
Maybe you need to add phploc to the windows PATH

### INSTALLING

Download this to the sublime text packages folder, or create a new plugin
clicking on Tools/New plugin and paste the content of this file and name it
as you wish. Just remember it has to have a .PY extension

### MENU

You may also add it to the Sublime Text menu.
Just create a file and paste the content between the dashed line, removing the comment character. 
Name it Main.sublime-menu(no extension needed) and save it in the same folder this file is placed:

```
[
{
    "id": "edit",
    "children":
    [
        {"id": "wrap"},
        { "command": "phploc", "caption" : "Analyse PHP"}
    ]
}
]
```

### USE IT
To use it, just click on Edit/Analyse PHP, while editing this file.A new unsaved file will appear with PHPLOC's info of this file
