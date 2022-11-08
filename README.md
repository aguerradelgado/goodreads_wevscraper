# webscrape-goodreads
A flask web application that webscrapes [Goodreads](https://www.goodreads.com/) to find tags that contains information such as author, current giveaways for related genre, and ratings. The user enters the title of the book they want to search for, and the corresponding results are displayed. 

<img width="400" alt="Screen Shot 2022-11-08 at 6 12 04 PM" src="https://user-images.githubusercontent.com/68759170/200696094-39c96f33-d714-4cf8-ad09-cdb3258e3880.png">

<img width="400" alt="Screen Shot 2022-11-08 at 6 12 33 PM" src="https://user-images.githubusercontent.com/68759170/200696105-3e04ac17-78e0-4ca6-aae8-b047484c58ae.png">       <img width="375" alt="Screen Shot 2022-11-08 at 6 12 44 PM" src="https://user-images.githubusercontent.com/68759170/200696113-641a516e-e230-4f6d-9646-ce84bfab1fdd.png">

This application is quite simple so far as we are simply just pulling html and displaying the data. We plan on adding more features:

TO DO:
1. Add backend to be used as a shopping cart
2. Once the user is ready to "check out" they will get an email of their order with links to where to buy (downloadable excel sheet) 
3. once the user checks out, we can send an email linking 
4. Add sorting (eg, sort books by author, genre, ratings) 
5. Adding database using SQL and JSON
6. Add error checking (eg user enters non-existing book title)
