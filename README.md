# MoviesApp 🎬

A React web app for discovering trending movies, checking ratings, and curating your personal watchlist — all in one place.

---

## Features

- **Trending Movies** — See what's popular right now
- **Ratings** — View movie ratings to help decide what to watch
- **Watchlist** — Keep track of movies you want to see
- **Search** — Find movies quickly by title

---

## Tech Stack

| Technology | Purpose |
|---|---|
| [React 19](https://react.dev/) | UI framework |
| [Vite](https://vitejs.dev/) | Build tool & dev server |
| [Tailwind CSS 4](https://tailwindcss.com/) | Styling |
| [Appwrite](https://appwrite.io/) | Backend-as-a-service (auth, database) |
| [react-use](https://github.com/streamich/react-use) | Utility hooks |

---

## Getting Started

### Prerequisites

- Node.js 18+
- An [Appwrite](https://appwrite.io/) project set up with the required collections

### Installation

```bash
git clone https://github.com/bhaumik694/MoviesApp.git
cd MoviesApp
npm install
```

### Environment Setup

Create a `.env` file in the root directory and add your Appwrite credentials:

```env
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
```

### Run Locally

```bash
npm run dev
```

The app will be available at `http://localhost:5173`.

### Build for Production

```bash
npm run build
npm run preview
```

---

## Project Structure

```
MoviesApp/
├── public/           # Static assets
├── src/              # Application source code
│   ├── components/   # Reusable UI components
│   ├── pages/        # Route-level views
│   └── ...
├── index.html        # App entry point
├── vite.config.js    # Vite configuration
└── package.json      # Dependencies & scripts
```

---

## Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview the production build |
| `npm run lint` | Run ESLint |

---

## License

This project is open source. See the repository for details.
