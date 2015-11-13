Selenium Standalone Image
=========================

This is a Docker image that runs selenium-standalone server for quick selenium
testing.  The image has Firefox installed along with a minimialistic desktop
environment called Fluxbox to make it easier to work with the browser.  Also
included is VNC for easy debugging of tests (this is exposed on port 5900, just
map it to a port in your root net namespace and use a vnc viewer).

To support Mac OS X's built-in VNC viewer, this now requires a password. The
password is `password`.
