# stu_store2
In this activity we will create a CMS (Content Management System) that allows users to upload blog posts. Users will also be able to view blog posts by other authors and filter them based on category. We will use the Context API to manage the application state globally, adhering to a design pattern that closely follows Redux. Although very complex applications may have several stores, we are going to keep it simple and store all stateful data in a single global store.

## Instructions

* Open the [Unsolved](Unsolved) folder and install dependencies by running `npm install` at the project root.

* Open another tab in your terminal and run `mongod`.

* Start the app by running `npm start` from the project root.

* Once the app starts open your browser to [localhost:3000](http://localhost:3000).

* Open [App.js](Unsolved/client/src/App.js).

* There are 4 main sections in this application:

  * A section that allows you to create new posts.

  * A section that lists all of the posts.

  * A detail page to view the contents of an individual post.
