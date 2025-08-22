
# Movie Recommendation App

An interactive web application that allows users to search for movies and get recommendations using a third-party movie API.

## Features

- Search for movies by title
- View movie details (poster, release year, rating, etc.)
- Get recommendations based on your search
- Responsive and modern UI



## Getting Started

### Prerequisites
- Node.js (v14 or higher recommended)
- npm (comes with Node.js)

### Installation
1. Clone the repository:

2. Install dependencies:
	```bash
	npm install
	```
3. Create a `.env` file in the root directory and add your API key:
	```env
	api_key=your_api_key_here
	```
	You can use `env_example` as a reference.

### Running the App
```bash
npm start
```
The app will run at [http://localhost:3000](http://localhost:3000).

## Usage

1. Enter a movie title in the search bar.
2. Browse the search results and click on a movie for more details.
3. View recommended movies based on your selection.

## Scripts

- `npm start` – Start the development server
- `npm run build` – Build for production

## Technologies Used
- React
- JavaScript (ES6+)
- CSS

## Credits

- Movie data provided by [The Movie Database (TMDb) API](https://www.themoviedb.org/documentation/api) or similar

## License

This project is licensed under the MIT License.

