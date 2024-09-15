A Myntra Clone e-commerce website where users can browse products, add items to their cart, and generate a bill for the selected products. The project utilizes local storage to persist cart data across sessions.

Features
Product Listing:

Products are displayed with details like the name, price, and image.
The list of products is sourced from a JavaScript file (items.js).
Add to Cart:

Users can add items to their shopping cart, which is reflected in the cart icon.
Cart data is stored in local storage, ensuring that the items remain in the cart even after refreshing or leaving the page.
Remove from Cart:

Users can remove items from their cart, and the total price is updated automatically.
Cart updates are stored in local storage.
Checkout/Bill Generation:

On the Cart page (bag.html), users can review the added items, view the total price, and proceed to checkout.
The total bill is generated based on the items in the cart.
Local Storage:

Cart data is stored in the browser’s local storage to persist between sessions.
The stored cart includes product ID, name, quantity, and price.


Project Structure
The project follows the directory structure below:


├── css/
│   ├── bag.css           # Styling for the cart page
│   └── index.css         # Styling for the homepage
├── data/
│   └── items.js          # Product data
├── images/               # Product and other website images
├── pages/
│   └── bag.html          # Cart page for reviewing items and generating bills
├── scripts/
│   ├── bag.js            # JavaScript for cart page functionality
│   └── index.js          # JavaScript for homepage and product listing
├── index.html            # Homepage listing products
└── README.md             # Project README file

Technologies Used
HTML: Structure of the web pages.
CSS: Styling for the homepage (index.css) and the cart page (bag.css).
JavaScript: Handles product data loading (items.js), cart operations (index.js, bag.js), and local storage management.
Local Storage: Used for persisting the cart data across user sessions.

Conclusion
This project is a basic clone of Myntra, showcasing how to use local storage for cart persistence and how to implement an "Add to Cart" and billing system in an e-commerce website. It provides a foundation for further development and improvements.
