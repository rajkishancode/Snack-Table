# Snack-Table
Machine Coding Round Three



App Features:#
1) Display a table to show the snacks data, with columns for ID, Product Name, Product Weight, Price, Calories and Ingredients. The JSON to populate data for these columns have been provided below at the end.
2) Create a search input field to allow users to filter the snacks by product name or ingredients, regardless of the case. Update the table dynamically as the user types in the search input to show only the products matching your search input.
3)Sorting:
Make all the table headers clickable to enable sorting (Ascending/Descending order) by the respective column. All the columns should have sorting functionality.
Indicate that the header is clickable by showing a pointer or some CSS as per your wish.
Update the displayed table dynamically when the sorting order changes.
Note: You cannot use any npm package for table.

This is how your table should look:#
![table-ui](https://res.cloudinary.com/krishanucloud/image/upload/v1687462125/mcr-31_itrp9j.png)

Filtered View on Search:#
![](https://res.cloudinary.com/krishanucloud/image/upload/v1687462124/mcr-32_alchus.png)

Sort by Price (Descending) View:#
Similarly your sorting should work for all the columns.
![](https://res.cloudinary.com/krishanucloud/image/upload/v1687462125/mcr-33_ow7vox.png)



JSON Data:
```
const snacks = [
    {
      id: 1,
      product_name: "Granola Bar",
      product_weight: "21g",
      price: 299,
      calories: 150,
      ingredients: ["Oats", "Honey", "Nuts", "Dried Fruits"]
    },
    {
      id: 2,
      product_name: "Fruit and Nut Mix",
      product_weight: "73g",
      price: 749,
      calories: 353,
      ingredients: [
        "Almonds",
        "Cashews",
        "Dried Cranberries",
        "Dried Blueberries"
      ]
    },
    {
      id: 3,
      product_name: "Veggie Chips",
      product_weight: "28g",
      price: 279,
      calories: 130,
      ingredients: ["Sweet Potatoes", "Beets", "Kale", "Sea Salt"]
    },
    {
      id: 4,
      product_name: "Protein Balls",
      product_weight: "100g",
      price: 499,
      calories: 318,
      ingredients: ["Dates", "Almond Butter", "Protein Powder", "Chia Seeds"]
    }
  ];
```
