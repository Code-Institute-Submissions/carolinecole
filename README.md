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
* A project I am excited about and is about to adapt and and content can be added to easily.
* A project I am passionate about and excited to add to my portfolio of work.
* Improve my skills as a developer and learn new exciting ideas and coding rules and langaues.


### User stories
* The ability to easily use and navigate the website.
* Relevant, interesting blog posts which leaves me wanting to come back for me.
* About page with information about the blogger and somewhere I can connect with her.
* A functing contact page, which allows me to contact the blog owner.
* Visual icons and images with functioning links to relevant webpages., making it easy to shop these products. 
* A section with functioning links to the blogger's social media accounts.

### Design Choices
* I designed this website to be a blog page which suits the blogger and her requirements which leaves the users wanting to come back for me. The following design choises were made with this in mind:

### Fonts
* I chose to use Questrial font from [Google Fonts]('https://fonts.googleapis.com/css2?family=Questrial&display=swap') in my project because it is simple, easy to read and stylish. Oringinally I wanted to use Montserrat font but I decided it was quite faint and not very easy to read so I changed to more of a solid font.

### Icons
* I chose to use the Twitter, Youtube and Instagram icons in my project with links to those pages from [Font awesome](https://fontawesome.com/).
* I chose to use teal buttons that appears when the image was hovered over. I added this to ensur the user is clear once the button is clicked it will take them elsewhere or open up another page.

### Colours
* I chose to keep the colours simple using black for fonts, a white background with a lovely teal footer and buttons for some added difference. Oringinally I wanted to do dark grey however I decided black stood out more, was easier to read and more user friendly.

### Backgrounds
* I chose to keep the backgrounds plain white because I will be adding images and I do not want it to look messy, or distract user from the page content. I added a lovely teal green to the heading line and footer to add some colour which I think suits the website and looks very chic.

### Images
* The images on my home page, about page and blog post pages have all been obtained from my personal archive of images. The shop page images have all been obtained from [H&M](https://www2.hm.com/en_gb/index.html) and [Net a Porter](https://www.net-a-porter.com/en-gb/)and a link has been added to these so my users can visit the page accordingly.

## Wireframes
These wireframes were created using Blasmiq during the Scope Plane part of my design and planning process.
* [Home page](assets/wireframes/home-page.pdf)
* [About page](assets/wireframes/about-page.pdf)
* [Shop page](assets/wireframes/shop-page.pdf)
* [Contact](assets/wireframes/contact-page.pdf)
* [Five ways to get through lockdown!](assets/wireframes/blog-page.pdf)
* [How to style Mom jeans!](assets/wireframes/blog2-page.pdf)
* [Guide to buying the perfect sportwear!](assets/wireframes/blog3-page.pdf)

## Technologies Used
* [Google Fonts](https://https://fonts.google.com/) has been used for my.
* [Font awesome](https://fontawesome.com/) has been used for my social media links in my header and footer.
* [Hover.CSS](https://ianlunn.github.io/Hover/) has been used for my menu bar hover.
* [CDNJS](https://cdnjs.com/libraries?q=hover) has been used for my menu bar hover.
* [Bootstrap](https://getbootstrap.com/docs/5.0/layout/grid/) has been used throughout my project.
* [Bootstrap](https://getbootstrap.com/docs/4.2/getting-started/introduction/#js)

## Testing
1. [W3 HTML validator](https://validator.w3.org/) validation came up with a few amendments I have added below:
    * I needed to remove the ``` autocomplete="off" ``` attribute and added in the ``` role="button" ``` attribute on my shop page and home page.
``` <a href="how-to-style-mom-jeans.html" class="btn btn-primary btn-shop blog-post-link" aria-pressed="false" autocomplete="off">Link to product</a> ```
    * I needed to change the ``` aria-controls=navbarSupportedContent ``` to ``` aria-controls="main-navbar" ``` so it targeted a nav in my document.
```<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#main-navbar" aria-controls="main-navbar" aria-expanded="false" aria-label="Toggle navigation"> ```
2. [W3C CSS validator](https://jigsaw.w3.org/css-validator/validator) found no error attached for ref [CSS Testing](assets/testing/css-testing.png)
3. [HTML validator](https://validator.w3.org/#validate_by_input) found no errors attached for ref [HTML Testint](assets/testing/html-testing.png)
4. [Lighthouse](https://web.dev/performance-scoring/) for each page:
    * Index page orginially got a lower perfomance rating that I hoped [lighthouse before amendments](assets/testing/lighthouse-index.png) I commented out the script links I was not using at the bottom of the page and reduced the size of my images which I then amended on every page and I am now very happy with my [Lighthouse after amendments](assets/testing/lighthouse-index-new.png).
    * About page originally got [Lighthouse before amendments](assets/testing/lighthouse-about.png) I amended the size of my image and adjusted the shape [Lighthouse after amendments](assets/testing/lighthouse-about-new.png).
    * Shop page originally got [Lighthouse before amendments](assets/testing/lighthouse-shop.png) I change the CSS code for the image size to have a width of auto which increased the best practice by 10. Then I needed to increase the resolution of my first image and I am now happy with what lighthouse is showing [Lighthouse after amendments](assets/testing/lighthouse-shop-new).
    * Contact page originally got [Lighthouse before amendments](assets/testing/lighthouse-contact.png). Once I have a fully functioning form I would hope this will improve.
    * Blog pages originally got [Lighthouse before amendments](assets/testing/lighthouse-blog.png). I commented out the ```<script>``` links I did not require at this moment and amended the image sizes slightly [Lighthouse after amendments](assets/testing/lighthouse-shop-new.png).

## Testing client stories from UX section of README.md
1. As a new visitor to the website, I want to easily use and navigate the website.
    * Every page the user visits, they can easliy find and use the navigation bar.
    * The footer has a link back to the home page.
    * The home page has further links when an image is hovered over to my blog posts.
    * The shop page is easy to navigate with a button to select linking to the website of the product.
    * There is a subscribe button at the for users to subscribe so they do not miss out.

2. As a new user to the website, I want to see relevant, interesting blog posts which leaves me wanting to come back for me.
    * The blog posts are featured on the home page with links to each blog when hovered over.
    * This page is designed to be added to new with relevant blog posts, so it will be continually evolving.
    * Blog posts are about relevant topics.

3. As a new user to the website, I would like an about page with information about the blogger.
    * A clearly labelled About page which is easy to navigate to and around.
    * An image of the the blogger and a message from her which is informally and very welcoming leaves me wanting to know more and visit her other social media accounts.

4. As a new user to the website, I want a contact page, which allows me to connect with her.
    * A clearly labelled contact page which is easy to navigate.

5. Visual icons and images with functioning links to relevant webpages, making it easy to shop these products. 
    * A good amount of images and easy to navigate around the images and sections.
    * Images when hovered over has a button to allow the user to know what she is selecting and where they are being taken to.
    * Links to the relevant websites are fully functioning.

6. A section with functioning links to the blogger's social media accounts.
    * The footer contains links to instagram and youtube pages.
    * This is easy to find and locate. 

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
9. Once selected my navbar was jumping, to stop this from happening I removed the html code ```<a class="navbar-brand" href="#"></a>``` aftering reviewing my code on dev tools and speaking with tutor support.


## Deployment

To deploy this page to GitHub Pages from its GitHub repository, the following steps were taken:
1. Log into **Github**.
2. From the list of repositories on the screen, select **carolinecole**.
3. From the menu items near the top of the page, select **settings**.
4. Scroll down to the **Github Pages** section
5. Under source click the drop-down menu labelled **None** and selcted **master branch/ main**.
6. On selecting **master branch** a section drop-down will appear, select **root**.
7. Select **save**, it might take 5-10 minutes for Github to finish building the site the first time.
8. Refresh your **GitHub Pages** section to get the link to the deployed wesbite. 

## How to run this project locally 
To clone this project into Gitpod you will need:
1. A Github accoun [Github account](https://github.com/)
2. Use the Chrome browser.

Then follow these steps:
1. Install the [Gitpod Browser Extentions for Chrome](https://www.gitpod.io/docs/browser-extension/)
2. after installation, restart browser.
3. Log into [Gitpod](https://www.gitpod.io/) with your gitpod account.
4. Navigate to the [Porject Github Repository](https://github.com/carolinecole25/carolinecole)
5. Clear the green Gitpod button in the top right corner of the repository.
6. This will trigger a new gitpos workspace to be created from the code in github where you can work locally. 

To work on the project code within a local IDE such as VSCode, Pycharm:
1. Follow this link to the [Porject Github Repository](https://github.com/carolinecole25/carolinecole).
2. Under the repository name click **Clone / Download**.
3. In the clone with HTTPs section, copy the URL for the repository.
4. In your local IDE open the terminal.
5. Change the current working directory to the location you want the cloned directory to be.
6. Type git clone, and then paste the URL you copied.
7. select enter and your local clone will be created.

## Credits
### Code

#### HTML
* Code for rows 7-10 taken from [Code Institue](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/tree/master/18-resume-for-download) and edited slightly to fit projects needs.
* Code for row 11 from [Google Fonts](https://https://fonts.google.com/specimen/Montserrat?preview.text_type=custom&sidebar.open=true&selection.family=Montserrat:wght@100) and amended slightly to fit project. 
* Code for rows 18-24 taken from [Code Institue](hhttps://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/tree/master/18-resume-for-download) and edited slightly to fit projects needs.
* Code for menu bar rows 34-54 talken from [Code Institue](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/tree/master/18-resume-for-download) and edited slightly to fit projects needs.
* Code for hover button taken from [Boostrap](https://getbootstrap.com/)and edited slightly to fit projects needs.
* Code for rows 87-102 taken from [Code Institue](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/tree/master/18-resume-for-download) and edited to fit projects needs.
* Code for Youtube logo taken from [Font Awesome](https://fontawesome.com/icons/youtube?style=brands).
* Code for instagram logo taken from [Font Awesome](https://fontawesome.com/icons/instagram?style=brands).
* Code for rows 67-83 on about page taken from [w3schools](https://www.w3schools.com/html/html_images.asp) and amended to suit project.
* Code for contact page form taken from [Code Institue](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/tree/master/18-resume-for-download) and amended to fit project.
* Code for rows 67-105 on shop page images layout was taken from [Bootstrap](https://getbootstrap.com/docs/5.0/layout/grid/) and amended to fit projet.
* Code for buttons on shop page rows 67-105 was taken from [Boostrap](https://getbootstrap.com/docs/4.1/components/buttons/)
* Code for nav bar rows 56-80 taken from [Boostrap](https://getbootstrap.com/docs/4.1/components/navbar/) and amended to fit project.
* The scripts links taken from [Boostrap](https://getbootstrap.com/docs/4.2/getting-started/introduction/#js).
* Code for the for the subscribe button rows 18-42 take from [Bootstrap](https://getbootstrap.com/docs/4.0/components/modal/) and amended to fit project.
 
 #### CSS
* Code for the menu bar rows 88-95 which contained a bug was taken from [Code Institue](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/tree/master/18-resume-for-download) becuase the menu bar was displaying on 2 lines.  
* Code for the footer rows 230-257 taken from [Code Institue](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/tree/master/18-resume-for-download) and [Code Institue](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/b51f7b8b815c4bcd9979d2281b6d97a9/?child=first) and edited to fit projects needs.
* Code for about page image rows 125-139 taken from [stackoverflow](https://stackoverflow.com/questions/787839/resize-image-proportionally-with-css) and amended to fit project. 
* Code for to centralise about page image rows 125-132 taken from [w3schools](/* credit: code taken from https://www.w3schools.com/howto/howto_css_image_center.asp and amended to fit project */) and amended to fit project.
* Code for contact page rows 180-220 form taken from [Code Institue](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/tree/master/18-resume-for-download) and amended to fit project.
* Code for button to only appear when hovered over row 14-25 taken from [Stack Overflow](https://stackoverflow.com/questions/40891570/show-button-on-hover-only/40891870) and amended to fit project.


## Media
* The photos used on the 'Home' page were obtained from my own personal archive.
* The photos used on 'Shop' page were obtained from [H&M](https://www2.hm.com/en_gb/index.html) and [Net a Porter](https://www.net-a-porter.com/en-gb/).
* The logo for my footer were taken from [Font Awesome](https://fontawesome.com/).


## Acknowledgements
* The tutor support have helped my during this project to overcome some issues I have experience which I have documents in my code section. 