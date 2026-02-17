# Code & Technology

This document provides a high-level overview of the technologies, libraries, and external tools used to build Visually.

## Core Technology Stack

Visually is built on a modern, robust, and scalable technology stack.

-   **Framework:** [Next.js](https://nextjs.org/) (a React framework) is used for both the frontend and parts of the backend (API routes). This allows for server-side rendering (SSR) and static site generation (SSG), providing a fast and SEO-friendly user experience.
-   **Language:** The entire codebase is written in [TypeScript](https://www.typescriptlang.org/), which adds static typing to JavaScript, improving code quality and maintainability.
-   **Styling:** [Tailwind CSS](https://tailwindcss.com/) is used for styling. It's a utility-first CSS framework that allows for rapid UI development.

## Frontend

The frontend is built with [React](https://react.dev/) and leverages a rich ecosystem of libraries.

-   **UI Components:** We use [Shadcn UI](https://ui.shadcn.com/), a collection of re-usable UI components that are built on top of Tailwind CSS. This ensures a consistent and accessible design system.
-   **Visual Flow & Diagrams:** The interactive, node-based editors for presentations, automations, and diagrams are powered by [React Flow](https://reactflow.dev/). This library provides the foundation for creating complex, draggable, and connectable nodes on a canvas.
-   **State Management:** For managing client-side state, we utilize [Zustand](https://zustand-demo.pmnd.rs/), a small, fast, and scalable state-management solution for React.

## Backend & Services

Our backend is composed of serverless functions and managed services to ensure scalability and reliability.

-   **Backend-as-a-Service (BaaS):** [Firebase](https://firebase.google.com/) is a core part of our backend. We use:
    -   **Firestore:** A NoSQL database for storing user data, presentations, and other application state.
    -   **Firebase Authentication:** For secure user authentication with various providers (email/password, Google, etc.).
    -   **Firebase Hosting:** For deploying and hosting the web application.
-   **Serverless APIs:** Next.js API routes are used to create serverless API endpoints for handling specific backend logic, such as proxying requests or communicating with other services.

## AI Integration

Artificial Intelligence is deeply integrated into the Visually platform.

-   **AI Flows:** We use [Google's Genkit](https://firebase.google.com/docs/genkit), a framework for building production-ready AI-powered features. Genkit orchestrates the logic for our AI tools, such as the chatbot, image generation, and presentation refiner.
-   **External AI Models:** Genkit allows us to connect to various large language models (LLMs) and other AI services, giving us the flexibility to use the best models for each task.
-   **Web Information Retrieval:** For features like *Websight*, which fetches information from URLs, we use services like the [Tavily API](https://tavily.com/) to perform efficient web searches and extract relevant content.

This combination of modern technologies allows Visually to be a powerful, flexible, and feature-rich platform for creating the future of presentations.
