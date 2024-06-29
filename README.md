# Vedio Tube
It is built using modern front-end technologies, including React, Redux Toolkit, TailwindCSS, and other libraries.

## Features

- **YouTube Clone:** The project is a replica of the YouTube platform, including its UI design and functionalities.
- **YouTube Video Preview:** Clicking on a video in the list opens a preview window that displays the selected video. The preview window includes basic details of the video, such as its title, description, and view count.
- **Search Suggestions:** As the user types in the search bar, the app displays a dropdown list of suggested search queries. This feature enhances the user experience and makes it easier to find relevant videos.
- **Search Caching:** To improve performance and reduce the number of API calls made, the app caches the results of previous searches. This means that if a user makes the same search query twice, the app will fetch the results from the cache instead of making a new API call.
- **Optimized Search Using Caching and Debouncing:** The app uses debouncing to optimize the search functionality. This means that instead of making an API call for every key press in the search bar, the app waits until the user has stopped typing before making the API call. Additionally, the app uses caching to fetch the results of previous searches faster.
- **Comments on YouTube:** The app includes a comments section that allows users to view and post comments on a video. The comments are fetched from the YouTube API and are displayed in a threaded view to enhance readability.
- **Live Chat of YouTube - Get Data Live, Update UI Continuously Developed with API Polling:** The app includes a live chat feature that allows users to view and send messages in real-time. The chat is implemented using API polling, which means that the app regularly makes API calls to fetch new messages and updates the UI accordingly.

## Usage

To use this project, follow these steps:

1. Clone the repository.
2. Install the dependencies using `npm install`.
3. Start the development server using `npm start`.
4. Open your web browser and navigate to `http://localhost:3000`.

## Conclusion

This YouTube uses React, Redux Toolkit, TailwindCSS, and other libraries. The project includes several useful features, such as search suggestions, search caching, optimized search using debouncing and caching, optimized API calls using debouncing, comments section, and live chat.

## Dependencies

This project uses the following dependencies:

- React
- Redux Toolkit
- React Icons
- React Router DOM
- TailwindCSS

## Live Link

`https://vediotube.onrender.com`
