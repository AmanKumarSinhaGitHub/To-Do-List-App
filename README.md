# To-Do List App ⭐
by nikhil dodtalle

The To-Do List App is a **Node.js, Express, MongoDB, and the EJS templating engine** based application designed to help users manage their tasks efficiently.

![todo_app_preview](https://github.com/AmanKumarSinhaGitHub/To-Do-List-App/assets/65329366/3e810143-7dbd-46d5-a21d-1bea26a731dc)

## Prerequisites
Before running this project, make sure you have the following installed:

* Node.js: [Download and Install Node.js](https://nodejs.org/en/download "Node.js Download")

* MongoDB: [Download and Install MongoDB](https://www.mongodb.com/try/download/community "MongoDB Download")

## Installation 

Follow these steps to set up the application:

1. Open Powershell/Terminal and Clone the repository to your local machine:

   ```bash
   git clone https://github.com/AmanKumarSinhaGitHub/To-Do-List-App.git
   ```

2. Navigate to the project directory:

   ```bash
   cd To-Do-List-App
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Install additional packages:

   ```bash
   npm install mongoose lodash
   ```

## Get Started

To run the To-Do List App, perform the following actions:

1. Open a new PowerShell window.

2. Start the MongoDB:

   ```bash
   mongod
   ```

3. Open another PowerShell window.

4. Launch the MongoDB shell:

   ```bash
   mongosh
   ```

5. Open another PowerShell window and Navigate to the project directory:

   ```bash
   cd To-Do-List-App
   ```

6. Start the application using nodemon:

   ```bash
   nodemon .\app.js
   ```

7. Open a web browser and navigate to [localhost:3000](http://localhost:3000) to access the application. Use [localhost:3000/work](http://localhost:3000/work) and whatever you want to create new todo list.

## Usage
* __Home Page (http://localhost:3000):__ This is the default page that shows the "Today" list. 
You can add new items to the list by typing in the input field and clicking the "+" button.

* __Custom Lists:__ You can create custom lists by adding a name in the URL (e.g., http://localhost:3000/work). You can then add items to the custom list and access it using the specified name.

* __Deleting Items:__ To delete an item, click on the checkbox next to the item. It will be marked as completed and automatically removed from the list.

* __About Page (http://localhost:3000/about):__ This page provides information about the To-Do List application.

## Project Structure
The project structure is as follows:

* `app.js:` The main entry point of the application. It configures the server, sets up the routes, and connects to the database.
   
   **Models:** "_app.js_" contains the Mongoose models for the database schema.

   * `Item:` The model for individual to-do list items.
   * `List:` The model for the custom lists.

* `public:` This directory contains static files such as CSS stylesheets.
   * `styles.css:` This file contains the CSS stylesheets for the application.

* `views:` This directory contains the EJS templates used to render the HTML pages.

   * `header.ejs:` The header template that is included in other EJS files.

   * `footer.ejs:` The footer template that is included in other EJS files.

   * `list.ejs:` The template for the to-do list page.

   * `about.ejs:` The template for the about page.
---

## Contributing
Contributions are welcome! 

If you have any suggestions or improvements, feel free to create an issue or submit a pull request.

---
## Acknowledgements
This project was created using Node.js, Express, MongoDB, and the EJS templating engine. 

Special thanks to the authors and contributors of these technologies for their valuable work. 

Additionally, I would like to express my gratitude to my instructor [Angela Yu](https://twitter.com/yu_angela "Twitter") for her guidance and support throughout the development of this project.

---

## 🚀 About Me

* I'm a final year BCA undergraduate and a full-stack developer.


### Contact Details
* Email: amankrsinha07@gmail.com

* LinkedIn Profile: [@AmanKumarSinha](https://www.linkedin.com/in/amankumarsinha)

---
