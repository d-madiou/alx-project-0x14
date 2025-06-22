# alx-project-0x14
# alx-project-0x14 - CineSeek Movie Application 🎬

This project is a modern web application that consumes the **MoviesDatabase API** to allow users to explore, filter, and interact with movie data. It’s built with **Next.js**, **TypeScript**, and **Tailwind CSS** for a professional frontend experience.

---

## 🚀 API Overview

The **MoviesDatabase API** provides programmatic access to movie metadata including titles, images, genres, release years, and more. It supports filtering and pagination and allows real-time data consumption of movie listings via RESTful endpoints.

---

## 📦 API Version

**v1.0.0**  
Hosted on [RapidAPI](https://rapidapi.com/SAdrian/api/moviesdatabase)

---

## 🔗 Available Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/titles` | GET | Fetch list of movie titles |
| `/titles/{id}` | GET | Get detailed info for a specific movie |
| `/titles/search/title/{title}` | GET | Search for movies by title |
| `/titles/utils/genres` | GET | Get all available movie genres |
| `/titles/utils/languages` | GET | Get supported languages |

---

## 📤 Request and Response Format

### ✅ Example Request

```http
POST /titles?year=2024&genre=Comedy&page=1
Host: moviesdatabase.p.rapidapi.com
Headers:
  x-rapidapi-host: moviesdatabase.p.rapidapi.com
  x-rapidapi-key: YOUR_API_KEY
