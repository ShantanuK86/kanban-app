# Kanban App

A modern and intuitive kanban application built with React and hosted on Firebase. Streamline your workflow and boost productivity with this powerful task management tool.

## Features

- Create boards to organize your projects
- Add tasks with descriptions, due dates, and priorities
- Drag and drop tasks between columns (To Do, In Progress, Done)
- Real-time updates with Firebase Realtime Database
- User authentication with Firebase Authentication
- Responsive design for optimal viewing on various devices

## Technologies Used

- React
- Firebase (Authentication, Realtime Database, Hosting)
- React Beautiful DnD (for drag and drop functionality)
- React Bootstrap (for styling)

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Create a Firebase project and enable Authentication and Realtime Database
4. Update the Firebase configuration in `src/firebase.js`
5. Start the development server: `npm start`
6. Open `http://localhost:3000` in your browser

## Deployment

This app is deployed on Firebase Hosting. To deploy your own instance:

1. Install Firebase Tools: `npm install -g firebase-tools`
2. Login to Firebase: `firebase login`
3. Initialize the project: `firebase init`
4. Build the app: `npm run build`
5. Deploy to Firebase: `firebase deploy`

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.
