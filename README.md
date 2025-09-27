# AI News Hub 📰

AI News Hub is a modern news aggregation and summarization platform powered by AI. Built with Next.js, TypeScript, and Tailwind CSS, it delivers personalized news summaries, real-time updates, and local information in an elegant, user-friendly interface.

## 🚀 Features

### 🤖 AI-Powered News
- **AI Summaries**: Generate concise, well-structured summaries of any news article with a single click
- **Smart Categorization**: News articles automatically sorted into relevant categories
- **Personalized Content**: Content tailored to user preferences (when logged in)

### 📱 Modern UI/UX
- **Responsive Design**: Fully responsive across all devices (mobile, tablet, desktop)
- **Dark/Light Mode**: Toggle between themes with a beautiful, animated transition
- **Accessibility**: WCAG compliant design for all users

### 👤 User Authentication
- **OAuth Integration**: Sign in with Google or GitHub
- **MongoDB User Storage**: Secure user data storage with MongoDB
- **Protected Routes**: Access control for authenticated features

### 📑 Content Management
- **Article Bookmarking**: Save articles to read later
- **Share Functionality**: Easily share news to social media
- **Search Capability**: Find articles across different categories

### 🌐 Additional Features
- **Local Weather**: Real-time weather updates for your location
- **Traffic Information**: Live traffic data visualization
- **News Categories**: Browse news by general, business, technology, entertainment, sports, science, and health topics

## 💻 Tech Stack

- **Frontend**: Next.js 14, React, TypeScript, Tailwind CSS, Framer Motion
- **Backend**: Next.js API Routes, MongoDB with Mongoose
- **Authentication**: NextAuth.js with OAuth providers
- **External APIs**: NewsAPI, GROQ AI API for summarization, Weather API
- **UI Components**: Shadcn UI for consistent design

## 🛠 Getting Started

### Prerequisites
- Node.js 18.x or higher
- MongoDB database
- API keys for:
  - NewsAPI
  - GROQ AI API
  - Weather API

### Installation

1. Clone the repository:
```bash
git https://github.com/Anuragarote/AI-News-Aggregator-.git
cd ai-newshub
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env.local` file in the root directory with the following variables:
```
# Database
MONGODB_URI=your_mongodb_uri

# NextAuth
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_nextauth_secret

# OAuth Providers
GITHUB_ID=your_github_client_id
GITHUB_SECRET=your_github_client_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

# APIs
NEXT_PUBLIC_GOOGLE_MAPS_API_KEY=your_google_maps_key
NEXT_PUBLIC_NEWS_API_KEY=your_newsapi_key
GROQ_API_KEY=your_groq_api_key
NEXT_PUBLIC_WEATHER_API_KEY=your_weather_api_key
```

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📄 Pages
- **Home**: Landing page with featured news and widgets
- **News**: Main news feed with category filtering and AI summaries
- **Saved Articles**: Bookmarked articles for registered users
- **About**: Information about the platform
- **Contact**: Contact form and information
- **Sign-in**: Authentication page

## 🔒 Security

- JWT-based authentication
- Server-side and client-side protected routes
- Secure API calls with proper error handling
- Database validation and sanitization


## 🧩 Future Improvements

- User preferences for news sources and categories
- Push notifications for breaking news
- Advanced filtering options
- Mobile app version
- Improved AI summary options with multiple models


## 🙏 Acknowledgements

- [NewsAPI](https://newsapi.org/) for news data
- [GROQ AI](https://groq.com/) for AI summarization capability
- [WeatherAPI](https://www.weatherapi.com/) for weather data
- [Shadcn UI](https://ui.shadcn.com/) for UI components
- [Next.js](https://nextjs.org/) for the amazing framework
- [Vercel](https://vercel.com/) for hosting

---

 
