# **Taskwise**

--

# **Task Management Web Application**

A full-stack task management web app that helps users efficiently manage and organize tasks by providing features like task categorization, sorting, searching, and reminders. The project also integrates various Data Structures and Algorithms (DSA) for better task handling.

## **Features**

- Create, update, and delete tasks
- Categorize tasks (Work, Personal, etc.) and set priorities (High, Medium, Low)
- Search for tasks by keywords, categories, or tags
- Sort tasks by priority, due date, or creation time
- Reminder system for upcoming tasks
- User authentication (JWT-based)
- Analytics for completed and pending tasks

## **Tech Stack**

### **Frontend**:

- React.js (or Vue.js)
- Tailwind CSS for styling

### **Backend**:

- Node.js with Express.js
- JWT for authentication

### **Database**:

- MongoDB (or MySQL)

## **Data Structures & Algorithms (DSA) Used**

1. **Task Sorting**:

   - Implemented using Quick Sort and Merge Sort to sort tasks based on priority, due date, or creation time.

2. **Task Search**:

   - Optimized search functionality with Binary Search and Hash Maps to search tasks efficiently by keywords, tags, or categories.

3. **Reminder System**:

   - Used a Min-Heap (Priority Queue) to manage reminders and notify users of tasks with the nearest deadlines.

4. **Task Scheduling**:
   - Implemented Greedy Algorithm to suggest an optimal sequence of tasks based on deadlines and priorities.

## **Project Setup**

### **Requirements**

- Node.js
- MongoDB (or MySQL)
- npm or yarn

### **Installation**

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/task-management-app.git
   cd task-management-app
   ```

2. **Install dependencies for both frontend and backend:**

   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. **Set up environment variables:**

   - Create a `.env` file in the `backend` folder.
   - Add the following environment variables:
     ```env
     MONGO_URI=your-mongodb-url
     JWT_SECRET=your-secret-key
     PORT=5000
     ```

4. **Run the application:**

   ```bash
   # Start the backend server
   cd backend
   npm run dev

   # Start the frontend
   cd ../frontend
   npm start
   ```

### **API Endpoints**

- **Task Management**:
  - `POST /tasks` - Create a new task
  - `GET /tasks` - Get all tasks
  - `PUT /tasks/:id` - Update a task
  - `DELETE /tasks/:id` - Delete a task
- **Authentication**:
  - `POST /auth/register` - Register a new user
  - `POST /auth/login` - Login user

## **Future Enhancements**

- Task collaboration (share tasks with other users)
- Task completion progress tracking
- Mobile app integration

