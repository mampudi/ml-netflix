# ml-netflix

1. Create a react app in the current directory
ml-netflix % yarn create react-app .

2. Add tailwind as a dev dependency to your project
yarn ad  -D tailwindcss postcss autoprefixer

3. Init command to generate both tailwind.config.js and postcss.config.js.
npx tailwindcss init -p

4. Configure your template paths. Add the paths to all of your template files in your tailwind.config.js file.
"./src/**/*.{js,jsx,ts,tsx}",

5. Add the Tailwind directives to your CSS (index.css)
6. Add some dependencies that are needed
yarn add axios react-router-dom firebase
