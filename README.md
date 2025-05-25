The **ALX Listing App** is a front-end web application inspired by Airbnb’s listing page. It is built using **Next.js 13+**, **TypeScript**, **Tailwind CSS**, and **ESLint** as part of the ALX Pro Development program.

The goal of this project is to build a responsive and scalable property listing page that demonstrates best practices in modern front-end development, including component reusability, clean code architecture, and type safety.

---

## 📁 Project Structure

Here's a breakdown of the key folders used in this project:

- **`components/`**  
  Contains all reusable UI components.  
  Example: `Card.tsx` and `Button.tsx` under `components/common/` for displaying property cards and reusable buttons.

- **`interfaces/`**  
  Houses TypeScript interface definitions used throughout the app to enforce type safety.  
  Example: `CardProps` and `ButtonProps` used to define props for components.

- **`constants/`**  
  Stores global constants such as API URLs, configuration values, and reusable static text.

- **`public/assets/`**  
  Contains static assets like images and SVGs used across the app.  
  Example: Placeholder property images, icons, and logos.

---

## 🚀 How to Run the Project Locally

Follow these steps to set up and run the project on your machine:

### 1. Clone the Repository

bash :
git git clone https://github.com/your-username/alx-listing-app.git
cd alx-listing-app

### 2. Install Dependencies

npm install

### 3. Start the Development Server

npm run dev

Open your browser and go to:

http://localhost:3000

You should now see the ALX Listing App running locally.

## 📄 Notes

Ensure you have Node.js version 16 or higher installed.

This project uses the Pages Router (not the App Router).

Tailwind CSS is configured with minimal styling to allow easy customization. 
