# donoftime2018.github.io
A place to show my portfolio projects, past work, growth, and more!

**Put a Price On It!**

A MERN stack I worked on during summer and fall of 2023. The purpose of this web app is to showcase the market price and popularity/rating of items available in the market so users can see which ones are best/worst rated and have the best/worst pricing. All the items are arranged in descending order in popularity and ascending order in price/name. So, the highest rated, least expensive items appear first and the lowest rated, most expensive items appear last. Users can add items using the form visible upon logging in. Users can use the search bar to search items only by name. The search was done by having a query state that is automatically changed when a query is entered in the search bar so the items array is filtered instantly. Users must login/register to use the app. Login was implemented using sessionStorage and an authContext. To run the app, one must run the react app in the root directory item-catalog, and to run the backend server, one must run start the server in the directory aptly titled server. 

In my searchParamsQuery branch, the state for holding the search query appears as a query parameter, q, in the URL. Also, the filtering of the items occurs instantly due to removing the formik submit handling. I got this idea from Web Dev Simplified. A link to the video in question.
https://www.youtube.com/watch?v=oZZEI23Ri6E&t=257s
