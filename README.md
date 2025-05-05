# React + Shadcn Template

![GitHub package.json dev/peer/optional dependency version](https://img.shields.io/github/package-json/dependency-version/awerito/react-shadcn-template/dev/vite?logo=vite)
![GitHub package.json prod dependency version](https://img.shields.io/github/package-json/dependency-version/awerito/react-shadcn-template/react?logo=react)
![GitHub package.json prod dependency version](https://img.shields.io/github/package-json/dependency-version/awerito/react-shadcn-template/tailwindcss?logo=tailwindcss)
![GitHub package.json prod dependency version](https://img.shields.io/badge/shadcn/ui-v2.5.0-blue?logo=shadcnui)
![GitHub package.json prod dependency version](https://img.shields.io/github/package-json/dependency-version/awerito/react-shadcn-template/react?logo=react)
![GitHub License](https://img.shields.io/github/license/Awerito/react-shadcn-template?logo=github&link=.%2FLICENSE)

This is a template for projects using [React](https://reactjs.org/) and
[Shadcn](https://ui.shadcn.com/) with JavaScript. It provides a solid,
customizable foundation for building modern web applications with ease.

## Features

- **React**: A popular JavaScript library for building user interfaces.
- **Shadcn**: A fully featured component library with all the tools you need
  to build a modern, user-friendly UI quickly.
- **JavaScript (ES6+)**: Modern JavaScript setup to keep your code efficient
  and clean.
- **Pre-configured tools**: Includes basic configurations for ESLint, Prettier,
  and other development scripts.
- **Dark Mode Support**: Integrated dark mode using Shadcn's theming system.

## Requirements

Make sure you have the following installed before getting started:

- [Node.js](https://nodejs.org/) >= 22.3.x
- [Yarn](https://yarnpkg.com/) >= 1.22.x

## Template Usage

This template provides a basic structure for building React applications with
Shadcn. You can start by modifying the existing components or creating new
ones to build your application.

1. Click on the `Use this template` button on the top right of the github
   repository.
2. Click on the `Create a new repository` button.
3. Clone the new repository to your local machine.

## Installation

1. Install the dependencies:

   Using npm:

   ```bash
   yarn
   ```

## Available Scripts

In the project directory, you can run the following commands:

### `yarn dev`

Runs the app in development mode. Open
[http://localhost:5173](http://localhost:5173) to view it in the browser. The
app will reload if you make edits.

### `yarn build`

Builds the app for production into the `build` folder. It optimizes the build
for the best performance.

### `yarn lint`

Runs ESLint to check for code style and syntax issues.

### `yarn preview`

Runs the production build locally to preview the app. Open
[http://localhost:4173](http://localhost:4173) to view it in the browser.

## Project Structure

```bash
.
├── public/               # Public files (index.html, favicon, etc.)
├── src/
│   ├── assets/           # Static assets like images and fonts
│   ├── components/       # Reusable React components
│   ├── services/         # API services
│   ├── hooks/            # Custom React hooks
│   ├── pages/            # Application pages
│   ├── App.jsx           # Root component
│   └── main.jsx          # Main React entry point
├── eslint.config.js      # ESLint configuration
├── package.json          # Project dependencies and scripts
├── package-lock.json     # Lock file for npm
├── postcss.config.cjs    # PostCSS configuration
├── README.md             # Project information
└── vite.config.js        # Vite configuration
```

## Customization

Feel free to modify the structure, components, and styling according to your
needs. Shadcn's documentation is an excellent resource for customizing the UI
components to fit your project.
