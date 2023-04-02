# Script Runner

## Description
Script Runner is a Mac utility app that is intended to allow you to run scripts without opening a terminal session.

Standard options for execution involve terminal sessions:

- If you set a script file's executable bit (e.g. `chmod +x myscript.sh`), you can execute it from a terminal.
- If you rename such a script to a `.command` file (or even remove the file extension), opening it from Finder will execute the script in a terminal window.

With Script Runner installed, you can rename your script to have a `.shx` (*shell-executable*) or `.rsh` (*run-shell*) file extension. When such a file is opened, Script Runner will execute the script instructions it contains, but it will do so in the background - without a terminal window being displayed.

The example folder in this repo contains an example file which will speak a sentence when executed; you can view the file content to verify the shell script code that will execute.


## Installation
1. Download the `Script Runner.app.zip` file from [the latest release in this repository](https://github.com/sylumer/scriptrunner/releases).
2. Unzip the zip file to get the `Script Runner.app` file.
2. Move the `Script Runner.app` file into your `Applications` folder.

# License
- [Application license](https://github.com/sylumer/scriptrunner/blob/main/.github/license.md).

## Donate
If you do find this app useful and want to say thanks with a coffee, you can do so here...

<a href="https://www.buymeacoffee.com/sylumer" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
