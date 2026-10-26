# NPTEL IoT — Study & Exam Preparation Dashboard
# Developer - Vineet Mishra
An interactive study dashboard for **NPTEL Introduction to Internet of Things (IoT)**, designed to help learners explore assignment questions, review answers, and prepare for exams in one place.

https://nptel-iot-vineet.vercel.app/

## Overview

NPTEL IoT Study Dashboard brings assignment resources and practice questions together in a clean, searchable interface. Learners can browse questions, filter content, review answers, and track their practice activity.

## Features

- **Interactive Question Bank** — Browse IoT questions and their corresponding answers.
- **Week-Based Filtering** — Explore questions organized by course week, where supported by the available data.
- **Search and Filters** — Find relevant questions using the available filtering options.
- **Assignment Resources** — Access included PDF assignment materials.
- **Practice Analytics** — View available statistics about questions and practice activity.
- **Responsive Interface** — Use the dashboard on desktop and mobile browsers.

## Tech Stack

| Technology | Purpose |
|---|---|
| React | User interface |
| TypeScript | Type-safe application code |
| Vite | Development server and production build |
| Tailwind CSS | Styling and responsive layouts |
| JSON | Question-bank data |

## Getting Started

### Prerequisites

Install the following before running the project:

- [Node.js](https://nodejs.org/) — preferably an active LTS release
- npm, included with Node.js
- [Git](https://git-scm.com/) (optional, for cloning the repository)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/VINEET-MISHRA-20/nptel-iot-personal.git
   ```

2. Navigate to the project directory:

   ```bash
   cd nptel-iot-personal
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open the local URL printed in your terminal, usually:

   ```text
   http://localhost:5173/
   ```

### Production Build

To create an optimized production build, run:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

The generated website files are placed in the `dist` directory.

## Project Structure

```text
nptel-iot-personal/
├── public/
│   └── assignments/       # Included assignment PDF resources
├── src/
│   ├── assets/            # Application assets
│   ├── components/        # Reusable UI components
│   ├── data/              # Question-bank data and utilities
│   ├── types/             # TypeScript type definitions
│   ├── utils/             # Application utility functions
│   ├── App.tsx            # Main application component
│   ├── index.css          # Global styles
│   └── main.tsx           # Application entry point
├── index.html
├── package.json
├── tailwind.config.js
├── tsconfig.json
├── vercel.json
└── vite.config.ts
```

## Deployment

This project can be deployed to [Vercel](https://vercel.com/).

1. Import the GitHub repository into Vercel.
2. Select **Vite** as the framework preset if it is not detected automatically.
3. Set the build command to `npm run build`.
4. Set the output directory to `dist`.
5. Deploy the project and use the generated public URL to access the website.

## Contributing

Contributions and improvements are welcome.

1. Fork the repository.
2. Create a branch for your changes.
3. Make and test your updates.
4. Submit a pull request describing your changes.

## Disclaimer

This is an independent educational study project and is not an official NPTEL website or service. Course materials and assignment documents are included for study and reference purposes. Please respect the original content owners' rights and applicable distribution policies.

## License

No license has been specified yet. Unless a license is added to this repository, reuse and redistribution are subject to applicable copyright laws.
