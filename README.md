brackets-occurrences-marker
===========================

Brackets [http://brackets.io/] extension that marks occurrences of a selected text or the word under the cursor. The occurrences of the word are marked with a small delay so that you can continue uninterrupted editing.


Installation
------------

Install using Extension Manager in the File menu.

If you wish to manually install the extension you can use two options:

1. Use Download ZIP to download zipped extension from github and then open Extension Manager in Brackets and drag the file there

2. Use Download ZIP to download zipped extension from github and then open Extension Folder from Brackets (Help -> Show Extension Folder). Unzip the file into the user subfolder.


Usage
-----

The extension has its own preferences dialog. Go to (Edit -> Occurrences Marker Preferences). You can enable/disable the extension, exclude certain file types, choose marking mode and setup how to mark the occurrences.

Selected text is marked at once. Marking the word under cursor can be delayed to allow normal editing.


Change Log
----------

2016-07-05
- Exclude preferences are now an array. You can clean old thevirtualeuoccur.preferences.exclude_* from your brackers.json
- Background color setting can contain CSS styles
- Initial background setting is: background-color: #555; opacity: 0.7; border-radius: 6px;

2016-01-11
- Allow time interval to be set from 0sec to 10sec.
- 0sec interval wil cause instant marking.
- Default value is set to 0.2sec.

2016-01-07
- Added configurable time interval.
- Fixed unmarking.
