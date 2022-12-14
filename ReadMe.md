# Learning HTML, CSS and JS with Ady

 Description here...
 
## Folder Structure
```text

Root -+- index.html
      |
      +- ReadMe.md
      |
      +- about folder -+- index.html
      |
      +- assets  -+- js -+-
                  |
                  +- css -+- site.css
                  |
                  +- img -+-
                  |
                  +- media -+-
```


## .gitignore
Create .gitignore with require file patterns.
> Use the plugin: .ignore in JetBrains IDEs
> 
>`CTL`+`ALT`+`S` (on Widows) to open settings
>
> Click on Marketplace to search for Plugins not installed.
> 
> In the search box at the top type in a word that may be part of the plugin needed, eg. ignore
>
> Locate the option and click INSTALL
> 
> Sometimes the IDE will need to restart to apply the changes.

## .keep
This file is used to force folders that are 'empty' to be committed...


Add to any folder you need to be added to version control but may not be using immediately.


Create it as a New Text file with the filename `.keep` .


## Useful Plugins

- .ignore
- CSV
- Rainbow Brackets
- Indent Rainbow
- JSON Helper
- Markdown Editor
- Paste Images into Markdown
- Zero Width Character locator
- Yet another emoji support
- GitToolBox
- Extra ToolWindow Colorful Icons
- Atom Material Icons
- .env file support

### Make Directory/Folder
In DOS command line (Terminal - Not Powershell):
``` shell
mkdir folder_name
```
Example:
``` shell
mkdir assets assets\img assets\js assets\css assets\media
mkdir about
```

Linux Example:
```shell
mkdir -p assets\{img,js,media,css} about
```