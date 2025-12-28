# web-dev-assignment-2
> Student Name: Raymond Brennan\
> Student Number: 20119115\
> Date: 28/12/2025
> 
> Assignment 2 - Web Development - Module Semester 1 2025
 
# RaysWhetherWeather
This project is a weather webpage which utilies the Bulma css framework, Eleventy(11ty), Netlify and versioning via GitHub.\
The Github repo for this webpage can be found at https://github.com/ERayBre/RaysWhetherWeather
 
## Reflection
>The project is ran and tested localy using 11ty serve and pushed to GitHub via Visual Studio, then pulled by Netlify to host the webpage.\
>Started by creating a local folder as a repository.\
>Linked this with vsCode and then Github.\
>Insalled NPN and 11ty and started 11ty serving from this location.\
>Linked this local repo to a new GitHub repo to allow for push etc.\
>created a new project in Netlify and linked it with Github, specifying the site directory as the one to publish.\
>Templating was achieved by way of 11ty nunjucks, this also allowed for generation of data from json files.
> 
>Limitations were hit during deployment of the project as Netlify had credits limits on the deployment of the project, I paused the deployment opting for manual push of the deployment once the credit limit was alomost reached.
>
>I ran into time constraints doing this assignent as i was sick for a number of weeks on the run up to christmas.
>
>All initial commits were by way of testing different functionality and layouts etc of the site, then on 28/12/2025 the project was taken back to scratch, then each release was commited via  branch on GitHub.
  
  
# How to run 
### Local
Download a copy of the .zip file.\
Extract the .zip file to expose contents on local machine.\
install 11ty, cd to the extracted directory, run the eleventy -serve command from this location, access at http://localhost:8080 
### Online
This webpage is published and hosted at Netlify and can be found at this link https://rayswhetherweather.netlify.app/ 

# Project Overview
This project simulates the POC and release schedule for a new weather app:\
It has encorporated the below
Usage of eleventy to develope
Usage of templates and layout
Reusable components such as header, footer, nav, city-focus-content, forecast-table and location-card
Independent learning about eleventy and nunjucks to allow for use of data from json files and using for loops and conditional statements\
The project structure is clearly layed out with the main index page at root and other pages in the pages and cities folders, images in the images folder and data in the \_data folder 
Repitition of code is greatly reduced using the templates and components to reduce code usage and make editing easier.
This readme.md file has been created to give an excellent overview of the overall assignment.
Link to GitHib repo https://github.com/ERayBre/RaysWhetherWeather
Full commit history on Github visible, multiple branches also for hte various deplyments.
Implemented Bulma breadcrumb component, also templated this.
Performed a manual upload to netlify when credits became limited.
Github push deployment to Netlify .
Released, POC-1
Released, POC-2
Released, POC-3
Released, Release-1
Released, Release-2
Released, Release-3

# Credits
Author: Raymond Brennan\
Course: SETU — WEB DEV - Assignment 2\
Sources: Bulma, Eleventy, UnSplash.com, Freepik.com, Eleventy and Bulma\
  \
*weather images downloaded from unsplash,created by @abid_ahmad_shah*\
https://unsplash.com/@abid_ahmad_shah
  \
*wind direction images sourced from freepik.com*\
https://www.freepik.com/icon
  \
*researched pulling data from json files here*\
https://benmyers.dev/blog/eleventy-data-cascade/
  \
*researched eleventy functionality here*\
https://www.11ty.dev/docs/data-configuration/
  \
*researched Bulma components, elements and layouts here*\
https://bulma.io/documentation/components

# License
This project is provided for educational, academic, and portfolio use. None of the media or visual content is intended for distribution beyond its use within this project.
