# donoftime2018.github.io
A place to show my portfolio projects, past work, growth, and more!

[**Put a Price On It!**](https://github.com/donoftime2018/ItemCatalog)

A MERN stack I worked on during summer and fall of 2023. The purpose of this web app is to showcase the market price and popularity/rating of items available in the market so users can see which ones are best/worst rated and have the best/worst pricing. All the items are arranged in descending order in popularity and ascending order in price/name. So, the highest rated, least expensive items appear first and the lowest rated, most expensive items appear last. Users can add items using the form visible upon logging in. Users can use the search bar to search items only by name (i.e. doesn't filter based on price, user, just name of item). Reset password also doesn't let me enter anything into the confirm password TextArea, so no reset password functionality for now. The search was done by having a query state that is automatically changed when a query is entered in the search bar so the items array is filtered instantly. Users must login/register to use the app. Login was implemented using sessionStorage and an authContext. To run the app, one must run the react app in the root directory item-catalog, and to run the backend server, one must run start the server in the directory aptly titled server. 

![Screenshot 2023-10-08 001623](https://github.com/donoftime2018/donoftime2018.github.io/assets/84360449/f668ad8f-d2fb-401a-9648-58fb9d5d7f23)
Login Screen

![Screenshot 2023-10-08 001800](https://github.com/donoftime2018/donoftime2018.github.io/assets/84360449/7eefbddb-dab6-4de2-9828-5b2038081761)
Dashboard with name of logged in user

![Screenshot 2023-10-07 235735](https://github.com/donoftime2018/donoftime2018.github.io/assets/84360449/7b8a9ee7-95bb-486a-9698-271f18a26f21)
Items added to the db with the name of the user who posted the item

![Screenshot 2023-10-07 235735](https://github.com/donoftime2018/donoftime2018.github.io/assets/84360449/566cc7e9-a851-4b44-800d-95ddb72bb449)
Click show desc button to see desc of item



In my searchParamsQuery branch, the state for holding the search query appears as a query parameter, q, in the URL. Also, the filtering of the items occurs instantly due to removing the formik submit handling. I got this idea from Web Dev Simplified. [Click here to see the video](https://www.youtube.com/watch?v=oZZEI23Ri6E&t=257s). Please note that searchParamsQuery is a few commits behind main, hence why the name of the item poster isn't present in the screenshots.

![Screenshot 2023-10-07 235124](https://github.com/donoftime2018/donoftime2018.github.io/assets/84360449/c106a330-0eb7-4699-83b9-fb9d5059a855)
![Screenshot 2023-10-07 235259](https://github.com/donoftime2018/donoftime2018.github.io/assets/84360449/5b7a7c85-6087-4cde-a762-2cb33575b444)
