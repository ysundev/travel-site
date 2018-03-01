##…or create a new repository on the command line
- echo "# travel-site" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git remote add origin git@github.com:ysundev/travel-site.git
- git push -u origin master

##…or push an existing repository from the command line
- git remote add origin git@github.com:ysundev/travel-site.git
- git push -u origin master

## Setup IDE
### Install Note.js
- Install jQuery and normalize.css

### Install Gulp globally

	> sudo npm install gulp-cli --global

### Install Gulp locall
   > cd treval-site
   
   > npm install gulp --save-dev
   
### Install Gulp-Watch
> npm install gulp-watch --save-dev

### Install Gulp-PostCSS
> npm install gulp-postcss --save-dev
> npm install autoprefixer --save-dev
> npm install postcss-simple-vars --save-dev
> npm install postcss-nested --save-dev
> npm install postcss-import --save-dev
> npm install browser-sync --save-dev