# Netflix Clone — React + Firebase

A Netflix-style movie browsing web app: browse movies by category in carousels, watch trailers, authenticate with Firebase, and manage the movie catalog through an admin page.

> 🇻🇳 Web xem phim kiểu Netflix — duyệt phim theo danh mục, đăng nhập Firebase, có trang quản lý phim. Tóm tắt tiếng Việt ở [cuối trang](#-tóm-tắt-tiếng-việt).

## Features

- **Home page** with hero banner and category carousels (Netflix-style UI)
- **Firebase Authentication** — sign up / sign in
- **Movie management page** — add/edit movie entries, poster upload (Firebase Storage)
- Movie data fetched via **Axios** from the backing API/TMDB
- Client-side routing with **React Router v6**

## Tech stack

| Layer | Tech |
|---|---|
| UI | React 18, SCSS |
| Build | Vite |
| Auth & storage | Firebase (Auth, Storage) |
| HTTP | Axios |
| Routing | react-router-dom v6 |

## Run locally

```bash
npm install
# create your own Firebase project and fill the config in src/config/firebase.js
npm run dev      # http://localhost:5173
```

## Project structure

```
src/
├── pages/            # home, movie-management
├── components/       # header, carousel, ...
├── config/firebase.js
└── utils/            # upload helpers
```

---

## 🇻🇳 Tóm tắt tiếng Việt

App web mô phỏng Netflix viết bằng **React 18 + Vite**: trang chủ có banner + carousel phim theo danh mục, đăng nhập/đăng ký qua **Firebase Auth**, trang quản lý phim (thêm/sửa, upload poster lên Firebase Storage), gọi API bằng Axios. Chạy local: `npm install && npm run dev` (cần điền config Firebase của bạn vào `src/config/firebase.js`).
