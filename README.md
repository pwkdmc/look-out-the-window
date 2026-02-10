# Look Out the Window
A web application that allows users to explore videos from different cities around the world. The app features a responsive interface with filtering by city and time of day, dynamic video loading, and a modern preloader animation.

## Features
- City Search: Find videos by entering a city name (e.g., "Санкт-Петербург").
- Time of Day Filter: Filter videos by morning, afternoon, or night.
- Dynamic Video Display: Main video player updates based on selection.
- Infinite Scrolling: Load more videos with a "Show more" button.
- Responsive Preloader: Custom CSS animation while content loads.
- Error Handling: User-friendly error messages for missing videos or failed requests.

## Tech Stack
- HTML5: Semantic markup with `<video>` and `<template>` tags.
- CSS3: Custom styling with animations and pseudo-elements.
- JavaScript (ES6): Asynchronous fetching, DOM manipulation, event handling.
- REST API: External video data source (`v-content.practicum-team.ru`).

## Usage
1. Enter a city name in the search field.
2. Optionally select time of day checkboxes.
3. Click "Найти" (Find) to load matching videos.
4. Click any video card to play it in the main player.
5. Use the "Показать ещё" (Show more) button to load additional videos.

## License
This project is for educational purposes as part of a coding exercise.