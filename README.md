# JS ToDo Single Page Application

The purpose of this application is to show some basic concepts and patterns. It is developed for educational purposes and is used as demo in January **JS Applications** course in SoftUni. It has very basic functionality, but is used as showcase for the following patterns and concepts:

1. JS OOP
   - Class
   - Constructor
   - Properties and Methods
   - Getters and Setters
   - Inheritance
2. Asynchronous programming in JS
   - Promises
   - Async / Await
3. SPA Application Router /*basic demo implementation*/
4. Template engine /*basic demo implementation*/
5. Http requester using Fetch Api
6. MVC
7. Repository pattern
   - Repository using firebase REST Api
   - Repository using firebase SDK
   - Two repositories are fully interchangeable
8. Usage of different tools when creating JS applications
   - NPM
     - Installing and managing packages
     - Creating and using npm scripts
   - Webpack
     - Loaders
     - Copy plugin
     - Building for different environments
     - Dev server
   - Babel
     - Transpile code
     - Using plugins to add special transpilers /*dotall-regex*/  

This application is using [Google Firebase](https://firebase.google.com/) as backend. To build and run the application you have to add **.secret** file to the root of the project. This file must export an object with firebase settings.

**.settings** content:

```JavaScript
export default {
    apiKey: "Your Firebase API Key",
    authDomain: "Your Firebase Auth Domain",
    databaseURL: "Your Firebase Database URL",
    projectId: "Your Firebase Project ID",
    storageBucket: "Your Firebase Storage Bucket",
    messagingSenderId: "Your Firebase Sender ID",
    appId: "Your Firebase App ID"
}
```
