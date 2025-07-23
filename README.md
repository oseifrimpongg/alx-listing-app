# ALX Listing App

A simplified Airbnb clone listing page built with **Next.js**, **TypeScript**, and **Tailwind CSS**. This project is part of the ALX Frontend curriculum and serves as the foundation for building a scalable, component-based web application.

---

## 📁 Project Structure

The project uses the **Pages Router** and does not include a `src/` directory to align with project requirements. Below is a breakdown of the key directories and files:

### `/pages/`

Contains the application routes. The main entry point is `index.tsx`.

### `/components/common/`

Reusable UI components:

- `Card.tsx`: Displays property information.
- `Button.tsx`: Reusable button component for user interactions.

### `/interfaces/`

Defines TypeScript interfaces used throughout the app:

- `CardProps`, `ButtonProps`, etc.

### `/constants/`

Stores constants such as static texts, config values, and reusable data.

### `/public/assets/`

Houses images and SVGs used in the app. Assets are organized for easy access.

---

## 🛠️ Technologies Used

- **Next.js** (with Pages Router)
- **TypeScript**
- **Tailwind CSS**
- **ESLint**

---

## 🚀 Getting Started

To run the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/alx-listing-app.git
   cd alx-listing-app
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the development server:

   ```bash
   npm run dev
   ```

4. Open your browser and go to:

   ```text
   http://localhost:3000
   ```

---

## ✅ Current Status

- ✅ Project scaffolded
- ✅ Folder structure set up
- ✅ Tailwind CSS configured
- ✅ TypeScript interfaces added (placeholder)
- ✅ Assets folder created
- ✅ Ready for component development

---

## 📌 Next Steps

- Implement real data and dynamic UI using the `Card` and `Button` components.
- Connect to backend services or mock APIs.
- Build the listing page layout and interactions.

---

## 💡 Goal

This project aims to mimic the core features of an Airbnb-style listing platform, emphasizing reusable components, clean architecture, and responsive design.
