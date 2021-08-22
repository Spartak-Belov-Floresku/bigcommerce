# Special Item hover effect

### Hover effect
[file base.html](https://github.com/Spartak-Belov-Floresku/bigcommerce/blob/main/templates/layout/base.html)

- The code was added on lines 41 through 243.
- Used AJAX to fetch data from the server for a specific product.
- If the product has multiple images, the hover effect is activated, which will show the second image on mouse hover.

### Adding the add and delete buttons on category page
[file category.html](https://github.com/Spartak-Belov-Floresku/bigcommerce/blob/main/templates/pages/category.html)

- The code was added on lines 8 through 187.
- Used RESTFul to fetch data to and from the server for the products.

- Adding products, the code will handle all available links on the page that user can use to add the products to the cart.
- Creates a JSON and sends it to the server to the cart repository and applies the products to the current user.
- The returned response will notify the user of the number of items in the cart, changing the user interface.
- A delete button will also be created

- The Delete button will activate the function that REStful will use.
- Will send the cart ID to the server and delete the current user's cart.
- The function also activates changes in the user interface, notifying the user of the changes in the cart.
- And will remove the delete button from the UI.
