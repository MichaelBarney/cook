![cook language](pics/cook-color.png)

## A programming language for cooking!

### Cook is a description language for all types of activities related to cooking. Possibilites include:

- Creating a Standard for Recipes
- Ofering new standard tools for recipes.
- Connecting multiple devices to fufill a role in a kitchen.
- Ofering commands for cooking robots!

## Documentation

### Info
The first block of COOK code needs to define descriptions for the recipe, this can be it's name (title), description, preperation time or servings.

![info](pics/info.png)
    
### Ingredients

- Every recipe needs ingredients, in COOK we need to define our second block as one to set all of the elements that make the recipe.
- COOK units can be in imperial or metric systems, this is because there will be integrated conversions systems in all of it's compilers.
- You can detail information about the ingredient used with information like: preperation (prep), brand or extras (ext).

![ingredients](pics/ingredients.png)

![ingredients2](pics/ingredients-2.png)

### Directions

- The final block of COOK code is the one containing all of the directions needed to prepare the recipe.
- Each object is seperetely defined for each component of a recipe. Inside the object identifier is where all of the directions will be positioned.
- Action keywords (RED) are the ones that tell what is going to be done to another object or ingredient.
    ```
    Example: 
    bake; place; mix; stir; heat;
    ```
- Action keywords (RED) are the ones that tell what is going to be done to another object or ingredient. 
    ```
    Example: 
    bake; place; mix; stir; heat;
    ```
- Action keywords (RED) are the ones that tell what is going to be done to another object or ingredient. 
    ```
    Example: 
    bake; place; mix; stir; heat;
    ```
- Condition keywords (VIOLET) complement the actions by telling parameters for the action to be sucessfull.
    ```
    Example: 
    on; until;
    ```
- Some actions are aplied to more than one object, in this case they are put inside braces and seperated by commas. 
    ```
    Example:
    mix(flour, sugar, salt, egg);
    ```
- You can be more specific to how an action will be made by defining variables like 'size' 'distance' or 'extras'.
- The last action of COOK code should always be 'serve' followed by the object that will be served.

![Directions](pics/directions.png)

## Examples

### Cookie Recipe

![cookie example](pics/cookie.png)
