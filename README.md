# Event Locator Web Application

## Project Overview
The **Event Locator** web application allows users to search for events happening in their city. The application provides a user-friendly interface to browse events with details such as event name, date, location, and a brief description. Users can filter events by date and category to refine their search.

## Features
- **Home Page:** A landing page with a search bar and filters for date and category.
- **Event List:** A page displaying a list of events based on the search criteria.
- **Event Details:** A page showing detailed information about a selected event.
- **Responsive Design:** The application is mobile-friendly using Bootstrap.

## Project Structure
```
/afd-2023M-event-locator/
│── index.html           # Home page with search and filters
│── events.html          # Event list page displaying filtered results
│── event-details.html   # Detailed page for a selected event
│── /css/                # Stylesheets
│   ├── styles.css       # Custom CSS file
│── /js/                 # JavaScript files
│   ├── script.js        # Main JavaScript file
│── /assets/             # Images and other assets
└── README.md            # Project documentation
```

## Setup and Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/afd-2023M-event-locator.git
   ```
2. Navigate to the project directory:
   ```sh
   cd afd-2023M-event-locator
   ```
3. Open `index.html` in a web browser to start using the application.

## Implementation Details
### 1. Home Page
- Create `index.html` with a search bar and filters for date and category.
- Use Bootstrap and custom CSS for styling.

### 2. Event List Page
- Create `events.html` to display a list of events based on user search.
- Implement JavaScript to dynamically generate event cards.
- Style event cards using Bootstrap.

### 3. Event Details Page
- Create `event-details.html` to show detailed information about a selected event.
- Use JavaScript to populate the page with event details dynamically.
- Apply Bootstrap styles.

### 4. JavaScript Functionality
- Implement search functionality to filter events by date and category.
- Use JavaScript to fetch and display event data.
- Add event listeners for user interactions.

### 5. Responsive Design
- Ensure all pages are responsive using Bootstrap's grid system and utilities.
- Test the application on different screen sizes for compatibility.

## Technologies Used
- **HTML5** for structuring the application.
- **CSS3 & Bootstrap** for styling and responsive design.
- **JavaScript** for dynamic content and interactivity.

## Contributing
Contributions are welcome! If you’d like to improve the project, feel free to submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
