# **Kanban Board Application**

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), a popular toolchain for setting up React projects quickly and efficiently.

---

## **Available Scripts**

In the project directory, you can run:

### **`npm start`**
- Starts the development server and runs the app in development mode.
- Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.
- The page reloads automatically when you make changes to the code.
- Any lint errors will appear in the console.

---

### **`npm test`**
- Launches the test runner in interactive watch mode.
- For more information, refer to the [Running Tests](https://create-react-app.dev/docs/running-tests/) section of the Create React App documentation.

---

### **`npm run build`**
- Builds the app for production, optimizing it for the best performance.
- Outputs a production-ready version of your app to the `build` folder.
  - The build is minified, and filenames include unique hashes.
  - Your app will be ready for deployment.

For additional details, visit the [Deployment Guide](https://create-react-app.dev/docs/deployment/).

---

### **`npm run eject`**

> **Note:** This is a one-way operation. Once you eject, you cannot undo this step.

- **What it Does**:
  - Removes the single build dependency (`react-scripts`) from your project.
  - Copies all configuration files and transitive dependencies (e.g., Webpack, Babel, ESLint) directly into your project.
  - Provides full control over the configuration, allowing you to modify it as needed.

- **Post-Ejection**:
  - All existing commands (except `eject`) will still work.
  - However, they will now reference the copied scripts instead of the original `react-scripts` package.

- **Recommendation**:
  - Ejecting is rarely necessary and is only recommended if you require significant customization of the configuration (e.g., for advanced Webpack modifications).
  - Consider alternative approaches like creating a custom Webpack configuration or using tools like [Craco](https://github.com/dilanx/craco) before resorting to ejecting.

---

## **Learn More**

- For a deeper understanding of Create React App, refer to the official [Create React App documentation](https://create-react-app.dev/docs/getting-started/).
- To learn React itself, explore the official [React documentation](https://reactjs.org/).

---

## **Additional Guides**

### **Code Splitting**
- Learn how to split your code for optimized performance: [Code Splitting Guide](https://create-react-app.dev/docs/code-splitting/).

### **Analyzing the Bundle Size**
- Optimize your app's performance by analyzing its bundle size: [Guide to Analyzing Bundle Size](https://create-react-app.dev/docs/analyzing-the-bundle-size/).

### **Making a Progressive Web App**
- Transform your app into a Progressive Web App (PWA): [PWA Guide](https://create-react-app.dev/docs/making-a-progressive-web-app/).

### **Advanced Configuration**
- For advanced customization options, refer to: [Advanced Configuration](https://create-react-app.dev/docs/advanced-configuration/).

### **Deployment**
- Learn how to deploy your app to various platforms: [Deployment Guide](https://create-react-app.dev/docs/deployment/).

### **`npm run build` Fails to Minify**
- Troubleshooting guide for minification issues: [Build Fails to Minify](https://create-react-app.dev/docs/troubleshooting/#npm-run-build-fails-to-minify).

---

# Kanban Board Application

This Kanban board application allows users to manage tasks across different stages: To Do, In Progress, Peer Review, and Done. The board supports drag-and-drop functionality for task movement and includes a search box to filter tasks by title.

## **Features**

### 🛠️ **Kanban Board**
- **Four Columns** representing task stages:
  - **To Do**: Tasks to be started.
  - **In Progress**: Tasks currently being worked on.
  - **Peer Review**: Completed tasks under review.
  - **Done**: Fully completed tasks.
- Tasks are visually categorized and easy to manage.

### 🗂️ **Task Cards**
- Each card displays:
  - **Task Title**: Shown prominently for quick identification.
  - **Task Description**: Brief details of the task.
- Fully **draggable** between columns for efficient workflow management.

### 🎯 **Drag-and-Drop Functionality**
- Move tasks seamlessly between columns.
- Rearrange tasks within the same column to set priorities.

### 🔍 **Real-Time Search**
- **Search Bar** at the top of the board filters tasks by title.
- Only tasks matching the query remain visible.

### ➕ **Add New Tasks**
- A **floating button** allows you to create tasks quickly.
- Newly added tasks are displayed in the **To Do** column.

### 📱 **Responsive Design**
- The layout adapts to different screen sizes, making it usable on desktops, tablets, and mobile devices.

## Technologies Used

- ReactJS
- Redux
- React-DnD (for drag-and-drop functionality)
- Material-UI (for styling)
- Local Storage (for data persistence)

## Getting Started

### Prerequisites

- npm 

### Installation

1. Clone the repository:

bash
git clone https://github.com/shivani-sha/Kanban_Board_ReactJs
cd kanban-board

2. Install dependencies:

   ```bash
   npm install
3. Start the development server:

   ```bash
   npm start


## Usage

### Creating a New Task
- Click the floating button to open the new task modal.
- Fill in the task title and description.
- Click **"Create"** to add the task to the **To Do** column.

### Moving Tasks
- Drag a task card to move it to a different column.
- Drop the task card in the desired column.

### Searching Tasks
- Type in the search bar to filter tasks by title.
- Matching tasks will be displayed, and non-matching tasks will be hidden.

---

## Features

### 1. Kanban Board Layout
- **Four Sections/Columns**:
  - **To Do**: Tasks that need to be started.
  - **In Progress**: Tasks that are currently being worked on.
  - **Peer Review**: Tasks that are completed and are awaiting review.
  - **Done**: Tasks that are completed and reviewed.
- Each section displays the tasks relevant to that stage.

### 2. Task Cards
- **Task Information**:
  - **Task Title**: Displayed prominently on the card.
  - **Task Description**: Displayed in a shortened form to fit within the card.
- **Draggable**: Tasks can be dragged and dropped between columns.

### 3. Drag and Drop Functionality
- **Drag-and-Drop**: Implemented using the React-DnD library.
- **Movement**: Tasks can be moved from one column to another.
- **Positioning**: Tasks can be placed in a specific order within a column.

### 4. Search Functionality
- **Search Bar**: Located at the top of the board.
- **Filtering**: Filters tasks based on the search input in real-time.
- **Matching Tasks**: Only tasks that match the search query are displayed.
- **Non-Matching Tasks**: Tasks that do not match the search query are hidden.

### 5. Add New Tasks
- **Floating Button**: A button that opens a modal to create new tasks.
- **Task Creation Form**:
  - **Task Title**: Input field for the task title.
  - **Task Description**: Input field for the task description.
- **New Tasks**: Created tasks are added to the **To Do** column.

### 6. Responsive Design
- **Responsive UI**: The application layout adjusts to different screen sizes, ensuring usability on both desktop and mobile devices.

### 7. State Management
- **Redux**: State management is handled using Redux.
- **Actions and Reducers**: Organized actions and reducers to manage the state of tasks.

### 8. Styling
- **Material-UI**: Used for consistent and modern styling of the application components.
- **Custom Styles**: Additional styles for specific components to ensure a polished look.

### 9. Data Persistence
- **Local Storage**: Tasks are stored in local storage, ensuring that task data persists across page reloads.

