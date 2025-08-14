# Disney+ Hotstar Clone 🎬

A modern, responsive Disney+ Hotstar clone built with React and Tailwind CSS. This project replicates the core functionality and design of the popular streaming platform, featuring a dynamic movie slider, genre-based content organization, and a sleek navigation system.

![Disney+ Hotstar Clone](https://img.shields.io/badge/React-18.3.1-blue?style=for-the-badge&logo=react)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.0.0-38B2AC?style=for-the-badge&logo=tailwind-css)
![Vite](https://img.shields.io/badge/Vite-6.0.5-646CFF?style=for-the-badge&logo=vite)

## ✨ Features

- **🎯 Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **🎬 Dynamic Movie Slider**: Interactive slider showcasing trending movies and TV shows with smooth navigation
- **🎭 Genre-based Content**: Organized content display by movie genres (Action, Adventure, Animation, Comedy, etc.)
- **🔍 Navigation System**: Intuitive navigation with search, home, TV, originals, movies, and sports sections
- **📱 Mobile-First**: Optimized mobile experience with collapsible navigation menu
- **🎨 Modern UI**: Clean, modern interface with hover effects and smooth transitions
- **📊 Real-time Data**: Fetches live movie data from The Movie Database (TMDB) API
- **⚡ Fast Performance**: Built with Vite for lightning-fast development and build times

## 🛠️ Technologies Used

- **React 18.3.1** - Modern React with hooks and functional components
- **Tailwind CSS 4.0.0** - Utility-first CSS framework for rapid UI development
- **Vite 6.0.5** - Next-generation frontend build tool
- **React Icons** - Comprehensive icon library
- **The Movie Database (TMDB) API** - Real movie and TV show data
- **ESLint** - Code linting and formatting

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/disney-hotstar-clone.git
   cd disney-hotstar-clone
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## 📁 Project Structure

```
DisneyHotstar/
├── src/
│   ├── Components/
│   │   ├── Navbar.jsx          # Main navigation component
│   │   ├── Navitem.jsx         # Individual navigation items
│   │   ├── Slider.jsx          # Movie slider with trending content
│   │   ├── Genre.jsx           # Genre-based content organization
│   │   ├── MovieListCard.jsx   # Movie card component
│   │   └── AlternativeCard.jsx # Alternative movie card layout
│   ├── assets/
│   │   ├── Images/             # Static images (logos, brand assets)
│   │   └── Videos/             # Video assets
│   ├── App.jsx                 # Main application component
│   ├── main.jsx                # Application entry point
│   └── index.css               # Global styles
├── package.json                # Project dependencies and scripts
├── vite.config.js             # Vite configuration
└── README.md                   # Project documentation
```

## 🎯 Key Components

### Navbar
- Responsive navigation with collapsible mobile menu
- Brand logo and user profile section
- Navigation items: Search, Home, TV, Originals, Movies, Sports

### Slider
- Dynamic movie slider with trending content
- Smooth horizontal scrolling with navigation arrows
- Fetches real-time data from TMDB API
- Hover effects and responsive design

### Genre
- Organizes content by movie genres
- Alternating card layouts for visual variety
- Displays top 5 genres with movie collections

## 🎨 Design Features

- **Dark Theme**: Cinematic dark background for optimal viewing experience
- **Hover Effects**: Interactive elements with smooth transitions
- **Responsive Grid**: Adaptive layouts for different screen sizes
- **Smooth Animations**: CSS transitions for enhanced user experience
- **Modern Typography**: Clean, readable font hierarchy

## 🔧 Configuration

### API Configuration
The project uses The Movie Database (TMDB) API for movie data. The API key is configured in the `Slider.jsx` component:

```javascript
const apiKey = 'cb55a2068c4fb8b52eca7166da3b0595'
const movieBaseUrl = 'https://api.themoviedb.org/3'
```

### Tailwind CSS
The project uses Tailwind CSS v4.0.0 with custom configuration for optimal styling and responsive design.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [The Movie Database (TMDB)](https://www.themoviedb.org/) for providing the movie data API
- [React Icons](https://react-icons.github.io/react-icons/) for the comprehensive icon library
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Vite](https://vitejs.dev/) for the fast build tool

## 📞 Contact

- **GitHub**: [@yourusername](https://github.com/Sahil1607cms)
- **Email**: your.sahil16072004@gmail.com

---

⭐ If you found this project helpful, please give it a star on GitHub! 
