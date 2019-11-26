This repository covers the following recipe from code.activestate.com:

[FRAME WITH BORDER COLOR FOR TKINTER
](https://code.activestate.com/recipes/580735-frame-with-border-color-for-tkinter/)

*Created by Miguel Martínez López on Sat, 17 Dec 2016*

This trick show how to add a border color to frame. These are the important configurations:

```
highlightbackground="your border color here"
highlightcolor="your border color here"
highlightthickness="the border width"
bd=0
```

## Usage

If you already have the [State Tool] installed you can simply run

```
state activate ActiveState-Recipes/recipe-580735-frame-border-color-tkinter
```

If you do not have the [State Tool] installed you can use the following convenient one-liner.

Linux: 
```
sh <(curl -q https://platform.activestate.com/dl/cli/install.sh) -n -f && state activate --path $HOME/ActiveState-Recipes/recipe-580735-frame-border-color-tkinter ActiveState-Recipes/recipe-580735-frame-border-color-tkinter
```

Windows: 
```
powershell "Set-Item -Path Env:NOPROMPT_INSTALL -Value 'true'; IEX(New-Object Net.WebClient).downloadString('https://platform.activestate.com/dl/cli/install.ps1')" && state activate --path %APPDATA%/ActiveState-Recipes/recipe-580735-frame-border-color-tkinter ActiveState-Recipes/recipe-580735-frame-border-color-tkinter
```

macOS: not yet supported

[State Tool]: https://www.activestate.com/products/platform/state-tool/