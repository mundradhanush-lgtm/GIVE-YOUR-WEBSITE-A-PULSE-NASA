
# NASA Astronomy Picture of the Day

This project uses NASA's Astronomy Picture of the Day (APOD) API to display the astronomical content featured for the day. It shows the title, image or video, and a short explanation provided by NASA.

## Features

- Fetches daily astronomical content from NASA.
- Displays the title and explanation.
- Supports both images and videos.
- Shows a loading message while fetching data.
- Displays an error message if the request fails.

## Technologies Used

- HTML
- CSS
- JavaScript
- Vite
- NASA APOD API

## Setup and Installation

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_LINK
```

### 2. Navigate to the project folder

```bash
cd YOUR_PROJECT_FOLDER
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure the NASA API key

Get a free API key from [NASA API](https://api.nasa.gov/).

Create a `.env` file in the root directory and add:

```env
VITE_NASA_API_KEY=your_api_key
```

Replace `your_api_key` with your actual API key.

### 5. Start the development server

```bash
npm run dev
```

Open the local URL provided by Vite in your browser.

## API

This project uses NASA's [Astronomy Picture of the Day API](https://api.nasa.gov/).

The API provides astronomical images or videos along with information and explanations about them.

## What I Learned

- How to fetch data from an API using JavaScript.
- How to work with promises using `.then()` and `.catch()`.
- How to use environment variables in Vite.
- How to display API data dynamically.
- How to handle different media types.

## Author

Made as part of a Stardance mission by DHANUSH MUNDRA.

