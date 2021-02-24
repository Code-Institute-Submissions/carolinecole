# Caroline Cole

I have designed this website inline with my Fashion Instagram account to give my followers and new users more. I want my website to be user friendly, innovative, fresh and elegant.
It will consist of 4 pages; home, about, shop and contact. 

## UX

### Project Goals

The primary goal for Caroline Cole is to provide a fresh and inovative website which leaves users coming back for more.
My target audience will be women ages between 20 and 40, and my followers on my Instagram account.  

User goals are:
* Blog posts about fashion, lifestyle, home and travel.
* My most recent Instagram posts.
* My most recent YouTube posts.
* A shop which has links to products websites on my wishlist, must buys or home.
* A visually appealing webiste, leaving users returning to my site.

Caroline Cole will meet users needs by:
* The website is styled around my instagram page to ensure the theme is consistant.
* The design process took the user requirments into account. 
* Includes links to websites I have talked about on my blog posts and shop page making this user friendly.
* All areas of the site are clearly layed out and easy to use.
* The overall feel of the site is simple yet elegant. 


### Developer and Business Goals 
* A professional website which is user friendly and stylist.
* A project I am excited about and is easy to add to.


### User stories
* The ability to easily use and navigate the website.
* Relevant, interesting blog posts which leaves me wanting to come back for me.
* A functing contact page, which allows me to contact the blog owner.
* Visual icons and images with functioning links to relevant webpages.
* A stylish, 


### Design Choices
* I designed this website to be 

### Fonts
I chose to use Questrial font from [Google Fonts]('https://fonts.googleapis.com/css2?family=Questrial&display=swap') in my project because it is simple, easy to read and stylish. Oringinally I wanted to use Montserrat font but I decided it was quite faint and not very easy to read so I changed to more of a solid font.

### Icons
I chose to use the Twitter, Youtube and Instagram icons in my project with links to those pages from [Font awesome](https://fontawesome.com/).

### Colours
I chose to keep the colours simple using black for fonts and a white background. Oringinally I wanted to do dark grey however I decided black stood out more, was easier to read and more user friendly.

### Backgrounds
I chose to keep the backgrounds plain white because I will be adding images and I do not want it to look messy, or distract user from the page content. I added a lovely teal green to the heading line and footer to add some colour which I think suits the website and looks very chic.

### Images
The images on my home page, about page and blog post pages have all been obtained from my personal archive of images. The shop page images have all been obtained from [H&M](https://www2.hm.com/en_gb/index.html) and [Net a Porter](https://www.net-a-porter.com/en-gb/)and a link has been added to these so my users can visit the page accordingly.

## Wireframes
These wireframes were created using Blasmiq during the Scope Plane part of my design and planning process.
* [Home page](assets/wireframes/home-page.pdf)
* [About page](assets/wireframes/about-page.pdf)
* [Shop page](assets/wireframes/shop-page.pdf)
* [Contact](assets/wireframes/contact-page.pdf)
* [Five ways to get through lockdown!](assets/wireframes/blog-page.pdf)
* [How to style Mom jeans!](assets/wireframes/blog2-page.pdf)
* [Guide to buying the perfect sportwear!](assets/wireframes/blog3-page.pdf)

## Features


### Existing Features



### Features Left to Implement



## Technologies Used
* [Google Fonts](https://https://fonts.google.com/) has been used for my.
* [Font awesome](https://fontawesome.com/) has been used for my social media links in my header and footer.
* [Hover.CSS](https://ianlunn.github.io/Hover/) has been used for my menu bar hover.
* [CDNJS](https://cdnjs.com/libraries?q=hover) has been used for my menu bar hover.
* [Bootstrap](https://getbootstrap.com/docs/5.0/layout/grid/) has been used throughout my project.
* [Bootstrap](https://getbootstrap.com/docs/4.2/getting-started/introduction/#js)

## Testing
* [W3 HTML validator](https://validator.w3.org/) validation came up with a few amendments I have added below:
1. I needed to remove the ``` autocomplete="off" ``` attribute and added in the ``` role="button" ``` attribute on my shop page and home page.
``` <a href="how-to-style-mom-jeans.html" class="btn btn-primary btn-shop blog-post-link" aria-pressed="false" autocomplete="off">Link to product</a> ```
2. I needed to change the ``` aria-controls=navbarSupportedContent ``` to ``` aria-controls="main-navbar" ``` so it targeted a nav in my document.
```<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#main-navbar" aria-controls="main-navbar" aria-expanded="false" aria-label="Toggle navigation"> ```
* [W3C CSS validator](https://jigsaw.w3.org/css-validator/validator) found no errors.

## Deployment

How to run this project locally


## Credits

### Bugs Discovered 
#### Solved bugs
1. The menu bar was showing on two lines instead of one, to fix this I used [Code Institue](this code was taken from https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/f99dac3afcfe4b2caf8d576273aea3e6/?child=first lesson to help fix this issue.
2. The menu bar was not centered to the page, it was positioned to the right of the page. To solve this I asked tutor support and I had a div taking up a huge section of the page so I removed the below code which I got from [Code Institue](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/f99dac3afcfe4b2caf8d576273aea3e6/?child=first):
    ```<div class="row no-gutters">
        <a href="index.html" class="col-md-4 logo"></a>
        <div class="col-md-8"> 
           <div class="row bg-color-name-title">
           ```
After amending this code, it menu bar still was not in the center of the page. I spent a while looking at my website on DevTools and selecting bit and eventually I added in the below code to CSS targeting the menu bar which has fixed the problem. 
    ```
    .menucontainer {
    font-size: 0px;
    text-align: center;
    } 
           ```
3. The font awesome social media icons I used did not load, after checking my links from font awesome I changed it slightly and it started working.
4. Image on my about page did not load, I used [w3schools](https://www.w3schools.com/html/html_images.asp) for coding tips and then asked tutor support. I had not added the full image link so amended this and it worked.
5. I wanted the buttons on my shop page to only appear when hovered over the image so the user can select to be taken to the website. I researched it and got the relevant code but reached out to Tutor Support as the button was not letting me select it. I had to amend the class I was selecting in CSS and this worked perfectly. 
6. The buttons for my shop page was underneath my images, I wanted these to be in the middle of my image. I contacted Tutor support to help me re-position these as it seemed to want to be placed towards one side of the image. Amendments were made to my code that enabled the image to be positioned in the middle of my image and it works exactly how I want it to now.
7. The navbar button was not functioning, I contacted tutor support and it was due to not having the ```<script> ```links at the bottom of my HTML file. Once this was added in it fuctioned properly.
8. Once I added in the script links to my webpage the links on my images stopped working. After using Dev tools and speaking to tutor support so realised it was the data-toggle="button" which seemed to blocking the href from working, once this has been removed it worked perfectly.
9. Once selected my navbar was jumping, to stop this from happening 

### Code

#### HTML
* Code for rows 7-10 taken from [Code Institue](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/ba5caa84354740b78b7f6c0bfa4d9286/?child=last) and edited slightly to fit projects needs.
* Code for row 11 from [Google Fonts](https://https://fonts.google.com/specimen/Montserrat?preview.text_type=custom&sidebar.open=true&selection.family=Montserrat:wght@100) and amended slightly to fit project. 
* Code for rows 18-24 taken from [Code Institue](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/f99dac3afcfe4b2caf8d576273aea3e6/?child=first) and edited slightly to fit projects needs.
* Code for menu bar rows 34-54 talken from [Code Institue](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/f99dac3afcfe4b2caf8d576273aea3e6/?child=first) and edited slightly to fit projects needs.
* Code for hover button taken from [Boostrap](https://getbootstrap.com/)and edited slightly to fit projects needs.
* Code for rows 87-102 taken from [Code Institue](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/b51f7b8b815c4bcd9979d2281b6d97a9/?child=first) and edited to fit projects needs.
* Code for Youtube logo taken from [Font Awesome](https://fontawesome.com/icons/youtube?style=brands).
* Code for instagram logo taken from [Font Awesome](https://fontawesome.com/icons/instagram?style=brands).
* Code for rows 67-83 on about page taken from [w3schools](https://www.w3schools.com/html/html_images.asp) and amended to suit project.
* Code for contact page form taken from [Code Institue](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/715392be2ba942abb1b6f9eaf566aed6/?child=first) and amended to fit project.
* Code for rows 67-105 on shop page images layout was taken from [Bootstrap](https://getbootstrap.com/docs/5.0/layout/grid/) and amended to fit projet.
* Code for buttons on shop page rows 67-105 was taken from [Boostrap](https://getbootstrap.com/docs/4.1/components/buttons/)
* Code for rows 30-35 taken from [Boostrap](https://getbootstrap.com/docs/4.1/components/navbar/) and amended to fit project.
* The scripts links taken from [Boostrap](https://getbootstrap.com/docs/4.2/getting-started/introduction/#js).

 #### CSS
* Code for the menu bar rows 82-84 which contained a bug was taken from [Code Institue](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/f99dac3afcfe4b2caf8d576273aea3e6/?child=first) becuase the menu bar was displaying on 2 lines.  
* Code for the footer rows 230-257 taken from [Code Institue](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/b51f7b8b815c4bcd9979d2281b6d97a9/?child=first) and [Code Institue](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/b51f7b8b815c4bcd9979d2281b6d97a9/?child=first) and edited to fit projects needs.
* Code for about page image rows 125-139 taken from [stackoverflow](https://stackoverflow.com/questions/787839/resize-image-proportionally-with-css) and amended to fit project. 
* Code for to centralise about page image rows 125-132 taken from [w3schools](/* credit: code taken from https://www.w3schools.com/howto/howto_css_image_center.asp and amended to fit project */) and amended to fit project.
* Code for contact page rows 162-196 form taken from [Code Institue](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/715392be2ba942abb1b6f9eaf566aed6/?child=first) and amended to fit project.
* Code for hover button row 14-25 from [Stack Overflow](https://stackoverflow.com/questions/40891570/show-button-on-hover-only/40891870) and amended to fit project.


## Media
* The photos used on the 'Home' page were obtained from my own personal archive.
* The photos used on 'Shop' page were obtained from [H&M](https://www2.hm.com/en_gb/index.html) and [Net a Porter](https://www.net-a-porter.com/en-gb/).
* The logo for my footer were taken from [Font Awesome](https://fontawesome.com/).


## Acknowledgements
* The tutor support have helped my during this project, whether it 