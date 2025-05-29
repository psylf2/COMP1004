HTML:

A screenshot of 100% accessibility score for the 'add vehicle' page from the browser developer tool. 100% accessibility needs to be achieved on all pages, but only one screenshot is needed. - Screenshot1.png in the zip file
A description of the changes you made to improve the accessibility score and where they are in
the code file - Added line breaks (the <br> tags) in each file after each input box.

CSS:

A screenshot of the webpage when the width is less than 500px. - Screenshot2.png in the zip file
A description of the code you add to achieve responsive layout and where they are in the code file (in which file from which line to which line). - Added media queries in styles.css on line 1 and line 43. This allows for the webpage to use different css code depending on the screen size.

Javascript and database:

A list of the conditions tested: always include at least one test that everything is performed correctly and include as many exceptions as you can. - In index.html line 42 tests whether the request is returned successfully. Line 21 checks whether both or none of the boxes are filled. In vehicle-search.html line 21 checks whether the box has an input. Line 37 checks whether the request is returned successfully. In vehcile.html line 23 checks whether any of the inputs are left blank. Lines 42, 48 and 73 check whether the request is returned successfully. Line 200 checks whether an identical record already exists (doesn't check personid as this will always be unique). Line 204 checks whether any inputs were left blank. Line 240 checks whether an input is empty, and if it is, disables the button.
