# Smart Language Translator

A modern, browser-based **Smart Language Translator** that automatically
suggests a user's local language using location detection and enables
seamless translation between **60+ global languages**. The application
is lightweight, responsive, and requires no backend setup.

------------------------------------------------------------------------

## Overview

The Smart Language Translator is a client-side web application designed
to provide fast and intuitive text translation. By leveraging browser
geolocation and public translation APIs, the app enhances user
experience through automatic language suggestions, real-time feedback,
and a polished user interface.

------------------------------------------------------------------------

## Key Features

-   Automatic location-based language suggestion\
-   Support for 60+ international languages\
-   Manual source and target language selection\
-   One-click language swap\
-   Character limit tracking (up to 5000 characters)\
-   Translation status indicators (loading, success, error)\
-   Copy translated text to clipboard\
-   Fully responsive UI for desktop and mobile devices

------------------------------------------------------------------------

## Technologies Used

-   HTML5 -- Semantic structure\
-   CSS3 -- Responsive design and modern UI styling\
-   JavaScript (ES6) -- Application logic and API interaction\
-   Browser Geolocation API -- Location detection\
-   Google Translate API (Unofficial endpoint) -- Text translation\
-   OpenStreetMap Nominatim API -- Reverse geocoding

------------------------------------------------------------------------

## Project Structure

    Smart-Language-Translator/
    │
    ├── index.html      # Application entry point
    ├── style.css       # UI styling and responsive design
    ├── app.js          # Core application logic
    └── README.md       # Project documentation

------------------------------------------------------------------------

## Application Workflow

1.  On load, the app requests user location permission.\
2.  The detected country is mapped to a commonly used local language.\
3.  The target language is auto-selected (modifiable by the user).\
4.  User enters text and selects languages as needed.\
5.  Translation is performed and displayed instantly.\
6.  Output text can be copied with a single click.

------------------------------------------------------------------------

## Setup and Usage

### Prerequisites

-   A modern web browser (Chrome, Edge, Firefox, Safari)
-   Internet connection

### Running the Application

1.  Clone the repository:

    ``` bash
    git clone https://github.com/your-username/smart-language-translator.git
    ```

2.  Navigate to the project directory:

    ``` bash
    cd smart-language-translator
    ```

3.  Open `index.html` in your browser.

> No additional dependencies or server setup required.

------------------------------------------------------------------------

## Limitations

-   Translation depends on third-party public APIs.
-   Accuracy may vary for complex or technical sentences.
-   Requires user permission for location-based suggestions.

------------------------------------------------------------------------

## Future Enhancements

-   Voice input and speech output\
-   Offline language support\
-   AI-powered language detection\
-   Dark mode toggle\
-   Translation history and favorites\
-   Progressive Web App (PWA) support

------------------------------------------------------------------------

## License

This project is released under the **MIT License** and is free for
educational and personal use.

------------------------------------------------------------------------

## Author

**Dhanush B P**\
AI Student \| Web Development & Machine Learning Enthusiast
