## ![Logo](./public/favicon-16x16.png) My Reads - React Nanodegree First Project

This is a mini project for managing user's book shelf. User can categories each book in following shelf categories at `/` route

1. 📖 Currently Reading Books
2. 📚 Books To Read
3. 📦 Completed Reading Books

Book can be removed or added from `/search` route. The shelf states of these books is persistent and stored in a backend provided by udacity. 

**Project Note** : 

1. Books which are present in shelf has **<span style="color: green">Green Action Menu</span>** button (rounded buttons above every book) & books which are not part of shelf has **<span style="color: blue">Blue Action button</span>**
2. Search Page tries to bring books through API after every letter is entered in input field.
3. Search Page shows no books when search field is empty or book for requested search string doesnot exists.

#### Routes

1. `/` Home Page containing Shelfs
2. `/search` Search Page
3. `/book/:bookId` Book Details Page


### ⚙️ Installation & Setup

You should have `npm` and `node` installed in your machine, to confirm type `node --version` in terminal. Below are steps to setup project in your system :

1. Clone the `my-reads` branch of this repository
2. Open Terminal in project folder (containing `package.json` file)
3. Run `npm install` and wait for all dependencies to download
4. Finally run `npm start` this will automatically launch application in default browser at `http://localhost:3000`



### 🕹 Test Online Version

The complete project is deployed at [**Netlify**](https://www.netlify.com/), Visit the following link to try it out : 

https://myreadskrupesh.netlify.app/



### 📖 Project Approach & Screenshots

![Approach](./project.jpg)




<hr />



#### Home Page Route : `/`

![Home Page](./home.png)


<hr />



#### Search Route : `/search`

![Search page](./search.png)



<hr />



#### Book Details Route : `/book/:bookId`

![Book details route](./book.png)
