# Intake


**Intake** is a web-based calorie tracker to log meals and workouts, and monitor your daily calorie intake.

---

## Features

- Add meals with calorie values  
- Add workouts with calories burned  
- Monitor total calorie intake  
- Modular architecture using Webpack  

---

## Technologies

- JavaScript (Vanilla)
- Webpack  
- HTML & CSS  (Vanilla)
- npm  

---

## Setup

1. Clone the repository:  
   ```bash
   git clone https://github.com/vsniranjan/intake
   cd Intake
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run in development mode:
   ```bash
   npm run dev
   ```
   Starts a local server with hot reloading.

4. Build for production:
   ```bash
   npm run build
   ```
   Production-ready files will be in the `dist/` folder.

---

## Project Structure

```
Intake/
├─ src/
│  ├─ css/
│  │  └─ bootstrap.css
│  ├─ webfonts/
│  ├─ app.js
│  ├─ Item.js
│  ├─ Tracker.js
│  ├─ Storage.js
│  └─ index.html 
├─ dist/          
├─ package.json
├─ package-lock.json
├─ favicon.ico
├─ webpack.config.js
└─ README.md
```

---

## Usage

1. Open the app in your browser (`npm run dev` or `dist/index.html` after build).
2. Add meals and workouts with calories.
3. Track total calorie intake and burned calories.

---

## License

MIT License
