<div align="center">

# Indian Heritage

A responsive React showcase of India's history, festivals, cuisine and traditional art forms,
with an interactive feedback form.

[![CI](https://github.com/gitswagata1/indian-heritage-react/actions/workflows/ci.yml/badge.svg)](https://github.com/gitswagata1/indian-heritage-react/actions/workflows/ci.yml)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=white)
![styled-components](https://img.shields.io/badge/styled--components-6-DB7093?logo=styledcomponents&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

## Table of contents

- [Features](#features)
- [Pages](#pages)
- [Getting started](#getting-started)
- [Project structure](#project-structure)
- [Tech stack](#tech-stack)
- [Deployment](#deployment)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)

## Features

- Fully responsive layout for phones, tablets and desktops
- Themed design system with global styles and smooth transitions
- Four content sections: history, festivals, cuisine and art forms
- Feedback form with validation
- Client-side routing with React Router

## Pages

| Route       | Description                                                                |
| ----------- | -------------------------------------------------------------------------- |
| `/`         | Landing page with interactive cards for History, Festivals, Cuisine and Art Forms |
| `/feedback` | Feedback form with validation and a confirmation state                     |

## Getting started

**Prerequisites:** Node.js 18 or newer.

```bash
git clone https://github.com/gitswagata1/indian-heritage-react.git
cd indian-heritage-react
npm install
npm start            # http://localhost:3000
```

| Command         | Description                          |
| --------------- | ------------------------------------ |
| `npm start`     | Start the development server         |
| `npm run build` | Create an optimised production build |
| `npm test`      | Run the test runner                  |

## Project structure

```
indian-heritage-react/
├── public/
│   └── index.html            HTML shell
├── src/
│   ├── components/
│   │   └── Navbar.js         Site navigation
│   ├── pages/
│   │   ├── LandingPage.js    Home page with section cards
│   │   └── FeedbackPage.js   Feedback form
│   ├── styles/
│   │   ├── GlobalStyles.js   Global CSS
│   │   └── theme.js          Colours, fonts and breakpoints
│   ├── App.js                Router and theme provider
│   └── index.js              Application entry point
├── package.json
├── LICENSE
└── README.md
```

## Tech stack

React 18, React Router 6, styled-components 6, Create React App.

## Deployment

```bash
npm run build
```

Deploy the `build/` folder to any static host such as Vercel, Netlify or GitHub Pages.

## Roadmap

See [ROADMAP.md](ROADMAP.md).

## Contributing

Contributions are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) and the
[Code of Conduct](CODE_OF_CONDUCT.md) first.

## License

Released under the [MIT License](LICENSE).

---

Built by **Swagata Banerjee** · [GitHub](https://github.com/gitswagata1)
