## Flask Application Design for an E-commerce Photography Equipment Website

### HTML Files

- **index.html**: Main landing page of the website, showcasing featured products, categories, and promotions.
- **products.html**: Displays a list of all available products, with options for filtering by category, price, and other attributes.
- **product-detail.html**: Dedicated page for each product, showing detailed information, images, specifications, and customer reviews.
- **cart.html**: Displays the contents of the user's shopping cart, allowing them to view and modify their selections.
- **checkout.html**: Page where users can provide their contact information, select a shipping method, and complete the purchase.

### Routes

#### Product Management
- **/products**: GET route to retrieve a list of all products.
- **/products/<product_id>**: GET route to retrieve details of a specific product.

#### Cart Management
- **/cart**: GET route to retrieve the contents of the user's shopping cart.
- **/cart/add**: POST route to add an item to the shopping cart.
- **/cart/remove**: POST route to remove an item from the shopping cart.

#### Checkout
- **/checkout**: GET route to display the checkout form.
- **/checkout/submit**: POST route to process the checkout request and complete the order.

#### Miscellaneous
- **/about**: GET route to display a page with information about the company and its mission.
- **/contact**: GET route to display a contact form for users to send inquiries or feedback.