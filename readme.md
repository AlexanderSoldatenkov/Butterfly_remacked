https://www.figma.com/file/LJ9l5lhvXDJNPmmy3NPoxb/astera
Features 🚀
1- Compatible with All Static Site like Bootstrap Template

2- Out of the box Uglifying/ Minifying of CSS, HTML, JS

3- SCSS Support

4- ES6+ Support

5- Hot Reloading

6- Runs on a local server

7- Auto prefixing - Support IE10 and last 4 versions of all browsers

How to use 🧐
Make sure you have node installed. If not, I recommend installing via nvm(Node Version Manager)

1- Put your code in src folder

There are sample files already present (feel free to delete them and add yours) to give you an idea about the architecture. You only to care about just one file i.e, index.html. You need to put at the src (src/index.html) folder level.

2- Install necessary packages - npm i or yarn

3- Run project (Development) - npm run start or yarn run start

4- Build(If you ready to deploy) - npm run build or yarn run build

Commands available 🛠:
There are only three commands

1- npm run start - It starts a local server so that you can work on your project without any hustle. Enjoy Hot reloading (Live Updates in browser) and SASS/SCSS support.

2- npm run build - When you are ready to deploy. You can build your project and deploy the dist folder made by this command.

3- npm run reset - It just cleans dist (output folder) and .cache folder. Run this command before starting work on a new project. Parcel caches some files for the faster builds so its good to remove them before switching project.

Advanced 👽
1- .browserslistrc - Default configuration targets IE-10 as well. If you don't want to support IE then you can delete configuration from this. Read more here

2- .postcssrc - This file is responsible to manage PostCSS plugin. This file can configure CSS plugins like AutoPrefixer, CSS Modules etc. Read more here

3- Everything- This project has been built on top of Parcel. You can configure completely as you want.

Creator 😈
Its Naman Gupta, FullStack Product Developer and FOSS lover.

Find me on Twitter, Linkedin, Dev.to and check out my Portfolio#   B u t t e r f l y _ r e m a c k e d  
 