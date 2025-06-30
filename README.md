# Movie Finder 🎬

A modern React application for discovering and searching movies using The Movie Database (TMDB) API. Built with Vite, React 19, and Tailwind CSS for a fast and responsive user experience.

## Features

- **Movie Discovery**: Browse popular movies on the homepage
- **Search Functionality**: Search for specific movies by title
- **Responsive Design**: Beautiful UI built with Tailwind CSS
- **Loading States**: Smooth loading indicators during API calls
- **Error Handling**: User-friendly error messages for better UX
- **Modern Stack**: Built with the latest React 19 and Vite

## Tech Stack

- **Frontend Framework**: React 19.1.0
- **Build Tool**: Vite 6.3.5
- **Styling**: Tailwind CSS 4.1.10
- **Language**: JavaScript (ES6+)
- **API**: The Movie Database (TMDB) API v3

## Prerequisites

Before running this project, make sure you have:

- Node.js (version 16 or higher)
- npm or yarn package manager
- TMDB API key (free registration at [themoviedb.org](https://www.themoviedb.org/))

## Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd movie-finder
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory and add your TMDB API key:
   ```env
   VITE_TMDB_API_KEY=your_tmdb_bearer_token_here
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:5173` to view the application

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality

## Project Structure

```
src/
├── components/
│   ├── Search.jsx       # Search input component
│   ├── Spinner.jsx      # Loading spinner component
│   └── MovieCard.jsx    # Movie card display component
├── App.jsx              # Main application component
└── main.jsx             # Application entry point
```

## API Integration

This app integrates with The Movie Database (TMDB) API to fetch:
- Popular movies for the homepage
- Search results based on user queries
- Movie details including titles, posters, and metadata

## Getting Your TMDB API Key

1. Create a free account at [themoviedb.org](https://www.themoviedb.org/)
2. Go to your account settings
3. Navigate to the API section
4. Request an API key
5. Use the Bearer Token (not the API key) in your `.env` file

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- [The Movie Database (TMDB)](https://www.themoviedb.org/) for providing the movie data API
- [Vite](https://vitejs.dev/) for the fast build tool
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework

---

**Note**: This project is for educational purposes. Make sure to comply with TMDB's terms of service when using their API.
