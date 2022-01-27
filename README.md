# Rocket Academy Coding Bootcamp: Noodles Express

This exercise is a post-class exercise for Rocket Academy to create a noodle recipe app using Express and recipe data provided by RA.

## Usage

### Get single recipe by index

http://localhost:3004/recipe/:index

http://localhost:3004/recipe/1

```json
{
  "source": "Smitten Kitchen",
  "label": "Noodle Kugel recipes",
  "url": "http://www.edamam.com/recipe/noodle-kugel-recipes-d6452a86e2edb13bbeb305904fd2a7f1/noodle",
  "ingredients": "1 pound wide egg noodles\n2 8-ounce packages cream cheese, softened\n1 pound (16 ounces) creamed cottage cheese, full fat\n1 1/2 cups sugar\n1 stick salted butter, melted, plus more for greasing the baking dish\n8 eggs\n2 teaspoons vanilla\n1 teaspoon cinnamon\n1 cup dried cherries",
  "yield": 4,
  "caution": "Sulfites",
  "image": "https://www.edamam.com/web-img/129/1299cd9a98464c5f76952710aa71aaba",
  "category": "Tree-Nut-Free"
}
```

### Get recipes by label

http://localhost:3004/recipe-label/:label

http://localhost:3004/recipe-label/udon-noodle-soup

```json
[
  {
    "source": "BBC Good Food",
    "label": "Udon noodle soup",
    "url": "http://www.edamam.com/recipe/udon-noodle-soup-bf283c727cd11fb8ce42b98f09dabbac/noodle",
    "ingredients": "1 vegetable stock cube\n50ml teriyaki sauce\n1 tbsp vegetable oil\n140g chestnut mushroom, sliced\n½ bunch spring onions, thinly sliced\n140g udon noodle\n200g bag spinach",
    "yield": 4,
    "caution": "Sulfites",
    "image": "https://www.edamam.com/web-img/7b2/7b24a14c8756cc1db75eb216fb593e6d.jpg",
    "category": "Vegan"
  },
  {
    "source": "Cookstr",
    "label": "Udon Noodle Soup",
    "url": "http://www.edamam.com/recipe/udon-noodle-soup-2b744ab3097f774c9c03436f4c1c4ab2/noodle",
    "ingredients": "6 cups cold water\n1½ pounds chicken necks, wings, and backs\n6 slices fresh ginger\n2 leeks, washed, including 2 inches of the green\n1½ teaspoons salt\n½ teaspoon freshly ground black pepper\n2 egg whites, beaten\n4 ounces udon noodles\n1 bunch radishes, thinly sliced\n1 bunch scallions, thinly sliced on the diagonal, including 2 inches of the green\n4 ounces Chinese cabbage, thinly sliced",
    "yield": 10,
    "image": "https://www.edamam.com/web-img/77f/77f47f5f878228fde83061784d302bae.jpg",
    "category": "Alcohol-Free"
  }
]
```
