# ACONEWS - News App

Welcome to ACONEWS, a cutting-edge news app powered by the [GNews API](https://gnews.io/). This app provides a sleek, responsive interface for reading the latest news from around the globe. Built as part of the Acowale Machine Test Round, this project showcases my ability to create a functional, user-friendly news application.

## Live Demo

You can view the live application [here](https://myidea-8943d.web.app/).

## Features

- **Responsive Design**: The app is designed to work seamlessly on mobile, tablet, and desktop devices.
- **Latest News**: Fetches and displays the latest news articles from the GNews API.
- **Search Functionality**: Allows users to search for news based on keywords.
- **Pagination**: Supports pagination to navigate through news articles efficiently.

## Setup Instructions

### Prerequisites

- Node.js (v14 or higher)
- Firebase CLI

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/UzumakiODZ/news-exam.git
    ```

2. Navigate to the project directory:

    ```bash
    cd news-exam
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Set up your Firebase project:

    - Create a `.env` file in the root directory and add your Firebase configuration details and GNews API key.

    ```env
    REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
    REACT_APP_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
    REACT_APP_FIREBASE_PROJECT_ID=your_firebase_project_id
    REACT_APP_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
    REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
    REACT_APP_FIREBASE_APP_ID=your_firebase_app_id
    REACT_APP_GNEWS_API_KEY=your_gnews_api_key
    ```

5. Start the development server:

    ```bash
    npm start
    ```

### Deployment

To deploy the app to Firebase:

1. Install Firebase CLI if you haven't already:

    ```bash
    npm install -g firebase-tools
    ```

2. Log in to Firebase:

    ```bash
    firebase login
    ```

3. Initialize Firebase in your project directory:

    ```bash
    firebase init
    ```

4. Deploy your app:

    ```bash
    firebase deploy
    ```

## API Key

This project uses the GNews API. You can obtain your own API key by signing up at [GNews](https://gnews.io/).

## Development

- **Frontend**: Developed using React.
- **Backend**: API requests handled directly from the frontend.

## Contributing

Feel free to fork the repository and submit pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



---

Happy coding and thank you for checking out ACONEWS!
