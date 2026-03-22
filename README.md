# AlmhdyCSS 🎨
AlmhdyCSS is a minimal, lightweight, and responsive CSS framework designed to simplify the development of clean, modern web interfaces. With no dependencies and a tiny footprint, it provides essential styling for layouts, typography, buttons, forms, and utilities.

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg) ![Language: HTML](https://img.shields.io/badge/Language-HTML-orange) ![Language: CSS](https://img.shields.io/badge/Language-CSS-yellow)



## 📋 Table of Contents
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)



## 🚀 Features
- **Responsive Grid:** 12-column flexbox-based grid system with mobile-friendly breakpoints.
- **Modern Typography:** Clean, readable base styles.
- **Component Library:** Pre-styled buttons (primary/outline) and form elements.
- **Utility Classes:** Extensive helpers for spacing, flexbox alignment, and text orientation.
- **Dark Mode Ready:** Built-in support for dark themes via simple class toggling on the `<body>`.
- **Zero Dependencies:** Pure CSS—no external libraries required.



## 🛠 Tech Stack
- **HTML5:** Semantic structure.
- **CSS3:** Flexbox layout, media queries, and transition animations.



## 📥 Installation
Since AlmhdyCSS is a static CSS library, simply include the stylesheet in your project:

1. Download the `almhdycss.css` file from the repository.
2. Add the following line inside your HTML `<head>` tag:

```html
<link rel="stylesheet" href="path/to/almhdycss.css">
```



## 💡 Usage



### Grid System
Use the `.container`, `.row`, and `.col` classes to build responsive layouts:

```html
<div class="container">
  <div class="row">
    <div class="col col-6 sm-col-12">Column 1</div>
    <div class="col col-6 sm-col-12">Column 2</div>
  </div>
</div>
```



### Dark Mode
Toggle dark mode dynamically by adding the `dark-mode` class to the `<body>` element:

```javascript
document.body.classList.toggle('dark-mode');
```



## 📂 Project Structure
```text
AlmhdyCSS/
├── index.html       # Documentation and component demo
├── almhdycss.css    # Core framework source code
├── README.md        # Project documentation
└── LICENSE          # MIT License file
```



## 🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request if you find any bugs or have suggestions for improvements.



## 📜 License
This project is licensed under the [MIT License](LICENSE).



## 🔗 Important Links
- **GitHub Repository:** [https://github.com/almhdy24/AlmhdyCSS](https://github.com/almhdy24/AlmhdyCSS)
- **Author:** [Almahdi](https://github.com/almhdy24)

---
*Created by Elmahdi. If you find this project useful, please consider starring it! 🌟*

