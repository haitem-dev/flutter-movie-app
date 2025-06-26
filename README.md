# flutter-movie-app
app to see the latest and popular movies and search in them

# 🎬 Movie App

A beautiful Flutter-based Movie App using [TMDb API](https://www.themoviedb.org/) to fetch movie data. The app features a responsive design, pagination, smooth hero animations, and a splash screen with custom branding.

## 📱 Screenshots
> Add screenshots here to showcase your app  
*(e.g. Home Page, Movie Details, Splash Screen)*

---

## 🚀 Features

- 🔍 Browse popular movies with poster previews
- 🎞 Hero transition animation to movie detail page
- 📝 Movie descriptions, ratings, and metadata
- 📦 Infinite scrolling with pagination
- 🌄 Splash screen with branded background and logo
- 🔙 Back navigation with styled button
- 📱 Fully responsive layout (adapts to screen size)
- ⚡ Built with Flutter & Riverpod

---

## 🧱 Tech Stack

- **Flutter**
- **Riverpod** for state management
- **GetIt** for dependency injection
- **TMDb API** for movie data

---

## 🛠 Setup & Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/movie_app.git
   cd movie_app
Install dependencies:

bash
Copy
Edit
flutter pub get
Configure API Key:

Create a file at assets/config/main.json:

json
Copy
Edit
{
  "BASE_API_URL": "https://api.themoviedb.org/3",
  "BASE_IMAGE_API_URL": "https://image.tmdb.org/t/p/w500",
  "API_KEY": "YOUR_TMDB_API_KEY"
}
Add asset reference in pubspec.yaml:

yaml
Copy
Edit
assets:
  - assets/config/main.json
  - assets/images/logo.png
Run the app:

bash
Copy
Edit
flutter run
🗂 Directory Structure
bash
Copy
Edit
lib/
├── models/          # Movie and Config models
├── services/        # HTTP & MovieService
├── pages/              # pages like main_page.dart or splash_screen  
├── main.dart        # Entry point
├── widgets/         #some widgets of the app
├── controllers/     #the functions that fetch the data from the api 
└── ... 
assets/
└── config/          # API configuration JSON

📦 TODO / Improvements

Watchlist & favorites

Genre/category filters

Trailer preview with YouTube player

Dark mode toggle

🧑‍💻 Author
Your Name
GitHub: @haitem-dev










