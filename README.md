# Vue.js Job Management Application

A modern job management application built with Vue.js 3, featuring a clean and intuitive user interface. This project demonstrates the implementation of Vue.js fundamentals, state management, and API integration.

## Features

- Task management with CRUD operations
- Real-time status updates
- RESTful API integration with JSON Server
- Responsive design
- User status management (active/pending/inactive)
- Modern UI with Tailwind CSS

## Technologies Used

- Vue.js 3
- Vite
- JSON Server
- Axios
- Vue Router
- Tailwind CSS
- Vue Toastification
- PrimeIcons

## Prerequisites

- Node.js (Latest LTS version recommended)
- npm (comes with Node.js)

## Getting Started

1. Clone the repository:

```bash
git clone [your-repository-url]
cd vue-crash-2024
```

2. Install dependencies:

```bash
npm install
```

3. Start the JSON Server (in one terminal):

```bash
npm run server
```

4. Start the development server (in another terminal):

```bash
npm run dev
```

5. Open your browser and navigate to `http://localhost:5173`

## 🔧 Project Structure

```
vue-crash-2024/
├── src/
│   ├── assets/         # Static assets
│   ├── components/     # Vue components
│   ├── router/         # Vue Router configuration
│   ├── views/          # Page components
│   ├── jobs.json       # JSON Server database
│   └── main.js         # Application entry point
├── public/             # Public static files
└── package.json        # Project dependencies and scripts
```

## Key Features Implementation

- **Task Management**: Add, view, and delete tasks with real-time updates
- **Status Management**: Toggle between different user statuses
- **API Integration**: Seamless integration with JSON Server for data persistence
- **Responsive Design**: Mobile-friendly interface using Tailwind CSS

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run server` - Start JSON Server

## Contributing

Feel free to fork this project and submit pull requests for any improvements.
