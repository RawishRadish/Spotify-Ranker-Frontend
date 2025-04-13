Spotify Ranker Frontend

This is the frontend application for Spotify Ranker, a tool that allows users to log in with their Spotify account and rank songs from their favorite artists. The application guides users through a series of pairwise comparisons between tracks, helping them create a personalized ranking of songs.​
GitHub

Features

Spotify Authentication: Users can securely log in using their Spotify credentials.​
Artist Discography Retrieval: Fetches the complete list of tracks from a selected artist's discography.​
Pairwise Song Comparison: Presents users with two songs at a time to choose their preferred track, facilitating an intuitive ranking process.​
GitHub
Personalized Rankings: Generates a custom ranking of songs based on user preferences.​
Responsive Design: Optimized for various devices to ensure a seamless user experience.​
Tech Stack

Framework: React.js​
GitHub
+2
GitHub
+2
GitHub
+2
Styling: Tailwind CSS​
GitHub
Build Tool: Vite​
GitHub
+3
GitHub
+3
GitHub
+3
Authentication: Spotify Web API​
Getting Started

Prerequisites
Node.js (v14 or later)​
npm or yarn​
Installation
Clone the repository:
git clone https://github.com/RawishRadish/Spotify-Ranker-Frontend.git
cd Spotify-Ranker-Frontend
Install dependencies:
npm install
# or
yarn install
Set up environment variables:
Create a .env file in the root directory and add your Spotify API credentials:

VITE_SPOTIFY_CLIENT_ID=your_spotify_client_id
VITE_SPOTIFY_REDIRECT_URI=http://localhost:3000/callback
Run the development server:
npm run dev
# or
yarn dev
The application will be available at http://localhost:3000.

Usage

Navigate to http://localhost:3000 in your browser.​
Click on the "Log in with Spotify" button to authenticate.​
GitHub
Search for an artist whose songs you want to rank.​
Begin the ranking process by choosing your preferred song in each pairwise comparison.​
GitHub
Once completed, view and share your personalized song ranking.​
Known Issues

User Session Handling: After a user logs out, the application may retain session data, allowing a new user to access the previous user's playlist during the comparison process. Implementing proper session management and clearing cached data upon logout is recommended.​
Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.​

License

This project is licensed under the MIT License.​
GitHub

For more information or to report issues, please visit the GitHub repository.​


