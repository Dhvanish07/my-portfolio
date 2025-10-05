# Dhvanish Dhulla — 3D Developer Portfolio

Modern, animated portfolio built with React, Three.js, TailwindCSS, and motion effects to showcase projects and experience.

---

## Features

- 3D visuals via React Three Fiber and Drei
- Smooth motion/scroll animations with Motion
- Responsive UI with TailwindCSS
- Contact form opens WhatsApp chat to +91 7798727444 with a prefilled message
- Fast dev/build with Vite

---

## Tech Stack

| Tech              | Description                           |
|-------------------|---------------------------------------|
| React             | Front-end JavaScript library          |
| Vite              | Fast bundler and dev environment      |
| TailwindCSS       | Utility-first CSS framework           |
| React Three Fiber | 3D rendering with Three.js in React   |
| Drei              | R3F helpers                           |
| Motion            | Animation library for React           |

---

## Project Structure

```bash
├── public/
│   ├── assets/             # Images, textures, models
│   ├── models/             # 3D Astronaut model
│   └── vite.svg
├── src/
│   ├── components/         # Reusable components
│   ├── constants/          # Reusable data
│   ├── sections/           # Page sections (Hero, About, etc.)
│   ├── App.jsx             # Main app file
│   ├── index.css           # Tailwind CSS
│   └── main.jsx            # Entry point
├── tailwind.config.js
└── vite.config.js
```

---

## Local Development

```bash
git clone https://github.com/Dhvanish07/my-portfolio.git
cd my-portfolio
npm install
npm run dev
# open http://localhost:5173
```

---

## Deploying to Vercel

1) Push this repo to GitHub (already done).
2) On Vercel, “Add New Project” → Import `Dhvanish07/my-portfolio`.
3) Framework preset: “Vite”.
4) Build Command: `npm run build`
5) Output Directory: `dist`
6) Environment variables: none required.

After deploy, set custom domain if needed.

---

## Contact

- Email: `dhvanish.07@gmail.com`
- WhatsApp: `wa.me/917798727444`
- LinkedIn: `linkedin.com/in/dhvanish07`

---

## License

This project is for personal portfolio use. You may reference structure/ideas with attribution.
