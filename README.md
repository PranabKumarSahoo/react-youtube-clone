# React YouTube Clone

## Overview
This project is a simple YouTube clone built using ReactJS and Tailwind CSS. It leverages the RapidAPI to fetch video data and display it in a familiar YouTube interface.

## Features
- YouTube API Integration: Utilizes the YouTube API from RapidAPI to fetch video data.
- Search Functionality: Users can search for videos using keywords. It displays a list of search results with video thumbnails, titles, and channel information.
- Video Player: Provides a youtube video player to watch the selected video.
- Responsive Design: The application is designed to work seamlessly on various devices.

## Technologies Used
- ReactJS
- Tailwind CSS
- RapidAPI (YouTube API)

## Getting Started

Follow these steps to get the project up and running on your local machine:

1. Clone the repository:

```bash
git clone https://github.com/PranabKumarSahoo/react-youtube-clone.git
```
2. Navigate to the project directory:

```bash
cd react-youtube-clone
```
3. Install dependencies:

```bash
npm install
```

4. Set up RapidAPI Key:

- Obtain a YouTube RapidAPI key by signing up at **RapidAPI** website.
- Then create a file in the project root, called `.env`.
- Set `REACT_APP_YOUTUBE_API_KEY` in that file with your actual `RapidAPI key`.

5. Run the application:
```bash
npm start
```
### Open your browser and visit `http://localhost:3000` to see the React YouTube Clone in action.

## License
This project is licensed under the [MIT License].
