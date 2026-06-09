# Movix 🎬

A modern movie and TV show discovery platform built with React and Vite. Browse trending content, search for your favorites, and explore detailed information about movies and TV series.

## ✨ Features

- **🔍 Advanced Search** - Find movies and TV shows instantly
- **📈 Trending Content** - Discover what's popular right now
- **⭐ Ratings & Reviews** - See ratings and detailed information
- **🎥 Trailers & Videos** - Watch trailers and behind-the-scenes content
- **📱 Responsive Design** - Perfect experience on all devices
- **♾️ Infinite Scroll** - Seamless browsing experience
- **🎭 Genre Filtering** - Browse by your favorite genres

## 🚀 Quick Start

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd movix-main
   ```

2. **Install dependencies**
    ```bash
    npm install
    ```

3. **Set up environment variables**
    ```env
    cp .env.example .env
    ```

    Add your TMDB API key to the .env file:
    ```
    VITE_APP_TMDB_TOKEN=your_api_key_here
    ```

4. **Start development server**
    ```bash
    npm run dev
    ```

5. **Open your browser Navigate** to ```http://localhost:5173```

# 🛠️ Scripts
- ```npm run dev``` - Start development server

- ```npm run build``` - Build for production

- ```npm run preview``` - Preview production build locally

# 🏗️ Tech Stack
- Frontend Framework: React 18
- Build Tool: Vite
- Styling: SCSS/Sass
- State Management: Redux Toolkit
- Routing: React Router DOM
- HTTP Client: Axios
- Icons: React Icons
- Date Handling: Day.js

📁 Project Structure
```
movix-main/
├── public/                # Static assets
├── src/
│   ├── assets/            # Images, logos, icons
│   ├── components/        # Reusable UI components
│   │   ├── carousel/      # Content carousel
│   │   ├── header/        # Navigation header
│   │   ├── footer/        # Site footer
│   │   └── ...
│   ├── hooks/             # Custom React hooks
│   ├── pages/             # Page components
│   │   ├── home/          # Homepage
│   │   ├── details/       # Movie/TV details
│   │   ├── explore/       # Browse content
│   │   └── ...
│   ├── store/             # Redux store configuration
│   ├── utils/             # Utility functions
│   └── App.jsx            # Main app component
├── .env                   # Environment variables
├── package.json           # Dependencies and scripts
└── README.md             # Project documentation
```

# 🎨 Key Components
- **Header** - Navigation with search functionality

- **HeroBanner** - Featured content showcase

- **Carousel** - Scrollable content sections

- **MovieCard** - Individual movie/show display

- **VideoPopup** - Trailer and video player

- **CircleRating** - Custom rating component

# 🔧 Configuration

## Environment Variables

Create a .env file in the root directory:
```env
VITE_APP_TMDB_TOKEN=your_tmdb_api_key
```

## API Integration
The app uses The Movie Database (TMDB) API. Get your free API key from TMDB.

### 📱 Pages
- **Home** - Trending movies, popular content, top rated

- **Details** - Movie/TV show information, cast, videos

- **Explore** - Browse movies or TV shows with filters

- **Search Results** - Search functionality results

- **Terms of Use** - Legal terms and conditions

- **Privacy Policy** - Privacy and data handling policy

- **About** - Information about the platform

- **Blog** - Entertainment news and updates

- **FAQ** - Frequently asked questions

### 🎯 Performance Features
- Lazy loading for images and components

- Infinite scroll for seamless browsing

- Code splitting for optimal bundle size

- Responsive design for all screen sizes

### 🤝 Contributing
- Fork the repository

- Create a feature branch (git checkout -b feature/amazing-feature)

- Commit your changes (git commit -m 'Add amazing feature')

- Push to the branch (git push origin feature/amazing-feature)

- Open a Pull Request

### 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

### 🙏 Acknowledgments
- TMDB for the comprehensive movie database API

- React Icons for the icon library

- Vite for the blazing fast build tool

### Author

Made with ❤️ by Deepak Majhi

