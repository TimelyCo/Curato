### Curato

This project is a feature-rich, fully responsive frontend application called Nexora — a personalized content dashboard designed to deliver a seamless, interactive user experience. Built using Next.js, TypeScript, Redux Toolkit, and Tailwind CSS, the application empowers users to curate and interact with content such as news articles, movie/music recommendations, and social media posts — all in one unified interface.

Users can customize their content preferences (e.g., categories like technology, sports, or entertainment), and the dashboard dynamically fetches personalized data from external APIs such as NewsAPI, TMDB, and a mock social feed. The layout includes intuitive navigation via a sidebar and a top header with search functionality, user settings, and dark mode toggle.

Core features include:

Personalized Feed: Aggregates multi-source content based on user preferences.

Trending & Favorites Sections: Displays top content and allows users to save favorites.

Drag-and-Drop Support: Enables users to reorganize their feed interactively.

Search with Debounce: Allows category-wide content search with optimized performance.

Dark Mode: Smooth theme toggle using Tailwind CSS and local storage.

Animations: Polished UI with transitions and hover effects using Framer Motion.

The app uses Redux Toolkit for global state management and RTK Query or Thunks for async data fetching. User preferences and session data are persisted with localStorage to ensure continuity across reloads. The project also includes unit, integration, and end-to-end tests using tools like Jest, React Testing Library, and Cypress to ensure robustness and user flow reliability.
