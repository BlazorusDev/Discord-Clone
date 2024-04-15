# Discord Clone

Welcome to the Discord Clone project! This is a feature-rich messaging application designed to replicate the popular Discord platform. It offers real-time messaging, attachment sharing, voice and video calls, advanced member management, and more. Below, we provide essential information to set up and use this Discord clone effectively.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

Before you begin, ensure you have the following tools and dependencies installed on your system:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Mohit-Mehra/Discord-Clone.git
   ```

2. Install server dependencies:

   ```bash
   npm install  # or yarn install
   ```

3. Create a `.env` file and configure your environment variables. You can use `.env.example` as a template.

4. Migrate the database using Prisma:

   ```bash
   npx prisma migrate dev
   ```

5. Start the server:

   ```bash
   npm run dev  # or yarn dev
   ```

## Usage

1. Open your web browser and navigate to `http://localhost:3000` to access the Discord clone.
2. Create an account or log in to an existing one.
3. Explore the chat rooms, send messages, and upload files.

## Key Features

### Real-time Messaging

Our application leverages Socket.io to provide a seamless real-time messaging experience. Chat with other users and witness instant message delivery.

### Attachment Support

Share files effortlessly by sending attachments as messages through the UploadThing feature.

### Message Editing and Deletion

Enjoy the ability to edit and delete messages in real-time, with all changes reflecting across all users in the conversation.

### Voice and Video Calls

Create text, audio, and video call channels for efficient communication with other members.

### Private Conversations

Initiate 1:1 conversations with other members for private discussions.

### Video Calls

Engage in 1:1 video calls with other members for face-to-face conversations.

### Member Management

Moderators have the power to manage members by kicking them from channels or altering their roles, ensuring a safe and organized server environment.

### Invite System

Generate unique invite links for your server and establish a fully functional invite system to invite new members.

### Infinite Message Loading

Messages load infinitely in batches of 10, offering a smooth user experience, thanks to the @tanstack/query library.

### Server Customization

Create and customize servers to tailor them to your specific needs.

### Beautiful UI

We've meticulously designed a visually appealing user interface using TailwindCSS and ShadcnUI, providing an intuitive and aesthetically pleasing experience.

### Responsiveness

Our application boasts full responsiveness, making it accessible on various devices, including mobile phones.

### Light and Dark Mode

Easily switch between light and dark modes to suit your preferences and reduce eye strain during nighttime use.

### Websocket Fallback

In case of WebSocket issues, our system gracefully falls back to polling with alerts to ensure uninterrupted communication.

### ORM and Database

Our application employs Prisma as its Object-Relational Mapping (ORM) tool and stores data in a MySQL database hosted on Planetscale.

### Authentication

User authentication is seamlessly handled by Clerk, ensuring the utmost security for your application.

## Technologies Used

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Prisma](https://www.prisma.io/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Socket.io](https://socket.io/)
- [UploadThings](https://uploadthing.com/)

## Contributing

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your fork and submit a pull request to the main branch