# Export IconJar, IconSet, or ZIP Archive

Icon Mason allows you to export your icons, arranged on individual artboards (one icon per artboard) to either [IconJar](https://geticonjar.com), [IconSet.app](https://iconset.io), or ZIP archive format. To select the format, simply change the file extension in the File Name field in the IconJar Exporter dialog as shown below.

The icon files will be named using the artboard names. Additionally, the icon tags in the meta data file will be set to the file name split on the `dash`. So if you want to tag your icons automatically, name the artboards to dash-separated keywords.

## How to Save to IconJar format

In the Save As dialog, simply add the file extension `.iconjar` to the file name. Icon Mason will forma the archive appropriately when it is exported.
## How to Save to IconSet.app format

In the Save As dialog, simply add the file extension `.set` to the file name. Icon Mason will forma the archive appropriately when it is exported.

## How to Save to ZIP archive format

In the Save As dialog, simply add the file extension `.zip` to the file name. Icon Mason will forma the archive appropriately when it is exported.

When exporting to ZIP format, the icons will be copied to a folder named `icons` inside the ZIP and the archive metadata will be stored in a file named `META.json`.

![Export IconJar](https://docs.iconmason.com/images/export-iconjar-v2.png#half-size)
