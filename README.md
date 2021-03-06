MultiUploadDialog Addon for MODx revolution
=================

This addon replaces the outdated default upload dialog without changing the codebase of the old upload dialog. It's using the great FileAPI library (https://github.com/mailru/FileAPI). 

Files for upload can be added either via the 'Choose file(s)...'-Button or by drag'n'drop files onto the upload dialog. The dialog will show small preview-thumbs for all browser-supported image files. It respects the values for the system settings 'upload_maxsize' and 'upload_files' and prevents uploading of invalid files.
Single items can be removed by right clicking on the item-row and choose 'Remove Item' from the context-menu.

You can always go back to the default upload dialog by uninstalling the package or simply disable the 'MultiUploadDialogInjector'-Plugin.

If you want to have the dialog translated in your language, send me pull requests. I will be more than happy to add them.

Note that, for now, this is only tested with MODx revo 2.2.12 in newest Firefox, Chrome and Opera. But it should work back to 2.2.0.

<img src="https://raw.github.com/thomasd/MultiUploadDialog/master/screenshots/screen2.png">
