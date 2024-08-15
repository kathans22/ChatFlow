# ChatFlow

## Project Overview

**ChatFlow** is a Laravel-based chat application that integrates real-time communication through WebSockets, enabling instant messaging, media sharing, and group chats. The app provides features such as status indicators, notifications, and secure user authentication to ensure a smooth, secure, and efficient chatting experience for users.

## Features

- **Real-Time Communication**: Instant messaging powered by WebSockets.
- **Media Sharing**: Share images, videos, and files within chats.
- **Group Chats**: Create and manage group conversations.
- **Status Indicators**: See when users are online, typing, or have read your messages.
- **Notifications**: Receive notifications for new messages and activities.
- **Secure Authentication**: User data and chats are protected with secure authentication mechanisms.

## Technologies Used

- **Backend**: Laravel
- **Frontend**: Vite, PostCSS, Axios, Lodash
- **Real-Time Communication**: WebSockets

## Prerequisites

- PHP 8.0 or higher
- Composer
- Node.js and npm
- MySQL or any compatible database


## Installation

### 1. Clone the Repository

git clone https://github.com/your-username/chatflow.git
cd chatflow


### 2. Install Dependencies

**composer install**
**npm install**

### 3. Configure Environment

Copy the .env.example file to .env:

**cp .env.example .env**
- Update your .env file with the necessary environment variables, including your database credentials.

### 4. Generate Application Key
**php artisan key:generate**

### 5. Set Up the Database
 - Create a MySQL database for the application.
 - Run the migrations:**php artisan migrate**

### 6. Build the Frontend Assets
 - For development:
   ```bash
       npm run dev
   ```
 - For production:
     ```bash
          npm run build
   ```


### 7. Run the Application
**Start the local development server:**

```bash
php artisan serve
```

## Access the application by navigating to **http://localhost:8000** in your web browser.

# Usage
## Sign Up: Create an account to start chatting.
## Messaging: Engage in instant messaging with other users.
## Group Chats: Create and join group conversations.
## Media Sharing: Share media files in chats.
## Notifications: Stay updated with notifications for new messages and activities.

# Configuration
**The configuration for WebSockets, authentication, and other environment-specific settings should be defined in the .env file. Refer to the Laravel documentation for more details.**

# Scripts
**Development: Start the development server with Vite.**

```bash

npm run dev
```

