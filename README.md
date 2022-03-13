# Sanity Shopping

## Lessons

1. Introduction
   1. What you will learn
   2. What you will build
   3. What Packages you will use
2. Install Tools
   1. VS Code
   2. Chrome
   3. Git
   4. Node.js
3. Create Next App
   1. npx create-next-app
   2. add @mui library
4. Publish to github
   1. create / login to github account
   2. push to github from vs code
5. Create Application Theme
   1. create classes utility with baseline styles
   2. creates Layout component as a Theme Wrapper for our application
6. Connect to Sanity.io
   1. install sanity
   2. initialize sanity
   3. create product model
   4. insert sample data to product model
7. List Products
   1. add localhost:3000 to the CORS origins in sanity
   2. fetch products from sanity
   3. render them in the screen
8. Create Product Details Screen
   1. add [slug].js to product folder
   2. create component
   3. get slug from the url
   4. fetch product from sanity client
   5. render product image, info
   6. show add to cart button
9. Create Dark and Light Mode
   1. definte Context, Store, and Reducer
   2. set darkMode flag
   3. use it on Layout
10. Implement Add to Cart
    1. define cart in context
    2. dispatch add to cart action
    3. set click event handler for add to cart button
    4. show cart items in header menu
11. Create Cart Screen
    1. get cart items from context
    2. render in the screen
    3. show cart items in the header menu
    4. implement add to cart in home page
12. Create Header Menu
    1. add cart link to header
    2. show cart items badge in header
    3. add login link to header
    4. implement add to cart in home page
13. Create Login and Register screen
    1. create login form
    2. create register form
14. Implement User Register API
    1. create user model
    2. create user create route api
    3. use it in the register screen
15. Implement User Login API
    1. create login api
    2. use login api in login screen
    3. implement logout
16. Create Shipping Screen
    1. create shipping component
    2. get address fields
    3. implement submit handler
    4. handle redirect
17. Create Payment Screen
    1. create payment component
    2. get payment method
    3. implement submit handler
18. Create Place Order Screen
    1. create place order component
    2. preview order
    3. create order model in sanity
    4. create order on place order click handler
19. Create Order Screen
    1. create order component
    2. display order information
