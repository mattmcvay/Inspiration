Project Name: Inspiration

Running the program.
- Currently the program looks to perform the way it was intended using the Chrome browser.  Still working on 
getting Internet Explorer and Edge to display the pages as intended.
- Currently there is only 1 folder used to store the images.  Still working on getting the webpage working
as intended when all files are in a better folder structure.  Therefore, to run the program currently, 
leave all the files loose in the Inspiration folder with the exception of the images folder.  All images should
stay in the images folder.

Description:
This is a simple website that show cases inspirational quotes in a slide show.  The webpage opens to show all the 
slides in the slide show, but the user can click the link above to narrow the slides down to slides pertaining
to the categories of Spiritual, Sports, Business, or Entertainment.  When the user narrows the width of the widow to 
760 PX or less, the slides adapt to the screen and the 'All Slides' option is left viewable.  There are two buttons
at the top of the page to change the background color to either grey or blue if desired.

Custom CSS:
1.) button - this gives the buttons a grey background, a border width of 1.5px, font size to italic, and opacity 
    .4.
2.) header - this gives a font size of 22 px, text align of center, adds color, margins, and shadow.
3.) html - this makes the background a grey color and then adds the ability to transition to another color 
    with a slight delay.

Note: Some of the CSS was take from examples from the internet like w3schools, but I've altered them so much, its
      hard to say if many of them should be considered custom or not. However, the ones mentioned above are custom.

Custom JavaScript function:
1.) Lines 12 and 13 of index.html - colorChangeBlue(), colorChangeGrey();
    This changes the background color until a link is click on, then the background reverts back to grey.	  

Responsiveness:
1.) There is a custom media query in the CSS that enhances the user experience when the width is 760px or less.
    This is at the bottom of the CSS page.
