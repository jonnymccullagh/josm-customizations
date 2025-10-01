# josm-customizations
Some configs for my preferred JOSM setup.

## Map Paint Styles
This is useful for coloring the building types so you can see at a glance whether a building has been tagged as building:yes or more precisely as a shed, garage or house.
My stylesheet is a slight modification of the existing 'Colored Buildings.en' by riiga with a few more buildings common in Ireland.
### Usage
- In JSOM visit Edit > Preferences
- Choose the 'Map Paint Styles' menu
- Choose the '+' button to add a new style
- For the url use: https://raw.githubusercontent.com/jonnymccullagh/josm-customizations/main/styles/coloured_buildings_1.4.en.css
- Give the style a name and click OK
- Click 'Okay' to exit the Preferences dialog
- You hopefully have coloured buildings
![Alt text](./images/map-paint-styles.jpg "Coloured Building Outlines in JOSM")

## Presets
An XML backup of the custom presets I like to add to the JOSM toolbar for quick access.
### Usage
This can be added to JOSM using:
- In JSOM visit Edit > Preferences
- Choose the 'Tagging Presets' menu
- Choose the '+' button to add a new preset
- For the url use: https://raw.githubusercontent.com/jonnymccullagh/josm-customizations/main/presets/josm_presets_20230413.xml
- Give the preset a name and click OK
- Click 'Okay' to exit the Preferences dialog


## Toolbar Icons
I couldn't find a way to export the shortcuts I have on my toolbar so screenshotting here for future reference. In JSOM visit `Edit > Preferences > Toolbar`.
![Alt text](./images/toolbar-icons.jpg "Custom JOSM Toobar Icons")

## Keyboard Shortcuts
I like to use function keys as shortcuts to label buildings. It seems difficult to manage this in the `Edit > Preferences > Keyboards` 
![Alt text](./images/josm-keyboard-shortcut.jpg "Set Shortcut")

My alternative is to right-click the toolbar icon and choose 'Edit Shortcut'
![Alt text](./images/edit-shortcut.png "Edit Shortcut")
- untick `use default`
- untick `Disable`
- Choose the shortcut key e.g. F5
- choose **Okay**
![Alt text](./images/shortcut-f8.jpg "Set Shortcut")


