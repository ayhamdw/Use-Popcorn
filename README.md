# 🍿 usePopcorn

> _Because life's too short to forget great movies_

## ✨ Your Personal Cinema Companion

**usePopcorn** is the movie diary you never knew you needed - a delightful React app that helps you track, rate, and remember every film adventure. No more "Wait, did I like that movie?" moments!

![usePopcorn Banner](https://via.placeholder.com/800x200?text=usePopcorn+-+Your+Movie+Diary)

## 🎬 Features That Pop

- **🔍 Smart Search** - Find any movie through the OMDB API
- **⭐ Star Power** - Rate films your way, from "meh" to "masterpiece"
- **📊 Compare & Contrast** - See how your ratings stack up against IMDb
- **📚 Build Your Archive** - Create a personal library of your cinematic journey
- **💾 Never Forget** - All your data persists locally, just like your opinions
- **⌨️ Keyboard Shortcuts** - Navigate like a pro:
  - `Enter` → Reset your search
  - `Escape` → Close movie details

## 🧰 Technical Brilliance

Built with modern web magic:

```
⚛️ React + ⚡ Vite + 🧠 Custom Hooks + 🎨 CSS + 🌐 OMDB API
```

## 🚀 Getting Started in 60 Seconds

```bash
# Clone this cinematic treasure
git clone https://github.com/ayhamdw/Use-Popcorn.git

# Enter the theater
cd use-popcorn

# Grab the popcorn (dependencies)
npm install

# Create your secret ticket (.env file)
echo "VITE_API_KEY=your_omdb_api_key_here" > .env

# Start the show
npm run dev
```

Then visit `http://localhost:5173` and let the movie marathon begin!

## 📂 Project Architecture

```
src/
├── components/           # UI building blocks
│   ├── MovieList.jsx     # Where films come to life
│   ├── MovieDetails.jsx  # The deep dive into cinema
│   ├── SearchBar.jsx     # Find your next favorite
│   └── StarRating.jsx    # Express your critical opinion
│
├── hooks/                # Custom React superpowers
│   ├── useMovies.js      # API communication magic
│   ├── useLocalStorageState.js  # Remember everything
│   └── useKey.js         # Keyboard shortcut wizardry
│
├── App.jsx               # The director of our app
└── main.jsx             # Where it all begins
```

## 💡 Behind the Scenes

- **Local Storage Magic** - Your watched list survives browser restarts
- **Custom Hook Architecture** - Clean, maintainable, and powerful code
- **Responsive Design** - Looks great from phone to ultrawide
- **Fast Performance** - No waiting for ratings to load

## 🤝 Join the Production Team

Love movies? Love coding? We welcome:

- Feature suggestions
- Bug reports (they happen to the best films)
- Pull requests
- Movie recommendations (we're always watching!)

> "Every great film should seem new every time you see it."
> — Roger Ebert

Happy watching! 🍿✨
