# ☁️ Salesforce Clone

> A pixel-conscious, responsive front-end clone of the Salesforce website, built with **HTML and CSS**.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/design-responsive-00A1E0)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

This project recreates the look and feel of the Salesforce homepage as a **front-end practice project**. It focuses on layout, typography, spacing, colors, and responsiveness using modern CSS, with no frameworks.

> ⚠️ **Disclaimer:** This is an educational project made for learning purposes only. It is not affiliated with, endorsed by, or connected to Salesforce, Inc. All trademarks, logos, and brand names belong to their respective owners.

**🔗 Live Demo:** _add your deployed link here_
**📦 Repository:** _add your GitHub link here_

---

## 📑 Table of Contents

- [Preview](#-preview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Design Details](#-design-details)
- [Responsive Breakpoints](#-responsive-breakpoints)
- [What I Learned](#-what-i-learned)
- [Future Improvements](#-future-improvements)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## 📸 Preview

> Create a `screenshots/` folder, add your images, and update the paths below.

| Desktop | Mobile |
| ------- | ------ |
| ![Desktop view](screenshots/desktop.png) | ![Mobile view](screenshots/mobile.png) |

---

## ✨ Features

- 🧭 **Sticky navigation bar** with logo, menu links, and call-to-action buttons
- 🦸 **Hero section** with headline, subtext, and sign-up buttons
- 🧩 **Product / solutions cards** laid out with CSS Grid
- 💬 **Customer stories and testimonials** section
- 📊 **Stats / highlights** section
- 📨 **Call-to-action banner** and footer with multiple link columns
- 🎨 **Hover effects and smooth transitions** on buttons and cards
- 📱 **Fully responsive** across mobile, tablet, and desktop
- ⚡ **Lightweight**: no frameworks or libraries

---

## 🛠 Tech Stack

| Technology | Purpose                                             |
| ---------- | --------------------------------------------------- |
| HTML5      | Semantic page structure                             |
| CSS3       | Styling, Flexbox, Grid, animations, media queries   |
| Google Fonts | Typography *(optional)*                           |
| Font Awesome | Icons *(optional)*                                |

---

## 📂 Project Structure

```
salesforce-clone/
├── index.html          # Main page
├── css/
│   └── style.css       # All styles
├── images/             # Logos, hero images, icons
├── screenshots/        # README preview images
└── README.md
```

> Update this tree to match your actual files and folder names.

---

## 🚀 Getting Started

No build step or installation is needed.

### Option 1: Open directly

1. **Clone the repository**

   ```bash
   git clone https://github.com/<your-username>/salesforce-clone.git
   cd salesforce-clone
   ```

2. **Open `index.html`** in your browser (double-click it).

### Option 2: Run with a local server (recommended)

Using the **Live Server** extension in VS Code:

1. Open the project folder in VS Code
2. Right-click `index.html`
3. Choose **Open with Live Server**

Or with Python:

```bash
python -m http.server 8000
```

Then visit **http://localhost:8000**.

---

## 🎨 Design Details

**Color palette** *(adjust to match your CSS variables)*

| Color        | Hex       | Usage                     |
| ------------ | --------- | ------------------------- |
| Salesforce Blue | `#00A1E0` | Primary buttons, links  |
| Dark Navy    | `#032D60` | Headings, footer          |
| Light Blue   | `#EAF5FE` | Section backgrounds       |
| White        | `#FFFFFF` | Cards, page background    |
| Gray         | `#5C5C5C` | Body text                 |

**Typography:** Salesforce Sans–style look using a clean sans-serif stack (e.g. `"Inter", "Segoe UI", Arial, sans-serif`).

**CSS techniques used**

- CSS Variables (`:root`) for colors and spacing
- Flexbox for navigation and alignment
- CSS Grid for card layouts and footer columns
- `position: sticky` for the navbar
- Transitions and `:hover` states for interactivity
- Media queries for responsive behavior

---

## 📱 Responsive Breakpoints

| Device  | Width           |
| ------- | --------------- |
| Mobile  | `max-width: 576px`  |
| Tablet  | `max-width: 992px`  |
| Desktop | `min-width: 993px`  |

---

## 📚 What I Learned

- Building complex layouts with **Flexbox and Grid**
- Structuring a large page with **semantic HTML**
- Writing reusable, maintainable CSS with **variables**
- Creating **responsive designs** with media queries
- Matching a real-world design through careful spacing and typography

---

## 🗺 Future Improvements

- [ ] Add JavaScript for a mobile hamburger menu
- [ ] Add dropdown / mega-menu navigation
- [ ] Add scroll animations
- [ ] Build additional pages (Products, Pricing, Login)
- [ ] Add dark mode
- [ ] Improve accessibility (ARIA labels, keyboard navigation)
- [ ] Optimize images for faster loading

---

## 🤝 Contributing

Suggestions and improvements are welcome!

1. Fork the repository
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Your Name**
GitHub: https://github.com/Ashis2005-prog
LinkedIn: https://www.linkedin.com/in/ashis-pradhan-4baa66229/

⭐ If you found this project helpful, please give it a star!
