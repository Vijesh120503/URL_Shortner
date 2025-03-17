# URL Shortener

## Description
The URL Shortener is a web-based application that allows users to generate short URLs from long links. It is built using Firebase for backend services and does not require a Node.js server. This project provides a simple and efficient way to manage and track shortened URLs.

## Features
- Generate short URLs from long links
- Copy shortened URLs with one click
- Track the number of clicks (if enabled in Firebase)
- Firebase Firestore for storing URLs
- Simple and responsive user interface

## Technologies Used
- HTML
- CSS
- JavaScript
- Firebase (Firestore & Authentication)
- Axios (for API requests if needed)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/url-shortener.git
   ```
2. Navigate to the project directory:
   ```bash
   cd url-shortener
   ```
3. Open `index.html` in your browser or use a local server:
   ```bash
   npx serve
   ```

## Firebase Setup
1. Create a Firebase project.
2. Enable Firestore Database.
3. Add Firebase configuration to your JavaScript file.
4. Enable authentication (if required).

## Usage
1. Enter a long URL in the input field.
2. Click the "Shorten" button.
3. Copy and share the generated short URL.

## Contribution
Feel free to fork this repository and submit pull requests for improvements.
