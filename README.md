# Browser-Extension-for-Canvas-LMS-Template

This can be used as a browser extension template to get started with making theme modifications to the Canvas LMS.

This template currently provides a "Hello World" alert on all pages in Canvas and modifies the background color of the logo in the global navigation.

Currently no icons are used, but icons can be added if you plan to publish the browser extension and/or want to make it easier to identify when using it.

In manifest.json, currently the content_scripts only has one match pattern that matches all web pages to apply the initial JavaScript and CSS files. This can be modified to use different matching patterns to limit the pages on which files load. Additional JavaScript and/or CSS files can also be added and applied to different matching patterns as desired. Regular expressions can also be used to test the pathname within JavaScript files to help further limit when the code is executed.

To load the browser extension to work, you will want to download this repository and do the following:

- [Load in Google Chrome](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world#load-unpacked)
- [Load in Microsoft Edge](https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/getting-started/extension-sideloading)
- [Load in Mozilla Firefox](https://extensionworkshop.com/documentation/develop/temporary-installation-in-firefox/)

To learn more about developing browser extensions you can visit:

- [Develop Google Chrome Browser Extension](https://developer.chrome.com/docs/extensions/get-started)
- [Develop Microsft Edge Add-on](https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/getting-started/part1-simple-extension?tabs=v3)
- [Develop Browser Extension from Mozilla Firefox](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension)
