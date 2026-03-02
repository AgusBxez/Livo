# 💻 Livo - Frontend (Client)

This is the frontend of the project, built with **Next.js** and **React**, focused on performance, an interactive interface, and solid data validation.

## 🚀 Main Technologies

This project uses a modern stack to ensure the best user and developer experience:

* **Framework:** [Next.js](https://nextjs.org/) (v16) with [React](https://react.dev/) (v19) and React Compiler.
* **Styling & UI:** [Tailwind CSS v4](https://tailwindcss.com/) and animations with [Framer Motion](https://www.framer.com/motion/).
* **Interactive Maps:** [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/api/).
* **Form Handling:** [React Hook Form](https://react-hook-form.com/) integrated with [Zod](https://zod.dev/) for strict schema validation.
* **File Uploads:** [React FilePond](https://pqina.nl/filepond/) (with image preview and orientation correction).
* **Icons & Utilities:** Lucide React, date-fns, Lodash.
* **Strict Typing:** TypeScript.

## 📋 Prerequisites

Before you begin, ensure you have the following installed on your system:
* [Node.js](https://nodejs.org/) (version 20 or higher recommended).
* A package manager like `npm`, `yarn`, or `pnpm`.

## ⚙️ Local Installation & Setup

1.  **Install dependencies:**
    Navigate to the client folder and run:
    ```bash
    npm install
    ```

2.  **Configure Environment Variables:**
    Create a `.env.local` file in the root of this folder. You will need to configure certain keys (for example, for Mapbox to work). Use this format as a guide:
    ```env
    # Required environment variables example
    NEXT_PUBLIC_MAPBOX_TOKEN=your_mapbox_token_here
    NEXT_PUBLIC_API_URL=http://localhost:3000/api # Your backend URL
    ```

3.  **Start the development server:**
    ```bash
    npm run dev
    ```
    Open [http://localhost:3000](http://localhost:3000) in your browser to see the running application.

## 📜 Available Scripts

In the project directory, you can run the following commands:

* `npm run dev`: Starts the application in development mode with hot-reloading.
* `npm run build`: Builds the app for production to the `.next` folder.
* `npm run start`: Starts a Next.js production server (requires running the build first).
* `npm run lint`: Runs ESLint to catch syntax errors and poor practices.

## 📁 General Structure

*The main structure follows Next.js standards (App Router / Pages Router), including reusable components for interactive maps, Zod-validated forms, and image upload components.*