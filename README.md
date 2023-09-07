# Random-Recipe-Picker
Display random recipe using a GUI Tkinter application, SQLite3 and RecipeDB
<br>
<br>
<h1>Usage</h1>
<br>
Launch the application by running the recipe_picker.py script.
Click the "SHUFFLE" button to randomly select a recipe from the database.
The selected recipe's title and ingredients will be displayed.
Click the "BACK" button to return to the main screen.
<br>
<br>
<h2>Database Structure</h2>
<br>
The application assumes that you have an SQLite database with a specific structure:

The database should contain multiple tables, each representing a recipe.
Each recipe table should have columns: id, name, quantity, unit.
The script fetches a random recipe by selecting a random table and retrieving its records.
<br>
<br>
<h3>Customization</h3>
<br>
You can customize the application by adjusting the colors, fonts, and styling in the recipe_picker.py script. Additionally, you can modify the database structure to suit your needs.
