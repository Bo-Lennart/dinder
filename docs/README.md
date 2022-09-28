# Dinder - HTML/CSS Essentials

Dinder is a matching service for dog owners in Stockholm, Berlin, and Dublin, founded by Johanna Hendrix. The webpage is intended to gather contact information about dog owners and match them together according to their location and interests.

![IMAGE ALT TEXT HERE](/docs/screenshots/responsive_pic.png)


## Live site

<a href="https://bo-lennart.github.io/dinder/" target="_blank">Dinder Home Page</a>


## Repository

<a href="https://github.com/Bo-Lennart/dinder" target="_blank">Go to Repository</a>

## Contents

- [Project Goals](#project-goals)
- [Target audience](#target-audience)
- [UX User Experience](#ux-user-eperience)
    - [User Stories](#user-stories)
    - [Color Scheme](#color-schemes)
- [Features](#features)
    - [Navigation](#navigation)
    - [Hero image](#hero-image)
    - [Member Interview](#member-interview)
    - [About page](#about-page)
    - [Find Match!](#find-match)
    - [Thank You Page](#thank-you-page)
    - [Footer](#footer)
- [Testing](#footer)
    - [Bugs](#bugs)
    - [Validator Testing](#validator-testing)
- [Deployment](#deployment)
    - [Deploy to GitHub Pages](#deploy-to-github-pages)
    - [To Fork the Repository](#to-fork-the-repository)
    - [To create a Local Clone](#to-create-a-local-clone)
- [Credits](#credits)
    - [Content](#content)
    - [Media](#media)

# Project Goals

* To create a web page where dog owners can sign up in order to connect with other dog owners for a client.

* To demonstrate my developer competency using HTML & CSS languages

# Target audience

Dog owners who want to meet other dog owners to find new friends for both themselves and their dogs.

# UX User Eperience

## User Stories

As a user I want to be able to:
* Understand what the purpose of this page is on loading.
* Have a smooth navigation experience as I click through the page.
* Build an understanding of what members think of Dinder's service.
* Be able to find information on how or why Dinder was created.
* Find a personal experience on the website which brings the importance of the founders interview into account. This gives a warmer feel and knowing that the founder actually is a dog owner herself and builds trust with the user.
* Be able to sign up and get clear instructions on what will happen once I've signed up.
* Learn more about the developer who built the site, which is provided by the social links at the footer of the page.

## Color schemes

The color schemes are selected from the header images and according to these, choices of colors are made for interview images to match harmonically with these schemes.

Colour schemes - Desktop:
![IMAGE ALT TEXT HERE](/docs/screenshots/dinder_desktop_color_schemes.png)

Colour schemes - Mobile:
![IMAGE ALT TEXT HERE](/docs/screenshots/color_schemes_mobile.png)



# Features

## Navigation

![IMAGE ALT TEXT HERE](/docs/screenshots/nav_bar.png)

* At the top of the page a navigation bar is displayed. The company's logo is on the left hand side, providing a link to the home page.
* On the mid-right hand side, there are three links: "Home", "About" and "Find a Match" which will navigate to these pages.
* The font style and color of the logo is chosen to present a playful feel that pops against the white background.
* The navigation font is discreet and clean to add contrast to the playfulness and clearly show the user how to navigate through the webpage.


## Hero Image
![IMAGE ALT TEXT HERE](/docs/screenshots/home_page_hero.png)

* The hero image is chosen to intuitively direct the first user towards what the page is about (dogs). Additionally, to clarify the purpose of what Dinder is, a paragraph is added to float over the image with a short description.

## Member Interview

![IMAGE ALT TEXT HERE](/docs/screenshots/member_interview.png)

* On the first section of the home page, there's a short sentence from a Dinder member who explains what she liked about the Dinder experience.


## About page
![IMAGE ALT TEXT HERE](/docs/screenshots/about_page.png)

* When the user navigates to the 'About' page, a new header is introduced to add a dynamic visual experience. They will find a shorter description of how Dinder came up and from where the idea began. Below this section they will find a short interview with the founder of Dinder - Johanna Hendrix.


![IMAGE ALT TEXT HERE](/docs/screenshots/founder_interview.png)

## Find Match!

![IMAGE ALT TEXT HERE](/docs/screenshots/sign_up_form.png)

* The sign-up section consists of a short form where the user is able to provide the information needed in order for Dinder to generate a match. All fields are necessary to fill out and once it's submitted with the "Find Match!" Button, the user is redirected to a 'Thank You' page!

## Thank You Page

![IMAGE ALT TEXT HERE](/docs/screenshots/thank_you.png)

## Footer

* The footer provides the user with social links where they will be redirected to linkedin, Github, and Facebook.

![IMAGE ALT TEXT HERE](/docs/screenshots/footer.png)

# Testing

* The page is tested and works responsively across web browsers such as Chrome, Firefox and Safari.

* I confirmed that the responsive design and chosen images for tablets and mobile screens work as intended. The header adjusts to the different screen sizes and navigation works fine.

* Social media links on the footer of the page work as intended and send the user to the desired web pages.

![IMAGE ALT TEXT HERE](/docs/screenshots/responsive_mobile_tablet.png) 

* The navigation bar is there to present clear navigation through the page. The purpose of putting it at the top of the page is to easily swipe up and navigate to the desired page.

* The form works and all required entry fields work. The email field will only accept an email address and the submit button won't redirect to the thank you page before all fields are filled out!

## Bugs

* When I deployed my project to GutHub, the project could not locate images and the file pathway to the stylesheet, even though it worked perfectly fine when running locally.
The bug was solved by setting a dot in front of the pathway and originating from the Dinder folder.
   
    [Solved: link rel="stylesheet" href="./assets/css/style.css"]

* Once the pathway was solved for the stylesheet, I had to do the same for the image pathways in the css file.

    [Solved: background: url('../images/hero_img_home.jpg') no-repeat center center;]

* The "Find Match!"  button didn't work and I did not discover this before late in the process when I started working with the "thank you page". The problem that had occurred was that I used the method="POST" without having somewhere to post it - error message occurred.

    [Solved: Removed the post method and added action link to redirect to thank you page.]

* During the final testing the radio buttons of the find match form did not work properly. All were selectable and I was not able to submit the form.
   * Cause: After the w3c validation I had blindly added and changed the code without paying attention to removing cruicial parts such as the name for each radio button.
   * Solution: A few tries of chaning the code back to how it was and some google searches I realized that the issue had to do with the name attribute and needs to be the same for each radio button, in order to be a unique selection.

## Validator Testing

* HTML
    * W3C validator
    * All the errors were adjusted/replaced accordingly
    ![IMAGE ALT TEXT HERE](/docs/screenshots/index_validation.png) 
    ![IMAGE ALT TEXT HERE](/docs/screenshots/about_thanks_validation.png) 
    ![IMAGE ALT TEXT HERE](/docs/screenshots/find_match_validation_first.png) 
    ![IMAGE ALT TEXT HERE](/docs/screenshots/find_match_validation_second.png) 
    * During the final validation after taking care of the radio button error on the 'Find Match' form that occurred, there were additional errors discovered. These are aswell replaced/removed accordingly.
    ![IMAGE ALT TEXT HERE](/docs/screenshots/final_validation.png) 


* CSS
    * Jigsaw
    * no errors or warnings were shown for the stylesheets document
    ![IMAGE ALT TEXT HERE](/docs/screenshots/css_validation.png) 

* Accessibility
   * I confirm that by running the webpage through lighthouse in devtools that font, colors, read and accessibility is performing well.

![IMAGE ALT TEXT HERE](/docs/screenshots/lighthouse_performance.png) 

# Deployment

The site was deployed to GitHub pages.

## Deploy to GitHub Pages
1. Navigate to the settings tab in the GitHub repository
2. Once in settings, navigate to the pages tab on the left of the page
3. Under source, select branch ‘master’ and then click ‘save’
4. Page will no automatically refresh and show a detailed ribbon display to indicate deployment

![IMAGE ALT TEXT HERE](/docs/screenshots/deploy_page_steps.png) 

## To Fork the Repository

To make a copy or ‘fork’ the repository:

1. Log into GitHub and locate repository
2. On the right hand side of the page select the ‘fork’ option to create and copy of the original

![IMAGE ALT TEXT HERE](/docs/screenshots/clone_process.png) 

## To create a Local Clone

1. under the repository name, click on the ‘code’ tab
2. in the clone box, HTTPS tab, click on the clipboard icon
3. in your IED open GitBash
4. Changed the current working directory to the location you want the cloned directory to be made
5. Type ‘git clone’ and then paste the URL copied from GitHub
6. press enter and the local clone will be created

![IMAGE ALT TEXT HERE](/docs/screenshots/fork_github_project.png) 



Live link to page: <a href="https://bo-lennart.github.io/dinder/" target="_blank">Dinder</a>

# Credits

## Content

* The idea of hero image placement with a floating description box is inspired from the CI <a href="https://github.com/Code-Institute-Org/love-running-2.0" target="_blank">Love Running Project</a>
    

## Media
    
* hero image [mobile size] 'Home' page is taken from: <a href="https://www.pexels.com/photo/portrait-of-a-dog-257540/" target="_blank">Pixels</a>

* hero image [desktop size] 'Home' page is taken from: <a href="https://www.pexels.com/photo/white-and-brown-puppy-on-black-car-7324407/" target="_blank">Pixels</a>

* member image - 'Home' page is taken from: <a href="https://www.pexels.com/photo/happy-black-woman-hugging-dog-on-street-5255596/" target="_blank">Pixels</a>

* hero image [mobile size] 'About' page is taken from: <a href="https://www.pexels.com/photo/dalmatian-sitting-white-surface-933498/" target="_blank">Pixels</a>

* hero image [desktop size] 'About' page is taken from: <a href="https://www.pexels.com/photo/photo-of-dog-peeking-on-vehicle-window-3097610/" target="_blank">Pixels</a>

* founder image - 'About' page is taken from: <a href="https://www.pexels.com/photo/woman-carrying-adult-fawn-dog-1612846/" target="_blank">Pixels</a>

* hero image [mobile size] 'Find Match!' page is taken from: <a href="https://www.pexels.com/photo/shih-tzu-sitting-on-the-floor-2623968/" target="_blank">Pixels</a>

* hero image [desktop size] 'Find Match!' is taken from: <a href="https://www.pexels.com/photo/english-cocker-spaniel-puppy-sitting-on-ground-beside-grass-1254140/" target="_blank">Pixels</a>

* hero image [desktop/mobile size] 'Thank you' page is taken from: <a href="https://www.pexels.com/photo/a-pet-dog-hiding-8473265/" target="_blank">Pixels</a>