# GiphyApp
Link To Live Project: https://vast-caverns-81496.herokuapp.com/

~~~~~
Technologies Used:
*HTML
*CSS
*Giphy API
*Bootstrap
~~~~~
![](https://media.giphy.com/media/Q7zHhhkcHsEeI/giphy.gif)

### Overview
I used the GIPHY API to make a dynamic web page that populates with gifs of user's choice.

### Set-up

* User GIPHY parameters: 
		* `q`
		* `limit`
		* `rating`

	* Maked sure to used public API Key is [provided here](https://github.com/Giphy/GiphyAPI#overview). 
  
### Instructions

1. Created an array of strings, each one related to a topic of interest. Save to a variable called `topics`. 

2. Your app takes the topics in this array and create buttons in HTML.

3. At the click of the button, the page grabs 10 static, non-animated gif images from the GIPHY API and place them on the page. 

4. When the user clicks one of the still GIPHY images, the gif should animate. If the user clicks the gif again, it should stop playing.

5. Under every gif, display its rating (PG, G, so on). 

6. Added a form in page that takes the value from a user input box and adds it into your `topics` array. Made a function call that takes each topic in the array remakes the buttons on the page.

7. **Rejoice**! You just made something really cool.

----------

## Copyright
Coding Boot Camp (C) 2016. All Rights Reserved.
