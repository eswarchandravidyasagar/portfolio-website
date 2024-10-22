# Portfolio Website

This repository contains the source code for my personal portfolio website. The website showcases my projects, skills, and contact information.

## Purpose

The purpose of this repository is to provide a platform to display my work and allow potential employers or collaborators to learn more about me and my projects.

## Setup and Deployment

Follow the instructions below to set up and deploy the project.

### Prerequisites

- Node.js (version 16 or higher)
- npm (Node Package Manager)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/eswarchandravidyasagar/portfolio-website.git
   ```
2. Navigate to the project directory:
   ```sh
   cd portfolio-website
   ```
3. Install the dependencies:
   ```sh
   npm install
   ```

### Development

To start the development server, run:
```sh
npm start
```
This will start the development server and open the website in your default browser. Any changes you make to the source code will automatically reload the page.

### Build

To build the project for production, run:
```sh
npm run build
```
This will create a `dist` directory with the optimized production build of the website.

### Deployment

The project is configured to deploy to GitHub Pages using GitHub Actions. The deployment workflow is defined in the `.github/workflows/deploy.yml` file.

To deploy the project, push your changes to the `main` branch. The GitHub Actions workflow will automatically build and deploy the website to GitHub Pages.
