# Netflix GPT
## Project Setup
Before starting the project, please add a .env file and include the TMDB and OpenAI keys as follows:

# About me:
<a href="https://www.linkedin.com/in/sagargaud332/" target="_blank"><img alt="" src="https://img.shields.io/badge/LinkedIn-000?logo=linkedin&logoColor=0A66C2&style=for-the-badge" style="vertical-align:center" /></a>

```sh
REACT_APP_TMDB_API_KEY=your_tmdb_api_key
REACT_APP_OPENAI_API_KEY=your_openai_api_key
```

## Features
Authentication
Login/Sign Up
Sign In / Sign Up Form
Redirect to Browse Page after authentication
Browse (after authentication)
Header
## Main Movie Section
Trailer in Background
Title & Description
Movie Suggestions
Movie Lists * N
NetflixGPT
Search Bar
Movie Suggestions
## Development Steps
### Setup
Create React App
Configure TailwindCSS
Setup Firebase
## Authentication
Implement Login Form
Implement Sign Up Form
Form Validation
Create SignUp User Account
Implement Sign In User API
Implement Sign Out
Unsubscribe from onAuthStateChanged callback
## Routing & State Management
Configure App Routing
Create Redux Store with userSlice
Redirect to Login Page if not authenticated
## UI Components
Create Header
Build Main Container and Secondary Container
Build Movie List and Movie Card Components
## API Integration
Register TMDB API & Get Access Token
Fetch Now Playing Movies Data from TMDB
Create Custom Hook for Now Playing Movies
Create movieSlice and Update Store with Movies Data
Fetch Trailer Video Data
Update Store with Trailer Video Data
## GPT Integration
Add Multi-language Feature
Get OpenAI API Key
Implement GPT Search API Call
Fetch gptMoviesSuggestions from TMDB
Create gptSlice and Add Data
Create GPT Search Bar and Movie Suggestions Container
## Enhancements
Memoization
Add Hardcoded Values to Constants File
Bug Fixes: Update displayName and Profile Picture on Sign Up
Redirect /browse to Login Page if not authenticated
TailwindCSS for Styling
Make Site Responsive
## Deployment
Deploy App to Production
Add .env File to .gitignore

```sh
src
├── components
│   ├── Auth
│   │   ├── LoginForm.js
│   │   └── SignUpForm.js
│   ├── Browse
│   │   ├── Header.js
│   │   ├── MainContainer.js
│   │   ├── SecondaryContainer.js
│   │   ├── MovieList.js
│   │   └── MovieCard.js
│   ├── GPT
│   │   ├── GPTSearchPage.js
│   │   └── GPTSearchBar.js
│   └── Shared
│       ├── NavBar.js
│       ├── Footer.js
│       └── Loader.js
├── hooks
│   ├── useNowPlayingMovies.js
│   └── usePopularMovies.js
├── redux
│   ├── slices
│   │   ├── userSlice.js
│   │   ├── movieSlice.js
│   │   └── gptSlice.js
│   └── store.js
├── services
│   ├── firebase.js
│   └── tmdb.js
├── utils
│   ├── constants.js
│   └── helpers.js
├── App.js
├── index.js
└── .env

```

//Active Project
