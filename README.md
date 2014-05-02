# 1080p-geo-person-shuffle

This is a stand-alone HTML5 web application which can query 
the API of a CIP Reporting server for person views to display 
on a full-screen 1080p display.

The application includes several visualization engines which
are applied randomly to the available views.  Each visualization
engine includes geo-spatial mapping of locations.

To use the application simply extract this archive on the host
or place this archive onto a web server and open the following
URL in an HTML5 capable web browser:

[Path to Files]/apps/1080p-geo-person-shuffle/index.html

NOTE: If you use the files locally (not on a web server) there
are issues with IE and Firefox.  IE does not allow HTML5 local
storage with local files which causes an error and the application
does not load.  Firefox does not allow loading fonts with local
files which can be changed in the security settings of Firefox
which results in the top menu glyphs not loading.

Ultimately this application will work better when served by a
web server across all browsers.  Google Chrome works great in all
environments.  

Full screen this web application with F-11 in all major browsers
for optimal display.
