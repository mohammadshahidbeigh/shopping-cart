# Shopping Cart

This code snippet demonstrates a simple shopping cart implementation in JavaScript. It generates random product data, calculates the cart total, applies taxes, and displays the cart contents along with a summary.

## Usage

1. Open an HTML file in your preferred browser.
2. Insert the provided JavaScript code into a `<script>` tag.
3. Ensure you have an HTML element with the id "Products" where the cart items will be displayed, and an element with the id "Summary" where the cart summary will be displayed.
4. Reload the page to see the generated cart items and summary.

## Code Explanation

- The `roll` function generates random numbers within a given range, optionally returning floating-point numbers.
- The `possibleProducts` array holds a list of emojis representing possible products.
- The `products` array is populated with randomly generated product objects, including title, price, weight, and count.
- The `cartTotal` variable calculates the total cost of the items in the cart.
- The `totalWeight` variable calculates the total weight of the items in the cart.
- The `taxRate` is randomly generated between 5% and 9%.
- The `taxed` function calculates the taxed total based on the cart total and tax rate.
- The `cart` element is used to display individual cart items.
- The `summary` element is used to display the cart summary.

## Output

The page will display a list of randomly generated products in a cart-like format. The summary section will display the total cost, tax rate, taxed total, and total weight of the items.

## Note

This code is a simple demonstration and might not cover real-world scenarios. It showcases the basic concepts of generating random data, calculating totals, and displaying information on a webpage.

Feel free to modify and extend the code to fit your specific needs.

Quick start:

```
$ yarn # npm install
$ yarn build # npm run build
```

## Development

Run Webpack in watch-mode to continually compile the JavaScript as you work:

```
$ yarn watch # npm run watch
```

Happy Coding!
