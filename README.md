![Sign it](/assets/images/logo-blue.png)

# FoodStuff

[View the live project here](https://jade-quinn.github.io/sign/)

FoodStuff aims to build a community around real, fast and delicious food that just so happens to be good for you!

## Table of Contents:

- [The Strategy Plane](#the-strategy-plane)
- [The Scope Plane](#the-scope-plane)
- [The Structure Plane](#the-structure-plane)
- [The Skeleton Plane](#the-skeleton-plane)
- [The Surface Plane](#the-surface-plane)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
- [Deployment](#deployment)
- [Credits](#credits)

## UX

### The Strategy Plane

**Why are we so special?**

FoodStuff allows users to store and easily access cooking recipes. Users are encourged to add recipes that are simple to make, with easy to access ingredients. FoodStuff is target towards young adults who find their busy lives can interfere with the quality of food they eat. The site aims to be visual apealing, user freindy with a focus on easilty prepared nutritious meals.

**Who else is building this?**

There is a vast number of recipe sites online at present. These include:
- [bbcgoodfood.com](https://www.bbcgoodfood.com/recipes/collection/easy-recipes)
- [allrecipes.com](https://www.allrecipes.com/recipes/)
- [bordbia.ie](https://www.bordbia.ie/recipes/)
- [taste.com](https://www.taste.com.au/recipes/collections)
- [simplyrecipes.com](https://www.simplyrecipes.com)

Each of these site has a slightly different layout and varies in features they offer.

**What are the tech considerations?**

As this application is trageted towards a tech savy audience, there should be a mobile first approach to design and functionality. This product is for general consumers. As this is a B2C product, it should focus heavily on styling and emotive design. The target user is short on time so navigation should be intuitive and layout should quickly and clearly communicate recipie steps and ingredients.

To determine the objectives and user needs for this release I have created the table below. 
Each opportunity/problem is rated on a scale of 1 - 5 in two dimensions; Importance and Feasibility.

Opportunity/Problem | Importance | Feasibility
------------ | ------------- | -------------
Allow users to easily access cooking recipies | 5 | 5
Include fields such as ingredients, preparation steps, required tools, cuisine, etc | 5 | 5
Create form(s) to allow users to add new recipes to the site, edit them and delete them | 4 | 3
Provide results in a manner that is visually appealing and user friendly | 3 | 3
Include a section to recomend cook books | 5 | 5
Provide statistics about recipes | 5 | 5

**User Stories**

- As a first time user, I want to browse through recipes for inspiration on what to cook.
- As a first time user, I want to search by category.
- As a first time user, I want to search a specific food type.
- As a first time user, I want to quickly read through a list of ingredients.
- As a returning user, I want to quickly find a recipie I have used before.
- As a returning user, I want to login in as a user to the site to add my own recipie.
- As a returning user, I want to update/delete a recipe I have added.
- As a returning user, I want to know that my changes have been saved successfully.

- As a site owner, I want to build a community around simple, nutritious meals.
- As a site owner, I want to be notified when a recipie has been added so I can review the content.


### The Scope Plane

#### Feature Scope

To establish the feature scope for this project I am using the agile methodology, I have made a list of all possible features and given each one a difficulty rating between 1 and 3.
Each release will allow for a maximum of 12 points. The table below will be used to determine which features to prioritise and which to schedule for a later release.

Feature | Rating
------------ | -------------
Logo that links to the home page so users can orientate themselves easily | 1
Clear, consistent hamburger navigation on each page | 2
Messaging that clearly communicates the focus of the site  | 1
Responsive design | 1
Load jacascript after DOM content is loaded | 1

Given limited resources, the features that offer the most value at this stage are:

- Clear, consistent hamburger navigation on each page
- Messaging that clearly communicates the focus of the site
- Responsive design

### The Structure Plane

As the site will not have a lot of content to begin with a linear narrative will work best.

### The Surface Plane

#### 1. Font

[DM Sans](https://fonts.google.com/specimen/DM+Sans?query=dm+sans#standard-styles) is a low-contrast geometric sans serif design, intended for use at smaller text sizes, this will be especially helpfull for recipies which have large bodies of text in the steps section as text will be clear and easy to read. The tone of the font is contempory and clear. A backup of `sans-serif`, is included in case of any particular font not rendering as expected. Lower cases is used on the description to enhance readability.

##### 2. Color Scheme

The colour scheme is simple and paired back to allow the focus to be on content and legibility. The primary colour of green is in refrence to nutritious food choices. Hues of the primary green as well as as complimentary hue of warm beige are used throughout the site to aid with visual naviagtion.

- Primary: rgb(177, 236, 178)
- Secondary: rgb(241, 250, 242)
- Tertiary: rgb(248, 245, 241)

##### 3. Logo

The logo incorporates the font DM Sans which has been used across the site to maintain a consistant styling 

### Database Design
Database Schema
ER Model

## Technologies Used

### Languages Used

BSON - bson.objectid is a required dependency for MongoDB management system.
CSS - used to create the styling throughout the site.
Google fonts - used to import fonts.
HTML - used to create the site structure.
Flask - framework used to create and populate the templates.
JavaScript - used for the sidenav, back-to-top button, image preview.
Jinja - Jinja templating language was used to simplify and display backend data in html.
jQuery - used to activate the Materialize functionality.
Materialize - library used for styling and responsiveness.
PyMongo - flask_pymongo was used for interacting with MongoDB database from Python.
Python - used to write the logic that operates the site.
Werkzeug - used for password hashing and authentication.

### Frameworks, Libraries & Programs Used

1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Space Grotesk' font into the style.css.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.



