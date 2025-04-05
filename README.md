# To-Do List App ⭐

The To-Do List App is a Node.js, Express, MongoDB, and EJS templating engine-based application designed to help users efficiently manage their tasks.

### Click Here to Open [To-Do List App](https://to-do-list-rz0n.onrender.com/)

![Todo App Preview](https://github.com/AmanKumarSinhaGitHub/To-Do-List-App/assets/65329366/3e810143-7dbd-46d5-a21d-1bea26a731dc)

## Prerequisites

Before running this project, ensure you have the following installed:

- Node.js: [Download and Install Node.js](https://nodejs.org/en/download)
- MongoDB: [Download and Install MongoDB](https://www.mongodb.com/try/download/community)

## Installation

Follow these steps to set up the application:

1. Clone the repository to your local machine:

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

2. Start MongoDB:

   ```bash
   mongod
   ```

3. Open another PowerShell window.

4. Launch the MongoDB shell:

   ```bash
   mongosh
   ```

5. Navigate to the project directory:

   ```bash
   cd To-Do-List-App
   ```

6. Start the application using nodemon:

   ```bash
   nodemon .\app.js
   ```

   **Note: If you encounter a "nodemon not recognized" error, install nodemon globally:**

   ```bash
   npm install -g nodemon
   ```

7. Open a web browser and navigate to [localhost:3000](http://localhost:3000) to access the application.

### Important: ⚠️

**Set up backend connection locally:**

- If running this project locally, uncomment the following code in `app.js`:

   ```js
   mongoose.connect("mongodb://127.0.0.1:27017/todolistDB");
   ```

   And comment out the below code in ```app.js```:

   ```js
   // const DB = process.env.DATABASE;
   // mongoose.connect(DB)
   ```

## Usage

- **Home Page (http://localhost:3000):** Default page showing the "Today" list. Add new items by typing in the input field and clicking the "+" button.

- **Custom Lists:** Create custom lists by adding a name in the URL (e.g., http://localhost:3000/work). Add items and access the list using the specified name.

- **Deleting Items:** Click the checkbox next to an item to mark it as completed and automatically remove it from the list.

- **About Page (http://localhost:3000/about):** Information about the To-Do List application.

## Project Structure

- `app.js:` Main entry point of the application. Configures the server, sets up routes, and connects to the database.

   **Models:**

   - `Item:` Model for individual to-do list items.
   - `List:` Model for custom lists.

- `public:` Directory containing static files such as CSS stylesheets.
   - `styles.css:` CSS stylesheets for the application.

- `views:` Directory containing EJS templates used to render HTML pages.

   - `header.ejs:` Header template included in other EJS files.
   - `footer.ejs:` Footer template included in other EJS files.
   - `list.ejs:` Template for the to-do list page.
   - `about.ejs:` Template for the about page.

## Contributing

Contributions are welcome! Please follow the steps below to contribute to the project:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them:

   ```bash
   git add .
   git commit -m "Add your meaningful commit message"
   ```

4. Push your changes to your forked repository:

   ```bash
   git push origin feature/your-feature-name
   ```

5. Open a pull request on the original repository.

### Code Style Guidelines

- Follow the existing code style and structure.

- Write meaningful commit messages.

### Bug Reporting

If you encounter any bugs or issues, please open an issue with a detailed description of the problem, steps to reproduce, and your system/environment information.

## Acknowledgments

This project was created using Node.js, Express, MongoDB, and the EJS templating engine. Special thanks to the authors and contributors of these technologies.

## 🚀 About Me

I'm a final-year BCA undergraduate and a full-stack developer.

### Contact Details

- Email: amankrsinha07@gmail.com
- LinkedIn Profile: [@AmanKumarSinha](https://www.linkedin.com/in/amankumarsinha)

## Checkout my new TO DO LIST app in REACT
- GitHub link - https://github.com/AmanKumarSinhaGitHub/React-To-Do-List-App
- LIVE demo - https://amankumarsinhagithub.github.io/React-To-Do-List-App/
- Addition feature of this app : Your to-do list is automatically saved to local storage. This means your tasks will stay even if you refresh the page or reopen the app.

## License

This project is licensed under the [MIT License](LICENSE).

