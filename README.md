Blank HTML Template for Building Mobile Web Apps.
=================================================

Use this template to start with a simple `index.html` file for creating mobile
web apps. This Intel XDK project has just an `index.html` file with the basic
html, head and body tags required for building HTML5 mobile web apps.

The `icon.png` and `screenshot.png` files are not required by your project. They
are included for use by the Intel XDK template/demo panel and have no use within
an actual project. You can safely delete them from your project directory.

You can build a *packaged Cordova web app* that can be submitted to a store
using the "Cordova Hybrid Mobile App Platforms” build tiles (for Crosswalk,
Android, iOS and Windows). The `intelxdk.config.additions.xml` file can be used
to include options that control your *packaged Cordova web app* builds. For
example, you can set the splash screen display time for a packaged Android or
Crosswalk Cordova app using this file.

If you see a "*Failed to load resource: net::ERR\_FILE\_NOT\_FOUND*" message
caused by the `cordova.js` script file in your `index.html`, do not be alarmed.
The `cordova.js` script is *only required* if you choose to convert your
"Standard HTML5 Project" into a "Standard HTML5 + Cordova Project."

You can:

-   safely ignore the "*Failed to load resource: net::ERR\_FILE\_NOT\_FOUND*"
    error message

or

-   comment out this script line if you will not be converting your project into
    a Cordova app that uses Cordova APIs.

The `cordova.js` script will be needed if you choose to convert your project to
a *Cordova project* and wish to utilize any Cordova APIs. It is not required to
build a *Cordova packaged web app* for distribution via the Android, iOS and
Windows stores *if that app does not use any Cordova APIs*.

This blank template does not require any Cordova APIs. If you wish to add
Cordova APIs (aka Cordova plugins) to your application you must first convert
your project into a Cordova project. You can do this by clicking the Cordova
icon in the *Project Info* section on the **Projects** tab. Or, you can create a
new Cordova project using a Cordova blank template or a Cordova demo or sample
app as a starting point.
