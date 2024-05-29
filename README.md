# QuickURL

QuickURL is a minimalist URL shortening service that allows users to create short and memorable URLs. With QuickURL, you can generate short links for long URLs, track the number of clicks, and view detailed analytics.

## Features

- **Shorten URLs**: Create short URLs for long links quickly and easily.
- **Track Clicks**: View the total number of clicks for each short URL.
- **Analytics**: Access detailed analytics including timestamps for each visit.
- **User-Friendly Interface**: Simple and intuitive interface for effortless URL management.

## Technologies Used

- **Frontend**: HTML, CSS
- **Backend**: Node.js, Express.js, MongoDB
- **Database**: MongoDB (for storing URL data)

## Getting Started

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository or download the source code.
2. Install dependencies using npm:
    ```bash
    npm install
    ```
3. Set up MongoDB and ensure it's running.
4. Start the server:
    ```bash
    npm start
    ```
5. Access QuickURL in your web browser at `http://localhost:3000`.

## Usage

1. **Shorten URL**:
    - Enter a long URL in the provided input field and click "Shorten".
    - Copy the generated short URL for sharing or distribution.

2. **Track Clicks**:
    - View the total number of clicks for each short URL.

3. **View Analytics**:
    - Access detailed analytics including timestamps for each visit.

## Project Structure

- **controllers/**: Contains controller functions for handling URL creation and analytics.
- **models/**: Defines Mongoose schema and model for URL documents.
- **routes/**: Defines Express routes for URL-related endpoints.

- **index.js**: Main application file.
- **package.json**: Project metadata and dependencies.
- **README.md**: Project documentation (you're reading now).

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

Thank you for using QuickURL!
