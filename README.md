# 📦 Frontend Take Home Assignment

This project is a React-based web application developed as part of a take-home assignment for Resollect. The app focuses on building responsive, reusable components and incorporates modern frontend best practices.

---

## 🚀 Live Demo

🔗 [Deployed Link]([(https://resollect-myproject.vercel.app/)](https://resollect-myproject.vercel.app/))

---

## 📂 GitHub Repository

🔗 [Repository Link](https://github.com/Ramendra777/resollect_myproject)

---

## 🛠 Tech Stack

- **React** (Functional Components + Hooks)
- **JavaScript / TypeScript** (used)
- **CSS Modules / Styled Components / TailwindCSS** 
- **Axios / Fetch API** – for API integration
- **Jest / React Testing Library** – for unit testing 
- **Vite / Create React App** – for bootstrapping the project

---

## 🧩 Key Features

- ✅ Fully responsive UI
- ✅ Upload functionality from the filter section
- ✅ Modular & scalable code structure
- ✅ Deployed live for easy access
- ✅ Bonus points ready: test cases 

---

## 📝 Instructions

- Clone the repository:
  ```bash
  git clone https://github.com/Ramendra777/resollect_myproject

---

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

```js
export default tseslint.config({
  extends: [
    // Remove ...tseslint.configs.recommended and replace with this
    ...tseslint.configs.recommendedTypeChecked,
    // Alternatively, use this for stricter rules
    ...tseslint.configs.strictTypeChecked,
    // Optionally, add this for stylistic rules
    ...tseslint.configs.stylisticTypeChecked,
  ],
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

You can also install [eslint-plugin-react-x](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-x) and [eslint-plugin-react-dom](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-dom) for React-specific lint rules:

```js
// eslint.config.js
import reactX from 'eslint-plugin-react-x'
import reactDom from 'eslint-plugin-react-dom'

export default tseslint.config({
  plugins: {
    // Add the react-x and react-dom plugins
    'react-x': reactX,
    'react-dom': reactDom,
  },
  rules: {
    // other rules...
    // Enable its recommended typescript rules
    ...reactX.configs['recommended-typescript'].rules,
    ...reactDom.configs.recommended.rules,
  },
})
```
