# MDF Movies Database

A simple, responsive web application for searching and viewing movie information. This project utilizes the OMDb API to fetch and display movie details including posters, plot summaries, ratings, and more.

![Project Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 🌟 Features

*   **Search Functionality**: Search for movies by title using the search bar.
*   **Dynamic Placeholder**: The search bar features a rotating placeholder text suggesting popular movies.
*   **Movie Cards**: Results are displayed in a clean, responsive card layout showing the poster, title, and release year.
*   **Detailed View**: Click "more details" on any movie card to open a modal with comprehensive information (Plot, Genre, Director, Actors, Awards, Ratings, etc.).
*   **Pagination**: Navigate through search results easily with "previous" and "next" buttons.
*   **Responsive Design**: Optimized for both desktop and mobile viewing using Bootstrap 5.

## 🛠️ Technologies Used

*   **HTML5**
*   **CSS3** (Custom styles & Animations)
*   **JavaScript** (ES6+)
*   **[Bootstrap 5](https://getbootstrap.com/)** - For responsive layout and components (Modals, Cards, Buttons).
*   **[jQuery](https://jquery.com/)** - For DOM manipulation and event handling.
*   **[OMDb API](http://www.omdbapi.com/)** - The Open Movie Database API for fetching movie data.

## 🚀 Getting Started

### Prerequisites

You just need a modern web browser to run this application.

### Installation

1.  **Clone the repository**
    ```bash
    git clone <repository-url>
    ```
2.  **Navigate to the project directory**
    ```bash
    cd simple-film-database
    ```
3.  **Open `index.html`**
    Simply open the `index.html` file in your preferred web browser.

    OR

    Use a live server extension (like Live Server in VS Code) to run it locally.

## 🔑 Configuration

The project currently uses a public OMDb API key inside `index.js`.
```javascript
const apiKey = 'cb2c7062'; // Example from code
```
> **Note**: For production or heavy use, it is recommended to replace this with your own API key which you can obtain for free from [OMDb API](http://www.omdbapi.com/apikey.aspx).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1.  Fork the project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 👤 Author

**Muhammad Dava Fahreza**

*   Website: [Simple Film Database](https://github.com/dava) (Link to repo/profile if applicable)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
