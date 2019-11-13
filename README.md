# Live.Love.Travel.
Code Institute -  User Centric Frontend Development Milestone Project

Welcome to my travel website where I showcase destinations from around the world along with some exciting and engaging stories from other explorers. 
On the site four places are highlighted and I share information on topics such as food, transport, accommodation, culture, climate and safety for each location.  


## Demo
Explore the site [here](https://lhynes.github.io/User-Centric-Frontend-Development-Milestone-Project/).

Desktop View
![Desktop View](https://raw.githubusercontent.com/lhynes/User-Centric-Frontend-Development-Milestone-Project/master/assets/images/desktopimage.png
"Desktop View")

## UX

### User stories

**External user’s goal:** 

Travel enthusiasts and explorers


As a travel fan and adventure seeker I want to learn more about travelling to cool and exciting travel destinations. 

As a female explorer I want to learn about someone elses travel story and share my own. 

As a social media enthusiast I want to be able to follow the jouney on the site and via social media channels.


**Site owner's goals:**

As a site owner I want to share my experience with people and hear about other travel adventures from peoples 

As a social person I want to connect with new people and share knowledge. 


### Strategy
My goal for this website was to make it clear and simple. Make information easy to access on all four destinations and all users to connect with me. 

### Scope
I wanted visitors to the site to know straight away what it was about and what informtion they could find there. 

### Structure
I wanted the structure to be very simple to enable users to make the minimum number of clicks to access the desired infomation. 

### Skeleton

[Homepage wireframe](https://github.com/lhynes/User-Centric-Frontend-Development-Milestone-Project/blob/master/wireframes/homepage.png)

[About me page wireframe](https://github.com/lhynes/User-Centric-Frontend-Development-Milestone-Project/blob/master/wireframes/aboutmepage.png)

[Destination page wireframe](https://github.com/lhynes/User-Centric-Frontend-Development-Milestone-Project/blob/master/wireframes/destinationpage.png)

[Travel stories page wireframe](https://github.com/lhynes/User-Centric-Frontend-Development-Milestone-Project/blob/master/wireframes/travelstoriespage.png)

### Surface
I chose a muted colour palette to ensure the images would take focus and not distract two much. I chose one accent colour for cards and buttons to empahise that content. 

## Technologies and Scripts

- [HTML](https://www.w3schools.com/html/html5_intro.asp)
    - The project uses **HTML5** for creating the website and leveraged it's semantic elements.

- [CSS3](https://www.w3schools.com/css/css_intro.asp)
    - The project uses **CSS3** for stlying elements of the page.
- [Bootstrap (4.3.1)](https://www.bootstrapcdn.com/)
    - The project uses **Bootstrap** framework to increase the efficiency of programming. 
- [Hover.css (2.3.1)](https://cdnjs.cloudflare.com/ajax/libs/hover.css/2.3.1/css/hover-min.css)
    - The project uses **hover.css** to support on hover elements.
- [Font Awesome (4.7.0)](https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css)
    - The project uses **Font Awesome** for icons. 
- [JQuery](https://jquery.com)
    - The project uses **JQuery** to support bootstrap navigation.

## Features

### Existing Features
This site currently contains the following features: 
- Showcases photos and information on a number of the travel destinations to motivate people to visit. 
- By clicking on each destination image from the homepages the user can learn more about that place. 
- Provides detail about the site owner. 
- Provide an option for people to submit stories to be featured on the site
- Provide links to external travel stories to help the reader learn about other destinations

### Features Left to Implement

In the future I would like the featured travel story to by populated dynamicaly from the collection of stories submitted via the website. 

I would also like to find the optimal way to share images on the site as they are such a key part of travel websites. 


## Testing

As part of my testing I reviewed the user stories I had set out in the UX sections above. 
The visitor to the site can review the destinations I've explored, see images related to them and find out key information points on each. 
The about me section offers the site visitor to find out about my passion for travel and the provides the option to the reader to ask me a question. 
Using the social media links in the footer they can also follow me on my journey

As the site owner I can share my information with the public on my favourite destinations, I can review stories from different people and I can start connecting with like minded people. 

**Site Responsiveness**

To ensure compatibility and responsiveness I tested the site on multiple browsers and devices. 

- **Browsers:**Chrome, Safari,FireFox

- **Devices:** In addition to testing responsivness with chrome inspector emulator tool I also asked people to test on four different devices: desktop, Samsung Galaxy, Google pixel 2 and Iphone10. 


**Contact Form**
There are two conact forms on the site one on the About Me page and one on the Travel Story Page.
If a site visitor is interested in contacting me or sharing a story they can fill out these forms by following the steps below: 


1. Contact form:
    1. Go to the "About Me" page
    2. Click the "Ask Me a Question" button
    3. Try to submit the empty form and verify that an error message about the required fields(name and email) appears
    4. Try to submit the form with an invalid email address and verify that a relevant error message appears
    5. Try to submit the form with all inputs valid and verify that a success message appears.

2. Contact form:
    1. Go to the "Travel Stories" page
    2. Click the "Share your story today" or "Share your story" button
    3. Try to submit the empty form and verify that an error message about the required fields(name and email) appears
    4. Try to submit the form with an invalid email address and verify that a relevant error message appears
    5. Try to submit the form with all inputs valid and verify that a success message appears.


**Page Links**
 
All links have been manually tested to ensure that none of them are broken and they point to the correct destination.


**Page Links**

All images have an assigned "alt" test attributed to them. 

**Code**

All HTML and CSS code was testing using the following code validators and returned without any errors
- [HTML](https://validator.w3.org/)
- [CSS](https://jigsaw.w3.org/css-validator/)

### Bugs and  problems

**Bootstrap**

I ran into some issue with the bootstrap framework but after some investigation and documentation reading all was resolved. 


**Images**

At first I was using high quality images that were very large in file size so I used an [online image compressor](https://compressjpeg.com/)) to compress images to enhance loading time. 
I'm still not 100% happy with the load time speed so this is something I will continue to work on. 

**CSS Duplication**

To remove CSS duplication for my hero images and four destination images I added an extra class to remove the duplicated css. 
 


## Deployment

This site is hosted using **GitHub pages** and deployed directly from the master branch.
To set up GitHub pages check out the following steps: 
- In GitHub, navigate to your <username>.github.io repository and click **Settings**.
- Within Settings, navigate to the **Source** section within the **Github Pages** section. 
- From the dropdown menu, select **master branch** and then click **Save**.

The sites landing page is  named `index.html` and this ensured thte site will deploy correctly on GitHub pages.
The deployed site version is updated automatically after new commits to the master branch. 


**Local deployment** 

To run locally, you can clone this repository directly into the editor of your choice by pasting 
`git clone https://github.com/lhynes/User-Centric-Frontend-Development-Milestone-Project.git` into your terminal. 

To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.



## Credits

### Content
- The text for the featured story content on the homepage was copied  [Hostel Geeks](https://hostelgeeks.com/machu-picchus-gigantic-aura-reminder-travel/)
- The Lorem Ipsum test was generatore from [this site](https://loremipsum.io/)


### Media
- The here images used on the site were all photos taken by me. 
- The photo of "Anna" for the featured story came from a [Bootstrap Template](https://blackrockdigital.github.io/startbootstrap-agency/img/team/1.jpg)
- The six images used for travel stories came from a site called [Hostel Geeks](https://hostelgeeks.com/?s=travel+stories) links for each below. 
    - [Nepal](https://hostelgeeks.com/best-hostels-in-kathmandu-nepal/)
    - [Laos](https://hostelgeeks.com/best-hostels-in-luang-prabang-laos/)
    - [Jaipur](https://hostelgeeks.com/best-hostels-in-jaipur-india/)
    - [Tokyo](https://hostelgeeks.com/tokyo-regretting-feeling-daring-travelstory/)
    - [Santorini](https://hostelgeeks.com/49-santorini-photos-pictures/)
    - [Andora](https://hostelgeeks.com/tarter-mountain-hostel-andorra-5starhostel/)

### Acknowledgements

- Tinted overlay for image -[site](https://css-tricks.com/tinted-images-multiple-backgrounds/)
- For the bootstrap elements I leverged the [bootstrap documentation site](https://getbootstrap.com/docs/4.3/utilities/)

### Inspiration

- I received inspiration for this project from my personal travels and passion to explore more and connect with other people. 


**This site is for educational use.** 