# Monsters RPG game
Welcome to the RPG Backend Organization!

## 1. Overview
Our organization is dedicated to providing robust, scalable, and open-source backend solutions for RPGs. We leverage Service-Oriented Architecture (SOA) principles and Node.js technology to empower game developers with flexible and efficient backend systems. Most of our projects are still WIP.

## 2. Features
- SOA Architecture: Our backend is designed using Service-Oriented Architecture, promoting modularity, scalability, and maintainability.
- Node.js Powered: Built with Node.js.
- Open Source: All our projects are open-source, fostering collaboration and community-driven development.
- Scalable: Our solutions are designed to scale effortlessly to accommodate the needs for all players.
- Flexible: With modular components, developers can easily customize and extend the backend to suit their specific game requirements.

## 3 Projects
Here are the projects currently available in our organization:

### 3.1 [Gateway](https://github.com/Monsters-RPG-game/Monsters-gateway)
Gateway is service created with express.js. It controlls authenitcation, data caching and user's requests. Its main point of this project, managing every other service involved.

### 3.2 [Users](https://github.com/Monsters-RPG-game/Monsters-users)
Users is another part of this project, managing user's accounts, in-game characters, inventories and user statistics.

### 3.3 [Messages](https://github.com/Monsters-RPG-game/Monsters-messages)
Messages communication system created to consume user messages and live chat.

### 3.4 [Fights](https://github.com/Monsters-RPG-game/Monsters-fights)
Fights is one of most important parts of this application. Its job is to manage battles, handle user's stats based on equimpent, rase and skill points.

### 3.5 [Fights](https://github.com/Monsters-RPG-game/Monsters-fights)
Maps is movment controller, managing where each user is located and how each  field should look like

### 3.6 [Web client](https://github.com/Monsters-RPG-game/Monsters-WebClient)
In currect state our project has only 1 client which is written in Vite with React, styled with tailwind. This client is text-based. In the future, we are planning on making desktop client or mobile client.

### 3.7 [Docs](https://github.com/Monsters-RPG-game/Monsters-Docs)
Gateway, as main point of entry includes swagger documentation. You can also find website with deeper explanantion of how things work, including UML diagrams.

### 3.8 [Head](https://github.com/Monsters-RPG-game/Monsters-head)
Head is simple project, containing scripts and settings to autmate preparing whole backend infrastructure. It includes docker configs, k8s configs and shell scripts to fasten whole process.

## Getting Started
To get started with our backend solutions, follow these steps:

- Clone the Repository
If you want to include every service, clone [Head](https://github.com/Monsters-RPG-game/Monsters-head) project and foolow instructions in `readme.md`. If you want only 1 service:

- Clone the repository
```shell
git clone <repository-url>
```

- Install dependencies
```shell
cd <project-directory>
npm install / yarn
```

- Configure the config files. Each service includes information about it in `readme.md`

- Start coding
```shell
npm start:dev / yarn start:dev
```

## 4. Contributing
We welcome contributions from the community! Whether it's bug fixes, feature enhancements, or documentation improvements, your contributions are valuable to us. To contribute, follow these steps:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Create new issue with proper description of what would you like to contribute
- Make your changes and commit them with `#taskNumber` and descriptive messages.
- Push your changes to your fork.
- Submit a pull request to the development repository ( in most cases `dev` ), explaining the purpose of your changes.
- For more details, please refer to the Contribution Guidelines.

## 5. License
All backend services are currently licenced under Apache 2.0 licence.

## 6. Live examples
- You can find docs website [here](https://docs.kiszczyc.pl/)

### 6.1 Production env
- Client is currectly deployed [here](https://kiszczyc.pl)
- Backend is currectly deployed [here](https://api.kiszczyc.pl)
- You can find swagger docs in [here](https://api.kiszczyc.pl/docs)

### 6.2 Development / Test env
Test env does not include client and it is open for our developers to work with clients on their machines. This env might include changes, which will break something.
- Backend is currectly deployed [here](https://test.api.kiszczyc.pl)
- You can find swagger docs in [here](https://test.api.kiszczyc.pl/docs)
