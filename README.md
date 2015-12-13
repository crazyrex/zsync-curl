# zsync-curl

Partial/differential file download client over HTTP.

Downloads a file over HTTP. zsync uses a control file to determine whether any blocks in the file are already known to the downloader, and only downloads the new blocks. 

This fork uses [libcurl](http://curl.haxx.se/libcurl/) in order to support __https__ and is mirrored from [Launchpad](https://launchpad.net/zsync-curl).
