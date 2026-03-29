# Content Placeholder Card (Skeleton Loader)

This project demonstrates a **skeleton loading UI** using HTML, CSS, and JavaScript. It displays animated placeholder elements while content is being "loaded", then replaces them with actual data after a short delay.

---

## 📌 Features

* Smooth animated skeleton loading effect
* Clean card-based UI design
* Responsive and centered layout
* Simulated data loading using `setTimeout`
* Easy to customize and extend

---

## 🛠️ Technologies Used

* HTML5
* CSS3 (Animations & Flexbox)
* Vanilla JavaScript

---

## 📂 Project Structure

```
project-folder/
│── index.html
│── style.css
│── script.js
```

---

## 🚀 How It Works

1. The page initially renders a card with animated placeholder elements.
2. CSS classes (`animated-bg` and `animated-bg-text`) create a shimmering loading effect.
3. After 2.5 seconds, JavaScript replaces placeholders with real content.
4. The animation classes are removed to reveal the final UI.

---

## 📖 Code Overview

### HTML

Defines the card structure:

* Header (image placeholder)
* Title
* Text excerpt
* Author section

### CSS

* Handles layout and styling
* Creates the skeleton animation using `@keyframes`
* Uses gradients for the loading shimmer effect

### JavaScript

* Selects DOM elements
* Simulates loading delay with `setTimeout`
* Injects actual content dynamically
* Removes animation classes after loading

---

## ▶️ Getting Started

1. Clone or download this project
2. Open `index.html` in your browser
3. Watch the skeleton loader transition into real content

---

## 🎯 Customization Tips

* Replace the image URLs with your own content
* Adjust animation speed in CSS:

  ```css
  animation: bgPos 1s linear infinite;
  ```
* Change loading time in JavaScript:

  ```js
  setTimeout(getData, 2500)
  ```

---

## 💡 Use Cases

* Blog post previews
* News cards
* Profile cards
* Dashboard loading states
* Any UI requiring async content loading

---

## 📸 Preview Behavior

1. Gray animated placeholders appear
2. Content loads after delay
3. Animation disappears
4. Final content is displayed smoothly

---

## 📜 License

This project is open-source and free to use for learning and personal projects.

---

## 🙌 Acknowledgements

* Images from Unsplash
* Profile pictures from Random User API

---

## ✨ Author

Created as a simple demonstration of skeleton loaders using pure frontend technologies.

---
"# content-placeholder" 
