Penn Manor Speed Dial Extension
===============

About the code
--------------
This Chrome extension is made to quickly and easily access Penn Manor School
District web services.

This extension mirrors the [Penn Manor Speed Dial](https://github.com/pennmanor/SpeedDial) page to provide ease of access for Chromebooks and other devices with limited configurability.

One may download and install the extension from the Chrome Web Store: [link](https://chrome.google.com/webstore/detail/penn-manor-speed-dial/mjagkeellilgpdfininohfelkjjpnlgh)

Using from source
---------------
Simply clone the repository and navigate to chrome://extensions.

From within the extensions page, select 'Load unpacked extension' and install the extension from the filesystem.

Packing extension for Store upload
----------------------------------

Make the changes as necessary. Make sure to update the manifest.json file to increment the version number.

Then run the command:
```bash
# Replace <VERSION> with the version of the release, taken from the manifest.json file
zip -r pmextension-<VERSION>.zip {images,Ubuntu-R.ttf,icon.png,manifest.json,popup.html,store-icon.png,styles.css,styles2.css}
```

Then the .zip file can be uploaded to the Chrome App Store
