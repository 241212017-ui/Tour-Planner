# Tour Planner

Tour Planner is a modern travel-planning web application that helps users create personalized trip itineraries using artificial intelligence. Users can enter their destination, trip duration, budget, and travel preferences to receive a customized travel plan with suggested hotels and places to visit.

## Overview

This project combines a sleek React frontend with AI-generated travel recommendations to make trip planning faster, smarter, and more convenient. It is designed for travelers who want a quick, structured, and personalized vacation plan without manually researching every detail.

## Key Features

- AI-generated travel itineraries
- Destination-based trip planning
- Budget and traveler-type customization
- Google authentication for secure access
- Saved trip history powered by Firebase
- Responsive and modern user interface

## Tech Stack

- React.js
- Vite
- Tailwind CSS
- Firebase Firestore
- Google Gemini AI
- Google Places API
- React Router DOM
- Radix UI components

## Project Structure

- src/components: Reusable UI components
- src/create-trip: Trip generation flow
- src/my-trips: Saved trip management
- src/view-trip: Detailed trip viewing experience
- src/service: Firebase and AI integration logic

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm or yarn

### Installation

1. Clone the repository
2. Navigate to the frontend folder
3. Install dependencies:

```bash
npm install
```

### Environment Variables

Create a .env file in the frontend folder and add the following variables:

```env
VITE_GEMINI_API_KEY=your_gemini_api_key
VITE_GOOGLE_MAP_API=your_google_maps_api_key
```

### Run the Application

```bash
npm run dev
```

The application will start locally in your browser.

## Usage

1. Sign in with Google
2. Enter your preferred destination
3. Select trip duration, budget, and traveler type
4. Generate your trip plan
5. View and manage your saved trips

## How It Works

The app collects your travel preferences, sends them to the AI model, and generates a structured itinerary with hotel suggestions and location recommendations. The generated trip is then saved to Firebase so you can revisit it later.

## Screenshots

The screenshot files are located in `frontend/screenshots/`.

If you want, you can place the actual screenshot files in `frontend/screenshots/` using the above filenames.

## Contributing

Contributions are welcome. If you would like to improve the project, feel free to fork the repository and submit a pull request.

## Contact

For questions or collaboration, contact 241212017-ui via GitHub: [241212017-ui](https://github.com/241212017-ui)

## Firebase Setup

The app uses Firebase Firestore to store generated trips. If you want to use your own Firebase project, update the configuration in the Firebase service file.

## Author

- Name: 241212017-ui
- GitHub: [241212017-ui](https://github.com/241212017-ui)

## License

This project is open-source and available for educational and personal use.
