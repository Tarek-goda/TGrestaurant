# TG Restaurant

[![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Deployments](https://img.shields.io/badge/Deployments-Vercel-000000?logo=vercel&logoColor=white)](https://vercel.com/)

A responsive, multi-page restaurant website built with HTML, CSS, and JavaScript.

**Live demo:** [tg-restaurant.vercel.app](https://tg-restaurant.vercel.app/index.html)

## Features

- Responsive navigation between Home, Menu, About Us, Contact, and Cart.
- Clean, user-friendly design for a restaurant website.
- Static site deployment on Vercel, with automatic deployments from GitHub.

## Project Structure

```text
src/
├── index.html
├── menu.html
├── menu.css
├── menu.js
├── style.css
├── Contact/
│   ├── Contact.html
│   └── Contact.css
├── about/
│   ├── aboutus.html
│   └── aboutus.css
├── cart/
│   ├── Cart.html
│   ├── Cart.css
│   └── Cart.js
└── img/                 # Images and shared visual assets
```

## Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/Tarek-goda/Mc-restaurant.git
   ```

2. Open `src/index.html` in a browser, or open the repository in VS Code and launch `src/index.html` with the Live Server extension.

## Deployment

The site is deployed on [Vercel](https://vercel.com/) and configured to publish the `src/` directory. GitHub deployments are automated when changes are pushed to the connected repository.
