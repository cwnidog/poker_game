poker_game
==========

The project was to extend a poker game from a SAMS guide in some way. The base code was coped from the web. I then added the Grid 960 system and provided containers for the cards and hold buttons. I tried adding 5 new containers, each holding a card image and its associated hold button, but this greatly interherred with the base code's reliance on the order that images appear in documents.images[], so I left it alone and went back to having the cards and buttons separate. I did take them out of the table that they were in, the table was used for layout and the Grid 960 system provides other, better ways to do layout. I also pulled teh Javascript out of the HTML file and into a separate javascript file, poker.js. I also added event listeners to teh hold and deal/draw buttons, but could not get them to function properly.

I'm a bit disappointed that I wasn't able to get all the things I wanted to add into the code, but I was able to accomplish the main goals of separating the Javascript from the HTML and using grids for layout instead of tables. In addition, while I didn't get all I wanted to done, I learned a great deal about grids and event listeners in debugging.

For references, I used the textbooks, Dexter and Ryan also assisted. For web resources I used mainly stackoverflow.com and www.w3schools.com.
