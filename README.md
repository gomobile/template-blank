Blank HTML Template for Building Mobile Web Apps.
=================================================

Use this template to start with a simple `index.html` file for creating mobile
web apps. This Intel XDK project has just an `index.html` file with the basic
html, head and body tags required for building HTML5 mobile web apps.

The `icon.png` and `screenshot.png` files are not required by your project. They
are included for use by the Intel XDK template/demo panel and have no use within
an actual project. You can safely delete them from your project directory.

You can build a *packaged web app* using the Cordova build tiles (for Crosswalk,
Android, iOS and Windows). See the `intelxdk.config.additions.xml` file for
instructions on how to set the splash screen display time for a Standard HTML5
web app that is distributed as a *packaged web app* using the Cordova build
system.

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
build a *Cordova packaged app* for distribution via the Android, iOS and Windows
stores *if that app does not use any Cordova APIs*.

This template does not use any Cordova APIs. If you wish to add Cordova APIs to
your application you must first convert your project into a Cordova project. You
can do this by pushing the Cordova icon in the *Project Info* section on the
**Projects** tab. Or, you can create a new Cordova project using the appropriate
blank template or a Cordova demo or sample app as a starting point.
