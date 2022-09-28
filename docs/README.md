# Dinder - HTML/CSS Essentials

Dinder is a matching service for dog owners in Stockholm, Berlin and Dublin, founded by Johanna Hendrix. The webpage is intended to gather contact information about dog owners and match them together according to their location and interests.

![IMAGE ALT TEXT HERE](/docs/screenshots/responsive_pic.png)


## Live site

<a href="https://bo-lennart.github.io/dinder/" target="_blank">Dinder Home Page</a>


## Repository

<a href="https://github.com/Bo-Lennart/dinder" target="_blank">Go to Repository</a>

## Contents

* Project Goals
* Features
    * Navigation
    * Hero image
    * Member Interview
    * About page
    * Find Match!
    * Thank You Page
    * Footer
* Testing
    * Bugs
    * Validator Testing

# Project Goals

* To create a web page where dog owners can sign up in order to connect with other dog owners for a client.

* To demonstrate my developer competency using HTML & CSS languages


# Features

## Navigation

![IMAGE ALT TEXT HERE](/docs/screenshots/nav_bar.png)

* On the top of the page a navigation bar is displayed. The companys' logo is on the left hand side providing a link to the home page.
* On the mid-right hand side, there are two links: "About" and "Find a Match" which will navigate to these pages.
* The font style and colour of the logo is chosen to present a playful feel that pops against the white background.
* The navigation font is descreet and clean to add contrast to the playfulness and clearly show the user how to navigation through the webpage. 


## Hero Image
![IMAGE ALT TEXT HERE](/docs/screenshots/home_page_hero.png)

* The hero image is chosen to intuitively direct the first user towards what the page is about (dogs). Additionally to clearify the purpose of what Dinder is, a paragraph is added to float over the image with a short description.

## Member Interview

![IMAGE ALT TEXT HERE](/docs/screenshots/member_interview.png)

* On the first section of the home page, there's a short sentence from a Dinder member who explains what she liked about the Dinder experience.


## About page
![IMAGE ALT TEXT HERE](/docs/screenshots/about_page.png)

* When the user navigates to the about page, a new header is introduced to add a dynamic visual experience. They will find a shorter description of how Dinder came up and from where the idea began. Below this section they will find a short interview with the founder of Dinder - Johanna Hendrix.


![IMAGE ALT TEXT HERE](/docs/screenshots/founder_interview.png)

## Find Match!

![IMAGE ALT TEXT HERE](/docs/screenshots/sign_up_form.png)

* The sign up section consists of a short form where the user is able to provide the information needed in order for Dinder to generate a match. All fields are neccessary to fill out and once it's submitted with the "Find Match!" button the user is redirected to a thank You page!

## Thank You Page

![IMAGE ALT TEXT HERE](/docs/screenshots/thank_you.png)

## Footer

* The footer provides the user with social links where they will be redirected to LinkedIn, Github and Facebook.

![IMAGE ALT TEXT HERE](/docs/screenshots/footer.png)

# Testing

* The page is tested and works responsively throughout web browsers such as Chrome, Firefox and Safari.

* I confirmd that the responsive design and chosen images for tablets and mobile screens work as intended.

![IMAGE ALT TEXT HERE](/docs/screenshots/responsive_mobile_tablet.png) 

* The navigation bar is easy to understand and the texts, paragraphs, headings, links, inputs, buttons are readable and work.

* The form works and all required entry fields work. The amail field will only accept an email adress and the submit button won't redirect to the thank you page before all fields are filled out!

## Bugs

* When I deployed my project to GutHub the project could not locate images and the file pathway to the stylesheet eventhough it had worked perfectly fine when running locally. 
The bug was solved by setting a dot infront of the pathway and originate from the Dinder folder.
   
    [Solved: link rel="stylesheet" href="./assets/css/style.css"]

* Once the pathway was solved for the stylesheet I had to do the same for the image pathways in the css file.

    [Solved: background: url('../images/hero_img_home.jpg') no-repeat center center;]

* The "Find Match!" submit button didn't work and I did not discover this before late in the process when I started working with the "thank you page". The problem that had occured was that I used the method="POST" without having somewhere to post it - error message occured.

    [Solved: Removed the post method and added action link to redirect to thank you page.]

## Validator Testing

* HTML
    * W3C validator
    * All the errors were adjusted/replaced accordingly
    ![IMAGE ALT TEXT HERE](/docs/screenshots/index_validation.png) 
    ![IMAGE ALT TEXT HERE](/docs/screenshots/about_thanks_validation.png) 
    ![IMAGE ALT TEXT HERE](/docs/screenshots/find_match_validation_first.png) 
    ![IMAGE ALT TEXT HERE](/docs/screenshots/find_match_validation_second.png) 

* CSS
    * Jigsaw
    * no errors or warnings were shown for the stylesheets document
    ![IMAGE ALT TEXT HERE](/docs/screenshots/css_validation.png) 

* Accessibility
    * I confirm that by running the webpage through lighthouse in devtools that font, colours, read and accessibility is performing well. 

![IMAGE ALT TEXT HERE](/docs/screenshots/lighthouse_performance.png) 

# Deployment

* The site was deploed to GitHub pages. The steps to deploy are the following:
    * Go to GitHub repository, navigate to the Settings tab.
    * From the source section drop-down menu, select the Master Branch.
    * Once the master branch has been selected, the page provided the link to the completed website.

Live link to page: <a href="https://bo-lennart.github.io/dinder/" target="_blank">Dinder</a>

# Credits

## Content

    * The code for the form was inspired by
    * The idea of hero image placement is inspired by

## Media
    
    * hero image [mobile size] Home page is taken from:
    * hero image [desktop size] Home page is taken from:
    * member image - Home page is taken from:
    * hero image [mobile size] About page is taken from:
    * hero image [desktop size] About page is taken from:
    * founder image - About page is taken from:
    * hero image [mobile size] Find Match! page is taken from:
    * hero image [desktop size] Find Match! is taken from: