<a name="top"></a>

# Yoga Online 

## Contents

- [Introduction](#Introduction)
- [Features](#Features)
    - [Main Page](#main-page)
- [UX](#ux)
    - [Site Goals](#site-goals)
    - [Typography](#typography)
    - [Wireframes](#wireframes)
- [Testing](#testing)
- [Deployment](#deployment)
- [Cloning the GitHub Repo](#cloning-the-github-repo)
- [Forking the GitHub Repo](#forking-the-github-repo)
- [Working with GitPod](#working-with-gitpod)
- [Citation of Sources](#citation-of-sources)

<br>
<br>

# Introduction

A website designed to promote Yoga training online. It contains a main page with a link to an E-learning website with Yoga lesson videos and a page to sign up. If I wanted to further develop the website, I would require users to sign up first in order to see videos. I embedded sample videos from youtube.com for the project. However for the final website I would create my own videos and publish them regularly.

Below are responsive images of the three pages.

![Responsive simulator image](readme/index-responsive.png)
![Responsive simulator image](readme/video-responsive.png)
![Responsive simulator image](readme/signup-responsive.png)

Below is the online website hosted by github.com

[Project Repository](https://github.com/ssmerd/online-yoga)

To see the project code and README.md use this link

[Live Site](https://ssmerd.github.io/online-yoga/)

<br>
<br>

# Features

## Main Page

* Navigation Bar

    * Featured on all pages, the full responsive navigation bar includes the website logo and links to the home, e-learning videos and signup page. 
    All these features are identical on all pages to allow for easy navigation.
    * The navigation bar will allow users to easily navigate from page to page across all devices without having to revert back to the previous page via 'back' button
    * Home link allow to easily revert to the home page
    * The E-learning link allow you to see sample online yoga videos. Currently they are embedded from youtube.com.
    * To use the E-learning link a user would have to sign up first. Hence there is a link to the signup page.



![Navigation Bar](readme/navigation-bar.png)


* The landing page

    * The landing page image includes a photograph with a text overlay to allow the user to learn what the page is about.
    * This section introduces users to Yoga Online explaining that the yoga videos are free for everyone and can be accessed from anywhere.


![Landing Page](readme/landing-page.png)


* The about section

    * This section presents the goal of the website and some information about its owners.
    * Its goal is to attract users to login, watch and shop on the website


![Landing Page](readme/about-page.png)



* Sign up for Newsletter section

    * The goal of this section is to allow user to sign up for the newsletter

![Landing Page](readme/newsletter-page.png)

* Footer section

    * The goal of this section is to redirect a user to social media channels related to the website.

![Landing Page](readme/social-media-page.png)


E-Learning page

* Navigation bar as in the main page

* Sample videos

    * The complete course of yoga. I have embedded sample youtube videos.

![Landing Page](readme/elearning-page.png)

* Sign Up page

    * This page allows users to sign up to the website in order to use videos

![Landing Page](readme/signup-page.png)


<br>
<br>

# UX

## Site Goals

The goal of the website is to attract users to watch yoga classes and buy some yoga artefacts in the online shop (the shop doesn't exist yet).
This website is easy to navigate as well as aesthetically pleasing. Administrator should be able to easily add videos. The yoga classes should be 
available post signing up to the website.

## User Stories

As a user:

* I want to watch and learn yoga online
* I want to sign up to the site in order to access videos
* I want to log in to the site to watch videos
* I want to get newsletter


As the site administrator:

* I want to be able to add new videos
* I want to update the website as little as possible
* I want to gather user emails to send them my weekly newsletter
* I want user to get familiar with my website
* I want user to access my yoga artefacts shop

## Typography

All fonts were sourced from Google Fonts:

 - Roboto used for the nav, about, newsletter and signup form sections
 - Mynerve used for the logo in the header

## Wireframes


Below are wireframes create for the project

* Main page

![Main Page](readme/home-page-wireframe.png)

* Video page

![Video Page](readme/elearning-page-wireframe.png)

* Signup page

![Sign Up](readme/signup-page-wireframe.png)

<br>
<br>

# Testing

* ### User and responsive design testing

| Test              | Outcome |
|-------------------|---------------|
|All navigation links take user to correct page|pass|
|Footer navigation and social & social links load correct pages|pass|
|Content reformats on smaller screens|pass|
|Newsletter form submits correctly|pass|
|Newsletter form prevents wrong data types|pass|
|Signup form submits correctly|pass|

All user stories were tested and no faults were found. All links are working fine.
I used a sample youtube videos, however, in the real website I would use my own. Also to access the videos, a user would have to be signed up.
Initially I had issues with reposnsivess but I managed to find css settings to make it look well.  This allowed me to adjust certain settings so the websites 
looked good on different devices. 

I thoroughly tested the website and its responsiveness with Google Inspect functionality and ui.dev/amiresponsive tool. This proved the most troublesome in the project. As advised by me mentor I should have built the mobile version first and then add functionality for bigger screen sizes, as opposed to building the desktop version first.

    
* ### Code and CSS validators

HTML and CSS validators were used to test the pages and css validity. No errors were returned for each page when passing through the official W3C validators.

* Home page html validation results

    - [Home Page](https://validator.w3.org/nu/?doc=https://ssmerd.github.io/online-yoga/)

* E-learning  page html validation results

    - [E-learning Page](https://validator.w3.org/nu/?doc=https://ssmerd.github.io/online-yoga/video.html)

* Signup page html validation results

    - [Signup Page](https://validator.w3.org/nu/?doc=https://ssmerd.github.io/online-yoga/signup.html)

* CSS validation results

    - [Jigsaw validator](https://jigsaw.w3.org/css-validator/validator?uri=https://ssmerd.github.io/online-yoga/index.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

* Accessibility

The accessibility of each of the main pages was checked using the lighthouse tool in devtools with a score within the 90 - 100% bracket for all metrics.

<br>

![Lighthouse](readme/lighthouse.png)

<br>
<br>

# Deployment

The yoga online page was deployed to GitHub. Below is the link:

[Live Site](https://ssmerd.github.io/online-yoga/)

This site was deployed to GitHub pages. The steps to deploy are as follows:

*   In the GitHub repository, navigate to the Settings tab
*   From the source section drop-down menu, select the Master Branch
*   Once the Master Branch has been selected, the page will be automatically refreshed with the detail ribbon display to indicate the successful deployment


<br>
<br>

# Cloning the GitHub repo

This repo can be cloned as follows:

*   On the main repo page [Repo page](https://github.com/ssmerd/online-yoga) navigate to the Code tab
*   Select the way you want to clone using HTTPs, SSH or GitHub CLI and click the copy button
*   Open Git Bash ot Terminal
*   In your terminal, in a chosen directory paste the command:
    *      https://github.com/ssmerd/online-yoga.git
*   Press Enter to create your local clone

<br>
<br>

# Forking the GitHub repo

In order to create a copy of the original repository on our GitHub account to view or edit it without affecting the original owner's repository we can fork it.


*   At the top of the Repository [Repo page](https://github.com/ssmerd/online-yoga), above the Settings button, locate the Fork button 
*   Once clicked, it will create as a copy of the original repository in your own GitHub account


<br>
<br>

# Working with GitPod

I used GitPod to work on the project. 

*   First I installed a GitHub GitPod extension in Chrome. This allows to create the workspace to work on the project on the repository
*   I usually start by pressing the GitPod extension as my GitPod workspaces usually time out.

[GitPod extension] (https://chrome.google.com/webstore/detail/gitpod-always-ready-to-co/dodmmooeoklaejobgleioelladacbeki)

<br>
<br>

# Citation of Sources


* ### Inspiration

The project was inspired by the code institute Love Running project. I used social media code from the Love Running project.


* ### HTML and CSS 

https://www.w3schools.com/

https://developer.mozilla.org/

https://stackoverflow.com/

* ### Wireframes

https://balsamiq.cloud

* ### Responsivness testing

https://ui.dev/amiresponsive

Chrome Inspect

* ### HTML and CSS validations

https://validator.w3.org/
https://jigsaw.w3.org/css-validator/

* ### Fonts and icons

Goole Fonts and Icons

https://fonts.google.com/


Font Awsome

https://fontawesome.com/


* ### Media

Photos used for the main and signup page come from:

https://www.shutterstock.com/

https://www.pexels.com/

Videos in the E-learning page come from:

https://www.youtube.com/results?search_query=yoga+with+adriene+

* ### Form testing

https://httpbin.org/post

<br><br>

# Future Features

Access to the videos would be secured by logging to website. First a user would have to sign up. Currently I don't have skills to do that.

I'd like to develop a shop selling yoga artefacts to monitize  the website. Currently I dont have skills to do that.

Also I would add a link to a donate website.

### <a name="acknowledge">Acknowledgements</a>

* Mentor - Chris Quinn
* Cohort Facilitator - Special credit to Alan Bushell who gave great support and tips when testing the website.


<br><br>
<a href="#top">BACK TO TOP 🔼</a>