# Changelog
This file lists all the notable changes to this project.

## Theme Designer 19.2.1 - 2019-09-06

### New Features

* The **Visual Tree Window** displays the visual structure of the current preview in the tree view. Refer to the Visual Tree Window documentation topic for more information.

    **IMAGE**

* The **Properties Window** displays the selected element's properties. Refer to the Properties Window documentation topic for more information.
    
    **IMAGE**

* The **Ignore System DPI** tool ignores the system's scaling value and allows you to display the preview with 100% scale. 

### Bug Fixes

* <a href="https://www.devexpress.com/Support/Center/Question/Details/T754663/theme-designer-the-preview-window-is-corrupted-when-the-custom-theme-name-is">T754663</a> - Theme Designer - The preview window is corrupted when the custom theme name is Office2019Colorful.


### Enhancements

* **View in XAML** tool became the **Inspect Element** tool. With this tool, you can select a UI element to display its properties, XAML code, and its Visual Tree position. 

    **IMAGE**

* The palette color's tooltips added to the CodeView Window's Intelligent Code Completion.

    **IMAGE**

### Changes

* The **Filter Colors** tool now displays only the colors the **selected element** uses. You can select an element using the Inspect Element tool or with the **Visual Tree Window**.

* Theme Designer now uses the Ribbon's Simplified mode.

    **IMAGE**

* The **Reset Layout** tool is moved to the Home ribbon tab.
* The **Views** ribbon tab is converted to the drop-down button and moved to the Home ribbon tab.

## Theme Designer 19.1.4 - 2019-05-27

### Bug Fixes

* <a href="https://www.devexpress.com/Support/Center/Question/Details/T743008/theme-designer-cannot-upgrade-a-theme-because-the-x-namespace-prefix-is-not-defined-in">T743008</a> - Theme Designer cannot upgrade a theme because the 'x' namespace prefix is not defined in certain files.

## Theme Designer 19.1.3 - 2019-05-17

### Changes

* The 'Palettes' button in the Palette ribbon tab is renamed to 'Import'.

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
