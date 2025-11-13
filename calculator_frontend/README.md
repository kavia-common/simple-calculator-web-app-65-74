# Simple Calculator Web App (Frontend)

A clean, modern web calculator built with React, enabling users to perform basic arithmetic operations quickly and easily via a responsive UI.

---

## 🚀 Live Preview

> **Note:** In this environment, the app runs on port **3000**. Preview and server startup are managed through the platform’s preview system (user controls start/stop from the dashboard).  
> **Do not use local `npm start` unless running outside this hosted preview system.**

---

## ✨ Features

- Addition, subtraction, multiplication, and division
- Clear/reset input
- Responsive UI: works on desktop and mobile devices
- Minimalist design with Ocean Professional theme
- Keyboard and mouse support (future improvement)
- Smooth transitions and accent highlights
  
---

## 🛠️ Tech Stack

- **Frontend:** [React](https://react.dev/)
- **Platform:** Web
- **Styling:** Modern Ocean Professional theme  
  - Primary: `#2563EB` (blue)  
  - Secondary: `#F59E0B` (amber)
  - Subtle gradients, minimalist layout, smooth transitions

---

## ⚡ Getting Started

### Prerequisites

- [Node.js LTS](https://nodejs.org/) recommended (v16+)

### Setup Instructions

1. **Install dependencies**
   ```
   npm install
   ```
2. **Run locally**
   ```
   npm start
   ```
   - Runs on [http://localhost:3000](http://localhost:3000)
   - **Note:** In cloud/online preview, use dashboard controls to start/stop, not CLI commands.

---

## 📂 Project Structure

```
calculator_frontend/
  ├── public/            # Static assets (icons, index.html)
  ├── src/               # Source code (React components, styles, utils)
  │   ├── components/    # Calculator display and buttons
  │   └── App.js         # Entry point
  ├── package.json       # Project scripts and dependencies
  └── ...                # Other config files
```

---

## 📜 Available Scripts

- `npm install` - Install dependencies
- `npm start` - Start development server (development only)
- `npm run build` - Build app for production
- `npm test` - Run test suite (if applicable)

---

## ⚙️ Environment Variables

All variables below are **optional**. _Core calculator features do not require any environment variables; these are reserved for advanced/future use._

| Variable                           | Description                                   | Default              |
|-------------------------------------|-----------------------------------------------|----------------------|
| REACT_APP_API_BASE                  | API base URL                                  | –                    |
| REACT_APP_BACKEND_URL               | Backend endpoint URL                          | –                    |
| REACT_APP_FRONTEND_URL              | Frontend URL                                  | –                    |
| REACT_APP_WS_URL                    | WebSocket URL                                 | –                    |
| REACT_APP_NODE_ENV                  | Node environment                              | –                    |
| REACT_APP_NEXT_TELEMETRY_DISABLED   | Next.js telemetry disabled                    | –                    |
| REACT_APP_ENABLE_SOURCE_MAPS        | Source maps enabled                           | –                    |
| REACT_APP_PORT                      | App port (default: 3000 if unset)             | 3000                 |
| REACT_APP_TRUST_PROXY               | Trust proxy configuration                     | –                    |
| REACT_APP_LOG_LEVEL                 | Logging verbosity                             | –                    |
| REACT_APP_HEALTHCHECK_PATH          | Health check endpoint path                    | –                    |
| REACT_APP_FEATURE_FLAGS             | Feature flags configuration                   | –                    |
| REACT_APP_EXPERIMENTS_ENABLED       | Enable experiments                            | –                    |
| REACT_APP_string                    | Example placeholder                           | –                    |
| REACT_APP_HOST                      | Host override                                 | –                    |

> _These are defined in `.env` and may be required for backend-integrated or customized deployments only._

---

## 🎨 Styling & Theme

- **Theme**: Ocean Professional — blue (#2563EB) and amber (#F59E0B) accents
- Modern, minimalist design with subtle shadows and rounded corners
- Responsive and touch-friendly
- Refer to [style guide](../assets/style_guide.md) for visual details.

---

## ♿ Accessibility & Responsiveness

- UI adapts to desktop and mobile screens
- Button labels are clear and high-contrast
- ARIA roles/labels should be used for accessibility
- Designed for keyboard operability (full support is a future improvement)

---

## 🪄 Future Improvements

- Full keyboard input (numerals, operators)
- Memory/save/recall functions
- Calculation history
- Progressive Web App (PWA) features
- Theming toggle (dark mode)

---

## 🤝 Contributions

Pull requests welcome! Please keep code readable and follow the minimalist Ocean Professional style.  
For larger features or ideas, open an issue to discuss first.

---

## 📄 License

<!-- Replace with real license before production use -->
[MIT](https://opensource.org/licenses/MIT) (suggested)  
_See main README or project owner for license questions_

---
