# Technical Tryout
**Glints Academy Tryout**

## **General Overview**


-----
Create a book store app that can handle realtime callback from 3rd party payment REST API.

**BE**

1. Create an API to show list of available book title and book image url. Also insert some dummy data with your favorite books!
2. Create an API to show the book detail by id. The book details are book title, total stock, genre, writer, published year, image url. 
3. Create an API to handle payment by book id, that will need to request to 3rd party API to handle the payment. When waiting for 3rd party API also update the total stock asynchronously. Source 3rd party API https://fierce-sands-20615.herokuapp.com/pay/{bookId}/{success} example https://fierce-sands-20615.herokuapp.com/pay/123/1 , 1 for success = true, and 0 success = false. Latency will be 10 seconds.
4. Create unit testing for each method that you have created.

**FE & Mobile**

1. Create page to show list of available books with the image, you can create a dummy json(Image title, image url).
2. Create a page to show selected book title from above, you can add more detail to dummy json(author, small description).
3. Add a pay button inside detail page, and after user click it, then show a pop up model to to input any pin number 123456 for success notification, and 654321 for failed notification pop up. 
4. Create unit testing for each method that you have created.

**Expectations**

1. Efficient methods to fulfill all the requirements.
2. Good use of Git (commit every changes that you think it is your checkpoint).
3. Document everything!


**Details**

1. Use any types of unit testing you are familiar with. (BE/FE/Mobile).
2. Use any public styling framework to work on the UI. (FE/Mobile).
3. Push your code to github classrooms using this repository that you've cloned.