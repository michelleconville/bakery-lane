# Bakery Lane
## Project Overview
Project 1 for Code Institute Full-stack development program: HTML/CSS Essentials

![The website displaying on all devices](assets/images/mock-up.JPG)

View the [Live site](https://michelleconville.github.io/bakery-lane/index.html)

This project is a Front-End website for an online bakery. 
A company's online presence can have a significant impact on its success, regardless of its industry. 
This website's main goal is to show users the bakery and introduce new customers to the brand. A contact form and social media channels allow users to interact with the business on the website, which is interactive and easy to use.

### Company goals
1.	Create an online presence for a bakery
2.	Provide a way for customers to contact the bakery
3.	Provide information about the bakery to customers

### Customer goals
1.	Find information about the bakery
2.	Be able to easily contact the bakery


## User Experience (UX)
### User Stories
First time users
*	I want to be able to find the types of cakes that are available
*	I want to be able to contact the Bakery
*	I want to be able to find out more information about the bakery

Returning User
*	I want to know what type of flavour cakes that are made at the bakery
*   I want to follow the bakery on social media
*   I want to be able to see samples of cakes that have been created

Site Owner
*   I want users to get to know more about the bakery
*	I want the users to be able to contact us
*   I want users to follow us on social media


## Design
### Color Pallette

![Colour Palette](assets/images/bakery-lane-colour-palette.jpg)
Cotton candy is used through out the site, mainly on the navigation bar and the footer. 
The midnight green is used for the text which includes the logo. 
Piggy pink, White and Onyx are used as background colours. All colours are used to style the buttons. 

### Fonts
The fonts used are Montserrat and Hind. 
Montserrat is used for the logo and the headers and Hind for the rest of the website. 
Fonts were imported from [Google Fonts](https://fonts.google.com/). The backup font of sans-serif was used incase the fonts do not load for the user.

### Structure
The Bakery Lane website is structured in a user friendly and easy to learn way. Upon arriving to the website, the user sees a navigation bar with the logo on the left-hand side and the navigation links to the right. The navigation bar and footer is located on all pages created.

The website consists of four pages:
*   The homepage has a hero image with a call-to-action button and two sections for types of cakes and flavours
*   An About Us page with a hero image, information about the bakery 
*   A gallery page with images highlighting the different kinds of cakes the bakery sells
*   A Contact Us page with a contact form

A thank you page when a user completes the contact us form and 404 page are also available.

### Wireframes
 <details>
<summary>Homepage</summary>

![index.html](assets/images/wireframes/index.html.png) 
</details>

 <details>
<summary>About Us page</summary>

![about-us.html](assets/images/wireframes/about-us.html.png)
</details>

 <details>
<summary>Gallery page</summary>

![gallery.html](assets/images/wireframes/gallery.html.png)
</details>

 <details>
<summary>Contact Us page</summary>

![contact.html](assets/images/wireframes/contact.html.png)
</details>

 <details>
<summary>Thank-you page</summary>

![thank-you.html](assets/images/wireframes/thank.you.html.png)
</details>

 <details>
<summary>404 error page</summary>

![404.html](assets/images/wireframes/404.html.png)
</details>

## Features 
### Site wide
#### Navigation Bar
*   This will contain the bakery logo and links to the Home, About Us, Gallery and Contact Us pages and will be responsive on all devices. By clicking on the logo, the user will be brought back to the home page.
*   This will allow users to easily navigate between the pages within the site on any size device.

![navigation bar](assets/images/features/navigation-bar-desktop.JPG)

#### Footer
*   This will contain both the contact information and the social media information for *Bakery Lane*. The social media websites will open in new tabs and be accessible to the visually impaired who may be using a screen reader, by the use of aria labels. 
*   This will allow the user to follow *Bakery Lane* on various social media where they can get more up to date information that may not be displayed on the website. The contact information will allow the user to contact *Bakery Lane* directly.

![footer](assets/images/features/footer-desktop.JPG)

#### Favicon
*   A site wide favicon will be implemented with the letter B for Bakery Lane using the same pink colour that is used in the navigation of the site.
*   This will provide an image in the tabs header to allow the user to easily identify the website if they have multiple tabs open.

![Favicon icon](assets/images/favicon/favicon-32x32.png)

#### 404 Page
*   A 404 page will be implemented and will display if a user navigates to a broken link.
*   The 404 page will allow the user to easily navigate back to the main website if they direct to a broken link / missing page, without the need of the browsers back button.

![footer](assets/images/features/404-page.JPG)

### Landing page
####	Landing page image and call to action button
*   An image will be carefully chosen for the background to make the landing page stand out from other websites, within the image there will be a text box and button to direct the user to the types of cakes *Bakery Lane* provides.
*   This will help to immediately show the user what the website is about.

![landing page](assets/images/features/landing-page.JPG)

#### Types of cakes
*   This section will be made up of three areas, Birthday Cakes, Tasty Treats and Bespoke Cakes. Each area will show an image, a short description and a link to a specific area to the gallery page.
*   This will allow the user understand the types of cakes that *Bakery Lane* specialise in and allow the user move to another section of the website.

![types of cakes](assets/images/features/types-of-cakes.JPG)


## Tesing

### Bugs

### validator Testing

### Browser compatability
The website was tested on the following browsers:

*   Google Chrome
*   Mozilla Firefox
*   Microsoft Egde

### Testing User Stories
**First time users**

1. I want to be able to contact the Bakery

| Feature         | Action                                                         | Expected result                 | Actual Result     |
|-----------------|----------------------------------------------------------------|---------------------------------|-------------------|
| Contact page | On any page click on the Contact link in the Navigation bar | Data submitted via contact form | Works as expected |
| Footer - contact information section | On any page scroll down to the footer | Find the contact information for the bakery | Works as expected |

2. I want to be able to find the types of cakes that are available

| Feature               | Action                                                                           | Expected result                     | Actual Result     |
|-----------------------|----------------------------------------------------------------------------------|-------------------------------------|-------------------|
| Call to action button | Navigate to the Home page, in the hero image, click on the types of cakes button | Locating the types of cakes section | Works as expected |
| Type of Cakes section | Navigate to the Home page, scroll down to types of cakes section                 | Locating the types of cakes section | Works as expected |

3. I want to be able to find out more information about the bakery

| Feature       | Action                                                       | Expected result                     | Actual Result     |
|---------------|--------------------------------------------------------------|-------------------------------------|-------------------|
| About page | On any page click on the About link in the Navigation bar | Locating the types of cakes section | Works as expected |

**Returning User**

4. I want to know what type of flavour cakes that are made at the bakery

| Feature                            | Action                                                                       | Expected result                                 | Actual Result     |
|------------------------------------|------------------------------------------------------------------------------|-------------------------------------------------|-------------------|
| Most popular flavour cakes section | Navigate to the Home page, scroll down to most popular flavour cakes section | Locating the most popular flavour cakes section | Works as expected |

5. I want to follow the bakery on social media

| Feature               | Action                                                           | Expected result                                | Actual Result     |
|-----------------------|------------------------------------------------------------------|------------------------------------------------|-------------------|
| Footer:  Social Media | On any page, navigate to the footer, click on the Facebook icon  | Facebook opened in a new tab in users browser  | Works as expected |
| Footer:  Social Media | On any page, navigate to the footer, click on the Instagram icon | Instagram opened in a new tab in users browser | Works as expected |
| Footer:  Social Media | On any page, navigate to the footer, click on the YouTube icon   | YouTube opened in a new tab in users browser   | Works as expected |
| Footer:  Social Media | On any page, navigate to the footer, click on the Twitter icon   | Twitter opened in a new tab in users browser   | Works as expected |

6. I want to be able to see samples of cakes that have been created

| Feature               | Action                                                                                         | Expected result               | Actual Result     |
|-----------------------|------------------------------------------------------------------------------------------------|-------------------------------|-------------------|
| Gallery Page          | On any page click on the Gallery link in the Navigation bar                                    | Find pictures of sample cakes | Works as expected |
| Gallery Page          | On any page click on the Gallery link in the footer                                            | Find pictures of sample cakes | Works as expected |
| Type of Cakes section | Navigate to the Home page, scroll down to types of cakes section, click on the view more links | Find pictures of sample cakes | Works as expected |

## Deployment
### Project creation
This project was created by using the [Code Institute Template](https://github.com/Code-Institute-Org/gitpod-full-template) in github. Gitpod was used to write the code and push the code to repository created in github.

The git commands I used to push the code from gitpod to github were

`git add .` - This command was used to add the file(s) to the staging area before they are committed.

`git commit -m “commit message”` - This command was used to commit changes to the local repository queue ready for the final step.

`git push` - This command was used to push all committed code to the remote repository on github.

### Deployment to Github Pages
The site was deployed to GitHub pages. The steps to deploy are as follows:
*   In the GitHub repository, navigate to the Settings tab
*   From the menu on left select *pages*
*   From the source section drop-down menu, select the Branch: main
*   Click the *save* button
*   A live link will be displayed in a green banner when published successfully.

View the [Live site](https://michelleconville.github.io/bakery-lane/index.html)


## Technologies Used
**Languages Used**
*   HTML
The structure of the Website was developed using HTML as the main language.
*   CSS
The website was styled using custom CSS in an external file.

**Programs Used**
*   GitHub
Source code is hosted on GitHub and delpoyed using Git Pages.
*   Gitpod
Used to commit and push code during the development of the website
*   Font Awesome
Icons were obtained from [Font Awesome](https://fontawesome.com/) and used for logo image and the Social media icons in the footer.
*   Photoshop
Images used throughout the website were modified using Adobe Photoshop
*   Favicon.io
THe favicon files were created at https://favicon.io/favicon-converter/
*   Balsamiq
Wireframes were created using Balsamiq
*   Techsini.com
Used to generate the website mockups



## Credits