# Llandudno Art Club

Llandudno Art Club website is designed to attract children and adults who are interested in art. The club is located in Llandudno, North Wales. It offers art classes to children of different age groups as well as adults and individual lessons. The classes are held in Craig y Don community centre. 

Introducing potential members to the facilities and courses available at the club and offering a variety of art classes for children of different age groups, in addition to adult lessons and individual tuition.

The club also offers various birthday party packages with an art theme (painting, drawing, sculpture, arts and crafts). Birthday parties are held either in the community centre or at the venue of the customers' choice.   

![Responsive Mockup](documentation/testing/ami-responsive.png)

## User Stories

- As a **first time visitor** I want to be able to find information about art casses available in Llandudno. I also want to know if there is a possibility of organising a birthday party with an art theme.

- As a **returning visitor** I want to be a able to check the timetable for classes. 


## UX

### Colour Scheme 

- The background colours of the website are pastel colours. 

![Llandudno Art Club Colour Palette](documentation/testing/background-colours.png)

- The colours of the font are mostly shades of orange and brown.

![Llandudno Art Club text colours](documentation/testing/text-colours.png)

The colour palettes were created using the [Coolors](https://coolors.co/) website. 


### Typography 

Google Fonts "Artifika" was used throughout the website. 


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

  The navigation bar is fully responsive. It is split into two parts. The first part includes links for three pages: Home, Gallery and Contact which are identical and responsive on each page. The second part is included only on the Home page and links a choice of classes to their descriptions situated on the Home page.

![Nav Bar](documentation/testing/nav-bar.jpg)

- __The landing page image__

  - The landing page offers the choice of art classes available at the Llandudno Club.

![Landing Page](documentation/testing/landing-page.jpg)

- __Timetable Section__

  - The timetable section provides the timetable for all the art classes available at the club. There is also a brief overview of the birthday parties options. 

![Timetable](documentation/testing/classes.png)

- __Map section__

  - This section shows the users the location of the community centre where the classes take place. 

  
![Timetable](documentation/testing/map.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for the Art Club. The links will open to a new tab to allow easy navigation for the user. 
  

![Footer](documentation/testing/footer.png)

- __Gallery__

  - The gallery contains the pictures of the children's and alults' art created during the lessons in the club.

![Gallery](documentation/testing/gallery-page.png)

- __The Contact Page__  

  On the Contact page the users can submit their name and email address and select the classes in which they are interested.

![Sign Up](documentation/testing/contact.png)


### Features Left to Implement

- Create a logo of the club.
- Pricing for the classes and birthday parties will be included soon.
- The club also has an idea for the future to sell art created by the members (children and adults) if anyone is interested.
- Separate page for the members to log in and view photos, club members' events, blogs.
- Make the web-site bi-lingual English/Welsh.

## Technologies Used 

The following technologies were used to create and test the website:

- HTML - HyperText Markup Language to create the structure of the website content.  
- CSS - Cascading Style Sheet Language to provide style to the website.
- [Balsamiq](https://balsamiq.cloud)
- [TinyPNG](https://tinypng.com)
- Gitpod - cloud based Integrated Developement Environment. 
- GitHub - provider for software development to store files.
- Git - version control system.
- [Coolors](https://coolors.co/d9912f-6d4712-ffa500-484738-e1f8d4) - Colour generator for the website used for README.md.
- [Google fonts](https://fonts.google.com/) Google fonts used throughout the website.
- [Font awesome](https://fontawesome.com/v6.0/icons) - Icons used for navigation, footer, "back to top" 
- Google Dev Tools - Development Tools to resolve issues with responsiveness and styling.
- [Favicon.io](https://favicon.io/) - Favicon creator.
- [Am I Responsive?](http://ami.responsivedesign.is/) - used to show the website landing page responsiveness on different devices.
- [README Markdownguide](https://www.markdownguide.org/cheat-sheet/) - tips for creation of README.md
- [CSS Jigsaw](https://jigsaw.w3.org/css-validator/)
- [HTML Vallidator](https://validator.w3.org/)
- [Squoosh](https://squoosh.app/) - Image compressor.

## Testing

To view all testing documentation please refer to [TESTING.md](TESTING.md)

## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the [GitHub repository](https://github.com/OlenaDen/llandudno-art-club), navigate to the Settings tab 
  - From the source section drop-down menu, select the **Main** Branch, then click "Save".
  - The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://olenaden.github.io/llandudno-art-club)

### Local Deployment

In order to make a local copy of this project, you can clone it. In your IDE Terminal, type the following command to clone my repository:

- `git clone https://github.com/OlenaDen/llandudno-art-club.git`

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/OlenaDen/llandudno-art-club)

## Credits 

### Content 

- The content for the website was invented.

- The building of the website was based on the learning outcome from Code Institute Programme. 

- The icons in the navigation bar and the footer were taken from [Font Awesome](https://fontawesome.com/)

- The favicon in the browser was taken from [Favicon](https://favicon.io/favicon-generator/)

- Part of the code was copied from Love Running to style images: 

```css
#photo {
    clear: both;
    line-height: 0;
    column-count: 4;
    column-gap: 0px;

#photo img{
    width: 100%;
}
```

- Part of the code copied from Runnable example CSS-CC-46-complete to style the footer. 

```css
    text-align: center;
    width: 100%;
    position: fixed;
    bottom: 0;
    right: 0;
    z-index: 3;
```

- The 'back to top' code was copied for from [Dave Horrocks](https://codepen.io/daveyjh/pen/GRMmqOO)

```css

<a href="#top" id="back-to-top"></a> 
#top {
  position: absolute;
  top: 0;
  ```

- Media query was copied from Love Running:

```css

/* For small screens sizes from 800px wide and down */
@media screen and (max-width: 800px){
    #photo{
        column-count: 2;
    }
}
}
```
Copied from Code Institute for the Contact page:

```html

 <form action="https://formdump.codeinstitute.net" method="POST">
   ```


- Love Running README boilerplate was used for the README.md

### Media

- The photo used on the Home page is taken from [Pixabay](https://pixabay.com/photos/painting-pencils-paint-pens-911804/).

- The background image which was slightly modified to a lighter version and used on all three pages is taken from [Pixabay](https://pixabay.com/illustrations/background-texture-abstract-art-6556409/) 

- The images used for the Gallery page are the developer's family and friends' creations.

### Acknowledgements

I would like to acknowledge the following people in helping me to create the website:

1. Tim Nelson, my mentor, for guiding me and helping me throughout the project, especially making me comfortable using gitpod and giving me handy tips.
2. All the people in slack who took time and replied to my questions and to other people's messages which I found very useful to read.
3. Dave Horrocks, for helping me to understand DevTools better and explaining the semantics of html.
4. Suzy Bennett, for taking her time to look at the Lighthouse results in DevTools.
5. My friends who let me use their art creations.
6. Sydney Clarke, my friend, who edited the content of the website and part of README.md.



