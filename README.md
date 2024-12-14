# BPL-DREAM 11

## Project Overview

BPL-DREAM 11 is a React-based cricket team management application that allows users to select and manage cricket players for their fantasy team. The app is built following a specific design on Figma, where users can increase their virtual coins, select players, and manage their team within a set coin limit. The system also includes a newsletter subscription feature and validation for player selection.

---

## Live Links

**BPL-DREAM 11**: https://inspiring-tartufo-ddb990.netlify.app/

---

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Challenges and Optional Features](#challenges-and-optional-features)
- [License](#license)

---

## Features

1. **Player Management**: Users can view, select, and manage cricket players based on their available coins.
2. **Coin Limitation**: Users need to manage their coins effectively to build the best team. Coins increase on banner button click.
3. **Player Selection Validation**: The system ensures that users cannot select the same player twice, and restricts selection to a maximum of 6 players.
4. **Remove Selected Players**: Users can remove players from their selected team.
5. **Dynamic UI**: Players are displayed in a responsive card layout with details like name, country, role, and bidding price.
6. **Toast Notifications**: Real-time feedback through React-Toastify replaces standard alerts for a seamless user experience.
7. **Newsletter Subscription**: Users can subscribe to a newsletter and have their email saved using LocalStorage.

---

## Technologies Used

- **React**: Frontend library for building the user interface.
- **React-Toastify**: For enhanced notification experience.
- **JavaScript (ES6+)**: Application logic.
- **CSS**: Custom styling for UI elements and responsiveness.
- **LocalStorage**: Storing user's email subscription locally.

---

## Setup Instructions

To run the project locally, follow these steps:

1. **Clone the repository**:
   git clone https://github.com/your-username/BPL-DREAM-11.git
2. **Navigate to the project folder**:
   cd BPL-DREAM-11

3. **Install dependencies**:
   npm install

4. **Start the development server**:
   npm run dev

5. **Open the application**:
   Visit `http://localhost:3000` in your browser to view the application.

---

## Project Structure

The project structure follows a typical React app layout with separate folders for assets, components, and utility functions. Here's a high-level overview:

├── public/
├── src/
│ ├── assets/ # Images and icons used in the project
│ ├── components/ # All the UI components like Navbar, Banner, PlayerCard, etc.
│ ├── data/ # playerData.json containing details of all available players
│ ├── App.js # Main App component
│ ├── index.js # Entry point of the app
│ ├── styles/ # Global and component-specific CSS files
│ └── utils/ # Utility functions and constants
├── package.json # Project metadata and dependencies
└── README.md # Project documentation

---

## Challenges and Optional Features

### Challenges

- **Validation on Player Selection**:
  - Users cannot select the same player twice.
  - The system alerts the user if they attempt to select more than 6 players.
- **Toast Notifications**:
  - Replaced all standard alerts with `React-Toastify` for better UX.

### Optional Features

- **Newsletter with LocalStorage**:  
  Users who subscribe to the newsletter will have their email stored in LocalStorage. Upon revisiting, a personalized message will greet them.

---

## Future Enhancements

1. **User Authentication**: Add user login and authentication to personalize player selections.
2. **Leaderboard**: Implement a leaderboard to track and display the highest-rated teams.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Author

Developed by **Maksudul Haque**. Connect with me on [GitHub](https://github.com/smmaksudulhaque2000) or [LinkedIn](https://www.linkedin.com/in/maksudulhaque2000/).
