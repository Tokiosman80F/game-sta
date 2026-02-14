```markdown
# 🎮 GameSTA

GameSTA is a modern, responsive single-page website built using pure **HTML5** and **CSS3**.  
This project focuses on clean architecture, scalable CSS structure, and maintainable frontend development practices.

---

## 🚀 Project Overview

GameSTA is designed as a high-quality front-end layout project that demonstrates:

- Structured CSS architecture
- Component-based styling
- Mobile-first responsive design
- Clean semantic HTML
- Organized folder structure for scalability

This project serves as a strong foundation-level portfolio piece showcasing professional frontend fundamentals.

---

## 🛠 Tech Stack

- HTML5
- CSS3
- Flexbox
- CSS Grid
- BEM Naming Convention
- Mobile-First Approach

No CSS frameworks or JavaScript libraries were used.

---

## 📁 Folder Structure
```

GameSTA/
│
├── index.html
│
└── css/
├── style.css (Main import file)
│
├── abstracts/
│ └── variables.css
│
├── base/
│ ├── reset.css
│ ├── typography.css
│ └── base.css
│
├── layout/
│ ├── header.css
│ ├── hero.css
│ ├── sections.css
│ └── footer.css
│
├── components/
│ ├── navbar.css
│ ├── button.css
│ └── card.css

````

---

## 🧠 Architecture Philosophy

### 1️⃣ Separation of Concerns
- **Base** → Global styles and resets
- **Layout** → Page structure and sections
- **Components** → Reusable UI elements
- **Abstracts** → Design tokens and variables

### 2️⃣ Component-Based Responsive Strategy (Option A)
Each component or layout file contains its own media queries to improve maintainability and scalability.

Example:

```css
.hero {
  padding: 40px 20px; /* Mobile default */
}

@media (min-width: 768px) {
  .hero {
    padding: 80px;
  }
}
````

This ensures:

- Easier debugging
- Better modularity
- Scalable growth as the project expands

---

## 📱 Responsive Design

GameSTA is fully responsive:

- Mobile-first structure
- Tablet breakpoints
- Desktop optimization
- Flexible layouts using Grid and Flexbox
- Fluid spacing and typography

---

## 🎨 Features

- Full-width hero section with background image
- Structured navigation bar
- Modern layout sections
- Clean typography system
- Organized CSS architecture
- Accessibility-aware structure

---

## ♿ Accessibility Considerations

- Semantic HTML5 elements
- Proper heading hierarchy
- Decorative background images handled via CSS
- Readable color contrast
- Scalable and responsive font sizing

---

## 🎯 Project Goals

- Practice scalable CSS architecture
- Apply BEM methodology
- Improve layout structuring skills
- Build production-quality static UI
- Strengthen frontend development fundamentals

---

## 🔮 Future Improvements

- Add animations (CSS transitions / keyframes)
- Implement dark mode
- Optimize images using WebP
- Improve Lighthouse performance score
- Convert to a React-based version

---

## 👨‍💻 Author

**Toki Osman**
Frontend Developer | Software Engineer

---

> GameSTA is a structured frontend project built to reflect real-world CSS architecture practices.

```

```
