# Collaborative Note-Taking Web App

## Overview

This project implements a collaborative note-taking web application that supports real-time collaboration using WebSockets. The application allows users to create, edit, and share notes while rendering content using Markdown. Built with React.js for the frontend and Node.js for the backend, it utilizes PostgreSQL as the database and Tailwind CSS for styling.

## Features

- **Real-Time Collaboration**: Multiple users can edit notes simultaneously, and changes are reflected instantly using WebSockets.
- **Markdown Support**: Users can format their notes using Markdown, which is rendered with the Marked library.
- **User Authentication**: Secure login and registration functionality to manage user access to notes.
- **Responsive Design**: Built with Tailwind CSS to ensure a responsive and modern user interface.
- **API Integration**: Provides a GraphQL API for interaction between the frontend and backend.
- **PostgreSQL Database**: Normalized to 3NF to efficiently store and manage user notes.

## React Client:

### How to run:

```sh
cd my-note-app
pnpm install
pnpm run dev
```

## PostGres Server:

### How to run:

```sh
cd my-note-app/my-note-app-backend
pnpm install
node serve.js
```
