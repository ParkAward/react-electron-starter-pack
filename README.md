# React Project with Electron and Vite

This project is a React-based application integrated with Electron and built using the Vite build tool. It also leverages TypeScript for type safety and Tailwind CSS for styling.

## Features

- **Electron**: Provides a desktop application environment.
- **React**: Frontend library for building user interfaces.
- **Vite**: Lightning-fast build and development tool.
- **TypeScript**: Adds type safety to JavaScript.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **ESLint**: Code linting to ensure consistent coding standards.

---

## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (Recommended: LTS version)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/) (npm comes with Node.js)

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

### Development

To start the development server, run:

```bash
npm run dev
# or
yarn dev
```

This will launch the Electron application with hot-reloading enabled for development.

### Build

To build the application for production, run:

```bash
npm run build
# or
yarn build
```

### Preview

To preview the production build, run:

```bash
npm run preview
# or
yarn preview
```

---

## Project Structure

```plaintext
src/         # Source code directory
  main/      # Electron main process code
  renderer/  # React renderer process code
out/         # Build output directory
```

---

## Scripts

The following scripts are available in the `package.json`:

- `dev`: Start the application in development mode with hot reload.
- `build`: Build the application for production.
- `start`: Start the built application.
- `lint`: Run ESLint to check for code issues.
- `preview`: Preview the production build in a local server.

---

## Dependencies

### Production Dependencies

- `@electron-toolkit/preload`: Preloading modules for Electron.
- `@electron-toolkit/utils`: Utility functions for Electron.
- `@radix-ui/react-slot`: Radix UI Slot component for advanced composition.
- `class-variance-authority`: Utility for conditional class composition.
- `clsx`: Utility for conditional classNames.
- `electron`: Framework for creating desktop apps.
- `lucide-react`: Icon library for React.
- `react` and `react-dom`: Core React libraries.
- `tailwind-merge`: Merges Tailwind CSS class names intelligently.
- `tailwindcss-animate`: Animations plugin for Tailwind CSS.

### Development Dependencies

- `@eslint/js`: ESLint configurations for JavaScript.
- `@types/node`: TypeScript types for Node.js.
- `@types/react` and `@types/react-dom`: TypeScript types for React.
- `@vitejs/plugin-react-swc`: Vite plugin for React with SWC.
- `autoprefixer`: PostCSS plugin to add vendor prefixes.
- `electron-vite`: Vite plugin for Electron.
- `eslint`: JavaScript linter.
- `eslint-plugin-react-hooks`: ESLint plugin for React Hooks.
- `eslint-plugin-react-refresh`: ESLint plugin for React Refresh.
- `globals`: Library for global variables.
- `postcss`: CSS post-processing tool.
- `tailwindcss`: Utility-first CSS framework.
- `typescript`: TypeScript language.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contributing

Feel free to submit issues or pull requests for improvements. Contributions are welcome!

---

## Contact

For further information or questions, please contact [parksangjun1363@gmail.com]
