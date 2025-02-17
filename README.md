3D Portfolio
This is a dynamic 3D portfolio built using Three.js, React Three Fiber, TailwindCSS, and Framer Motion. It showcases interactive 3D models, animations, and responsive design. The portfolio includes email integration, performance optimizations, and scalable code practices for a professional user experience.

Table of Contents
Demo
Features
Installation
Usage
Project Structure
Technologies
License

Features
Interactive 3D models using Three.js and React Three Fiber
Smooth animations with Framer Motion
Responsive design with TailwindCSS
Email integration with EmailJS
Performance optimizations


Installation
Clone the repository:
Navigate to the project directory:
Install the dependencies:

Usage
Start the development server:
Open your browser and navigate to http://localhost:3000.
Project Structure
.
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── postcss.config.js
├── public/
│   ├── desktop_pc/
│   │   ├── license.txt
│   │   └── scene.gltf
│   ├── planet/
│   │   ├── license.txt
│   │   └── scene.gltf
├── README.md
├── src/
│   ├── App.jsx
│   ├── assets/
│   │   ├── company/
│   │   ├── index.js
│   │   └── tech/
│   ├── components/
│   │   ├── components/
│   │   │   ├── About.jsx
│   │   │   ├── canvas/
│   │   │   ├── Contact.jsx
│   │   │   ├── Experience.jsx
│   │   │   ├── Feedbacks.jsx
│   │   │   ├── Hero.jsx
│   │   │   ├── Navbar.jsx
│   │   │   ├── Works.jsx
│   │   ├── hoc/
│   │   │   ├── index.js
│   │   │   └── SectionWrapper.jsx
│   ├── constants/
│   │   └── index.js
│   ├── index.css
│   ├── main.jsx
│   ├── styles.js
│   ├── utils/
│   │   └── motion.js
├── tailwind.config.js
├── vite.config.js
