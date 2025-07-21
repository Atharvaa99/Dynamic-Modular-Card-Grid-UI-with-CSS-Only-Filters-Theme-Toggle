# 📦 Dynamic Modular Card Grid UI — CSS-Only Interface

A fully modular, responsive card-based UI system built entirely with **HTML + CSS** — no JavaScript at all.  
Supports **category filters**, **product focus view**, **theme toggling**, and **adaptive sidebar**, all powered by **checkbox/radio hacks** and **Container Queries**.

> 🔥 This UI architecture is perfect for e-commerce galleries, product catalogs, and interactive dashboards.

## 🧠 Features

- 🎯 **Focus Mode**  
  Click a product to highlight it, blur the rest, and visually emphasize the selected card.

- 🗂️ **Filter System (Sidebar)**  
  Dynamically filter product types (Chair, Phone, Camera, etc.) using CSS-only checkboxes. Includes **Clear Filter** support.

- 🌒 **Dark Mode Toggle**  
  Pure CSS theme switcher with backdrop blur and symbol rotation.

- 🧱 **Responsive Grid Layout**  
  Uses `auto-fit` + `minmax` + `clamp()` for fully responsive columns across screen sizes.

- 🔍 **Container Queries**  
  Internal layout of cards adapts individually when their container size shrinks.

- 💡 **Interactive Visuals**  
  Blur, scaling, highlighting, and transitions powered by modern CSS (`:has()`, `:is()`, `filter`, `scale`, `transform`).

## 🌈 Tech Stack

| Layer       | Tech              |
|-------------|-------------------|
| Structure   | HTML5             |
| Styling     | Modern CSS (no JS)|
| Layout      | CSS Grid + Flexbox|
| Responsiveness | Clamp Units + Container Queries |
| Interaction | Checkbox/Radio + `:has()` selector |

## 📐 Responsive Design

- 📱 **Mobile-first** layout
- 🖥️ Automatically adjusts grid columns
- 🧩 Each card is container-query aware

## 🛠️ How to Use

1. Clone or download the repository.
2. Open `index.html` in a browser.
3. Click any product to focus.
4. Use the sidebar (☰) to filter products.
5. Toggle 🌓 for dark mode.

## 🚀 Live Demo

👉 [View Live Demo](https://dynamic-modular-card-grid-ui-with-c.vercel.app)



