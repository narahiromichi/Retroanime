# RetroAnime

A responsive anime discovery web app built with React and Redux Toolkit. It uses the [Jikan API](https://jikan.moe/) (an unofficial MyAnimeList API) to show the current season's anime, let users search by title or browse by genre, and view detailed information about each show.

## Features

- **Current season:** browse anime airing this season, with pagination
- **Search:** find anime by title
- **Browse by genre:** pick one or more genres and see matching anime
- **Anime details page:** full information for each title, including its opening and ending theme songs, with a link to search each song on YouTube
- **Light and dark themes:** switch between them from the navigation menu
- **Responsive layout:** separate layouts for desktop and mobile
- **Loading states:** a loading spinner while data is being fetched

## Built With

- React 18
- Redux Toolkit and RTK Query for state management and API data fetching
- React Router v6 for page navigation
- Axios
- CSS

## Running Locally

```bash
git clone https://github.com/narahiromichi/Retroanime.git
cd Retroanime
npm install
npm start
```

Then open http://localhost:3000 in your browser.

## About

I built this project in July 2022 while teaching myself front-end web development through online tutorials and official documentation. It was my first complete React project, and I used it to practise working with APIs, Redux Toolkit and React Router.
