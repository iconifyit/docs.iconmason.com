# Import IconJar, ZIP, IconSet, or Folder

Icon Mason can import icons from an IconJar archive, [IconSet.app](https://iconset.io) archive, ZIP archive, or a folder of SVG icons. Click the `Import IconJar` button (highlighted below) and follow the prompts. Once you have selected your IconJar, IconSet.app, ZIP, or folder of SVG icons, each icon will be imported and placed on its own artboard. The artboard name will be set to the file name, minus the file extension.

Keep in mind that Illustrator, as of October, 2020 allows a maximum of 1,000 artboards. In version 1.0 of Icon Mason, if your IconJar, ZIP, or folder contains more than 1,000 icons, only the first 1,000 will be imported. In a future version of Icon Mason we will have the extension create as many new documents as are needed to import the full icon collection.

## ZIP archives

In order for Icon Mason to import a ZIP archive of icons, the icons must be contained inside of a folder named `icons` inside of the ZIP archive.

*UPDATE*: In version 1.0 of Icon Mason, the ZIP archive must contain a folder named `icons` inside of it. Starting with version 1.1, ZIP archives can contain any number of folders and files. The only requirement is that there must be at least one SVG file with the extension `.svg` present in the ZIP archive.

![Import IconJar, ZIP, or folder](https://docs.iconmason.com/images/import-iconjar.png#half-size)


## IconSet archives

IconSet is a proprietary app format based on the ZIP format. You can learn more about the IconSet app at https://iconset.io. IconSet.app format was added in version 1.1 of IconMason. If you have an earlier version the format is not compatible.

## Cross-platform support
IconJar is a Mac OS-only format. ZIP and IconSet archives are supported by both Mac and Windows.