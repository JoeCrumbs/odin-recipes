# recipes

## Assignment ([The Odin Project Challenge Nr.1](https://www.theodinproject.com/lessons/foundations-recipes))

> [!NOTE]
> After coming back to The Odin Project after a longer break, the initial challenge/project was updated. The first challenge after the HTML and CSS section used to be a replica of the Google homepage. Now, there are two separate projects for HTML and CSS. Since I have already completed the Google homepage project, I only did the bare minimum to meet the assignments.

### Iteration 1: initial structure

1. [x] Within the `odin-recipes` directory, create an `index.html` file.
1. [x] Fill it out with the usual boilerplate HTML and add an `h1` heading "Odin Recipes" to the body.

### Iteration 2:  recipe page

1. [x] Create a new directory within the `odin-recipes` directory and name it `recipes`.
1. [x] Create a new HTML file within the  `recipes` directory and name it after the recipe it will contain. For example `lasagna.html`. You can use the name of your favorite dish or, if you need some inspiration, you can find a recipe to use at [Allrecipes](https://www.allrecipes.com/). Be sure to include the usual boilerplate HTML. This boilerplate code should be in every `.html` file you create.
1. [x] For now, just include an `h1` heading with the recipe's name as its content.
1. [x] Back in the `index.html` file, add a link to the recipe page you just created. Example: Under the `<h1>Odin Recipes</h1>` heading, write out the link like so: `<a href="recipes/recipename.html">Recipe Title</a>`. The text of the link should again be the recipe name.
1. [x] **Add a link back to the index page** on your recipe page for easier navigation. You can place this link at the top or bottom of your recipe page (e.g., `lasagna.html`). Here's an example:

   ```html
   <a href="../index.html">Home</a>
   ```

   This allows users to quickly return to the home page after viewing the recipe.

### Iteration 3:  recipe page content

Your new recipe page should have the following content:

1. [x] An image of the finished dish under the h1 heading that you added earlier. You can find images of the dish on Google or [Allrecipes](https://www.allrecipes.com/).

1. [x] Under the image, it should have an appropriately sized "Description" heading followed by a paragraph or two describing the recipe.

1. [x] Under the description, add an "Ingredients" heading followed by an **unordered list** of the ingredients needed for the recipe.

1. [x] Finally, under the ingredients list, add a "Steps" heading followed by an **ordered list** of the steps needed for making the dish.

#### Iteration 4: add more recipes

1. [x] Add two more recipes with identical page structures to the recipe page you've already created.
1. [x] Don't forget to link to the new recipes on the index page. Also, consider putting all the links in an unordered list so they aren't all on one line.

Example:

```html
 <ul>
    <li><a href="recipes/yourrecipe.html">Recipe Title 1</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 2</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 3</a></li>
  </ul>
```
  
Your links won't be flashy, but for now, just focus on building them out.

</div>

