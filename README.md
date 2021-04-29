# important-tailwind-commands
A small collection of important Tailwind commands and tools.

## Install Tailwind CSS
1. Go to the folder where Tailwind should be installed / used.
2. Create a`.gitignore` file with the content:
   `node_modules/`
    
3. `npm init -y` -> generates the `package.json`
4. `npm install tailwind postcss postcss-cli autoprefixer` -> installed tailwind and postcss
5. `npm tailwindcss init -p` -> generates the `tailwind.config.js` , `-p` generate the `postcss.config.js`
6. The following order structure must be created:
    * The file `tailwind.css`
    * The folder `dist/css` -> the `dist` folder contains the code to publish.
    * The file `styles.css` in the`dist/css` folder.
    * Create an `index.html` in the `dist` folder.

### Node.js
Node.js is indispensable for working with a tailwind.

### IDE
Visual Studio Code usefull extensions.
* Headwind - An opinionated class sorter for Tailwind CSS
* Tailwind CSS IntelliSense - Intelligent Tailwind CSS tooling for VS Code
* Alpine.js IntelliSense - Simple IntelliSense & Snippets for Alpine.js framework.
