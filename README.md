# 🚀 Triangle of Knowledge

Welcome to Triangle of Knowledge! This project is built using modern web technologies like **TypeScript**, **React**, **NestJS**, and **MongoDB**, and is containerized using **Docker**. The app consists of a client-side application and a backend server.

## Prerequisites

Before you start, ensure you have the following installed:

- 🟢 [Node.js](https://nodejs.org/) – JavaScript runtime built on Chrome's V8 engine (npm comes with Node)
- 🐳 [Docker](https://www.docker.com/) – Containerization platform for building, sharing, and running applications

## Getting Started

To run the project locally, follow these steps:

1. 📁**Clone the repository:**
   ```bash
   git clone https://github.com/alexandermirzoyan/triangle-of-knowledge.git
   cd triangle-of-knowledge.git
   ```
2. 🌐**Clone client and server:**
   Run the following command to clone the client and server components automatically:
   ```bash
   npm run clone
   ```
3. 🚀**Start the application:**
   Set up environment variables, start Docker containers, and run the app with:
   ```bash
   npm run start
   ```
4. ✉️**Mailing Configuration:** \
   To enable the mailing system (for user registration), you need to configure the mailing settings in the server: \
   - Navigate to the `triangle-of-knowledge-api.git` directory.
   - Set up the required mailing environment variables (e.g., SMTP credentials) in the `.env` file.
   - Once configured, the mailing system will send registration emails to users.

The client will run on http://localhost:3000. \
The server will run on http://localhost:5000.

## Technologies Used

- 🟦 **TypeScript** – Typed superset of JavaScript
- ⚛️ **React** – A JavaScript library for building user interfaces
- 🚀 **NestJS** – A progressive Node.js framework for building server-side applications
- 🍃 **MongoDB** – NoSQL database for modern applications
- 🐳 **Docker** – Containerization platform for building, sharing, and running applications

## License

This project is licensed under the [MIT License](LICENSE).

Made with ❤️ by [Miqayel Srapionyan](https://github.com/miqo-srapionyan)
