# test-project

> A Vue.js project

## Build Setup

``` bash


#install Vue-CLI, this is used to bootstrap the skeleton of the project. It is a command line interface
npm install -g vue-cli

#Then it is time to new app using a webapp template
vue init webpack test-project

#Answer questions and cd into the directory where project was created

# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

#This should open up the development server on your selected editor (I am using Visual Studio Code)

#Modifications can be made to the script, css, and html through the template to reflect the Vue components(a self-contained set of HTML, CSS, and JS functionality that is revealed through a unique, custom HTML tag).

#Create a repository on Github for the webapp, do not include any README.me or LICENSE.md files.

#Follow the directions to make a new repository
git init
git add -A
git commit -m 'first commit'
git remote add origin git@github:username/repository-name-from-above.git
git push -u origin master

#Configure WebPack to place our files in a docs/ directory. Edit the config/index.js file
"dist" to "docs"
assetsPublicPath from "/" to ""

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

#Any edits will be done with git push origin, no need for -u anymore
```


For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
