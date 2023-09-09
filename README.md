# Discord Clone

![Discord Clone]([link_to_your_image_here](https://images-eds-ssl.xboxlive.com/image?url=Q_rwcVSTCIytJ0KOzcjWTYl.n38D8jlKWXJx7NRJmQKBAEDCgtTAQ0JS02UoaiwRCHTTX1RAopljdoYpOaNfVf5nBNvbwGfyR5n4DAs0DsOwxSO9puiT_GgKqinHT8HsW8VYeiiuU1IG3jY69EhnsQ--&format=source))

This is a full-stack, real-time Discord clone built using Next.js 13, React, Socket.io, Prisma, Tailwind CSS, and MySQL. It offers a comprehensive set of features, including servers, channels, video calls, audio calls, message editing and deletion, member roles, and much more. This README will guide you through the setup and provide an overview of the key features.

## Table of Contents

- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Key Features

- **Real-time Messaging:** Utilizing Socket.io to provide real-time messaging for a seamless chat experience.
- **Attachments:** Send attachments as messages using UploadThing.
- **Message Editing & Deletion:** Edit and delete messages in real-time for all users.
- **Channel Types:** Create text, audio, and video call channels.
- **1:1 Conversations:** Have private 1:1 conversations between members.
- **1:1 Video Calls:** Initiate video calls between members.
- **Member Management:** Administer members by kicking, changing roles, or assigning guest/moderator status.
- **Invite System:** Implement a fully functional invite system with unique invite link generation.
- **Infinite Message Loading:** Utilize `@tanstack/query` to load messages in batches of 10.
- **Server Customization:** Create servers and customize them to your liking.
- **Beautiful UI:** Crafted using Tailwind CSS and ShadcnUI for a stunning user interface.
- **Responsiveness:** Achieve full responsiveness and optimize for mobile UI.
- **Light / Dark Mode:** Offer both light and dark mode themes for users.
- **Websocket Fallback:** Implement a WebSocket fallback with polling and alerts for reliability.
- **ORM Using Prisma:** Utilize Prisma for object-relational mapping.
- **MySQL Database:** Employ MySQL database hosted on Planetscale.
- **Authentication:** Implement authentication with Clerk.

## Technologies Used

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Socket.io](https://socket.io/)
- [Prisma](https://prisma.io/)
- [Tailwind CSS](https://tailwindcss.com/)
- [ShadcnUI](https://shadcn.com/)
- [MySQL](https://www.mysql.com/)
- [Planetscale](https://planetscale.com/)
- [Clerk](https://clerk.dev/)

## Getting Started

Follow these steps to set up and run the Discord clone locally:

1. Clone this repository: `git clone https://github.com/yourusername/discord-clone.git`
2. Change to the project directory: `cd discord-clone`
3. Install dependencies: `npm install`
4. Set up your MySQL database on Planetscale.
5. Configure your environment variables for Prisma and Clerk.
6. Run the migrations and seed data with Prisma: `npx prisma migrate dev && npx prisma db seed --preview-feature`
7. Start the development server: `npm run dev`
8. Open your browser and access the app at `http://localhost:3000`

## Usage

1. Register or log in using Clerk for authentication.
2. Create a server or join an existing one.
3. Customize your server by adding channels and inviting members.
4. Start chatting, making audio and video calls, managing members, and exploring all the features of the Discord clone.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Feel free to reach out to the maintainers or open issues for any questions or concerns. Happy coding!
