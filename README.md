Chat Application

This is a WhatsApp Web-like chat application built using React.js, InstantDB, and IndexedDB. It features a responsive and user-friendly design for real-time messaging with offline capabilities.

Features

Core Functionality

Contact List: Displays a list of contacts on the left sidebar.

Chat Window: Shows the chat history for a selected contact on the right.

Send Messages: Includes a message input field to send new messages.

Add New Contacts: Allows users to manually add new contacts with names and phone numbers.

Real-Time Data and Offline Support

Real-Time Messaging: Integrates with InstantDB for real-time message storage and retrieval.

Offline Support: Uses IndexedDB to store data locally, ensuring seamless operation even when offline.

Modern UI/UX

Responsive Design: Fully responsive interface that adapts to different screen sizes.

Styling with Material-UI (MUI): Leverages MUI components and styling for a sleek look.

Timestamp Display: Messages include timestamps in small, oval-shaped containers for clarity.

App Branding: Displays an app logo and maintains a professional look and feel.

Technologies Used

Frontend

React.js: Core framework for building the application.

Material-UI (MUI): Provides pre-styled UI components and customization.

CSS: For custom styles and layout adjustments.

Backend and Data Management

InstantDB: Handles real-time data synchronization.

IndexedDB: Enables local storage for offline capabilities.

Project Structure

├── public/
│   ├── index.html
│   ├── vite.svg
├── src/
│   ├── components/
│   │   ├── AddContactForm/
│   │   │   ├── AddContactForm.jsx
│   │   │   ├── AddContactForm.styles.js
│   │   ├── ChatWindow/
│   │   │   ├── ChatWindow.jsx
│   │   │   ├── ChatWindow.styles.js
│   │   ├── ContactList/
│   │   │   ├── ContactList.jsx
│   │   │   ├── ContactList.styles.js
│   │   ├── MessageInput/
│   │   │   ├── MessageInput.jsx
│   │   │   ├── MessageInput.styles.js
│   ├── context/
│   │   ├── ChatContext.jsx
│   ├── main.jsx
│   ├── App.jsx
├── package.json

Setup and Installation

Clone the Repository:

git clone https://github.com/your-repository/chat-app.git
cd chat-app

Install Dependencies:

npm install

Run the Application:

npm run dev

Open in Browser:
Navigate to http://localhost:3000.

Usage


Sending Messages

Select a contact from the list.

Type your message in the message input field.

Press Enter or click the "Send" button to send the message.

Real-Time Messaging

Messages will update in real-time for all users connected to the app.

Development Notes

React Context and Hooks

React Context: Manages global state for contacts and messages.

useReducer: Handles state updates efficiently.

Custom Hooks: Reusable logic for IndexedDB and InstantDB integration.

Material-UI Styling

@mui/material: Provides pre-built React components.

@mui/system: Enables custom styling using makeStyles and other utilities.

IndexedDB Integration

Local data is cached to IndexedDB, ensuring that users can:

View previous messages.

Send messages while offline (pending sync).

Future Enhancements

User Authentication: Implement login/logout functionality.

Group Chats: Allow group conversations.

Message Search: Add a search bar to find specific messages.

Notifications: Real-time notifications for new messages.

File Sharing: Enable sharing images, videos, and documents.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Contact

For questions or feedback, feel free to reach out at [prakhar.tripathi1998@example.com].

