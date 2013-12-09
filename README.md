GPGAutoVerify
=============

Mac OS X Folder Actions to automatically download and verify gpg signatures


Requirements
------------

* GPGServices (included in [GPG Suite](https://gpgtools.org/gpgsuite.html))
* curl		 (should come with any os x)
* plistbuddy (should come with any os x)

Usage
-----

Double-click to install, then right-click on your Downloads folder and select 'Folder Actions Setup...' from the Services mneu. Pick 'VerifyGPG.workflow' from the list and also add 'DownloadSignatures.workflow' to automatically download file signatures when Safari starts a download.