# MediCart - Your Online Pharmacy

MediCart is a simple yet functional frontend application designed to replicate an online pharmacy. It allows users to browse a list of medicines, add them to a shopping cart, adjust quantities, and proceed to a simulated checkout. The project focuses on demonstrating core e-commerce functionalities and a responsive user interface.

## Live Demo:
VISIT LIVE WEBSITE:https://hareeshwar-chowdary-mullapudi.github.io/Medicart/

## Built with:

* HTML5
* CSS3
* Bootstrap 5
* JavaScript

## Guide to use the project:

1.  **HTML Structure:** The `index.html` file serves as the main page, displaying available medicines, a search bar, and a cart icon. The `cart.html` file provides the shopping cart interface.
2.  **Styling:** Custom CSS in `style.css` is used for specific elements like medicine cards, cart images, search bar, notifications, and the footer. Bootstrap 5 is integrated for responsive layout and pre-built components (navbar, cards, buttons).
3.  **Medicine Data:** Medicine details (id, name, price, use, image) are stored in the `medicines.js` array, acting as a mock database.
4.  **Core Logic (app.js):**
    * `renderMedicines()`: Dynamically displays medicine cards based on the `medicines` array, with an optional filter for search functionality.
    * `addToCart()`: Handles adding items to the local storage-based cart, including quantity updates for existing items.
    * `updateCartCount()`: Updates the number displayed on the cart icon in the navigation bar.
    * `showNotification()`: Displays a temporary success message when an item is added to the cart.
    * Event listeners are set up for search input and "Add to Cart" buttons.
5.  **Cart Logic (cart.js):**
    * `loadCart()`: Retrieves cart items from local storage and renders them in the `cart.html` page.
    * `updateQuantity()`: Modifies the quantity of items in the cart (increment/decrement).
    * `removeItem()`: Removes items from the cart.
    * `updateTotal()`: Calculates and displays the total price of items in the cart.
    * `showNotification()`: Displays messages for cart actions (e.g., empty cart, checkout successful).
    * The "Proceed to Checkout" button clears the cart and redirects to the home page after a successful (simulated) checkout.

## Things I've mastered with this project:

* Implementing a client-side shopping cart using Local Storage for persistence.
* Dynamic rendering of content (medicine cards, cart items) using JavaScript.
* Event handling for interactive UI elements (add to cart, quantity change, remove, checkout).
* Responsive web design principles using Bootstrap 5 for layout and components.
* Basic search/filtering functionality on a list of items.
