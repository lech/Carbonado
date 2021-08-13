# [Carbonado](https://en.wikipedia.org/wiki/Carbonado) - A clean icon theme for [Inkscape](https://inkscape.org/).

![Carbonado - A clean icon theme for Inkscape](carbonado.png)

## About

Carbonado is a complete icon replacement for Inkscape 0.92.x which was largely inspired by the [tool icons originally developed by Nick Saporito](http://logosbynick.com/new-icons-for-inkscape/). Nearly all of the replaceable Inkscape icons have been redrawn for a cleaner, minimal Inkscape experience.


## Release information

- 08/12/2021 - DISCONTINUED! This is being archived as a new branch `Grey(0.9x)`
- 01/01/2018 - Initial release


For newer Inkscape releases, please reference the main repo.

## Motivation & Design

The idea behind this icon set was to flesh out a minimal icon style which Nick had started. My primary focus was for it to blend in across all platforms. Inkscape is a great tool with powerful features, however the default icon set has not aged very well over time and some may find its design language initially confusing. Ultimately I wanted to create a crisp icon set that helps define Inkscape functions cleanly and look great at the same time.

## Make your own

Feel free to fork or use this set as a starting point for your own theme, the grids and groundwork are already prepared for you. Additionally, the [Themable](http://wiki.inkscape.org/wiki/index.php/Themable_icons) and [Tangoified](http://wiki.inkscape.org/wiki/index.php/TangoifiedIcons) icon pages found on the Inkscape wiki contain a comprehensive list of icon names, descriptions along with other useful Inkscape information.

## Known Issues, bugs and other errors

When creating this set I did not immediately take into account that some of the icons are pushed to sizes smaller than 16 x 16 pixel dimensions. As a result, some of these icons appear less recognizable. Rumor has it that there will be changes in how icons will be displayed in the future, for now these will be left as-is and may be revisted at a later date.

Another known issue is that some icons are rendering blurred. I'm not sure if this is an issue with rendering these icons specifically or the byproduct of something else. Path tools > difference and intersection menu items are good examples of this blurring bug. Setting `Preferences` > `System` > `Pre-render named icons` fixes the few broken/blurred icons but creates other new blurred icons after a restart.

Below is a complete list of icons (on Windows) which will have to be solved by the Inkscape Devs before they can be used by any icon theme.

The following icons have a broken or an incorrectly referenced icon:
 - **XML editor**
  - New element
  - New text node
  - Duplicate node
  - Delete node
  - Indent node


Incorrectly assigned icons:
- Create 3D Boxes
  - X, Y and Z values all display as the same icon.


The following icons currently have no working override and cannot be replaced in Inkscape 0.92.x on Windows (Mac and Linux may display different results):

 - **File menu**
  - New
  - Open
  - Save / Save as
  - Print
  - Document properties
  - Close
  - Quit


 - **Edit Menu**
  - Cut
  - Paste
  - Find/Replace
  - Delete
  - Preferences


 - **View menu**
  - Swatches
  - Fullscreen


 - **Text menu**
  - Check spelling


 - **Magnify context bar**
  - Zoom in
  - Zoom out
  - 1:1


 - **Objects window**
  - Move up/down to top/bottom arrows


 - **Swatches window**
   - Swatches dialog icon


 - **Miscellaneous**
  - Star and poly, Spiral and Draw freehand line tool context bar - Reset shape (brush)
  - Warning icon used for Mesh tool
  - Select all objects (Select and transform menu)

## Installation and usage

**Warning:** You may potentially damage your Inkscape installation! If you are not comfortable with this then do not proceed.

Before you begin, make proper backups of the files you will be overwriting in case you ever want to revert any changes. Making changes to these files may require administrative rights, consider yourself warned.

Please reference the customization instructions located on the [Inkscape Wiki]( http://wiki.inkscape.org/wiki/index.php/Customizing_Inkscape) for additional assistance.

If you're comfortable with proceeding, let's locate your Inkscape `icons.svg` file. Note that you may need to show hidden system files on certain systems.

**Windows:** `C:\Program Files\Inkscape\share\icons`

**Linux:** `~/home/.config/inkscape/icons/`

- Rename and backup the default `icons.svg` file.
- Copy the Carbonado `icons_.svg` file into this directory and rename it to `icons.svg`.
- Restart Inkscape and enjoy your new icons.
