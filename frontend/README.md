This project is a movie application built with React and Vite. It allows users to search for movies, view popular movies, and manage a list of favorite movies. The application uses The Movie Database (TMDb) API to fetch movie data.

### Project Structure

```
frontend/
	.gitignore
	eslint.config.js
	index.html
	package.json
	public/
	README.md
	src/
		App.jsx
		assets/
		components/
			MovieCard.jsx
			NavBar.jsx
		context/
			MovieContext.jsx
		css/
			App.css
			Favorites.css
			Home.css
			index.css
			MovieCard.css
			Navbar.css
		main.jsx
		pages/
			Favorites.jsx
			Home.jsx
		services/
			api.js
	vite.config.js
```

### Key Files and Directories

- \*\*

src/App.jsx

\*\*: The main application component that sets up routing and context providers.

- \*\*

src/main.jsx

\*\*: The entry point of the application.

- \*\*

src/context/MovieContext.jsx

\*\*: Provides context for managing favorite movies.

- \*\*

src/services/api.js

\*\*: Contains functions to interact with the TMDb API.

- \*\*

src/pages/Home.jsx

\*\*: The home page component where users can search for movies and view popular movies.

- \*\*

src/pages/Favorites.jsx

\*\*: The favorites page component where users can view their favorite movies.

- \*\*

src/components/MovieCard.jsx

\*\*: A component to display individual movie details.

- \*\*

src/components/NavBar.jsx

\*\*: A navigation bar component.

- \*\*

src/css/

\*\*: Directory containing CSS files for styling the application.

### Features

- **Search Movies**: Users can search for movies using the search bar on the home page.
- **Popular Movies**: Displays a list of popular movies fetched from the TMDb API.
- **Favorites Management**: Users can add or remove movies from their list of favorites, which is stored in local storage.

### Scripts

- **`dev`**: Starts the development server.
- **`build`**: Builds the application for production.
- **`lint`**: Runs ESLint to check for code quality issues.
- **`preview`**: Previews the production build.

### Dependencies

- **React**: A JavaScript library for building user interfaces.
- **React Router DOM**: A library for routing in React applications.
- **Vite**: A build tool that provides a fast development server and optimized production builds.

### Development

To start the development server, run:

```sh
npm run dev
```

To build the application for production, run:

```sh
npm run build
```

To preview the production build, run:

```sh
npm run preview
```

### API Key

Replace `"Enter your API key here"` in

api.js

with your TMDb API key to fetch movie data.
