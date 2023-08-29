# phone-shop

- [DEMO LINK] ( https://nazar-medushevskyi.github.io/react_phone-catalog/ )

Technologies used: HTML, SCSS, React, JS, TypeScript with React, Routes, API, ClassNames, Local Storage, and others.

Global state was utilized for control purposes.

Phone Catalog - A comprehensive and functional e-commerce website, where you can explore various phone models, choose your favorite phones, add them to your favorites or cart, and much more!

This catalog consists of 12 pages: Home, Phones, Accessories, Favorites, Cart, GitHub, Contacts, Page Not Found, Nothing Found, Review, Rights, Selected Phone.


Home Page:

- Features a slider with an indicator that tracks the current slide.
- Includes a "Hot Prices" block, where phones fetched from the backend are filtered to display only those with hot prices, not exceeding $1050 since 2018, with prices starting from $300.
- Contains the "Shop by Category" block with links to Phones, Tablets, and Accessories. This block also showcases the number of models available in each category on the website at that moment.
- Concludes with the "Brand New Models" block, which features phones where the maximum price does not exceed $2000, released from 2018 onwards, and the minimum price is $1400.



Phones Page:

- At the top of the page (https://imgur.com/a/U1r5xxF), there's a path that indicates we are currently on the Phones Page after navigating from the Home Page.

- Additionally, the page indicates "Mobile phones" where you have the option to sort products in the order that suits you best: Alphabetically, from cheap to expensive, and start showcasing from the newest models. When selecting the number of phones you want to display, an indicator appears at the bottom, allowing you to switch between phones that didn't fit on the page.

- Also, this page features a search tool that allows us to find any phone. The search tool is intelligent, so you can enter the phone name, memory, and color in the order you prefer. Phones that match the criteria will be instantly displayed on the page, while those that don't meet the criteria won't be shown. If the search yields no results, you'll be redirected to the "Nothing Found" page, which includes an animation and a suggestion to return to the homepage or simply clear incorrect search terms and start anew.

- The number of models displayed changes based on how many phones were found on the page.



Tablets & Accessories Pages:

- These pages are currently (supposedly) under development, as the backend for these pages is not available, and naturally, there are no products to be displayed. Therefore, upon opening the page, you will be greeted with an animation and a suggestion to navigate to the Home Page.



Review Page:

- A page that opens when you click on a phone image.

- On this page, you can read all the necessary information about the phone. You can also choose a color you like and select the amount of gigabytes for each color that interests you.

- On this page, you have the option to add the phone to your favorites or cart by clicking a button. To remove them, you can simply click the button again.

- In addition to the description at the bottom of this page, you'll find phones that the store owner wants to recommend to customers.

- Additionally, on the right side of each selected phone, there will be its ID, which you can use to search for any phone using the search tool.



Page not found:

- This page opens when a user enters an incorrect URL in the address bar, leading to a page with no information on the website.

- The "Page not found" page welcomes you with an animation and a warning that the requested page does not exist. It then suggests returning to the Home Page.



Favorites Page:

- Upon the first visit, this page is empty. When empty, you'll encounter an animation with the message "Favorite Products Not Found." Later on, it suggests returning to the Home Page to select phones that you like.

- The page displays a counter indicating the number of phones added by the user.

- When a phone is added, it is displayed with a red heart instead of a white one, indicating it's in the favorites list.

- Phones can be arranged in a row, with a maximum of 4 phones. Any additional phones will be displayed below in rows of up to 4 models each.



Cart Page:

- This is the page where phones are added when the "Add to Cart" button is pressed.

- The page displays a counter indicating how many phones have been added.

- The page features rectangular phone cards, each with an image that can be clicked to navigate to the Review Page for that specific phone. Within these cards, you can also increase or decrease the quantity of phones, or completely remove a model from the cart by clicking on the cross icon.

- On the right side of the phones, a counter displays the total number of phones and the sum total for purchasing all the phones added to the cart.

- Additionally, there is a button that allows you to go back to the previous page.

- There will also be a button that allows you to make a purchase. However, since the store is for personal use only, no actual transactions will take place.



GITHUB:

- Leads you to the GitHub page where you can explore my projects and learn more about me.



Contacts:

- A page containing digital information about me, along with an animation of a bear on the right.


Rights:

- A page where you can familiarize yourself with the terms of use for this website, as well as the Mate Academy logo, which will direct you to the page - ( https://mate.academy/?utm_source=google&utm_medium=cpc&utm_term=mate%20academy&utm_content=659738949798&utm_campaign=gs_brand_ua_mxd&gad=1&gclid=Cj0KCQjwi7GnBhDXARIsAFLvH4mrOOL--09Stad1YoO2sM9EgFgurThfHsz6Liin0rsU20mnbRHLSrYaAthwEALw_wcB )




Regarding the phone cards:

Each card comprises several aspects:

- Phone image: Clicking on it leads to the Review Page.
- Phone name.
- Price: The current discounted price, with the original price struck through.
- Phone description based on aspects such as Screen, Capacity, and RAM.

 Additionally, there are two buttons:

- "Add to Cart" button: Clicking it adds the item to the cart. Upon clicking, the button style changes and the label becomes "Added to Cart." Clicking again reverts the button to its default state.
- Heart button: Clicking it adds the phone to favorites, allowing for more detailed exploration. Upon clicking, the heart icon turns red until clicked again to remove it from favorites.




To set up the project:

Create Your Own Copy: Begin by making your own version of the repository by clicking the "Fork" button located at the upper right corner of this page.

Copy to Your Machine: Clone the repository onto your local computer. Open your terminal, navigate to the location where you want the project, and use the command git clone 'your link'.

Install Necessary Components: Once you're inside the cloned folder using the terminal, execute the command npm install or npm i to install all the required components.

Launch the Application: After you've successfully installed the necessary components, initiate the application using the command npm start.

Access the Application: With the app up and running, open your web browser and go to http://localhost:3000 to access and utilize the application.

Prerequisites: It's advisable to fork this repository using Node.js version 14, as the application makes use of specific features that are present in Node.js 14.
