# VS Code extension for GibbsCAM macro language
[Visual Studio Code](https://code.visualstudio.com/) extension for syntax highlighting of [GibbsCAM macro language](https://macros.gibbscam.com/index.php?title=Main_Page).

## Installation
From VS Code Extension page, select *Install from VSIX* and select `gibbscam-macro-language-x.x.x.vsix` from `build` folder.

## Test
From the workspace `VS-Code-extension-for-GibbsCAM-macro-language`, press *F5* to run the extension in debug mode.

## Build
In `src` folder, run command `vsce package --out ../build/` from a terminal. This will build de `vsix` package ready for installation.

## License
Please read file `src/LICENSE.txt`.