#Objectives
- Practice pulling in Bootstrap 4’s CDN and using its class based styling.

##Setup
01. Create a new folder for these drills, title it Bootstrap 4 Drills
- Go ahead and initialize a git repository on this project so it will be available to view on your github account.
02. Create a README.md file, copy and past these drill instructions into that file.
03. Create an index.html page, use the keyboard shortcut to get the html doc started.
04. Go to the following link copy the cdn link and past it in the head of your html document.
- You now have connected the bootstrap cdn to your project and can begin using Bootstrap 4! Hooray.
05. Add a styles.css document, link it to your html document AFTER the bootstrap link.
####Containers and the Grid System
01. Add a div to your html document, using bootstraps container class, have this be a container.
02. To visually see what a container class does to a div, we will need to apply some styling to it in css. Let’s go to our css document and apply a background-color of blue and a height of 500px to anything with a class named container (Which for know should only be 1 element).
03. Change the class on the div from a container to a container-fluid. Refresh and take not of the differences. Once you are finished visually seeing the difference between the two, remove or comment out the styling in the css file.
04. Insert a div inside of the existing container div. Give this div a class name of row, then insert an h1 element inside of the row div. Have the text read *“First Boostrap Project”*.
05. Refer this link on the grid system to learn how rows and alignment work using bootstrap. Lets try to center align our h1, go to the following link to explore how to do so. (*Hint: Jump to the horizontal alignment section of bootstraps documents, you may need to adjust the amount of columns, 1 through 12, to keep everything on 1 line*).
06. Add a new div which will be another row of elements. Add 3 divs, give each some text of your choice and apply bootstrap styling to have 1 div appear at the start of the row, one in the center, and one at the end.
####Bootstrap Forms
01. Use this link for reference for the next section:
02. Create a form inside of the existing container but outside of any existing rows or other content (ask for help if nesting elements is confusing).
03. Have this form contain an input for an email and password. Make sure each input has labels!
04. Add 2 checkboxes to the form, one for cats and one for dogs.
05. Add 3 radios, have them say Cheese Pizza, Vegetable Pizza, and Meat Pizza
**Make Sure the form has a submit input!**
####Cards
01. Refer to this link for more information on cards.
02. Outside of the form but still inside of the container, create a basic card with a card body and have it have an h3 which will be a friends name, and a paragraph element containing a small piece of info on your friend. Create 6 of these cards.
03. Have them align so there are 2 per row.
04. Once you get them aligning 2 per row, change it so it is 3 per row.