# Movie Search App

A simple **React** application that allows users to search for movies using **The Movie Database (TMDb) API**. This project also integrates with **Appwrite** for tracking search counts and managing trending movies.

## Features

- 🔍 Search for movies in real-time
- 📊 Track trending movies with **Appwrite**
- 🎬 Fetch movie details from **TMDb API**
- ⏳ Debounced search input for optimized performance
- 📄 Pagination to browse through results

## Getting Started

### Prerequisites

Ensure you have **Node.js** installed on your machine. You can download it from [Node.js Official Site](https://nodejs.org/).

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/n0tg0d/Movie_aggregator_2025
   cd Movie_aggregator_2025
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Create a `.env` file in the root folder and add your **TMDb API Key**:

   ```sh
   VITE_TMDB_API_KEY=your_api_key_here
   ```

4. Start the development server:

   ```sh
   npm run dev
   ```

5. Open the application in your browser at:
   ```
   http://localhost:5173
   ```

## Appwrite Configuration

This project integrates **Appwrite** for storing trending movie searches. To set it up:

1. Create an Appwrite project at [Appwrite Cloud](https://cloud.appwrite.io/).
2. Configure your database and collection.
3. Set up environment variables for **Appwrite API**.

   ![Movie Search App](assets/screenshots/movie-search.png)

## Available Scripts

- **Start Development Server:**
  ```sh
  npm run dev
  ```
- **Build for Production:**
  ```sh
  npm run build
  ```
- **Lint Code:**
  ```sh
  npm run lint
  ```

## Technologies Used

- **React.js** – Frontend framework
- **Appwrite** – Backend for storing search data
- **TMDb API** – Fetching movie details
- **Tailwind CSS** – Styling

## License

This project is open-source and available under the **MIT License**.
