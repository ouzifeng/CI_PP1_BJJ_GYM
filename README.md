![BJJ logo](https://github.com/ouzifeng/bjj-gym/blob/main/assets/images/bjj-logo.webp)

# Brazilian Jiu-Jitsu Club



### Use Case

A client, who is starting up their own Brazilian Jit-Jitsu (BJJ) club in the local area, approached me to build a website for their new gym. They feel that a website will be invaluable to their business for finding new students, and keeping existing students up to date with timetables and any other club related updates

![Responsive Image](https://github.com/ouzifeng/bjj-gym/blob/main/docs/responsive-design.png)
[Live Site](https://ouzifeng.github.io/CI_PP1_BJJ_GYM/)

## Table of Content

1. [Project Scope](#project-scope)
    1. [End User Requirements](#end-user-requirements)
    2. [Customer Goals](#project-scope)

2.  [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [UX IU](#ux-ui)

3. [User Stories](#user-stories)
    1. [New Students](#new-students)
    2. [Existing Students](#existing-students)
    3. [Parents](#parents)
    4. [Site Owner](#site-owner)

4. [Design](#design)
    1. [Fonts](#fonts)
    2. [Colour Scheme](#colour-scheme)
    3. [Wireframes](#wireframes)

5. [Technologies & Resources Used](#technologes-&-resources-used)

6. [Testing](#testing)
    1. [HTML validation](#html-validation)
    2. [CSS validation](#css-validation)
    3. [Accessbility](#accessibility)
    4. [Performance](#performance)
    5. [Performance test on different devices](#performance-test-on-different-devices)
    6. [Browser compatibility](#browser-compatibility)
    7. [Testing User Stories](#testing-user-stories)

7. [Features](#features)
    1. [Structure](#structure)
    2. [Logo and Navigation Bar](#logo-and-navigation-bar)
    3. [Carousel](#carousel)
    4. [Video](#video)
    5. [Map](#map)
    6. [Pricing and Free Trial](#pricing-and-free-trial)
    7. [Timetables](#timetables)
    8. [Contact Form](#contact-form)
    9. [Social Links](#social-links)
    10. [Children's Classes](#childrens-classes)
    11. [404 Page](#404-page)

8. [Bugs](#bugs)

9. [Deployment](#deployment)

10. [Credits](#credits)

11. [Acknowledgements](#acknowledgements)





## Project Scope

### End User Requirements

* Need to be able to find the gym
* Need to be able to contact the gym
* Need to know prices
* Need to know lesson schedule

### Customer Goals

* Find new students
* Be contactable by email
* Provide critical information about the gym to customers
* Promote the business on social media platforms
* Feel "friendly" and approachable

## User Experience

### Target Audience

* Potential students who are new to the sport and looking to join a gym for the first time
* Students who are already training but are looking for a new gym closer to their existing one
* Parents who want their children to try a new sport

### UX UI

* Responsive design across mobile, tablet and desktop/laptops
* Easy to navigate and find critical information -> prices and timetable
* No dead links
* Placeholder for Facebook and Instagram pages (these are currently not setup)
* Simple way to contact the gym owner. The owner prefers to communicate through email as they don't have access to take calls during the day
* Simple design without distracting elements or long blocks of text

## User Stories

### New Students

1. I want to know how to get to the gym, preferrably via an embedded map on the contact page
2. I want to know how much it will cost me on a monthly or class by class basis, and whether there is a free trial
3. I want to be able to check the timetable to see when classes are on
4. I want to see images of the gym and students to get a feel for the place
5. I want to be able to contact the gym if I have questions

### Existing Students

6. I want to be able to check the timetable to see when classes are on
7. I want to see images of myself and/or my classmates training
8. I want links to social media pages to see any new update of photos

### Parents

9. I want to be able to see children's timetable
10. I want to be able to see how much children's classes are
11. I want to see photos of children training to get a feel for the gym
12. I want to be able to contact the gym if I have questions

### Site Owner

13. I want dead links to redirect to a 404 page
14. I want new and existing students to be able to contact me via email, not phone. Also give an explanation as to why there is no phone number available (I am often busy during the day and cannot takes calls)
15. I want new and existing students to be able to find timetable and pricing easily


## Design

### Fonts

For the font choice we needed something which looked professional but also welcoming and friendly.

* Montserrat for headings
* Lato for body

### Colour Scheme

Based on how the leading gyms have built their colour schemes:
 * https://rogergracie.com/
 * https://ekbjj.com/ 
 * https://www.bjjlondon.com/
 * https://www.10thplanetjj.com/

 They are clean with plenty of constrasting colours - namely white with black. 

![](https://github.com/ouzifeng/bjj-gym/blob/main/assets/images/website-colours.png)

To keep with this theme, but with a lisght twist the 2 main colours will be baby powder and rich black, coupled with a choice of bolder colours for CTAs

### Wireframes

<details>

<summary>Home</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/wireframes/Home-Page-Desktop.png">
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/wireframes/Home-Page-Tablet.png">
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/wireframes/Home-Page-Mobile.png">

</details>

<details>

<summary>Timetable</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/wireframes/Timetable-Desktop.png">
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/wireframes/Timetable-Tablet.png">
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/wireframes/Timetable-Mobile.png">

</details>

<details>

<summary>Contact</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/wireframes/Contact-Desktop.png">
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/wireframes/Contact-Tablet.png">
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/wireframes/Contact-Mobile.png">

</details>

<details>

<summary>Classes</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/wireframes/Classes-Desktop.png">
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/wireframes/Classes-Tablet.png">
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/wireframes/Classes-Mobile.png">

</details>

<details>
<summary>404</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/wireframes/404-Desktop.png">
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/wireframes/404-Tablet.png">
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/wireframes/404-Mobile.png">

</details>

## Technologies & Resources Used

#### HTML AND CSS

* Balsamiq for wireframe designs 
* Google Fonts for fonts
* Photoshop
* Canva
* Coolors
* Bootsrap V5
* Microsoft Bing Image Generator (logo)
* Compressor.io to losslessy reduce image size


## Testing

### HTML validation

Tool for HTML Validation - W3C HTML Validation Service


index.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fouzifeng.github.io%2FCI_PP1_BJJ_GYM%2Findex.html)

404.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fouzifeng.github.io%2FCI_PP1_BJJ_GYM%2F404.html)

classes.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fouzifeng.github.io%2FCI_PP1_BJJ_GYM%2Fclasses.html)

contact.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fouzifeng.github.io%2FCI_PP1_BJJ_GYM%2Fcontact.html)

prices.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fouzifeng.github.io%2FCI_PP1_BJJ_GYM%2Fprices.html)

timetable.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fouzifeng.github.io%2FCI_PP1_BJJ_GYM%2Ftimetable.html)


### CSS Validation

Tool for CSS Validation - W3C CSS Validation Service

Full site validation: [results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fouzifeng.github.io%2FCI_PP1_BJJ_GYM%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

Results = 25 errors and 491 warnings. 

25 errors are coming from Bootstrap's https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css 
419 warnings from Bootstraps https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css

Manually copy and pasting the style.css into the validator results in "Congratulations! No Error Found."

### Accessibility

The WAVE WebAIM web accessibility evaluation tool was used to ensure the website met the neccessary accessibility standards.

There are zero errors on all pages

index.html [results](https://wave.webaim.org/report#/https://ouzifeng.github.io/CI_PP1_BJJ_GYM/index.html)

404.html [results](https://wave.webaim.org/report#/https://ouzifeng.github.io/CI_PP1_BJJ_GYM/404.html)

classes.html [results](https://wave.webaim.org/report#/https://ouzifeng.github.io/CI_PP1_BJJ_GYM/classes.html)

contact.html [results](https://wave.webaim.org/report#/https://ouzifeng.github.io/CI_PP1_BJJ_GYM/contact.html)

prices.html [results](https://wave.webaim.org/report#/https://ouzifeng.github.io/CI_PP1_BJJ_GYM/prices.html)

timetable.html [results](https://wave.webaim.org/report#/https://ouzifeng.github.io/CI_PP1_BJJ_GYM/timetable.html)

### Performance

Google Lighthouse was used to measure performance of each page

Performance has been impacted main by third party resources, please see known bugs for more information. Performance is throttled by 3rd party libraries namely:
* Index page - YouTube's JS library required to embed videos
* All pages - Bootstrap's CSS and JS CDN and Google font's CDN. The option to install Bootstrap files directly into the project was considered, but maintaining upgrades and changes to Bootstrap files would require new packages to be downloaded and installed. Using a CDN was decided the best way to counteract this.

All images are taken using Chrome's built-in Lighthouse tool, measured on mobile. Desktop version yield better results

<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/validation/render-blocking.png">
Render-blocking resources impacting page performance

<details>
<summary>Home</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/validation/lighthouse-performance-index.png">
</details>

<details>
<summary>404</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/validation/lighthouse-performance-404.png">
</details>

<details>
<summary>Classes</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/validation/lighthouse-performance-classes.png">
</details>

<details>
<summary>Contact</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/validation/lighthouse-performance-contact.png">
</details>

<details>
<summary>Prices</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/validation/lighthouse-performance-prices.png">
</details>

<details>
<summary>Timetable</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/validation/lighthouse-performance-timetable.png">
</details>







### Performance test on different devices
The website was tested on the following screen sizes and devices:
- Windows desktop 28inch and 22inch screens
- Macbook pro
- Huawei 8" tablet
- Apple iPhone 13
- Google Pixel 7

### Browser compatibility
The website was tested onthe following browsers:
- Chrome
- Safari
- Firefox

### Testing User Stories

#### New Students

1. I want to know how to get to the gym, preferrably via an embedded map on the contact page

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Map | Visit contact page | Loads a Google map of the gym and has the address in text format | Works as expected |
| Footer/Header | Click on "contact" link in header or footer | Takes user to contact page where address is | Works as expected |

<details>
<summary>Find Map</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/map.png">
</details>

2. I want to know how much it will cost me on a monthly or class by class basis, and whether there is a free trial

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Pricing Matrix | Visit Prices page | Loads pricing cards | Works as expected |
| CTA card | Visit Index or Timetable page | Has free trial CTA | Works as expected |

<details>
<summary>Pricing Cards</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/prices-feature.png">
</details>

<details>
<summary>Free trial</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/free-trial-feature.png">
</details>

3. I want to be able to check the timetable to see when classes are on

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Timetables | Visit timetable page | Loads adults and children's timetable | Works as expected |

<details>
<summary>Adults Timetable</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/adults-timetable-feature.png">
</details>

<details>
<summary>Children's Timetable</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/childrens-timetable-feature.png">
</details>

4. I want to see images of the gym and students to get a feel for the place

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Image carousel | Visit index page | carousel load with 3 images of the gym and students | Works as expected |
| Youtube video | Visit index page | video of the gym load | Works as expected |
| Images on classes page | Visit Classes page | 3 sections - our faciilites, adult classes and children's classes should laod with images | Works as expected |

<details>
<summary>Carousel</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/carousel-feature.png">
</details>

<details>
<summary>Youtube Video</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/youtube-video.png">
</details>

5. I want to be able to contact the gym if I have questions

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact Form | Visit contact page | Contact form loads | Works as expected |

<details>
<summary>Contact Form</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/contact-page.png">
</details>

#### Existing Students

6. I want to be able to check the timetable to see when classes are on

 **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Timetables | Visit timetable page | Loads adults and children's timetable | Works as expected |

<details>
<summary>Adults Timetable</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/adults-timetable-feature.png">
</details>

7. I want to see images of myself and/or my classmates training

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Image carousel | Visit index page | carousel load with 3 images of the gym and students | Works as expected |
| Youtube video | Visit index page | video of the gym load | Works as expected |

<details>
<summary>Carousel</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/carousel-feature.png">
</details>

<details>
<summary>Youtube Video</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/youtube-video.png">
</details>

8. I want links to social media pages to see any new update of photos

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Social links in footer | Click FB or IG link in footer | links open up gym FB or IG page | Pages not created yet so href is set to "#" |

<details>
<summary>Social Links</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/social-links-feature.png">
</details>

#### Parents

9. I want to be able to see children's timetable


| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Timetables | Visit timetable page | Loads children's timetable | Works as expected |

<details>
<summary>Children's Timetable</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/childrens-timetable-feature.png">
</details>

10. I want to be able to see how much children's classes are

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Pricing Matrix | Visit Prices page | Loads childrens pricing card | Works as expected |

<details>
<summary>Pricing Cards</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/prices-feature.png">
</details>

11. I want to see photos of children training to get a feel for the gym

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Children's classes area | Visit classes page | Loads children's classes area | Works as expected |

<details>
<summary>Pricing Cards</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/childrens-classes-feature.png">
</details>

12. I want to be able to contact the gym if I have questions

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact Form | Visit contact page | Contact form loads | Works as expected |

<details>
<summary>Contact Form</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/contact-page.png">
</details>

#### Site Owner

13. I want dead links to redirect to a 404 page

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| 404 page | visit deadlink i.e /deadlink | Redirect to 404 page | Works as expected |

<details>
<summary>404 Redirect</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/404-feature.png">
</details>

14. I want new and existing students to be able to contact me via email, not phone. Also give an explanation as to why there is no phone number available (I am often busy during the day and cannot takes calls)

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact form/explanation a to why no phone number | visit contact page | Contact form and paragraph about containg via email not phone load | Works as expected |

<details>
<summary>Contact Page</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/contact-page.png">
</details>

15. I want new and existing students to be able to find timetable and pricing easily

 **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Navbar | Click Timetable or Pricing in navbar | Sends user to timetable or Prices page | Works as expected |
| Futher links | Scroll to bottom of index page, click on "View Timetable" | Sends user to timetable page | Works as expected |

<details>
<summary>Navbar</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/navbar-feature.png">
</details>

<details>
<summary>Further Links</summary>
<img src="https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/further-links.png">
</details>


## Features

### Structure

The website consists of 6 pages:

1. Home page -> an overview of the gym, with clear links to other key parts of the site and a clear CTA to join
2. Classes page -> more information about the gym, the adult classes and the children's classes
3. Contact page -> clearly laid out contact form and map of the gym's location
4. Pricing page -> options to view the 3 different pricing tiers
5. Timetable page -> new and existing sutdents can find out when their next class is
6. 404 page -> redirects any deadlinks to the 404 page

and 11 features:

### Logo and Navigation Bar

* Featured on all pages
* Simple layout with minimal number of options for easy navigation
* Fully responsive on desktops, laptops, tablets and mobiles. On mobile the links are displayed as a hamburger menu. Active links are highlighted in a different colour
* User story no. 15

#### Desktop Version
![](https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/navbar-feature.png)

#### Mobile Version
![](https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/navbar-mobile-feature.png)



### Carousel

* Shows image of the club and its students
* Has clear CTA embedded to sign up for the free trial
* User stories no. 4, 7 

#### Carousel image (1 of 3)
![](https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/carousel-feature.png)


### Video

* Found on landing page directly under carousel
* Gives a more indeoth intorduction to the gym vs images
* User stories 4, 7

#### Embedded Video
![](https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/feature-video.png)

### Map

* Interactive map via a Google maps embed
* Allows viewing of larger map
* Has address written underneath
* User story 1

#### Embedded Map
![](https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/local-map-feature.png)

### Pricing and Free Trial

* Clearly shows pricing tier for adults, children and one off visits
* Links to contact form if user has more questions
* Free trial CTA clearly states 1 week free without any obligations
* User stories 2, 10, 15

#### Pricing Cards
![](https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/prices-feature.png)

#### Free Trial CTA
![](https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/free-trial-feature.png)


### Timetables

* Separate timetables for adults and children's classes
* Timetables scroll on mobile for a better user experience
* Additional information included, for example what to bring
* User stories 3, 6 , 9, 15

#### Adult Timetable
![](https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/adults-timetable-feature.png)

#### Children's Timetable
![](https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/childrens-timetable-feature.png)

### Contact Form

* Does not require user to input too many personal details, just name and number
* Checkbox to agree to have the users personal details processed
* Includes message about free trial
* User story 5, 12, 14

#### Contact Form
![](https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/contact-form-feature.png)

### Social Links

* Facebook and Instagram link
* Links set to open up in new tab
* In footer of every page
* User story 8

#### Social Links
![](https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/social-links-feature.png)

### Children's Classes 

* Set of photos showing children training at the club
* Children look happy and enjoyign the lesson
* There is an instructor nearby coaching them and keeping them safe
* User story 11

#### Children's Classes
![](https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/childrens-classes-feature.png)

### 404 Page

* Any dead links will redirect to 404 page
* 404 page has a link to take users back to the index page

#### 404 Page
![](https://github.com/ouzifeng/bjj-gym/blob/main/docs/features/404-feature.png)


## Bugs

| **Bug** | **Fix** |
| ----------- | ----------- |
| Links to social media pages are not live | Gym needs to setup necessary social media pages and provide links/names |
| The contact form does not work | Build a PHP script to handle sending messages from the website |
| The contact form is not using required attributes | Add required to  HTML input |
| Youtube video on index page loads heavy unused JS files, impacting performance | These originate from the Youtube API so we cannot defer them using HTML. Either lazy load the video using JS or use a light embed |
| GIF on 404 page is 1mb and impacts performance | Convert the GIF to video, serve the GIF via a CDN, implement lazy loading or change to a static image |
| Photos are not being served using next gen format | Convert .jpg and .png images to .webp |
| Images are not being cached | Serve static assets with an efficient cache policy |
| Bootstrap, FontAwesome and Google Fonts require JS and CSS files that impact performance | Load the scripts using async, or defer attribute to avoid blocking document parsing |

## Deployment

To deploy the website using GitHub Pages, perform the following steps:

* Visit the relevant GitHub repository and click on the Settings tab.
* From the left-side menu, select the Pages option.
* Choose the source as Branch: master.
* Upon page refresh, you will observe a banner at the top indicating: "Your site is published at https://ouzifeng.github.io/CI_PP1_BJJ_GYM/"
* If you wish to fork the repository, adhere to these steps:

* Navigate to the desired GitHub repository.
* Find and click on the Fork button situated in the top right corner.
* To clone the repository, execute these steps:

* Visit the specific GitHub repository.
* Find the Code button placed above the file list and click on it.
* Decide your preferred cloning method: HTTPS, SSH, or Github CLI and hit the copy button to clone the URL to your clipboard.
* Launch Git Bash.
* Modify the current working directory to your preferred location for the cloned directory.
* Enter the command 'git clone' followed by the URL copied from the clipboard (e.g., $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY).
* Hit Enter to initialize your local clone.

## Credits
Images below do not belong to the developer, but they either have permission to use them from the owner or they can be used under Google's creative commons license

### Images

In order of appearance:

#### Index Page:

| **File Name** | **Link** |
| ----------- | ----------- |
| slider.webp | https://carlsongraciebjjsurrey.com/ |
| slider1.webp | https://carlsongraciebjjsurrey.com/ |
| slider2.webp | https://carlsongraciebjjsurrey.com/ |
| free-trial.webp | https://www.istockphoto.com/ |
| adults-class.webp | https://carlsongraciebjjsurrey.com/ |
| childrens-class.webp | https://carlsongraciebjjsurrey.com/ |
| bjj-timetable.webp | https://www.istockphoto.com/ |

#### 404:

| **File Name** | **Link** |
| ----------- | ----------- |
| 404.webp | https://www.istockphoto.com/ |

#### Classes:

| **File Name** | **Link** |
| ----------- | ----------- |
| bjj-mats.webp | https://www.istockphoto.com/ |
| bjj-gym.webp | https://www.istockphoto.com/ |
| adults-class-1.webp | https://carlsongraciebjjsurrey.com/ |
| adults-class-2.webp | https://carlsongraciebjjsurrey.com/ |
| adults-class-3.webp | https://carlsongraciebjjsurrey.com/ |
| childrens-classes-1.webp | https://carlsongraciebjjsurrey.com/ |
| childrens-classes-2.webp | https://carlsongraciebjjsurrey.com/ |

#### Prices:

| **File Name** | **Link** |
| ----------- | ----------- |
| pricing-bjj.webp | https://www.istockphoto.com/ |

### Video

| **Video** | **Link** |
| ----------- | ----------- |
| Index page - YouTube video | Carlson Gracie Surrey BJJ Youtube Page/ |

### Code

In order of appearance

* The responsive navbar was built using <a href="https://getbootstrap.com/docs/5.3/components/navbar/" target="_blank">Boostrap V.5.3 Navbar components</a>
* The image carousel was built using <a href="https://getbootstrap.com/docs/5.3/components/carousel/" target="_blank">Boostrap V.5.3 Carousel components</a>
* 404 page was build using description on <a href="https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-custom-404-page-for-your-github-pages-site" target="_blank">GitHub Docs</a>

## Acknowledgements:


* My teammates, for always pushing me to train harder
* My mentor Mo Shami for challenging me to always do my best work



