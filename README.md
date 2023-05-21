Meal Finder This is a JavaScript code that allows users to search for meals based on ingredients and view the recipes and details of the selected meal. It utilizes the MealDB API to fetch meal data.

Features Search for meals by entering ingredients. Display a list of meals that match the entered ingredients. View the recipe and details of a selected meal. Play a video tutorial for the meal (if available). Usage To use this code, follow these steps:

Include the following HTML structure in your web page:

html Copy code Search

Close
Add the JavaScript code to your web page.
The JavaScript code will handle the event listeners and perform the necessary API requests to retrieve meal data.

Code Explanation The code selects necessary elements from the HTML using document.getElementById and document.querySelector methods. Event listeners are added to the search button, meal list items, and recipe close button. When the search button is clicked (getMealList function), a request is made to the MealDB API to fetch meals that match the entered ingredients. The resulting meals are displayed in the meal list. When a recipe button is clicked (getMealRecipe function), a request is made to the MealDB API to fetch the recipe details for the selected meal. The details are displayed in a modal. When hovering over a meal item (getMealDetails function), the meal details are retrieved and displayed in the console. The mealRecipeModal function creates a modal with the recipe details, including the meal title, category, instructions, image, and a link to a video tutorial. The showTitle function displays the meal category in the console. Feel free to customize and modify the code to fit your specific needs. Enjoy exploring different meals!
