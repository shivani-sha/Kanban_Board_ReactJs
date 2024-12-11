# **Kanban Board Application**

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), a popular toolchain for setting up React projects quickly and efficiently. It provides an intuitive Kanban board to manage tasks across stages like **To Do**, **In Progress**, **Peer Review**, and **Done**.

---

## **Available Scripts**

In the project directory, you can run:

### **`npm start`**
- Starts the development server and runs the app in development mode.
- Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.
- The page reloads automatically when you make changes to the code.
- Any lint errors will appear in the console.

### **`npm test`**
- Launches the test runner in interactive watch mode.
- For more information, refer to the [Running Tests](https://create-react-app.dev/docs/running-tests/) section of the Create React App documentation.

### **`npm run build`**
- Builds the app for production, optimizing it for the best performance.
- Outputs a production-ready version of your app to the `build` folder.
  - The build is minified, and filenames include unique hashes.
  - Your app will be ready for deployment.

### **`npm run eject`**

> **Note:** This is a one-way operation. Once you eject, you cannot undo this step.

- **What it Does**:
  - Removes the single build dependency (`react-scripts`) from your project.
  - Copies all configuration files and dependencies (e.g., Webpack, Babel, ESLint) directly into your project for full control.
- **Post-Ejection**:
  - All existing commands (except eject) will still work.
  - However, they will now reference the copied scripts instead of the original `react-scripts` package.
- **Recommendation**: Avoid ejecting unless absolutely necessary.

---

## **Features**

### 🛠️ **Kanban Board**
- **Four Columns** for managing tasks:
  - **To Do**: Tasks yet to be started.
  - **In Progress**: Tasks currently being worked on.
  - **Peer Review**: Completed tasks awaiting review.
  - **Done**: Fully completed and reviewed tasks.

### 🗂️ **Task Cards**
- **Title and Description**: Display essential task information.
- Fully **draggable** for seamless workflow management.

### 🎯 **Drag-and-Drop**
- Move tasks between columns and reorder them within columns.

### 🔍 **Search Functionality**
- Filter tasks by title using a real-time search bar.

### ➕ **Add New Tasks**
- Use a floating button to create new tasks, which are added to the **To Do** column.

### 📱 **Responsive Design**
- Works flawlessly on desktops, tablets, and mobile devices.

---

## **Technologies Used**
- **ReactJS**: Core framework for building the UI.
- **Redux**: State management.
- **React-DnD**: Drag-and-drop functionality.
- **Material-UI**: Styling and design.
- **Local Storage**: Persists task data across sessions.

---

## **Getting Started**

### **Prerequisites**
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (with npm)

### **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/shivani-sha/Kanban_Board_ReactJs
   cd kanban-board
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```
   Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

### **Building for Production**
To build the app for deployment:
```bash
npm run build
```

---

## **Usage**

### Creating a New Task
- Click the floating "+" button.
- Enter the task title and description.
- Click **Create** to add the task to the **To Do** column.

### Moving Tasks
- Drag a task card to the desired column.
- Reorder tasks within a column using drag-and-drop.

### Searching Tasks
- Type in the search bar to filter tasks by title.
- Only tasks matching your query will remain visible.

---


## **License**

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it.

---

### **Learn More**

- [Create React App Documentation](https://create-react-app.dev/docs/getting-started/)
- [React Documentation](https://reactjs.org/)
