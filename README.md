# Webdev
“This repository contains a basic web application where users can fill out a form with details such as name, registration number, phone number, and email. It also includes installation steps to set up the environment using NVM (Node Version Manager) for running the application.”
# Form_website

A simple React-based registration form using Firebase Realtime Database. Includes input validation and toast notifications for user feedback. Built with HeroUI components and deployed locally.

---

## Features
- **Firebase Integration**: Uses Firebase Realtime Database to store user data.
- **Form Validation**: Ensures users provide valid input before submission.
- **Toast Notifications**: Provides feedback for success or error during form submission.
- **HeroUI Components**: Utilizes HeroUI for styled inputs and buttons.

---

## Technologies Used
- **React** (with Next.js)
- **Firebase** (Realtime Database)
- **Tailwind CSS** (for styling)
- **HeroUI v2** (for components)
- **React Toastify** (for notifications)
- **JavaScript/TypeScript**

---

## How to Use

### Clone the Repository
Clone this project using the following command:
```bash
git clone https://github.com/YOUR_USERNAME/webdev.git
**Install Dependencies**

You can use npm, yarn, or pnpm to install the dependencies. Example using npm:
npm install
Run the Development Server

Start the development server with:
npm run dev

Firebase Setup
	1.	Go to the Firebase Console.
	2.	Create a new project and enable the Realtime Database.
	3.	Download the firebase-config JSON file and place it in your project.
	4.	Update your Firebase initialization file with the new configuration.

⸻

Setup pnpm (Optional)

If you are using pnpm, add the following code to your .npmrc file:
public-hoist-pattern[]=*@heroui/*

After modifying the .npmrc file, run:
pnpm install

Deployment
1.Build the project for production:
npm run build
2.Start the production server:
npm start

Try it Online

You can try this template live on CodeSandbox or deploy it to a service like Vercel or Netlify.

⸻

Contributing

Feel free to fork this repository, open an issue, or submit pull requests for improvements.
