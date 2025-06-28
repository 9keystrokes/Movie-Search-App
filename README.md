# 🎬 Movie Search App - Assignment 2 Submission

A movie search frontend application built with Next.js and TypeScript, integrating with the OMDB API.

## 📋 Assignment Requirements

This submission implements **Assignment 2: Movie Search App (Frontend)** with all required features and bonus functionalities.

## 🛠️ Tech Stack Used

- **Next.js** with App Router
- **TypeScript** 
- **Redux Toolkit** for state management
- **Tailwind CSS** for styling
- **shadcn/ui** for components
- **OMDB API** for movie data
- **React Query** for data fetching (bonus)
- **Framer Motion** for animations (bonus)

## 📄 Pages Implemented

### `/movies` - Movie List Page ✅
- Displays list of movies fetched from OMDB API
- Movie cards show: poster image, title, year
- Each card is clickable and navigates to details page
- Search functionality with auto-complete
- Debounced API calls to avoid unnecessary requests
- Search filters for genre and year (bonus)

### `/movies/:id` - Movie Details Page ✅  
- Shows detailed movie info using IMDb ID
- Includes: poster, title, year, genre, director, actors, plot summary
- Star rating system for user ratings
- Ratings stored in localStorage (client-side only)

## ✨ Features Implemented

### 🔍 Search Functionality ✅
- Search bar on `/movies` page
- Auto-complete movie titles as user types  
- Debounced API calls (500ms delay)
- Real-time search results

### ⭐ Rating Feature ✅
- 5-star rating system on movie details page
- Client-side only implementation
- Stored in localStorage for persistence

### 🌙 Dark Mode Toggle ✅
- Toggle between light and dark themes
- Theme persisted in localStorage
- System preference detection on first load

### 🏆 Bonus Features ✅
- **React Query** for data fetching with caching and background updates
- **Loading states** with elegant spinners during API calls
- **Error states** with user-friendly error messages
- **Framer Motion** for page transitions and hover effects  
- **Search filters** for year and genre
- **Responsive design** works on all device sizes

## 🚀 Setup Instructions

### Prerequisites
- Node.js 18+
- npm or yarn
- OMDB API Key (free from [omdbapi.com](http://omdbapi.com/))

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd movie-search-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   
   Create `.env.local` file in root directory:
   ```env
   OMDB_API_KEY=your_api_key_here
   ```
   
   Get your free API key from [OMDB API](http://omdbapi.com/apikey.aspx)

4. **Run the application**
   ```bash
   npm run dev
   ```

5. **Open browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🌐 API Used

**OMDB API** - The Open Movie Database
- Free API for movie information
- Provides comprehensive movie details
- Used for search and individual movie data

## 📊 Assignment Criteria Met

| Category | Status | Implementation |
|----------|--------|----------------|
| **API Integration** | ✅ | OMDB API with proper error handling |
| **Routing** | ✅ | Next.js App Router with dynamic routes |
| **UI/UX** | ✅ | Responsive layout with Tailwind CSS |
| **Component Design** | ✅ | Modular, reusable components |
| **State Management** | ✅ | Redux Toolkit for global state |
| **Search Experience** | ✅ | Debounced search with autocomplete |
| **Bonus Features** | ✅ | React Query, animations, filters |

---

**Submission by:** Nayan Mandal  
Reach me at: bt22csd035@iiitn.ac.in (Professional Email) | nayan.iiitn@gmail.com (Personal Email)
