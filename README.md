# Welcome to my Portfolio! 
## Learn all about me and my journey as a developer.
#### This is a web application designed using HTML, CSS, JS, and Bulma. Employers can use this page to learn about me, the projects I have worked on, view my various social media accounts, and download my current resume. 

## Link to Deployed Site

[Portfolio](https://beardomattix.github.io/Portfolio/)

## Table of Contents
  * [Motivation and Technologies](#motivation)
  * [Functionality](#functionality)
  * [File Architecture](#file-architecture)
  * [Challenges](#challenges)
  * [Usage](#usage)

## Motivation

For this updated version of my portfolio I wanted a clean design that highlighted my progress as a new developer. I used the Bulma CSS framework in conjunction with vanilla CSS to create the design of the site, and added some JS functionality to the menu that appears when the site is viewed on mobile devices. I also added a link to my resume that employers can click to download a copy of my resume. 

#### Technologies
* HTML
* CSS 
* JavaScript
* Bulma

## Functionality

![landing-demo](https://user-images.githubusercontent.com/82903201/126918471-c28a7faf-e0cb-42d7-85e3-731ce9bdb95e.gif)


#### The demo shows the main functions of Skillet and Shaker recipe finder:
* The landing page introduces the site, has buttons to navigate to the Food and Drink search pages, and includes a "Featured Recipes" section for users who prefer not to spend time searching.
* Users click on either "Search Food" or "Drink Search" in the navbar which leads them to a page for finding food recipes or drink recipes by certain search parameters. 
* On the "Search Food" page, the user is presented with a search form with the parameters of ingredient, diet, and cooktime.  
* The user must enter an ingredient, but can select a preferred diet type and cooktime from dropdown menus.
* Recipes are shown in a modal with multiple cards displaying a picture of the dish, the name of the dish, a link to the recipe, and a "save recipe" button. 
* If the user hits the save recipe button, the recipe card is shown at the bottom of the page along with any other previously saved recipes. These saved items are stored in local storage.
* The favorites sections have a "Clear Favorites" button for users to reset their favorites.
* The "Search Drinks" page functions in the same fashion as the "Search Food" page, except that the search parameters are  ingredient, cocktail name, and a button to show a random cocktail recipe.

## File Architecture
```
├── assets
│   ├── images
│   │   ├── Christopher\ Mattix\ Resume.pdf
│   │   ├── Head_Shot_resized2.jpg
│   │   ├── Montana.jpg
│   │   ├── Weather-DEMO.gif
│   │   ├── blue-shirt.jpg
│   │   ├── code-quiz-demo.gif
│   │   ├── landing-demo.gif
│   │   └── resume-preview.png
│   ├── scripts
│   │   └── script.js
│   └── styles
│       └── style.css
└── index.html
```
## Challenges
The main challenge I faced with this project was deigning a mobile-first site. I wanted my portfilio to look and function well on mobile devices, and spent a lot of time making sure the site functioned on smaller screens. 

## Usage
* Employers cab quickly see my projects and resume.  
* Employers can get a sense of my visual design skills. 
* Employers can use the "Contact Me" section to see my social media accounts, ask questions, and email me. 

## Future Development
* Add functionality to send an email whenever a user asks a question in the Contact Me section. 
* Include animations to make the projects section look better. 