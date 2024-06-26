# Nabi Book Club
## A website built for the Nabi Book Club, dedicated mostly to korean literature.
This book club is dedicated to reading and discussing about Korean literature translated into English. We have monthly picks and at the end of the month we talk about our thoughts on our Discord server. Our picks vary between recent releases and older books, following the mood of the members throughout the year. The club is hosted by Elisa Biagiarelli. On her Instagram profile you can find a lot of recommendations on Korean and Asian literature, live talks with translators, movie reviews and much more.
![preview of Nabi Book Club site in different devices](https://i.ibb.co/Zc5THBY/nabibookclubmockupimage.png)
### [Live site](https://biagiarelliadriano.github.io/BookClub/index.html)
### [Repository](https://github.com/BiagiarelliAdriano/BookClub)
## Features

### Existing Features

 - Navigation Bar
	 - Featured on both the Home page and the Contact Us page, the full responsive navigation bar includes links to the Home page, the About Us section, the Sign Up section and the Contact Us page and this section is fixed to the top of the page for easy navigation.
	 - This section will allow the user to easily navigate from section to section of the Home page and from the Home page to the Contact Us page across all devicecs without having to revert back to the previous page via the back button.
	 - This section has visual response in the terms on hovering effects on desktop for a better user experience.

![the nabi book club navigation bar](https://i.ibb.co/JBrprVm/nabibookclubnav.png)

 - Hero Section
	 - The Hero section introduces the user to Nabi Book Club with an image with vibrant colors and text overlay to immediately know what the page is about.

![the nabi book club hero section](https://i.ibb.co/c6FRYGr/nabibookclubhero.png)

 - About Us Section
	 - The About Us describes to the user what Nabi Book Club is and what they will find once they join.
	 - This section also includes some examples of what type of books people are going to read in this book club, including descriptions of the books and images of the cover of the books.

![the nabi book club about us section](https://i.ibb.co/k8rvXLk/nabibookclubaboutus.png)

![the nabi book club book examples](https://i.ibb.co/8M0qPXt/nabibookclubbooksexamples.png)

 - Sign Up Section
	 - This Sign Up section will allow the user to get signed up to Nabi Book Club to start exploring Korean literature together with the community. The user will be able to share what their favorite book is and what genre of books they are more interested in. The user will be asked to submit their full name and email address.

![the nabi book club sign up section](https://i.ibb.co/5hQXYYT/nabibookclubsignup.png)

 - The Footer
	 - The Footer section includes links to the relevant social media sites for Nabi Book Club. It includes Nabi Book Club Instagram profile, Nabi Book Club Discord Server and Elisa Biagiarelli's Instagram profile, the host of Nabi Book Club. The links will open to a new tab to allow easy navigation for the user.
	 - The Footer is valuable to the user as it encourages them to keep connected via social media.
	 - This section also has visual response in the terms on hovering effects on desktop for a better user experience.

![the nabi book club footer section](https://i.ibb.co/HtdbLSy/nabibookclubfooter.png)

 - The Contact Us page
	 - This page includes an introductory image to Nabi Book Club 2024 with text overlay explaining what to do to contact the host and members of Nabi Book Club.
	 - In this page the user will more easily be welcomed to the footer, which will be directly in sight for them.

![the nabi book club contact us page](https://i.ibb.co/q5C4FV9/nabibookclubcontactus.png)

### Features To Implement In The Future

 - When interacting with the navbar items, instead of directly appearing in the selected section, the page will scroll through the page and stop once it reaches the selected section. It will be a smoother and overall better user experience.
 - Add more book examples, with even a top 10 book recommendation to get into the Korean literature.

## Technology Used
### Html
Used to structure the webpages and the bones of any web project.
### CSS
Used to style and add layout to the project.
### Font Awesome
Used for all the icons in the project.
### GoogleFonts
Used for all the fonts used in the project and to compare potential fonts.
### TinyPNG
Used to optimize and compress images to reduce size and improve web loading speed.
### ImgBB
Used to add images to the Readme file.

### Testing for links and Sign Up
| Feature | Test Method | Expectation | Outcome |
|---|---|---|---|
| Logo text Nabi Book Club brings the user to the main page | Click on Nabi Book Club in the navigation bar | If the user is already within the main page, the page simply reloads. If not, the main page will be loaded.| Pass |
| About Us element on navigation bar brings the user view to the About Us section of the main page | Click on About Us in the navigation bar | Directly moves the view of the user to the About Us section | Pass |
| Sign Up element on navigation bar brings the user view to the Sign Up section of the main page | Click on Sign Up in the navigation bar | Directly moves the view of the user to the Sign Up section | Pass |
| Contact Us element in the navigation bar opens the Contact Us page | Click on Contact us in the navigation bar | The user is directly brough in the Contact Us page opening in a new tab and keeping the main page open | Pass |
| Sign Up section lets users sign up by giving only essential informations to join the Nabi Book Club, without being able to provide bad data | Omit data from one or multiple sections, try to submit data only containing spaces and not actual writing, try to omit the @ symbol in the email section | Users can only submit when all the required sections are compiled with actual formatting for the text and email sections | Pass |
| Footer elements will open up in a new tab the correct links connected to Nabi Book Club Instagram profile, Nabi Book Club Discord Server and Elisa Biagiarelli's Instagram profile | Click on the Footer elements with the icons | Opens in a new tab the correct page connected to the correct links of the Footer | Pass |

## Google Lighthouse Testing

### index.html
![google lighthouse test for main page](https://i.ibb.co/Fz427GL/indexhtmllighthousetest.png)

The Performance score is due to the size of the Hero background image.

### contactus.html
![google lighthouse test for contact us page](https://i.ibb.co/gwxtrZJ/contactuslighthousetest.png)

## HTML Validation
### index.html
![html validation for index.html](https://i.ibb.co/ySzx3X4/htmlvalidatortest.png)
**Result: No Errors**

### contactus.html
![html validation for contactus.html](https://i.ibb.co/GP0s5xX/contactushtmlvalidation.png)
**Result: No Errors**

## CSS Validation
![css validation](https://i.ibb.co/FX9dDg0/cssvalidation.png)
**Result: No Errors**

## Bugs

 - Issue with Navigation Bar color background overlapping Main Content. **fixed**
 - Issue with Favicons in Footer elements not centering correctly. **fixed**
 - Issues with images for the book examples in the About Us section not going correctly to the side of the text. **fixed**
 - Image not in correct aspect ratio for the Contact Us page. **fixed**

## Deployment
To deploy the project I followed these steps starting from the main project repository [here](https://github.com/BiagiarelliAdriano/BookClub).

 1. Clicked on `Settings` on the navigation menu in the repository.
 2. I then selected the `Pages` menu on the side bar.
 3. In the first dropdown menu labeled `Source` I selected the branch of the name `main` from the dropdown.
 4. In the next dropdown labeled `/root` I left as the default option.
 5. Selected Save.

I then received a notification from GitHub that my project is being deployed and after about 1 minute and a couple of refreshes of the page, it was ready and live.

## Credits
### All images were made by Elisa Biagiarelli. Links for available images included below

hero: Photo by Elisa Biagiarelli <br>
the magical language of others: (https://www.instagram.com/p/CN7yihGHFzN/) <br>
in limbo: (https://www.instagram.com/p/C6TSNGSt-Kw/) <br>
contact us page background: (https://www.instagram.com/p/C1kBrwQouqD/)

## Content & Resources
### Elisa Biagiarelli's Instagram
Images used in this project.
### W3 Schools
Instructions on how to implement input pattern attribute for the Sign Up form.
### W3C Markup Validation Service
Used to validate HTML code.
### W3C CSS Validation Service
Used to validate CSS code.
### StackEdit
Used to write Readme file.
### ChatGPT
For general instructions on how to position images next to text with CSS.
### Code Institute
Project created in line with course content and within project 1 scope. Using some of the code instructed in the Love Running Project Walkthrough.

## Acknowledgments
### Elisa Biagiarelli
For allowing her images to be used, to allow the project to be based on her Book Club and for all the support.
### Alan Bushell
My mentor who provided me with constructive feedback and positive reinforcement where applicable.
### My parents
For always believing and supporting me in all that I do.
