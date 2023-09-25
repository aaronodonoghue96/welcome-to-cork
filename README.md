# welcome-to-cork
A website about things to do and see in Cork


Fixed Bugs:

Links in nav bar were displaying in standard blue/purple with underline and bullet points because CSS link was not updated to account for the fact style.css was moved to the css folder. The path is now updated in all pages, and the links are displaying correctly.

Some captions in pictures.html page were displaying in a different column to their image if the image was at the end of the column because the media queries used column-count to divide the grid into columns, which did not treat each div containing an image and its caption as a unit. This has been fixed by using flexbox to display the images (together with their captions), in rows instead of columns.

Unimplemented Features:

There was originally going to be a timetable section on the thingstodo.html page with timetables for the Cork City Bus Tour and transport to locations of tourist attractions in Cork such as Blarney and Midleton, but this was scrapped to avoid clutter on the page.