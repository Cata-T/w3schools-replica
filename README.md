# Pug starter
## Table of contents
* [YouTube video tutorials](#youtube-video-tutorials)
* [Live projects built with pug-starter](#live-projects-built-with-pug-starter)
* [Prerequisites](#prerequisites)
* [Installation](#installation)
* [Usage](#usage)
* [Style](#style)

## **baseUrl** 

add ***modularCss*** support. When enabled in the config of `package.json` it will convert all SCSS/SASS files to its correspondent CSS path.

add ***baseurl*** support which can be configured for GitHub.io and custom domain. Check *package.json* config section for
* *deployToGithubIo* - (true|false) by default it is set to *true* and will affect the value of *baseUrl* when you want to deploy to GitHub.io; You want to set it to *false* if you want to use *customUrl* as the value of *baseUrl*
* *customUrl* - if you want baseUrl to have a value like http://my-project.github.io or any other one;
* *githubUrl* - if you want baseUrl to have a value like http://github.com/CatalinaTeguiani/w3schools-replica.git or any other one;

In the end you can use *baseUrl* to prefix your paths like:
```
link(rel="stylesheet", href=`${baseUrl}/style.css`)
```
