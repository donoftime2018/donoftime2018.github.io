# donoftime2018.github.io
A place to show my portfolio projects, past work, growth, and more!

[**Put a Price On It!**](https://github.com/donoftime2018/ItemCatalog)

A MERN stack I worked on during summer and fall of 2023. The purpose of this web app is to showcase the market price and popularity/rating of items available in the market so users can see which ones are best/worst rated and have the best/worst pricing. All the items are arranged in descending order in popularity and ascending order in price/name. So, the highest rated, least expensive items appear first and the lowest rated, most expensive items appear last. Users can add items using the form visible upon logging in. Users can use the search bar to search items only by name (i.e. doesn't filter based on price, user, just name of item). Users can use the blue star button to add a star to the rating, and the yellow - button to remove a star from the rating. Ratings can only exist between 0 and 10. Reset password also doesn't let me enter anything into the confirm password TextArea, so no reset password functionality for now. The search was done (in main branch) by using a boolean state, a query state, and a Formik submit handler that would update the query state to what the user entered and a boolean state that would turn true if the query state wasn't an empty string. Users must login/register to use the app. Login was implemented using sessionStorage and an authContext. To run the app, one must run the react app in the root directory item-catalog, and to run the backend server, one must run start the server in the directory aptly titled server. 

![Screenshot 2023-10-08 001623](https://github.com/donoftime2018/donoftime2018.github.io/assets/84360449/f668ad8f-d2fb-401a-9648-58fb9d5d7f23)
Login Screen

![Screenshot 2023-10-08 001800](https://github.com/donoftime2018/donoftime2018.github.io/assets/84360449/7eefbddb-dab6-4de2-9828-5b2038081761)
Dashboard with name of logged in user

![Screenshot 2023-10-07 235735](https://github.com/donoftime2018/donoftime2018.github.io/assets/84360449/7b8a9ee7-95bb-486a-9698-271f18a26f21)
Items added to the db with the name of the user who posted the item

![Screenshot 2023-10-08 005653](https://github.com/donoftime2018/donoftime2018.github.io/assets/84360449/123da71c-30e9-430f-bb63-16bddc93cd46)
Click show desc button to see desc of item

**UPDATE as of 10/8/2023**

I am adding 2 search bars. One for item and one for the poster of the item. If only item is searched, items will be filtered by item name alone. If only poster is searched, items will be filtered by the poster alone (i.e. all items posted by praorapper will appear if query is praorapper). If both are searched, items with substring searched posted by poster searched will appear (i.e. all items with "wooden" posted by praorapper will appear).

![Screenshot 2023-10-08 222945](https://github.com/donoftime2018/donoftime2018.github.io/assets/84360449/45c07c04-d0b2-4b6c-8b17-4bdb30663902)
All items posted by johnsmith100 appear

![Screenshot 2023-10-08 222914](https://github.com/donoftime2018/donoftime2018.github.io/assets/84360449/2cd9e8c8-71b1-4b01-bc79-6d0cd075e1a6)
All items that have "Wooden" in the name posted by johnsmith100 appear

**UPDATE as of 10/17/2023**

I added a Profile and Login/Registration System. Also, made some UI/UX changes based on a fellow Software Developer's input. On the profile, the logged in user can look at the 5 most recently liked and posted items. Also, add items form on Dashboard can be closed/opened. Moreover, a navbar is available so a user can visit their profile or logout if they please. The navbar remains in the same place on the page. A user cannot like an item more than once. Moreover, the user who posted an item cannot like that same item. 

In my searchParamsQuery branch, the state for holding the search query appears as a query parameter, q, in the URL. Also, the filtering of the items occurs instantly due to removing the formik submit handling. I got this idea from Web Dev Simplified. [Click here to see the video](https://www.youtube.com/watch?v=oZZEI23Ri6E&t=257s). Please note that searchParamsQuery is a few commits behind main, hence why the name of the item poster isn't present in the screenshots.

![Screenshot 2023-10-07 235124](https://github.com/donoftime2018/donoftime2018.github.io/assets/84360449/c106a330-0eb7-4699-83b9-fb9d5059a855)
![Screenshot 2023-10-07 235259](https://github.com/donoftime2018/donoftime2018.github.io/assets/84360449/5b7a7c85-6087-4cde-a762-2cb33575b444)
