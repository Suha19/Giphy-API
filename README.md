# Giphy-API

#Instructions:

This app displays buttons related to a certain topic and allows you to add search terms to generate additional buttons that when clicked, accesses the GIPHY API and generates 8 static GIPHY images. Click on an image to pause or play the GIF.

![image](https://user-images.githubusercontent.com/47680905/57551704-53513980-732f-11e9-87d1-07c6f5da823e.png)

#Getting Started

Click on the link to see the completed assignment:
https://suha19.github.io/Giphy-API/

#Requirements:
The app takes the entered search term topics from a user input box and pushes them into array from which it creates buttons in the HTML. Clicking on a button grabs 8 static, non-animated gif images from the GIPHY API and places them on the page.
When the user clicks one of the still GIPHY images, the gif should animate.
If the user clicks the gif again, it should stop playing.
With every gif is displayed its rating (PG, G, etc.).

#Built With:
HTML
CSS Bootstrap
JavaScript to make the page dynamic
jQuery for Dom Manipulation
AJAX for API GET requests

#Code Explanation:
A form was implemented to take the value from a user input box and add it into the topics array.
CSS Bootstrap was used to arrange the page into columns and display the gifs in a gallery format.
AJAX Call to Giphy's API was created to access the images by topic entered.
