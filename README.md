# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
# mern_client_enquery

## Client-Side (Frontend) Description

Project Title: User Inquiry Management System (Frontend)
Tech Stack: ReactJS, Axios, Tailwind CSS

## Description:
The frontend is a user-friendly interface built with ReactJS that allows users to submit inquiries and administrators to manage those inquiries. The UI provides functionality to Create, Read, Update, and Delete (CRUD) inquiries, ensuring smooth interaction with the backend API.

## Key Features:

Inquiry Submission Form: Users can submit their name, email, phone number, and a message.

Inquiry List Display: Displays all submitted inquiries in a styled, responsive table.

Edit & Update: Allows users to edit and update inquiry details.

Delete Functionality: Enables the deletion of inquiries with confirmation prompts.

Real-Time Updates: Automatically refreshes the inquiry list after submission, update, or deletion.

Notifications: Uses toast messages to provide success and error feedback.


## API Integration:

Connected to the backend through Axios to perform CRUD operations.

Uses environment-specific API URLs (development with localhost, production with the deployed server).
