ALEX PRESS — WEBSITE
====================

WHAT'S IN THIS FOLDER
---------------------
index.html    The "About Me" landing page
contact.html  The Contact page
work.html     The Work page (blank for now, waiting on Alex's list)
style.css     All the design (colors, fonts, spacing) for all three pages
images/       Put the headshot photo in here
README.txt    This file


TO LOOK AT THE SITE
-------------------
Double-click index.html. It opens in your browser. That's the whole site,
running on your computer. Nothing is online yet.


TO ADD THE HEADSHOT
-------------------
1. Save the photo into the images/ folder, named exactly:  headshot.jpg
2. Open index.html in a text editor.
3. Find these two lines (about halfway down):

     <div class="headshot-placeholder">Headshot goes here<br>(images/headshot.jpg)</div>

     <!-- <img src="images/headshot.jpg" alt="Alex Press" class="headshot"> -->

4. Delete the first line entirely.
5. On the second line, delete the "<!--" from the front and the "-->" from
   the end, leaving just:

     <img src="images/headshot.jpg" alt="Alex Press" class="headshot">

6. Save, then refresh the browser.

(If the photo is a .png instead of a .jpg, change "headshot.jpg" to
"headshot.png" in that line.)


TO ADD THE REAL CONTACT DETAILS
-------------------------------
Open contact.html and replace the ALL-CAPS placeholders:

  EMAIL@EXAMPLE.COM   ->  her actual email address
  USERNAME            ->  her actual Twitter/X handle, then her Instagram handle


TO FILL IN THE WORK PAGE
------------------------
Open work.html. Inside the big comment block, there's a template. For each
piece, add one line like this, above the closing </div>:

  <p><a href="https://LINK-TO-THE-ARTICLE">Headline of the piece</a><br>
  Publication, Month Year</p>

Newest at the top. Send me the list and I'll do it in one go instead.


TO CHANGE ANY OF THE WRITING
----------------------------
Open the .html file in a text editor and type over the words. Anything
between < and > is code — leave those alone and only change the plain
English between them.


TO CHANGE HOW IT LOOKS
----------------------
Everything visual is in style.css. The font size is set near the top as
"font-size: 16px" — that is exactly 12 point. Making it bigger or smaller
there changes it across both pages at once.
