# Astro Personal Blog

A clean, minimalist personal blog built with **Astro**, **Tailwind CSS**, and **TypeScript**.

## 🚀 Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed.

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/allababbot/blog.git
    cd blog
    ```

2.  Install dependencies:
    ```bash
    npm install
    ```

3.  Start the development server:
    ```bash
    npm run dev
    ```

## 🛠️ Tech Stack

- **Framework**: [Astro](https://astro.build/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Icons**: [Iconify](https://iconify.design/)

## 📁 Project Structure

- `src/pages/`: Your blog pages and routing.
- `src/components/`: Reusable UI components.
- `src/layouts/`: Global page layouts.
- `src/styles/`: Global CSS styles.
- `public/`: Static assets (favicons, etc.).

## 🔧 Troubleshooting

### Running Astro Commands
If you encounter an error like `'astro' is not recognized`, it means Astro is not installed globally. Use `npx` to run Astro commands locally:

```bash
# Example: Disable the Dev Toolbar
npx astro preferences disable devToolbar
```

### Build the Project
To generate a production build:
```bash
npm run build
```
