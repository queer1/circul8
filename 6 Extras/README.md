**Alternate Icons**

These icons are variations of already included icons + icons that I won’t include as default.

* Delete ~xx at the end of the folder name if it's there (e.g. com.agilebits.onepassword-ios~dark -> com.agilebits.onepassword-ios).
* Copy it to the Bundles folder inside Alternatives C8.theme.
* Copy Alternatives C8.theme to Library/Themes on your iDevice.
* Move to the top of the list in winterboard and activate.



**Blank icons**

* Use these for whatever you like



**Folder Icons**

* Add this repo in cydia: http://cydia.myrepospace.com/Vertex
* Find FolderIcons and install it (be sure that you get the new beta and not the old version)
* Copy the correct sized icons to User/Media/FolderIcons/Foregrounds
* Hold down on a folder until it wiggles and the settings badge pops up
* Click that and switch “show thumbnails” off
* Click on the foreground field and you should see the C8 icons on the bottom or on the next page for you to choose (swipe)
* Click on the icon you want, back and close.



**Preferences Icons**

Some Cydia apps settings icons will not theme with Winterboard.

* Go to /Library/PreferenceLoader and copy and backup the Preferences folder.
* Replace the icons in /Library/PreferenceLoader/Preferences with them from the C8 Preferences Icons folder.
* Same procedure with /Library/PrefenceBundles.



**Source Sans.font**

* Get BytaFont on Cydia
* Copy C8 Source Sans.font to var/mobile/Library/MyFonts (create directory if it isn't there)
* Activate in BytaFont



**Wallpapers**

* Visit this folder on your iDevice and click on the pngs inside the folders. 
* Save to camera roll and apply normally.



**Zeppelin logo**

* Get Zeppelin on Cydia.
* Copy circul8zeppelin to /Library/Zeppelin.
* Open settings/preferences.app and choose the icon in Zeppelin settings.



**Shared artwork**

Themes the share icons that winterboard won’t theme. Retina only.
This is editing system files so proceed at own risk. It’s very easy tough.

* Copy Shared@2x.artwork_circul8 into /System/Library/Frameworks/Ulkit.framework/ in your iDevice.
* Rename Shared@2x.artwork to Shared@2x.artwork_backup
* Rename Shared@2x.artwork_circul8 to Shared@2x.artwork
* Respring.
