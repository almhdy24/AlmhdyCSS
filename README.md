# AlmhdyCSS

AlmhdyCSS is a minimal and responsive CSS framework created by Almahdi ([github.com/almhdy24](https://github.com/almhdy24)).

It is designed to be simple, lightweight, and easy to use. You can use it to quickly build layouts, buttons, forms, and more.

---

## Features

- Responsive 12-column grid system
- Basic typography and styles
- Buttons (primary and outline)
- Forms with focus states
- Utility classes for spacing, flex, and text alignment
- Dark mode support
- Mobile-friendly responsive helpers

---

## Demo

Open `index.html` in your browser to see a live demo.

---

## How to Use

1. **Include the CSS file in your project:**

``` html
<link rel="stylesheet" href="css/almhdycss.css">
```

2. **Start using containers, rows, columns, buttons, forms, and utilities.**

---

## Example

```html
<div class="container">
  <h1 class="text-center">Welcome to AlmhdyCSS</h1>

  <div class="row">
    <div class="col col-6 sm-col-12">
      <p>This is a simple column layout.</p>
      <button class="btn btn-primary">Primary</button>
      <button class="btn btn-outline">Outline</button>
    </div>
    <div class="col col-6 sm-col-12">
      <form>
        <input type="text" placeholder="Your name">
        <input type="email" placeholder="Your email">
        <button class="btn btn-primary">Submit</button>
      </form>
    </div>
  </div>

  <div class="text-center mt-3">
    <button onclick="document.body.classList.toggle('dark-mode')" class="btn btn-outline">
      Toggle Dark Mode
    </button>
  </div>
</div>
```

---

## Dark Mode

To use dark mode, add the `dark-mode` class to the `<body>` tag:

```html
<body class="dark-mode">
```

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Created by Almahdi ([github.com/almhdy24](https://github.com/almhdy24))
