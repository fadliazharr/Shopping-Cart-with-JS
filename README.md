# Shopping-Cart-with-JS
You can access the project in the link below: 
https://fadliazharr.github.io/Shopping-Cart-with-JS/
---

## Shopping Cart for Desserts  

This project is a simple, interactive shopping cart for a dessert store. It allows users to browse a selection of desserts, add items to their cart, and view the total cost, including taxes. The cart can also be cleared with a single button click.  

---

### **Features**  

- **Dynamic Product Listing**: The page displays a variety of desserts, each with a name, price, and category.  
- **Add to Cart**: Users can add desserts to their cart, with item counts updating in real-time.  
- **Cart Management**: The cart shows the total number of items, subtotal, taxes, and final total.  
- **Show/Hide Cart**: Users can toggle the visibility of the cart.  
- **Clear Cart**: Users can remove all items from the cart with a confirmation prompt.  

---

### **How It Works**  

1. The desserts are pre-defined in an array of objects, each containing details like name, price, and category.  
2. When the page loads, JavaScript dynamically creates and displays dessert cards.  
3. Clicking **"Add to Cart"** adds the selected item to the shopping cart. If the item is already in the cart, its quantity updates instead of creating a duplicate entry.  
4. The cart dynamically calculates and displays:  
   - **Subtotal**: The total cost of all items before taxes.  
   - **Taxes**: A fixed percentage (8.25%) applied to the subtotal.  
   - **Total**: The final cost after adding taxes.  
5. Clicking **"Show/Hide Cart"** toggles the visibility of the cart.  
6. Clicking **"Clear Cart"** removes all items after a confirmation prompt.  

---

### **Technologies Used**  

- **HTML**: Provides the structure of the page, including buttons and containers for desserts and the shopping cart.  
- **CSS**: Styles the interface with a clean and visually appealing design, including buttons, product cards, and responsive layouts.  
- **JavaScript**: Implements the core functionality, including event handling, cart calculations, and dynamic content updates.  

---

### **Code Breakdown**  

#### **1. HTML (Structure)**  
The webpage includes:  
- A **header** with the title.  
- A **button** to toggle the cart visibility.  
- A **cart container** that displays selected items, total price, and a "Clear Cart" button.  
- A **dessert card container**, where products are dynamically displayed.  

#### **2. JavaScript (Functionality)**  
- A **`products` array** defines the available desserts.  
- A **loop** dynamically generates HTML for each product and inserts it into the page.  
- A **ShoppingCart class** handles:  
  - Adding items to the cart.  
  - Keeping track of item counts.  
  - Calculating totals (subtotal, taxes, and final amount).  
  - Clearing the cart when needed.  
- **Event listeners** handle:  
  - Clicking "Add to Cart" to update the cart.  
  - Toggling cart visibility.  
  - Clearing the cart with a confirmation prompt.  

#### **3. CSS (Styling & Responsiveness)**  
- Uses a **dark theme** for the background with contrasting light elements.  
- Product cards are styled with **rounded edges, padding, and spacing**.  
- Buttons use **gradient effects** to enhance visibility.  
- The layout adjusts for **different screen sizes** using media queries.  

---

### **Expected Output & User Interaction**  

- The page loads with dessert options displayed as cards.  
- Clicking "Add to Cart" updates the cart in real-time.  
- Clicking "Show/Hide Cart" reveals or hides the cart.  
- Clicking "Clear Cart" resets the cart after user confirmation.  
- The total price updates dynamically as items are added or removed.  

---

### **Potential Enhancements**  

- Adding **images** for each dessert to make the UI more visually appealing.  
- Implementing a **search/filter feature** to find desserts by name or category.  
- Adding a **checkout system** with payment integration.  
- Allowing users to **adjust item quantities** directly in the cart.  
- Storing cart data using **local storage** so items remain in the cart even after a page refresh.  

