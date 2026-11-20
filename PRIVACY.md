# AlwyIDM privacy policy

Last updated: November 20, 2026

This policy covers the AlwyIDM browser extension and the AlwyIDM app for Windows.

## What the extension handles

When you start a download, or click the download button on a video, the extension passes the following to the AlwyIDM app running on your own computer:

- the file's link and name
- the page it came from
- the cookies and browser user agent for that site, so downloads that need you to be signed in keep working
- a checksum, if the page shows one

When you choose "Grab links with AlwyIDM", it also passes the links found on that page.

To offer videos for download, the extension watches the browser's network requests for video and audio streams, and it notices clicks on download links so it can hand them to the app.

## Where that data goes

All of this goes from your browser to the app on the same computer through Chrome's native messaging. It never leaves your computer and is not sent to us or to any other server. The app uses it only to download the file you asked for. Cookies are kept in memory for that download and are never written to disk.

We don't sell or share this data, don't use it for anything other than downloading, and don't use it for advertising, credit or lending decisions. AlwyIDM has no accounts, analytics, tracking or ads, and the extension makes no network requests of its own.

## Settings

The extension stores one setting, whether capturing downloads is turned on, in your browser's local extension storage.

## Changes

If this policy changes, the new version will be posted on this page with a new date.

## Contact

Questions can be opened as an issue at https://github.com/hishamalwy/AlwyIDM-Releases/issues
