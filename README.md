# How to Format Your Recipe File

## Quick Start Template
Copy this and replace with your recipe details:
```
### Recipe Name category:type

Ingredients | Amount | Unit
Ingredient here | 1 | cup
Another ingredient | 2 | Tbsp

1. First step of cooking instructions.
2. Second step goes here.
3. Continue numbering each step.
```

## Detailed Formatting Rules

### Recipe Title Line
- **Must start with:** `###` (three hashtags and a space)
- **Format:** `### Recipe Name category:type`
- **Example:** `### Chicken Parmesan italian:chicken`

**Available Categories:** american, asian, swedish, italian, mexican, indian, french
**Available Types:** chicken, beef, pork, tofu, sauce, soup, salad, breakfast

You can use multiple tags: `### Beef Tacos mexican:beef:sauce`

### Cocktail Title Line

Same format as recipes: ### Cocktail Name type:spirit
Example: ### Old Fashioned classic:whiskey

Available Cocktail Types: classic, modern, tiki, sour, fizz, martini, highball, punch, shot, frozen, hot
Available Spirits: vodka, gin, rum, whiskey, bourbon, tequila, mezcal, brandy, wine, champagne, beer
You can use multiple tags: ### Long Island Iced Tea modern:vodka:gin:rum:tequila

### Ingredients Section
- **Header line:** Must contain the words "Ingredients", "Amount", and "Unit" separated by pipes
- **Format each ingredient:** `Ingredient name | Amount | Unit`
- **Use pipes ( | ) to separate** the three columns

**Examples:**
```
Ingredients | Amount | Unit
Chicken breast | 2 | pounds
Olive oil | 3 | Tbsp
Salt | to taste |
Garlic, minced | 4 | cloves
```

**Tips for amounts:**
- Use fractions: `1/2`, `1/4`, `2 1/2`
- Use ranges: `2-3`, `1-2`
- Use descriptions: `to taste`, `as needed`, `for frying`
- Leave unit blank if not applicable (like for "1 onion")

### Instructions Section
- **Start each step with a number and period:** `1.` `2.` `3.` etc.
- **Write naturally** - if a step is long, let it wrap to the next line
- **Leave a blank line** between instructions and the next recipe

**Example:**
```
1. Preheat the oven to 350°F.
2. Season the chicken with salt and pepper. If you're using 
   a marinade, let it sit for at least 30 minutes in the fridge.
3. Heat oil in a pan over medium-high heat.
```

### Multiple Recipes
Just add more recipes below the first one, with a blank line between:
```
### First Recipe italian:pasta

Ingredients | Amount | Unit
Pasta | 1 | pound

1. Cook pasta according to package directions.


### Second Recipe american:breakfast

Ingredients | Amount | Unit  
Eggs | 3 |
Bacon | 4 | strips

1. Fry the bacon until crispy.
2. Cook eggs in bacon fat.
```

## Example Complete Recipe

```
### Spaghetti Carbonara italian:pork:pasta

Ingredients | Amount | Unit
Spaghetti | 1 | pound
Eggs | 4 |
Egg yolks | 2 |
Pancetta | 8 | oz
Pecorino Romano, grated | 1 1/2 | cups
Black pepper, freshly ground | 2 | tsp
Salt | for pasta water |

1. Bring a large pot of salted water to boil and cook spaghetti according 
   to package directions until al dente.
2. While pasta cooks, cut pancetta into small cubes and fry in a large 
   skillet until crispy, about 5-7 minutes.
3. In a bowl, whisk together eggs, egg yolks, and most of the cheese 
   (save some for garnish).
4. When pasta is done, reserve 1 cup of pasta water before draining.
5. Add hot pasta to the pancetta pan (off heat) and quickly toss.
6. Add egg mixture and toss vigorously, adding pasta water as needed 
   to create a creamy sauce. The residual heat will cook the eggs.
7. Season with black pepper and serve immediately with remaining cheese.
```


**Remember:** The format is flexible for amounts and units, but the structure (###, pipes, numbered steps) must be followed exactly for the parser to work correctly.