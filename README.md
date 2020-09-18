# store_app
E-commerce store
STORE_APP
1) This is a Guitar/Guitar Accessories app implemented in Django with select Vue front end features. 
2) This was a collaboration between me and other edx.org edition remote CS50 students, Nathan Kawaller and Natalie Sterling.
3) My contributions we're largely backend
    3a) We designed the majority of the models after a group discussion on how these would basically be connected
    3b) There are UserProfile, Products, Reviews, TransactionHistory, and Cart
    3c) We used json fixture files to loaddata as it was inputted for testing 
    3d) One of the major triumphs was implementing the image field on the Products model
4) We each contributed tests to the tests.py files in both apps
    4a) By both apps, I mean we separated the front end "app", from the rest framework "api"
    4b) our goal was to contribute one test per day a piece as we worked on this. 
    4c) Although we feel comfortable presenting this project now, we'll continue to develop it and compose more tests
5) Our team developement philosophy was originally to take a feature and develop it front to back. 
    5a) That's essentially how it's worked
    5b) My features were:
        ~Products display whether user.is_authenticated or not
        ~Filter Products by category/brand/keywords from search whether user.is_authenticated or not
        ~Shop By Category which queries db for categories, lists those as links and takes user to filtered products list
        ~Add product to Cart if user.is_authenticated = True and update the cart button with current cart quantity
        ~Connecting said cart button to cart page and writing to disk
        ~See customer reviews for a given product
        ~Write a review for a given product
        ~So my babies were mainly the Reviews and Products models
        ~wrote tests for my features and models along the way
     5c) Feel free to hit the blame tab on any file to check which lines I contributed!
6)A major part of this project was collaborating via GitHub, pull requests and using fixtures to have similar data.
    6a) The git collaboration and flow was the newest element of the process for us. 
