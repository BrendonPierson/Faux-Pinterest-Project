#NSS Group Project:  Faux Pinterest
An NSS group project with contributions from Brendon Pierson, Brittney Corona, Juan Rodriguez, and @pmconnolly80.  The assignment for this project was to create an open ended Pinterest-esque web app.  For our faux pinterest web app, users login and can see all the pins that have been added.  Users can click on any of the pins to add it to their board, or they can add it to a new board.  

Users can also add a new board and new pins.  To make a new pin the user can either enter the information in a form or try the beta function: enter a link to self-populate the information.  The selfpopulating function uses client side web-scraping through a CORS proxy to parse through the linked page's html for the relevant bits of information.  This function works great on well-optimized sites like [The Huffinton Post](http://www.huffingtonpost.com/entry/google-grocery-delivery-service-whole-foods-costco_55f022ffe4b03784e2772696?utm_hp_ref=technology), but struggles on poorly organized sites.

###Technologies used:
1. [Angular](https://angularjs.org/)
2. [lodash](https://lodash.com/)
3. [Bootstrap](http://getbootstrap.com/)
4. [Firebase](https://www.firebase.com/)
5. [jQuery](http://jquery.com/)
6. [Grunt](http://gruntjs.com/)
7. [CrossOrigin.me](http://crossorigin.me/)

###Requirements:
1. [Nodejs](https://nodejs.org/en/)
2. [Bower](http://bower.io/)

###Installation Instructions
1. ```git clone https://github.com/BrendonPierson/Faux-Pinterest-Project.git && cd Faux-Pinterest-Project/lib```
2. ```npm install``` May take a few minutes to download all dependencies, also runs bower install.
3. ```npm start``` This fires up the web server 
