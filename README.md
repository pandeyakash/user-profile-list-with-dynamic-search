# User Profile List with Dynamic Search

## Description

A React application that renders a list of user profiles and includes a search feature to filter users by name. Profiles are displayed in a card layout with relevant details like name, email, and occupation.

## Features

- Display of 10 user profiles.
- Dynamic search functionality to filter profiles by name.
- Conditional rendering to show a "User Not Found" message when no match is found.

## Installation

- The project uses React, ReactDOM, and Babel through CDN links, so no package installation is required.

## Usage

1. Open the HTML file in your browser.
2. Use the search bar to filter users by name.
3. Matching profiles will be displayed based on the input.

## Technologies Used

- React (via CDN)
- ReactDOM (via CDN)
- Babel (for JSX transformation via CDN)
- HTML5, CSS3

## How to Run

1. Download or copy the provided HTML file.
2. Open the file in any modern web browser (Chrome, Firefox, etc.).
3. The application will run automatically.

## Code Explanation

- **User Data**: An array of user objects is stored in the `users` array, each with properties like `name`, `email`, and `occupation`.
- **UserProfile Component**: A reusable component to display user details.
- **App Component**: The main component that handles state (`searchInput` and `searchTerm`) and filters the user list.
- **Search Functionality**: The `handleSubmit` and `handleChange` functions allow users to search profiles by name.
