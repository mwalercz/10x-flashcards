# 10x-flashcards

## Project Description

10x-flashcards is a web application that enables users to quickly create and manage educational flashcards. The app leverages a large language model (LLM) via an API to automatically generate flashcard suggestions from any pasted text. Users also have the option to manually create, edit, and delete flashcards. Additional features include user authentication, spaced repetition for effective learning, and detailed statistics for generated flashcards.

## Tech Stack

- **Frontend:** Astro 5, React 19, TypeScript 5, Tailwind CSS 4, Shadcn/ui
- **Backend:** Supabase (PostgreSQL, authentication, and database management)
- **AI Integration:** Openrouter.ai for accessing various LLM models
- **CI/CD:** GitHub Actions
- **Hosting:** DigitalOcean

## Getting Started Locally

1. **Clone the repository:**
   ```sh
   git clone <repository_url>
   cd 10x-flashcards
   ```

2. **Install Node.js dependencies:**
   Make sure you are using Node version specified in the `.nvmrc` file (22.14.0):
   ```sh
   nvm install
   nvm use
   npm install
   ```

3. **Run the development server:**
   ```sh
   npm run dev
   ```
   This will start the Astro development server. Open your browser and navigate to the displayed local address.

## Available Scripts

- `npm run dev` - Start the development server.
- `npm run build` - Build the project for production.
- `npm run preview` - Preview the production build locally.
- `npm run lint` - Run ESLint to analyze code for potential issues.
- `npm run lint:fix` - Automatically fix linting issues.
- `npm run format` - Format code using Prettier.

## Project Scope

The project aims to deliver a streamlined flashcard creation and learning experience through the following features:

- **Automatic Flashcard Generation:** Generate flashcard suggestions from pasted text using an LLM API.
- **Manual Flashcard Management:** Create, edit, and delete flashcards manually.
- **User Authentication:** Register, log in, and manage user accounts securely.
- **Learning Sessions:** Leverage spaced repetition algorithms to optimize the learning process.
- **Statistics Tracking:** Monitor generated flashcards and user acceptance rates.

## Project Status

This project is currently in the MVP stage, with core functionalities implemented. Further enhancements and optimizations are planned as the project evolves.

## License

This project is licensed under the MIT License. 