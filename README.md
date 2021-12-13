# Hang In There
​
This webpage uses preloaded data in the HTML, CSS and Javascript and user inputted data to allow users to generate random or create and save their own motivational poster! The hope of this product is to lift the user's spirit when they're searching for motivation!
​
​
​
## Contributors
​
Geena Jackson - [GitHub](https://github.com/gjax78)
​
Casey Halstead - [Github](https://github.com/chalstead16)
​
Geena and Casey partnered to create this project while at Turing School of Software and Design. We're excited to share our code with the coding community. Feel free to fork or create a pull request of this project to play around or add functionality. Let your creativity be your motivation!
​
​
​
## Technologies Used
​
**Built With**: Javascript, HTML, CSS and JQuery
​
**Web Browser**: Google Chrome/ Safari
​
**Text Editor**: Atom
​
​
​
## Project Roadmap
​
The Project Roadmap shows the iteration steps we completed in this project. Please note, we've included iteration steps beyond what was completed by the contributors listed above.
​
#### Iteration 0 - Main Page
​
- [x] When the page loads, we should see a poster with a randomly selected image, title, and quote
​
- [x] Every time the user clicks the Show Random Poster button, a new random poster is displayed.
​
#### Iteration 1 - Switching Views
​
- [x] When a user clicks the “Make Your Own Poster” button, we should see the form, and the main poster should be hidden
- [x] When a user clicks the “View Saved Posters” button, we should see the saved posters area, and the main poster should be hidden
- [x] When a user clicks the “Nevermind, take me back!” or “Back to Main” buttons, we should only see the main poster section
- [x] In summary: Be able to switch between the three views (main poster, form, and saved posters) on the correct button clicks
​
#### Iteration 2 - Creating a New Poster
​
- [x] On the new poster form view, users should be able to fill out the three input fields and then hit the Show My Poster button
- [x] When the Show My Poster button is clicked, several things will happen:
  - [x] Use the values from the inputs to create a new instance of our Poster class (part of your data model)
  - [x] Save the submitted data into the respective arrays (image URL into the images array, etc - all part of your data model) so that future random posters can use the user-created data
  - [x] Change back to the main poster view (hiding the form view again)
  - [x] Use the new instance of the Poster class (part of your data model) to display the newly created poster image, title, and quote in the main view on the DOM
​
#### Iteration 3 - Saving & Viewing Posters
​
- [x] When a user clicks the “Save This Poster” button, the current main poster will be added to the `savedPosters` array.
- [x] If a user clicks the “Save This Poster” more than once on a single poster, it will still only be saved once (no duplicates)
- [x] When a user clicks the “Show Saved Posters” button, we should see the saved posters section
- [x] All the posters in the `savedPosters` array should be displayed in the saved posters grid section
​
#### Iteration 4 - Deleting Saved Posters
​
*Note to reader:  This script does not currently have this funcationality, but we've included these steps for you to try on your own!*
​
- [ ] From the saved posters view, if a user double clicks a saved poster, it will be deleted
  - [ ] `onclick` functionality should not be used in any HTML code - all functionality should be through JavaScript.
​
​
​
## Instructions for Hang In There
​
1. Click this [link](https://gjax78.github.io/geena-casey-hang-in-there/) to load Hang In There. You will see a randomly selected motivational poster on the main page.
​
#### <img src="/Users/catherinehalstead/Library/Application Support/typora-user-images/Screen Shot 2021-12-11 at 9.58.52 PM.png" alt="Screen Shot 2021-12-11 at 9.58.52 PM"  />
​
​
​
### Generate Random Poster
​
1. Click "Show Another Random Poster" to generate a new motivational poster on the main page.
​
![Screen Shot 2021-12-12 at 5.50.09 PM](/Users/catherinehalstead/Library/Application Support/typora-user-images/Screen Shot 2021-12-12 at 5.50.09 PM.png)
​
​
​
### Make Your Own Poster
​
1. Click "Make Your Own Poster" to create your own poster. Clicking the "Make Your Own Poster" button will open the "Create your own motivational poster" page, as seen below.
​
   - To create your own poster, skip to step 2.
​
   - To go back to the main page, click "Nevermind, take me back!".
​
2. Copy and paste the image link address into the "Image url" input field.
​
3. Type your motivational title in the "Motivation title" input field.
​
4. Type your motivation quote in the "Motivation quote" input field.
​
5. Click "Show my poster" to see your custom poster on the main page.
​
![Screen Shot 2021-12-12 at 5.35.01 PM](/Users/catherinehalstead/Library/Application Support/typora-user-images/Screen Shot 2021-12-12 at 5.35.01 PM.png)
​
​
​
### Saving Your Own Poster
​
1. From the main page click "Save This Poster" button to save your newly created poster.
​
![Screen Shot 2021-12-12 at 5.44.05 PM](/Users/catherinehalstead/Library/Application Support/typora-user-images/Screen Shot 2021-12-12 at 5.44.05 PM.png)
​
​
​
### Viewing Your Saved Poster
​
1. To view your saved poster, click "Show Saved Posters". Note, you cannot save the exact same poster twice.
​
![Screen Shot 2021-12-12 at 5.47.08 PM](/Users/catherinehalstead/Library/Application Support/typora-user-images/Screen Shot 2021-12-12 at 5.47.08 PM.png)
