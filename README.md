# 🐦 Twitter Clone

A responsive and visually appealing clone of the Twitter (now X) user interface, built with **HTML**, **Tailwind CSS**, and **JavaScript**. This project replicates the core layout and design elements of the popular social media platform, offering a seamless experience across desktop and mobile devices.

## 🚀 Features

*   **Authentic UI**: Replicates the familiar Twitter layout including the sidebar navigation, main feed, and right-hand trending section.
*   **Responsive Design**: Fully optimized for various screen sizes.
    *   **Desktop**: Full 3-column layout.
    *   **Mobile**: Optimized layout with tabbed navigation for "For You" and "Following" feeds.
*   **Interactive Elements**:
    *   Hover effects on buttons, icons, and navigation items.
    *   Mobile-specific interactions to toggle between feed views.
*   **Static Content**: Includes sample posts, trending topics, and "Who to follow" suggestions to simulate a live environment.

## 🛠️ Tech Stack

*   **Frontend**: HTML5, JavaScript (Vanilla)
*   **Styling**: [Tailwind CSS](https://tailwindcss.com/) (Utility-first CSS framework)
*   **Build Tool**: [Vite](https://vitejs.dev/) (Fast frontend build tool)

## 📂 Project Structure

```
Twitter-Clone/
├── assets/              # Images and icons used in the project
├── node_modules/        # Project dependencies
├── src/
│   ├── input.css        # Tailwind CSS input file
│   └── output.css       # Compiled Tailwind CSS output
├── index.html           # Main HTML file
├── script.js            # JavaScript for mobile interactivity
├── package.json         # Project metadata and dependencies
├── tailwind.config.js   # Tailwind CSS configuration
└── README.md            # Project documentation
```

## ⚙️ Installation & Setup

Follow these steps to get the project running locally on your machine.

### Prerequisites

*   **Node.js**: Ensure you have Node.js installed. You can download it from [nodejs.org](https://nodejs.org/).

### Steps

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Khwajazeeshan/Twitter-Clone/-.git
    cd Twitter-Clone
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

3.  **Run the development server**:
    ```bash
    npm run dev
    ```
    This will start the Vite development server. Open the URL provided in your terminal (usually `http://localhost:5173`) to view the app.

4.  **Build for production** (optional):
    To generate the production-ready CSS, you can run the Tailwind build command if configured, or rely on Vite's build process.
    ```bash
    npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
    ```

## 📖 Usage

*   **Navigation**: Use the sidebar on the left to navigate between different (static) sections like Home, Explore, Notifications, etc.
*   **Feed**: Scroll through the main feed to view tweets.
*   **Mobile View**: On smaller screens (< 500px), use the "For You" and "Following" tabs at the top to switch views.
*   **Trending**: Check the right sidebar for trending topics and suggested accounts to follow.

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project, please follow these steps:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourFeature`).
3.  Commit your changes (`git commit -m 'Add some feature'`).
4.  Push to the branch (`git push origin feature/YourFeature`).
5.  Open a Pull Request.

## 📄 License

This project is licensed under the **ISC License**.
