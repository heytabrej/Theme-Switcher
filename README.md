
# Theme Switcher

A simple React application that allows users to toggle between light and dark themes. This project leverages the Context API for state management and Tailwind CSS for styling, ensuring a seamless and responsive user experience.

## Features

- **Theme Toggle**: Switch between light and dark themes using a simple toggle button.
- **State Management**: Utilizes React's Context API to manage the theme state across the application.
- **Responsive Design**: Ensures a consistent experience on different screen sizes with Tailwind CSS.

## Project Structure

```
src/
├── assets/
├── components/
├── context/
├── App.jsx
└── App.css
```

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Node.js
- npm (Node Package Manager) or yarn

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/theme-switcher.git
    cd theme-switcher
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

    or

    ```bash
    yarn install
    ```

### Running the Application

To start the development server:

```bash
yarn dev
```

Open [http://localhost:5173](http://localhost:5173) to view the application in your browser.

## Usage

**Theme Toggle**: Use the toggle button to switch between light and dark themes. The state is managed using the Context API, and the theme change is reflected throughout the application.

**Customization**: Tailwind CSS is used for styling. You can customize the styles by editing the \`App.css\` file or adding new classes directly to the components.

**Components**:
- **ThemeToggleButton**: The button that toggles the theme.
- **Card**: A sample card component showcasing a product.

## How It Works

**Context API**: The `ThemeContext` provides the current theme and functions to toggle between themes. This context is wrapped around the main application in `App.jsx`, making the theme state accessible to all components.

**State Management**: The theme state is managed using React's `useState` hook. The `useEffect` hook is used to apply the theme class to the HTML element whenever the theme state changes.

**Responsive Design**: Tailwind CSS ensures that the application is responsive and looks good on all screen sizes.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.



## Contact

For any questions or suggestions, feel free to reach out at [hi.tabrej@gmail.com](mailto:hi.tabrej@gmail.com).

