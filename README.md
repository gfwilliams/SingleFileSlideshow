SingleFileSlideshow
===================

A single-file slideshow that runs in a web browser and can be used on a Web Server without server-side scripting

Setup is as follows:

   * Save 'slideshow.html' into a file on your server/nas box in the root of your Photos folder, and ensure that it is hosted by a Web Server *that allows directory listing* (see below)

   * If you are running offline, you may wish to download jQuery to your server and change the file accordingly

   * Start a web browser on the device you want to use for the Slideshow, and enter the URL of the slideshow - for example http://192.168.1.234/media/Pictures/slideshow.html or maybe http://localhost/slideshow.html if it's your own computer.

   * Wait for a few seconds (it may take some time if you have a lot of pictures!), and then photos randomly selected from your entire library will be displayed every 10 seconds.

Currently the photos just appear suddenly when they are loaded. If you implement a nice CSS transition between them, please contact me - I'd love to improve what is here!

NOTES
======

* **Directory listing** means that when you go a a link like http://your_server/a_folder then if there's no `index.html`, all the files in that folder are shown in a webpage. Without this, this tool can't work.
* If using an iPad to view the slideshow, tap the button to the left of the address bar, then 'Add to Home Screen'. Then when you tap the icon on your home screen, the slideshow will open in Fullscreen mode.
