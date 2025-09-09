"# PH-Assignment-06"
i have some api. using those i want to show in to my html page. these are the apis and details.
🌴 API Endpoints
Get 🌴All Plants
https://openapi.programming-hero.com/api/plants
Get 🌴All categories
https://openapi.programming-hero.com/api/categories
Get 🌴plants by categories
https://openapi.programming-hero.com/api/category/${id}
https://openapi.programming-hero.com/api/category/1
Get 🌴Plants Detail
https://openapi.programming-hero.com/api/plant/${id}
https://openapi.programming-hero.com/api/plant/1
⚙️ Functionalities
Category Loading Load Tree Categories dynamically on the left side.

Category Click → Tree Data On clicking a category: load trees of that category.

Display in a 3-column card layout.

Card Contents Each card includes:

 - Image

 -  Name

 - Short description

 - Category

 - Price

 - Add to Cart button. the cart should be on the right side
Modal on Card Click Clicking a tree name on a card opens a modal with full tree details.
1) Add to Cart 
Clicking Add to Cart: - Adds the tree to Cart List
                      - Shows tree name 

2) Total Calculation 
Calculate total price of trees in cart.

3) Remove from Cart 
Clicking ❌ removes tree and deducts price from total.

4) Loading Spinner
Show spinner while data is loading.

5) Active Button State 
Highlight active category button when selected.
JavaScript (Vanilla only, no frameworks)