# Cyro BrainWave Frontend

This repository contains the frontend application for the **Cyro BrainWave** project. It's built using **React**, **Vite**, **TailwindCSS**, and various additional libraries to create an interactive, modern web experience. The project focuses on providing a sleek and responsive interface with motion graphics and slick carousels.

---

## Project Structure

The repository consists of the following:

1. **Cyro BrainWave Frontend**: A React-based single-page application (SPA) powered by Vite for fast development, framer-motion for animations, and slick-carousel for a modern carousel experience.

---

## Prerequisites

Before running the application, ensure you have the following installed:

* **Node.js** (v16 or above)
* **npm** (Node Package Manager, comes with Node.js)
* **git** (to clone the repository)
* **Yarn** (optional, but recommended for some projects)

---

## Getting Started

Follow these steps to set up the **Cyro BrainWave** frontend project on your local machine.

### 1. Clone the Repository

Clone the repository using the following command:

```bash
git clone <repository-url>
cd cyro-brainwave-frontend
```

### 2. Install Dependencies

Install the required dependencies by running:

```bash
npm install
```

This will install both the production and development dependencies listed in `package.json`.

---

## Running the Project

After installing the dependencies, you can run the project in development mode.

### Run the Development Server

To start the Vite development server:

```bash
npm run dev
```

This will start the development server at `http://localhost:3000`, and the application will automatically reload on file changes.

---

## Build

Once you're done with development and want to create a production-ready build of the project, you can use the following command:

```bash
npm run build
```

This will generate optimized production files in the `dist/` directory.

### Preview the Production Build

To preview the production build locally:

```bash
npm run preview
```

This will serve the production build on a local server, typically available at `http://localhost:5000`.

---

## Linting

To ensure the code adheres to consistent style guidelines, you can run the linting script:

```bash
npm run lint
```

This will check your code for style issues and potential errors based on the configured ESLint rules.

---

## Technologies Used

* **React**: A JavaScript library for building user interfaces.
* **Vite**: A fast build tool and development server for modern web apps.
* **TailwindCSS**: A utility-first CSS framework for rapidly building custom designs.
* **Framer Motion**: A library for animations and transitions in React.
* **React Slick**: A carousel component built for React.
* **Slick Carousel**: A jQuery plugin for creating responsive carousels.
