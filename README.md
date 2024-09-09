# Recipe and Nutrition Information Prototype

This Python script demonstrates a simple prototype that helps users retrieve recipe information, ingredient details, and calorie information using the Spoonacular and Nutritionix APIs.

## Features

- Retrieves meal recipe information based on a provided `meal_ID` using the Spoonacular API.
- Extracts and formats the ingredients of the recipe into a user-friendly format.
- Retrieves calorie information for each ingredient using the Nutritionix API.
- Displays the recipe URL, a formatted list of ingredients, and the total calories for the recipe.

## Prerequisites

To run this script, you need to set up API keys for:

- **Spoonacular API** (for retrieving recipe information and ingredients)
- **Nutritionix API** (for retrieving calorie information of ingredients)

Make sure to add these API keys to  the SECRETS tab in Colab

You will also need to insert your own Nurtionix API key and ID in 'x-app-id' & 'x-app-key' under the 'Function to get calorie information for ingredients' section for the code to run properly.

## Usage

1. Run the cells in order
2. When prompted, enter a meal name (pasta, sushi, sandwich)
3. The notebook will display a link to the recipies website, the recipe ingredients, and a list of each ingredient with it's calorie information.


## Note:
This is a prototype for educational purposes. In a real-world application, additional features such as a user interface, recipe rating, nutrition breakdowns, and more robust error handling would be implemented.

