# Llandudno Art Club

Llandudno Art Club website is designed to attract people of different ages interested in art. The club is situated in Llandudno, North Wales. It offers art classes to children of different age groups as well as adults and individual lessons. The classes are held in Craig y Don community centre. 

The club also offers various birthday party packages with an art theme (painting, drawing, sculpture, arts and crafts). Birthday parties are held either in the community centre or at the venue of the customers' choice.   

![Responsive Mockup](assets/images/light-lime.jpg)

## Wireframes

index.html 

![Index Wireframe](documentation/wireframes/home-page.png)

gallery.html 

![Index Wireframe](documentation/wireframes/gallery-page.png)

form.html 

![Index Wireframe](documentation/wireframes/contact-page.png)


## Features 

### Existing Features

- __Navigation Bar__

  The navigation bar is fully responsive. It is split into two parts. The first part includes links for three pages: Home, Gallery and Contact which are identical and responsive on each page. The second part is included only on the Home page and links a choice of classes to their descriptions which are situated on the Home page.

![Nav Bar](documentation/testing/nav-bar.jpg)

- __The landing page image__

  - The landing page offers the choice of art classes available at the Llandudno Club.

![Landing Page](documentation/testing/landing-page.jpg)

- __Timetable Section__

  - The timetable section provides the timetable for the diffrernt age art classes.

![Timetable](documentation/testing/classes.png)

- __Map section__

  - This section shows the users the location of the community centre where the classes take place. 

  
![Timetable](documentation/testing/map.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for the Art Club. The links will open to a new tab to allow easy navigation for the user. 
  

![Footer](documentation/testing/footer.png)

- __Gallery__

  - The gallery contains the pictures of the children's and alults' art created during the lessons in the club.

![Gallery]()

- __The Contact Page__  

  On the Contact page the users can submit their name and email address and select the classes in which they are interested.

![Sign Up](documentation/testing/contact.png)


### Features Left to Implement

- Pricing for the classes and birthday parties will be included soon.
- The club also has an idea for the future to sell art created by the members (children and adults) if anyone is interested.
- Separate page for the members to log in and view photos, club members' events, blogs.
- Make the web-site bi-lingual English/Welsh

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://olenaden.github.io/llandudno-art-club/index.html


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The content for the Home page is made up.

-  The building of the website was based on the learning outcome using Code Institute Programme. 

- Specific codes copied from Love Running: 
#photo {
    clear: both;
    line-height: 0;
    column-count: 4;
    column-gap: 0px;

#photo img{
    width: 100%;
}


- Copied from Runnable example CSS-CC-46-complete. Coders Coffeehouse Final code.
    text-align: center;
    width: 100%;
    position: fixed;
    bottom: 0;
    right: 0;
    z-index: 3;

- The code was copied to add br between two nav bars: https://stackoverflow.com/questions/899252/can-you-target-br-with-css

br
{   content: "A" !important;
    display: block !important;
    margin-bottom: 1.5em !important;
}

- The code was copied for 'back to top' https://codepen.io/daveyjh/pen/GRMmqOO

<a href="#top" id="back-to-top"></a> 
#top {
  position: absolute;
  top: 0;
- The icons in the navigation bar and the footer were taken from [Font Awesome](https://fontawesome.com/)

- Media query was copied from Love Running:

/* For small screens sizes from 800px wide and down */
@media screen and (max-width: 800px){
    #photo{
        column-count: 2;
    }
}
}

- Love Running README boilerplate was used for the README

### Media

- The photo used on the Home page is taken from https://pixabay.com/photos/painting-pencils-paint-pens-911804/
- The background image used on all three pages is taken from https://pixabay.com/illustrations/background-texture-abstract-art-6556409/. The image was modified to slightly lighter version.
- The images used for the Gallery page are the author's family and friends' creations.



