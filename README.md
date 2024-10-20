# Unsplash-Image-Gallery
A dynamic image gallery application that fetches images from the Unsplash API and displays them in a responsive layout. Built with React and styled for an engaging user experience, this app allows users to search for high-quality images on the go.

## Features

- Search for images by keywords via Unsplash API
- Responsive gallery display
- Toggle between light and dark themes
- Fast image loading and optimized for performance

## File Structure

```
Unsplash-Image-Gallery/
│
├── public/                    # Public assets
│   └── vite.svg               # Vite assets
├── src/                       # Main application source code
│   ├── assets/                # Images and static assets
│   ├── components/            # React components for the app
│   ├── Gallery.jsx            # Gallery component
│   ├── SearchForm.jsx         # Search form component for searching images
│   ├── ThemeToggle.jsx        # Component for theme toggling
│   └── main.jsx               # Entry point of the React app
├── node_modules/              # Dependencies
├── package.json               # Project dependencies and scripts
├── .gitignore                 # Files to ignore in git
└── README.md                  # Project documentation
```

## Installation

To get this project running locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/unsplash-image-gallery.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd unsplash-image-gallery
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Create a `.env` file:**

   Create a `.env` file in the root directory and add your Unsplash API credentials:

   ```env
   REACT_APP_UNSPLASH_ACCESS_KEY=your_access_key
   ```

5. **Run the app:**

   ```bash
   npm run dev
   ```

   The app will be running at `http://localhost:3000/`.

## Usage

- Open your browser and navigate to `http://localhost:3000/`.
- Use the search bar to find images by keyword.
- Toggle between light and dark themes for better visibility.

## Technologies Used

- React.js
- Unsplash API
- Vite for build tool
- CSS for styling

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```

Let me know if you'd like to adjust or add any details!
