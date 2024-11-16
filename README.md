# Sort Imports by Line Length

Organize your imports effortlessly!

This extension helps you tidy up that bulk of imports at the top of your file, for a nicer look and feel.

- 🧹 Sort imports in ascending order by their line length for a cleaner look.

---

<span style="font-size: 0.8em;">*Only supports .py files for now, see [Coming Soon](#coming-soon) section for more*</span>



## Features

Use the command 'Sort Imports' or use the shortcut `Ctrl+Alt+I` to sort all imports in your file

![Sort Your Imports!](demo.gif)

## Keyboard Shortcuts

This extension provides the following default keyboard shortcuts:

- `Ctrl+Alt+I` (Windows/Linux) or `Cmd+Alt+I` (Mac): Run the import sorter command.

### Customizing Shortcuts

You can customize the keyboard shortcuts by modifying the keybindings in your **keybindings.json** file.

1. Go to **File > Preferences > Keyboard Shortcuts** or press `Ctrl+K Ctrl+S`.
2. Search for `linelength-import-sorter.sortImports`.
3. Right-click the command and select **Change Keybinding**.
4. Enter your preferred key combination.

Alternatively, you can edit the **keybindings.json** file directly:

```json
{
    "key": "Ctrl+Shift+I",
    "command": "linelength-import-sorter.sortImports",
    "when": "editorTextFocus"
}
```

## Coming Soon
- Sort in order of descending line length
- Sort blocks with commented imports
- Sort within a selected chunk of text
- Support for Javacript
- Support for Arial and Helvetica fonts (coming not so soon because who even codes in arial or helvetica? :) 


## Supported Fonts and Languages

Currently only works with python (🐍`.py` files) and <span style = "font-family: courier new;">monospace</span> fonts

## Release Notes

### 0.1.0
Initial Release

## Credits
Development and Logo Design by [Youssef Tarek](https://github.com/Youssef1241/import-sorter)

If you face any problems or would like to suggest new features, just [open an issue on the repo](https://github.com/Youssef1241/linelength-import-sorter/issues), or leave a review on the [marketplace](https://marketplace.visualstudio.com/items?itemName=lavish-studios.linelength-import-sorter&ssr=false#review-details)
