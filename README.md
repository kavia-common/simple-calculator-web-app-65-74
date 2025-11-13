# Simple Calculator Web App

## Overview

This project is a **Simple Calculator Web App** designed to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The application features a clean, modern, and responsive UI that makes performing calculations straightforward for users on any device.

Calculators are essential tools that aid in solving arithmetic operations quickly and accurately, making this web app suitable for anyone needing quick calculations in a browser without additional installations.

---

## History of Calculators

- **Abacus (c. 2000 BCE):** One of the earliest known calculating devices, used in ancient Mesopotamia and later throughout Asia and Europe for basic arithmetic.
- **Pascaline (1642):** Invented by Blaise Pascal, the Pascaline was a mechanical calculator capable of performing addition and subtraction using gears and dials.
- **Leibniz Wheel (Stepped Reckoner, 1672):** Developed by Gottfried Wilhelm Leibniz, this improved mechanism enabled multiplication and division as well.
- **Arithmometer (1820):** The first commercially successful mechanical calculator, invented by Charles Xavier Thomas de Colmar, brought calculators into popular business use.
- **Mechanical Desktop Calculators (Late 19th–Mid 20th Century):** Various mechanical calculators—like the Comptometer and Monroe—became standard office equipment.
- **Electronic Calculators (1960s):** Advancements in transistor and integrated circuit technology enabled the first electronic calculators, which were initially desk-sized.
- **Handheld Calculators (1970s):** Devices like the HP-35 (1972) and TI-30 (1976) brought affordable, portable calculators to the public.
- **Software & Digital Calculators (1980s–present):** With the rise of personal computers, smartphones, and web apps, software calculators became ubiquitous and multi-functional, accessible to everyone.

---

## Features

- Basic arithmetic operations (addition, subtraction, multiplication, division)
- Responsive and clean user interface
- Keyboard input support (enter numbers and operations using keyboard)
- Clear/Reset function to reset the calculation
- Division by zero handled gracefully (displays error or warning)
- Styled according to a light theme with #3b82f6 (primary) and #06b6d4 (secondary accent) colors

---

## Getting Started

> **Note:** If you are using a cloud preview or online code preview environment, preview/server startup is managed via platform-provided controls.

To run the project locally (requires Node.js):

1. **Install dependencies**  
   ```
   npm install
   ```
2. **Start the app**  
   ```
   npm start
   ```
   The app will be available at [http://localhost:3000](http://localhost:3000) by default.

---

## Usage

- **Entering Numbers:** Click the number buttons or use your keyboard to enter numbers.
- **Performing Operations:** Click the operation buttons (`+`, `-`, `×`, `÷`) or use the corresponding keyboard keys for arithmetic operations.
- **Equals:** Press `=` or the Enter key to compute the result of the current operation.
- **Clear:** Press the clear (`C`/`AC`) button or hit the `Escape` key to reset the display to zero.

---

## Tech Stack

- **Frontend Framework:** [React](https://react.dev/)
- **Platform:** Web
- **Styling:** CSS-in-JS or CSS modules, following a light theme style guide
  - Primary color: `#3b82f6`
  - Accent color: `#06b6d4`
  - Clean, modern look, as per provided style guide

---

## Environment Variables

This app is a frontend-only calculator and does not require backend integration, so all environment variables are **optional and may be unused** unless custom features or deployment needs arise.

List of available (but likely unused for basic operation) environment variables from `.env`:

- `REACT_APP_API_BASE` - Base URL for API calls (if needed for future enhancements)
- `REACT_APP_BACKEND_URL` - Backend service URL
- `REACT_APP_FRONTEND_URL` - Frontend URL
- `REACT_APP_WS_URL` - WebSocket URL
- `REACT_APP_NODE_ENV` - Node environment
- `REACT_APP_NEXT_TELEMETRY_DISABLED` - Next.js telemetry toggle
- `REACT_APP_ENABLE_SOURCE_MAPS` - Source map generation toggle
- `REACT_APP_PORT` - App port override
- `REACT_APP_TRUST_PROXY` - Trust proxy configuration
- `REACT_APP_LOG_LEVEL` - Logging verbosity
- `REACT_APP_HEALTHCHECK_PATH` - Health check endpoint path
- `REACT_APP_FEATURE_FLAGS` - Feature flag configuration
- `REACT_APP_EXPERIMENTS_ENABLED` - Toggle for experimental features
- `REACT_APP_string` - Placeholder/example variable

> These variables are generally not required for the core calculator functionality.

---

## Folder Structure

_Generic outline for the `calculator_frontend` project:_

```
calculator_frontend/
  ├── public/              # Static assets (icons, index.html)
  ├── src/                 # React source code (components, utils, styles)
  │   ├── components/      # Calculator button/display components
  │   └── App.js           # Entry point
  ├── package.json         # Project metadata and scripts
  └── ...                  # Other configuration files (e.g., .gitignore)
```
_Folder details may vary. Please refer to the project for up-to-date structure._

---

## Accessibility & Limitations

- **Division by zero:** The calculator displays an error or warning (usually "Error" or "Infinity") if division by zero is attempted.
- **Floating-point precision:** Calculations may suffer from standard floating-point rounding errors, as is typical for JavaScript calculators (e.g., `0.1 + 0.2 ≈ 0.30000000000000004`).

---

## License

MIT License  
*If your project needs a specific license, please update this section.*  
*(TODO: Review and update license as required)*

---

## Licenses

This project does not yet have a definitive license selection.

> **TODO:** Please select and apply a license for this project (e.g., MIT, Apache-2.0, GPL-3.0, etc.).  
> See below for common options:

### MIT License

A short and permissive open source license, allowing commercial use, modification, distribution, and private use with minimal requirements regarding attribution and inclusion of license notice.  
- [MIT License Full Text](https://opensource.org/licenses/MIT)

### Apache License 2.0

A permissive open source license with explicit terms regarding sublicensing, patent rights, and contribution. It allows commercial use, modification, distribution, and private use, but with certain legal requirements (notably, patent grant and a NOTICE file for significant changes).
- [Apache License 2.0 Full Text](https://www.apache.org/licenses/LICENSE-2.0)

### GNU General Public License v3.0 (GPL-3.0)

A strong copyleft open source license that guarantees end users the freedom to use, modify, and distribute the software and its derivative works. Any derivative or combined work must also be distributed under the GPL-3.0, ensuring continued openness. Imposes certain obligations on distribution, including source code disclosure and preservation of license notices.
- [GPL-3.0 License Full Text](https://www.gnu.org/licenses/gpl-3.0.html)

#### Key Differences: MIT vs Apache-2.0 vs GPL-3.0

- **MIT**: Highly permissive, minimal requirements—just attribution and original license inclusion. Allows proprietary derivative works with no copyleft requirements. No explicit patent protection.
- **Apache-2.0**: Permissive license with explicit patent grant. Requires preservation of license, attribution, and NOTICE file if changes are made. Allows proprietary derivatives but offers more legal clarity and patent safety than MIT.
- **GPL-3.0**: Strong copyleft license—any distribution of derivative works must also be under GPL-3.0. Requires source code disclosure for derivatives and combined works. Prohibits imposing further restrictions on recipients. All contributors grant a patent license. Not compatible for inclusion in proprietary/commercial closed-source products.

---
