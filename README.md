# 📌 Pinterest Clone

A modern Pinterest-style image gallery web app built using **HTML**, **Tailwind CSS**, and **JavaScript**. This project is part of a minor academic submission and demonstrates search-based filtering, dynamic rendering, and fullscreen image preview functionality.

---

## 🚀 Features

- 🖼️ Pinterest-style masonry layout
- 🔍 Live image search suggestions based on name
- 👆 Click-to-preview images in a full-screen popup
- ❌ Close popup by button, clicking outside, or Escape key
- 📱 Fully responsive for all screen sizes
- 🎨 Styled using Tailwind CSS and Remix Icons

---

## 🛠️ Tech Stack

- **HTML5**
- **Tailwind CSS** (via CDN)
- **Vanilla JavaScript**
- **Remix Icons**
- **Unsplash CDN Images**

---

## 💡 Functionality Overview

- All image data is stored in a JavaScript array of objects.
- The gallery is generated dynamically using `.forEach()`.
- The search bar provides live suggestions based on what the user types.
- Clicking any image shows it in a centered modal popup with its name and a close button.
- Accessibility features like pressing `Escape` or clicking the background to close are supported.

---

## 🛣️ Future Improvements

Here are some possible enhancements to take this project further:

- Allow users to upload their own images
- Implement keyword-based or fuzzy search (not just "starts with")
- Add next/previous navigation in the popup view
- Enable zooming and panning of fullscreen images
- Integrate with a real-time database like Firebase
- Use Unsplash API to load live images
- Add download/save-to-gallery buttons
- Add user profile and login/logout functionality
- Improve mobile experience with swipe gestures
- Add dark/light theme toggle

---

## 📝 How to Use

1. Clone or download the project.
2. Open `index.html` in your browser.
3. Enjoy the Pinterest clone functionality.

No frameworks or build tools needed.

---