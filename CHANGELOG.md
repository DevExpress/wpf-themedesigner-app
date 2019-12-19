# Changelog
This file lists the important changes to this project.

## Theme Designer 19.2.5 - 2019-16-12

### New Features

* Command Line Interface (CLI) allows you to clone and export theme solutions. You can use the CLI on a build server and then build the theme solution with [msbuild](https://docs.microsoft.com/en-us/visualstudio/msbuild/msbuild).

    Refer to the <a href="https://docs.devexpress.com/WpfThemeDesigner/401518/command-line">Command Line Interface</a> topic for more information.

## Theme Designer 19.2.4 - 2019-25-11
### Bug Fixes

* <a href="https://www.devexpress.com/Support/Center/Question/Details/t835710/the-wpf-theme-designer-preview-is-not-displayed-if-the-target-version-is-17-2">t835710</a> - The WPF Theme Designer preview is not displayed if the target version is 17.2 


## Theme Designer 19.2.3 - 2019-12-11
### Bug Fixes

* <a href="https://www.devexpress.com/Support/Center/Question/Details/T830995/themedesigner-does-not-launch-the-complex-preview">T830995</a> - ThemeDesigner does not launch the complex preview


## Theme Designer 19.2.2 - 2019-01-10

### Bug Fixes

* <a href="https://www.devexpress.com/Support/Center/Question/Details/T816015/show-error-messages-when-the-output-window-is-hidden">T816015</a> - Show error messages when the Output window is hidden

* <a href="https://www.devexpress.com/Support/Center/Question/Details/T719715/theme-designer-preview-is-empty-in-certain-cases">T719715</a> - Theme Designer shows an empty preview in certain cases

## Theme Designer 19.2.1 - 2019-12-09

### New Features

* The [Visual Tree Window](http://docs.devexpress.com/WpfThemeDesigner/401169/workspace/visual-tree-window) displays the preview's visual element structure.

    <img src="media/Changelog/19.2.1-VisualTree-2x.png" width="50%" alt="Theme Designer 19.1.3 - Visual Tree Window"/>

* The [Properties Window](http://docs.devexpress.com/WpfThemeDesigner/401212/workspace/properties-window) displays the selected element's properties.
    
    <img src="media/Changelog/19.2.1-Properties-2x.png" width="50%" alt="Theme Designer 19.1.3 - Properties Window"/>

* The **Ignore System DPI** tool ignores the system's scaling value and displays the preview with 100% scale. 

### Enhancements

* A palette color's tooltips are added to the CodeView's Intelligent Code Completion pop-up window.

    <img src="media/Changelog/19.2.1-Code-Completion-2x.png" width="50%" alt="Theme Designer 19.1.3 - Code Completion Enhancement"/>

### Bug Fixes

* <a href="https://www.devexpress.com/Support/Center/Question/Details/T754663/theme-designer-the-preview-window-is-corrupted-when-the-custom-theme-name-is">T754663</a> - The preview window is corrupted when the custom theme name is Office2019Colorful

### Changes
* The **View in XAML** tool was replaced with the **Inspect Element** tool. **Inspect Element** allows you to select a UI element and display its properties, XAML code, and position in the Visual Tree.

* The **Filter Colors** tool now displays only the colors from the **selected element and its children**. You can use the Inspect Element tool or **Visual Tree Window** to select an element.

* The Theme Designer now uses the Ribbon's Simplified mode.

    <img src="media/Changelog/19.2.1-Simplified-Ribbon-2x.png" width="50%" alt="Theme Designer 19.1.3 - Ribbon Simplified Mode"/>

* The **Reset Layout** tool was moved to the 'Home' ribbon tab.
* The **Views** ribbon tab was converted to a drop-down button and moved to the 'Home' ribbon tab.


## Theme Designer 19.1.4 - 2019-05-27

### Bug Fixes

* <a href="https://www.devexpress.com/Support/Center/Question/Details/T743008/theme-designer-cannot-upgrade-a-theme-because-the-x-namespace-prefix-is-not-defined-in">T743008</a> - The Theme Designer cannot upgrade a theme because the 'x' namespace prefix is not defined in certain files.

## Theme Designer 19.1.3 - 2019-05-17

### Changes

* The 'Palettes' button in the Palette ribbon tab was renamed to 'Import'.

    <img src="media/Changelog/19.1.3-Ribbon-Palette-Tab-2x.png" width="50%" alt="Theme Designer 19.1.3 - Ribbon Palette Tab"/>

### Enhancements

* Internal enhancements and bug fixes.

## Theme Designer 19.1.2 - 2019-04-26

### New Features

* You can create new themes based on your custom theme at runtime. Refer to the <a href="https://docs.devexpress.com/WPF/400728" target="_blank">WPF Palettes</a> topic for more information.

* Export your current theme palette to a .cs file.

    <img src="media/Changelog/19.1.2-Ribbon-2x.png" width="50%" alt="Theme Designer 19.1.2 - Export Theme to a .cs file"/>
    
* Apply a predefined palette available in the current theme.

    <img src="media/Changelog/19.1.2-Ribbon-2x-Palettes.png" width="50%" alt="Theme Designer 19.1.2 - Predefined Palette List"/>

    
## Theme Designer 19.1.1 - 2019-03-22


### New Features

* Incremental build.

* The Output window now can display the  **Build Output**, **Preview Output**, and **Logs**.

    <img src="media/Changelog/19.1-output-window.png" width="50%" alt="Theme Designer 19.1 - Output Window"/>


### Enhancements

* When you close a theme solution, the Theme Designer remembers the files you had open previously and restores them when you re-open the theme solution.

* The application's layout has changed to borderless.

    <img src="media/Changelog/19.1-borderless-layout.png" width="50%" alt="Theme Designer 19.1 - Borderless Layout"/>

* Resolve Merge Conflicts - you do not need to use the KDiff3 tool to choose a file version.

    <img src="media/Changelog/19.1-resolve-merge-take-mine.png" width="50%" alt="Theme Designer 19.1 - Resolve Merge Conflicts"/>

* New **Show in Explorer** and **Copy Path** items in the CodeView window's context menu.

    <img src="media/Changelog/19.1-showinexplorer-and-copy-path-menu-items.png" width="50%" alt="Theme Designer 19.1 - New CodeView Menu Items"/>

* Visual Studio-Inspired syntax highlighting.

    <img src="media/Changelog/19.1-code-view-code-highlighting.png" width="50%" alt="Theme Designer 19.1 - New CodeView Syntax Highlighting"/>
