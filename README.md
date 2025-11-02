# 🌍 REST Countries API with Color Theme Switcher

A modern, responsive web application built with Vue 3 that allows users to explore information about countries around the world. This project integrates with the [REST Countries API](https://restcountries.com/) to display country data with an elegant dark/light theme switcher.

## ✨ Features

- 🔍 **Search Countries**: Search for countries by name with real-time filtering
- 🌎 **Filter by Region**: Filter countries by region (Africa, America, Asia, Europe, Oceania)
- 📱 **Responsive Design**: Fully responsive layout that works on all device sizes
- 🌓 **Dark/Light Mode**: Toggle between dark and light themes with persistent preferences
- 📊 **Country Details**: View detailed information about each country including:
  - Native name and official name
  - Population statistics
  - Region and subregion
  - Capital city
  - Top-level domain (TLD)
  - Currencies
  - Languages
  - Border countries
  - Country flags
- ⚡ **Fast & Modern**: Built with Vue 3 and Vite for optimal performance
- 🎨 **Beautiful UI**: Clean, modern interface built with Tailwind CSS

## 🛠️ Tech Stack

- **Vue 3** - Progressive JavaScript framework
- **Vite** - Next-generation frontend build tool
- **Vue Router** - Official router for Vue.js
- **Tailwind CSS** - Utility-first CSS framework
- **REST Countries API** - Free API for country information
- **Lucide Icons** - Beautiful icon library
- **Reka UI** - Vue component library
- **VueUse** - Collection of Vue Composition utilities

## 📋 Prerequisites

- Node.js (version ^20.19.0 or >=22.12.0)
- npm or yarn package manager

## 🚀 Getting Started

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd rest-countries-api-with-color-theme-switcher
```

2. Install dependencies:
```bash
npm install
```

### Development

Run the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or the next available port).

### Build for Production

Create a production build:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

## 📖 Usage

### Searching Countries

- Type a country name in the search box and press Enter to filter countries
- Clear the search box to view all countries again

### Filtering by Region

- Use the "Filter by region" dropdown to filter countries by continent
- Select a region to view countries from that area only
- The filter can be cleared by searching for a country

### Viewing Country Details

- Click on any country card to view detailed information
- Use the "Back" button to return to the main countries list
- Border countries are displayed as clickable badges on the detail page

### Theme Switcher

- Click the theme toggle button in the navigation bar to switch between dark and light modes
- Your theme preference is saved in localStorage and persists across sessions
- The app automatically detects your system's color scheme preference on first visit

## 🏗️ Project Structure

```
rest-countries-api-with-color-theme-switcher/
├── src/
│   ├── assets/           # Static assets (images, SVGs)
│   ├── components/       # Vue components
│   │   ├── ui/          # Reusable UI components
│   │   ├── CountryCard.vue
│   │   └── Navbar.vue
│   ├── composables/     # Vue composition functions
│   │   ├── country.js   # Country data fetching logic
│   │   └── theme.js     # Theme management logic
│   ├── lib/             # Utility functions
│   ├── routes/          # Vue Router configuration
│   ├── views/           # Page components
│   │   ├── Countries.vue
│   │   └── Country.vue
│   ├── App.vue          # Root component
│   └── main.js          # Application entry point
├── public/              # Public static files
├── index.html           # HTML template
├── vite.config.js       # Vite configuration
└── package.json         # Project dependencies
```

## 🎨 Customization

### Theme Colors

The theme colors can be customized in the Tailwind CSS configuration. The app uses CSS custom properties for theme colors that can be modified in your stylesheet.

### API Configuration

The app uses the REST Countries API v3.1. The API endpoints are configured in `src/composables/country.js`. You can modify the API calls to fetch different country fields or use different endpoints.

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## 🌐 API Reference

This project uses the [REST Countries API](https://restcountries.com/) to fetch country data. The API is free and doesn't require authentication.

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [REST Countries API](https://restcountries.com/) for providing free country data
- [Frontend Mentor](https://www.frontendmentor.io/) for the design challenge
- [Vue.js](https://vuejs.org/) community for the excellent framework
