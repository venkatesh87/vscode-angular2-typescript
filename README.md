# VS Code Angular2 Typescript Files Generator

This extension allows you to add Angular2 typescript files including snippets to your VS Code project.

> Inspired by angular-cli (https://github.com/angular/angular-cli)
> Inspired by [Dominik Kundel](https://github.com/dkundel)'s [Advanced New File - Visual Studio Code Extension](https://github.com/dkundel/vscode-new-file) and [John Papa](https://github.com/johnpapa)'s [Angular 2 TypeScript Snippets for VS Code](https://github.com/johnpapa/vscode-angular2-snippets).
> Forked from[Sebastian Baar](https://github.com/sebastianbaar/vscode-add-angular2-files) VS Code Add Angular2 Files

![VS Code Angular2 Typescript](https://github.com/venkatesh87/vscode-angular2-typescript/raw/master/images/logo.png)

## Changelog

### 1.0.0
* Integrated angular-cli for file generation 


## Features

Right click on a file or a folder in your current project. 
You can find multiple options been added to the context menu:

Menu Options  |
---           | 
New Component |
New Directive | 
New Pipe      |
New Service   | 
New Module    |

Menu Options  |
---           | 
New Class     | 
New Interface |
New Enum      | 

**The naming of the files as well as the (boilerplate) snippets are based on the [official Angular2 Style Guide](https://angular.io/docs/ts/latest/guide/style-guide.html)**

## Installation

1. Install Visual Studio Code 1.5.0 or higher
2. Launch Code
3. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
4. Select `Install Extension`
5. Type `angular2 files` and press enter
6. Reload Visual Studio Code

# Disclaimer

**Important:** This extension due to the nature of it's purpose will create
files on your hard drive and if necessary create the respective folder structure.
While it should not override any files during this process, I'm not giving any guarantees
or take any responsibility in case of lost data. 

# License

MIT
