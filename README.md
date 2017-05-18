# Watergap


Bootstrap Website / SMS Twilio DEMO

Here is a link to the wordpress documentation: http://sites.bxmc.poly.edu/~lilliankorinek/webdev/index.php/2017/05/16/final-project-twilio-extension/

Here is a link to a Google Drive folder with images for the website: https://drive.google.com/drive/folders/0B9T54mwf52qUY2lVdXRrRm94R1U?usp=sharing

Due to poor internet connection where I am, I cannot upload large files to github at this time. Download the Google Drive folder and place
a folder called "images" in the "assets" folder next to bootstrap, css and js. This should provide the proper pathway to view the entirety 
of the project. 

To access live server, cd to "watergap" on terminal. Type "npm install"-- the package.json file lists the project's dependencies and will 
automatically install the necessary packages. Next type "node index.js." The site should then be running and terminal should notify you as well.
In Google Chrome type "localhost:3000." The website should show live on your browser. 

Issues: There is an issue somewhere in the code regarding the pathway between views/index.html and index.html. The node.js file (the file that hosts the live server) is written to prompt the html files placed in the "views" file. However, the CSS/JS does not follow that pathway and is written to edit an html page in the main project folder. As a result, the live hosted website lacks many of the css edits implemented by Bootstrap. Launch the independent <index.html> locally to see the full website; launch <views/index.html> to see the live hosted website. Hopefully, with some more trial/error I will be able to resolve this issue soon.

Future Plans: The navigation bar needs to be changed. Currently it is awkward and difficult to see when scrolling through different sections. 

A data section needs to be added to showcase consumers' responses to the Twilio survey. The development of that can be found at the link 
here: https://github.com/lilliankorinek/TwilioDemo

I'll be adding onto this project pretty regularly! Hopefully I can figure out a better system with this slow internet! Happy summer!
