# 👩‍🍳 Escuela de Cocina – Responsive Web Design with SASS & Gulp

Escuela de Cocina is a *study project* developed as part of a Udemy course by Juan Pablo De la Torre Valdez. It is a responsive website prototype for a cooking school, built to demonstrate skills in modern front-end development using SASS, CSS Grid, Gulp, and BEM methodology.  
This is not a fully functional application, but a design-focused exercise showcasing layout, component architecture, and task automation.

## 🔗 Live Preview

*Coming soon...

## 📁 Project Structure

├── gulpfile.js  
├── package.json  
├── build/  
│   ├── css/  
│   ├── img/  
├── src/  
│   ├── img/               # Project images (logos, backgrounds, etc.)  
│   ├── scss/              # SCSS styling structure  
│   │   ├── app.scss       # Main SCSS entry  
│   │   ├── base/          # Variables, mixins, global styles  
│   │   ├── ui/            # UI component styles (header, footer, etc.)

## ✨ Features

- Responsive Design using CSS Grid and media queries  
- SASS Architecture following modular structure with BEM naming  
- Task Automation with Gulp for SCSS compilation and image optimization  
- Image Optimization with automatic WebP/AVIF generation  
- Developer-friendly Folder Structure for easy maintenance  

## 🛠️ Technologies Used

- HTML5 – Markup for semantic structure  
- SCSS – CSS preprocessor for modular and scalable styling  
- Gulp – Task runner for automating development workflows  
- CSS Grid – Layout system for responsive design  
- BEM – Naming methodology for clean and maintainable CSS  

## ⚙️ Getting Started

To run the project locally:

1. Clone the repository  
   `git clone <repository-url>`

2. Navigate to the project folder  
   `cd escuela_cocina`

3. Install dependencies  
   `npm install`

4. Start the development server  
   `npm run dev`

This will:
- Compile SCSS to CSS  
- Optimize images  
- Watch for file changes in `src/`

## 🎨 SCSS Architecture

### base/
- _variables.scss: Colors, fonts, breakpoints  
- _mixins.scss: Media queries and reusable logic  
- _globales.scss: Base resets and typography

### ui/
- _header.scss, _footer.scss, _nav.scss: Component-specific styles

## 👩‍💻 Author

Juliana García Corredor  
GitHub: [@JuliGeralDev](https://github.com/JuliGeralDev)
