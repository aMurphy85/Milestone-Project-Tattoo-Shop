# __METAMORPHOSIS TATTOO STUDIO OF TIVERTON__

A local Tattoo shop wanted to upgrade there current webpage to increase client base, by providing better visual 
representationthat not only showcases the art work the shop have done but to also capture your attention as soon
as you open the webpage, making the client want to re-visit the site and tell others to visit it for there tattoos
too.

## __UX__

### __User Stories__

- As a new user to the website, I want to be able to navigate through the site easily and find what I need effieciantly.

- As a new user to the site, I want to be able to find the *gallery* easily, find the particular style of tattoo I'm thinking
  getting, look at the images clearly to help me with my own design/ ideas.

- As a potential customer, I want to know about the history of the studio and that the artist is qualified, competent
  and follows the UK Health & Saftey current standards.

- As a potential customer, I want to know about other customer experiences using the studio and artist to give me 
  confidence to use the studio myself.

- As a potential customer, I want to be able to contact the studio easily, get a swift response on price range to compare 
  with competitors and check I can afford to have the work done, also about any general information I might not know about
  fully and booking time slots to have the work done.

- As a potential customer, I would like to be able to follow the studio on social media websites for any updates on deals they
  might be offering and recent news.

- As a returning customer, I want to be able to quickly contact the studio on booking me in for my next stage of my tattoo work
  or on my new art work i would like next.

### __Wireframe mockups__

- ![Home]()
- ![Gallery]()
- ![Contact Us]()

## __Features__

- __Navigation bar__ holds the title of the shop and links to the gallery and contact page in the top right corner, that is constant 
across all of them which follows users as you scroll down the page making swapping between pages much easier and quicker. The navigation 
links change from text to a burger icon for a dropdown menu of the links on smaller devices.

- __Hero-image__ is very large and very eye catching image of the shop owner tattoing a customer. Taking up most of the 
viewport as you open the webpage making it clear what the website is about. It is the same for the gallery page but the picture is
of a painting the shop owner has painted himself showing off his talents to the users.

- __About us__ section gives a background story into the shop and Sam the shop owner. The shop logo (branding) is used to help make
the shop more recognisable. 

- __Recent work__ section is images showcasing a number of different tattoos, in different styles and themes to help users/ potential 
clients see the quality of work the shop do and to help users/ clients see options they can use for there own designs.

- __Testimonials__ section has comments from previous and current customers that have had great experiences getting there tattoos 
from Sam at his shop. This could help anyone who is unsure/ undecided on whether to get there tattoo from here or someone else.

- __Footer__ holds links to social network websites facebook and instagram that users to the site can click on and view more stuff 
the shop has posted like images or even deals on tattoos etc. This is also constant across all the pages making them easier to
access.

- __Gallery__ has multiple sub-headings of different tattoo style names Sam carries out and showcases a number of those images in
that particular style.

- __Contact page__ has general contact information like the address, phone number, email address and opening times. There is a 
simple form the user can fill out and send off to the shop to get a price guide or ask about any general enquiry they may have.

### __Existing Features__

### __In the furture I would like to implement the following features__

1. A banner advertising gift cards and after care products the studio offer.

2. Animation to the hero image to capture users attention and so the site isnt so static.

3. A more attractive grid system to display the images.

4. Showcase more styles of tattoos, larger gallery.

5. Have a more interactive gallery, where you would need to click on the style of tattoo sub-heading which would open 
    the images inside.

6. Be able to look at a picture closer by getting an enlarged view of the image once you have clicked on it.

7. have more customer testimonials scrolling accross the screen.

8. In the form add a upload section so customers can send there own designs or images they have found to the studio
    for more accurate pricing and to be worked on to make them more unique.

9. A search input so you can find what you are looking for on the site wuicker like certain style of tattoos or contact form.

## __Technologies Used__

- [BootStrap](https://getbootstrap.com/docs/4.1/content/tables/)

    - **Bootstrap classes** to make elements responsive to different screen devices.

- [Font Awesome](https://fontawesome.com/)

    - **Font awesome** was used in the webpage to make links to external social media links clearer for the users.

- [Google Fonts](https://fonts.google.com/)

    - **Google fonts** was used for the font of the website.

## __Testing__

1. __Navbar links Desktop__

    1. From the "Home" page click on the "Gallery" page link
         verify that you navigate to the "Gallery" page of the site.

    2. From the "Gallery" page click on the "Home" page link
         verify that you navigate back to the "Home" page of the site.

    3. From the "Home" page click on the "Contact Us" page link
         verify that you navigate to the "Contact Us" page of the site.

    4. From the "Contact Us" page click on the "Home" page link
         verify that you navigate back to the "Home" page of the site.

    5. From the "Gallery" page click on the "Conatact Us" page link
         verify that you navigate to the "Contact Us" page of the site.

    6. From the "Contact Us" page click on the "Gallery" page link
         verify that you navigate to the "Gallery" page of the site.

    7. From the "Home" page click on the *Metamorphosis Tattoo Studio Tiverton* branding
         verify that you navigate back to the top of the home page.

    8. From both the "Gallery" page and the "Contact Us" page click on the *Metamorphosis Tattoo Studio Tiverton* branding
         verify that navigate back to the home page.

2. __Footer socials icon links__

    1. Hover over "Instagram" and "Facebook" Font Awesome icons with mouse cursor
         verify the icons fade in to a deep red colour from there static grey colour.

    2. Click on the Font Awesome icons
         verify you navigate to the respective social networking platforms assosiated with the *Metamorphosis Tattoo Studio Tiverton* pages.

    3. Repeat above process across the "Home" page, "Gallery" page and the "Contact Us" page
         verify the links work from all 3 pages.

5. __Contact Us form__

    1. Go to "Contact Us" page.

    2. Try to submit an empty form
        verify that an error message for required fields appears.

    3. Submit complete form
        verify the form was successfully sent.

## __Bugs__

### __Solved bugs__

1. __Hero image,__
    - My original image I was planning on using wouldn't stretch the full width of the container width.
    - I tried using css styling like the following but the image would not fill the whole space.

        * #hero-image {
        * height: 600px;
        * width: 100%;
        * background: url("../images/main-image.jpeg");
        * background-position: center;
        * background-repeat: no-repeat;
        * background-size: cover;
        * }

    - After contacting the slack community and the Code Institute tutors, I realised the image sizing was the problem.
    - To solve this issue I had to find a larger image.

2. __Contact form,__
    - I used the the bootstrap classes to input my contact form at first which was fine and worked an aligned central to the page.
    - Once i added some css styling to the elements to make it my own the form would only align to the left of the page.
    - To solve this bug I decided to write out my own form from scratch and add the bootstrap classes i wanted after.

3. __Navbar toggler icon,__
    - On desktop viewport the navbar looks as intended, but when I inspected the page on a smaller device my nav links didn't change
    to a burger icon like I wanted.
    - To solve this I watched youtube videos and google searches to find correct bootstrap class inputs.
    * [bootstrap Navbar](https://getbootstrap.com/docs/4.0/components/navbar/)
    * [stack overflow](https://stackoverflow.com/questions/42586729/bootstrap-4-change-hamburger-toggler-color)

4. __Images (recent work & gallery),__
 - 

### __Unsolved bugs__

1. __Contact form email input,__
    - While testing the contact form I noticed that I would get a input required message if no email address was entered, but 
    do not get an error message if the email has been entered incorrectly (i.e. murv121@hotmial.co.uk) didn't pick up that the "a" and 
    the "i" were the wrong way round.
    - I have tried to find the solution to this on bootstrap and google but unable to find one that worked.

2. __Navbar dropdown menu,__
    - Once I had solved the burger icon on smaller devices issue I noticed that when clicked on I didn't have a dropdown menu to
    select my nav link.
    - I have been using bootstrap to find the correct class inputs to solve this but haven't found the right one thats works.

3. __Colour scheme of website,__
    - I intended on using the colours in the shop logo but after a couple reviews I was informed that it affected the UX.
    - To solve this I decided to use one colour throughout the website and use a bit of the red to breakup sections of the site.

4. __Footer,__
    - Information overload in the footer with the opening times and contact info.
    - As this information was going to be repeated on the *Contact Us* page I decided to only put the social links, making the UX 
    more pleasing.

## __Deployment__


## __Credits__


### __Content__

- The content for the *testimonial* was copied from the 
[Metamorphosis tattoo & piercing shop webpage](https://metamorphosis-tattoo-and-piercing.business.site/)

### __Media__

- The photos used in this project website were obtained directly from the owner of the tattoo shop via email and from his facebook 
page [Metamorphosis tattoo & piercing shop Facebook page](https://www.facebook.com/Metamorphosis-tattoo-piercing-studio-204114539734458)

### __Acknowledgements__