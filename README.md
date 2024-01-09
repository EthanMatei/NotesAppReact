# React + TypeScript + Vite + React Router + React Bootstrap

This Project uses the VITE React typescript template for the user to have a base to build the project on and a web server to test

using react-router I was able to route to the different pages and create an element that can be called upon arrival at that link

React Bootstrap helped do some styling as I wanted the notes to look somewhat styled though CSS wasn't the focus of the project


-Notes Main Page
The notes main page is where you can see the list of the current notes and a search bar for both tags and titles 
you will see 2 buttons in which you can create a new note or edit the current tags
upon clicking new note you are redirected to the new note page and that object is rendered
upon clicking edit tags a drop-down box overlays the screen with small X's to clear them is presented

-New Note Page
on the new note page, there are form inputs for both tags Body and Title
In the tags box, you can assign already made tags or create a new one that will enter the tags list when you save
at the bottom of this page, you can see the save and cancel buttons which respectively will either add the note to the note list or cancel the form and not add it to the list

-Edit Note Page
When you click on a new note you are brought to a new form that has the current values already loaded in their fields to edit 
here there is also a save and cancel button 
