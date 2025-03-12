# CommunionHub React Project

A responsive React web application for connecting people of all faiths through events and community support.

## 📋 Overview

CommunionHub is a platform designed to bring together people across different faiths and interests. The application allows users to browse events, filter them by category, and add new events to the platform.

## ✨ Features

- **Home Page**: Welcoming landing page with information about CommunionHub
- **Events Page**: Browse, filter, and add community events
- **Responsive Design**: Fully responsive UI for both desktop and mobile devices
- **Animations**: Smooth transitions and animations powered by Framer Motion
- **Persistent Storage**: Event data persists between sessions using local storage

## 🛠️ Technologies Used

- React.js
- React Router DOM
- Styled Components
- Framer Motion
- Context API for state management
- Local Storage for data persistence

## 🚀 Getting Started

### Prerequisites

- Node.js (v14.0.0 or later)
- npm (v6.0.0 or later)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/communion-hub.git
   cd communion-hub
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Start the development server
   ```bash
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000`

## 📁 Project Structure

```
communion-hub/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── EventCard.js
│   │   ├── AddEventForm.js
│   │   └── Loading.js
│   ├── context/
│   │   └── EventContext.js
│   ├── pages/
│   │   ├── HomePage.js
│   │   └── EventsPage.js
│   ├── App.js
│   ├── App.css
│   └── index.js
├── package.json
├── README.md
└── vercel.json
```

## 🌐 Deployment

This project is configured for easy deployment to Vercel:

1. Push your code to a GitHub repository
2. Connect your repository to Vercel
3. Vercel will automatically detect the React configuration and deploy your application

Alternatively, you can deploy manually:

```bash
npm run build
```

Then upload the contents of the `build` folder to your hosting provider.

## 💡 Usage

- Browse the Home page to learn about CommunionHub
- Navigate to the Events page to see all community events
- Filter events by category using the dropdown menu
- Add a new event using the "Add Event" button and form

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
