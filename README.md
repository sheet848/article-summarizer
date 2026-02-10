# 🧠 Article Summarizer App

A modern web app that summarizes any article using OpenAI’s NLP model. Built with React, Vite, and integrated with RapidAPI for fetching summaries.

## 🔗 Live Demo

👉 [View Live App](https://ai-summarizer-three-bay.vercel.app/)

## 📸 Overview

This app allows users to input any article URL and get a concise summary powered by AI. Summaries are cached locally, so users can revisit previously summarized content instantly.

## ⚙️ Tech Stack

- ⚛️ React + Vite
- 🧠 OpenAI API via [RapidAPI](https://rapidapi.com/restyler/api/article-extractor-and-summarizer/)
- 🔖 Redux Toolkit (for state management)
- 💅 Tailwind CSS (for styling)
- 🧠 Custom Hooks & Functional Components
- 🗂 LocalStorage (for history)

## 🚀 Features

- Summarize any article from a URL
- View and copy summaries easily
- Persistent history using localStorage
- Clean, responsive UI
- Error handling for invalid or blocked URLs

## 📁 Project Structure

```
src/
├── assets/assets/   # svg images used
├── components/      # Reusable UI components
  |-- Demo.jsx
  |-- Hero.jsx 
├── services/        # redux store
  |-- article.js
  |-- store.js
├── App.jsx          # the homepage
├── App.css
├── main.jsx
└── index.css
```

## 🧠 API Used

- [Article Extractor and Summarizer API](https://rapidapi.com/restyler/api/article-extractor-and-summarizer/) via RapidAPI

Made with 💻 by [Sheetal Naik]
---

**Inspired by JavaScript Mastery’s YouTube Tutorial.**
