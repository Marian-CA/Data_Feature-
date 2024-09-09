# PPDS - Acitivity 01- Data Feature: Recipe and Calories Generator 

This notebook demonstrates the creation of a simple data feature protoype that helps users to get the meal recipe that they need and its associated calories.  Particularlyy it helps people who are curently on a diet/workout, enjoys to cook but are running out of ideas.

## Features

- Retrieves meal recipe information based on a provided `meal_ID` using the Spoonacular API.
- Extracts and formats the ingredients of the recipe into a user-friendly format.
- Retrieves calorie information for each ingredient using the Nutritionix API.
- Displays the recipe URL, a formatted list of ingredients, serving size of the meal, and the total calories for the recipe.

## Chosen APIs 
For the purpose of this activity we chose 2 two APIs, Spoonacular and NutritionIX for its user friendly features, comprehensive documentation, and its large database. We believe that these APIs would provide us with the opportunity to experiment and iterate, and grow as programmers. 

## Prerequisites

To run this script, you need to set up API keys for:

- **Spoonacular API** (for retrieving recipe information, ingredients, and serving size)
- **NutritionIX API** (for retrieving calorie information of ingredients)

Make sure to add these API keys to  the SECRETS tab in Colab

**Note: You will also need to insert the NutritionIX API key and the ID in 'x-app-id' & 'x-app-key' under the get_calories function section for the code to run properly. (This information can be found in the Lytspace assignment submission description)**  

## Usage

1. Run the cells in order
2. When prompted, enter a meal name (pasta, sushi, sandwich)
3. The notebook will display a link to the recipies website, the recipe ingredients, serving zie, total calories, and a list of each ingredient with it's calorie information.


## Note:
In a real data product, we would have additional features implemented like a user interface, the ability to generate multiple meal recipes, nutrition breakdown (i.e. total fat, sodium, carbohydrate, cholesterol, protein, etc), robust error handling, etc..., but for now though we can simply have the user enter a meal and then display the top recipe result.

