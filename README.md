# Netflix GPT
- Create React App
- configure TailwindCSS (CRA support not there)
    - npm install -D tailwindcss@3.4.1 postcss@8 autoprefixer@10(--save-dev devDependencies)
        - PostCSS is a tool that transforms CSS with JavaScript.
    - npx tailwindcss init -p (create tailwind.config.js and postcss.config.js)

# Features
- Login/ Sign Up
    - Sign In/ Sign Up Form
    - redirect to browser page
- Browse (after authentication)
    - Header
    - Main Movie
        - trailer in background
        - title and description
        - movie suggestions
            - MovieLists * N
- NetflixGPT
    - Search Bar
    - Movie suggestions
    