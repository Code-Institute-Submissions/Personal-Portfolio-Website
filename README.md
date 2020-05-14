
Marjolein van Leeuwens Portfolio Website
---------------------------------------
**First Milestone Project: User Centric Frontend Development - Code Institute**

This personal portfolio website is meant as a display for prospective employers. 
It’s my way to make a good first impression.
I would like visitors to get to know me personally and show them what my skills and capabalities are. 
Since I am from the Netherlands, I made it a bilingual portfolio website. 

**User stories**

* The first thing employers and recruiters will see on my website is my name, my picture and a [CV][CV] they can directly download.
* The navigation bar allows users to quickly visit any section within my site.
* If the visiter wants to go back to the top, there is a back-to-top arrow on the bottom right.
* The visiter can view my two projects in the Work section which shows my capabilities in coding

**Demo**

For a demo of my portfolio website click [HERE][1]

**Strategy**

* My strategy was to create a clean and simple design that draws users attention and is easy to read.
* I choose the google font: Lato, which is easy to read.
* With the parallax feature, users take in an active role in their interaction with my site. 
This active role gives users the impression that they choose to engage, making them more positive and receptive to my message.

**Scope**

My goal for this website is to provide employers and recruiters a brief overview of myself and my skills. 
The users get a glimpse of who I am, read my story, see my coding skills and can contact me if they please.

**Structure**

* The Home page features a responsive navigation bar. 
* The Navigation bar consists of an EN/NL, About, Work, Skills and Contact section.
* In the Home section, its possible to directly download a PDF of my CV.
* You can see my picture on the background and a download button for my CV.
* In the About section you read my personal story .
* In the Work section you find my two projects I worked on during my fullstack development course for Code Institute
* In the Skills section, you see the progress of my coding languages.
* In the Contact section: The visiter can contact me through a contact form.


**Skeleton** 

The wireframe was made in Balsamiq. I was able to create a first draft of what I wanted my Portfolio Website to look like.
Along the way of building my website I discovered that some features I made in my wireframe were not functional or difficult to create.

So my website has not become exactly like the wireframe I created.
The features that has changed are explained here:

* [Homepage wireframe][1a] The navigation bar is only found on the homepage and does not scroll down because of the parallax feature. I let the navbar stick on top. 
That's why I created a bottom-to-top arrow, so it is possible to directly go back to the navigation bar.
* [About wireframe][1b] The image of myself is seen on the Homepage and not in the About section anymore. 
* [Work wireframe][1c] I added a Github Icon to click on, which directs you to my projects on my github page. 
* [Skills wireframe][1d] I made use of the bootstrap progress bar instead of the round circles I originally wanted. 
* [Contact wireframe][1e] In the Contact section I originally wanted to add a picture of myself, but instead I put the image of myself in between the Work and Skills section.

**Surface**

* I chose for the opacity css property for my background images, because of the more sophisticated look. 
* My website made use of the colors: ##383838, white, black and rgb(74, 133, 74).

**Technologies**

1. HTML
2. CSS
3. Bootstrap

**Features**

* This site uses the parallax feature to create a scrolling effect. 
* The navbar sticks on the top, and when you scroll down, it doesn't interfere with my content.
* The visitor is able to switch languages EN/NL in the navigation bar.
* I used a scroll top button (arrow) in the website, so you can return quickly to my navigation bar.
* In the Footer (on the right) the visiter can click on my social platform links: Github, Instagram and LinkedIn.
* The Footer contains copyright info.

**Features Left to Implement**

* In the future I would like to add moving texts and animations with CSS. I tried doing this for my name, but I failed, because I had difficulty implementing and understanding this code. 
* In the About section I would like to add a promotional video of myself.
* In the Work section I would like to make flipcards, so the website looks less static and more playful.

**Testing**

- The Navigation bar takes you to the different sections in my website. 
- The arrow top button takes you back to the homepage and navigation bar. 
- When the visiter switches languages, they see a dutch written portfolio website when they click on NL. 
- At the Work section the visitor is able to click on two projects I made for Code Institute. 
The links take you to my GitHub pages.
- In the Contact section visitors are able to fill out the contact form and click on send. 
A modal (in CSS code) will let visitors know that this contact form does not send a message and will not gather personal data.
- In the footer the Github, LinkedIn and Intsagram icons take you to my social platforms.
- **All links have been manually tested**

This site was tested on the Chrome browser and on multiple mobile devices (iPhone 5, 6, 7, 8, iPad, Ipad-pro, Iphone X, Moto G4, Galaxy S5, Pixel 2 and Pixel2XL) to ensure compatibility and responsiveness. 

Testing problems I encountered:
* Everytime I tested the responsiveness on all devices, I discovered something was off in the font-size
I adjusted the font sizes on the Home page and made them responsive.
* I discovered that I had difficulty setting the right media query for the iphone 5, .......
* Downloading my CV gave a "failed- No File" error. I discovered I had to adjust the href link, to make it possible to download my CV.
* With the W3C HTML validation tool I checked my HTML code on errors. My only error in the HTML code was that: "the element button must not appear as a descendant of the a element". If I tried to change the code for my CV button, I wasn't able to see the button on my website as I wanted and couldn't download my CV anymore. 
* With the W3C validator for CSS I discovered 33 bootsrap errors in my CSS code and 684 warnings I didnt understand. With the help of my mentor I understood the problem and discovered that....

**Deployment**

This project was developed using GitHub.

I followed the next steps to deploy my page on the GitHub pages:

* Log into GitHub.
* Select Sweetzia/Personal-Portfolio-Website in the repository list.
* Go to Settings
* Scroll down to the GitHub Pages section.
* Select the Master Branch
* On selecting Master Branch the page is automatically refreshed, the website is deployed.
* The link can be retrieved to the deployed website.

**Credits**

* All content in the "About","Work", "Skills" and "Contact" sections in this portfolio site were written by myself.
* Media: I used two photo's from [unsplash.com][4] ( a free stock image libary).

- *Photo 1*: Photo of Marjolein made by Darinde Heerema
- *Photo 2*: Photo made by by Nolan Issac on Unsplash
- *Photo 3*: Photo of Marjolein made by Darinde Heerema
- *Photo 4*: Photo by Nathan Riley on Unsplash

**Acknowledgements**

*I got inspiration from:*
* The example project of [Haley Schafer][5]
* The demo of [Diya Thomas][7] one page personal template
* the example project of [Anna Gilhespy][9]

*I used HTML and CSS codes from these sources and edited it for my Portfolio Website:*
* Code from the youtube tutorial from [Traversy Media][5a] about creating a basic parallax website with HTML and CSS. 
* [Marvin Orendain][6] Pure CSS Modal code
* Code from the youtube tutorial from [DarkCode][8] about creating a back to top button using only HTML & CSS
* Code from the "Putting it all together/ Mini project" from the User Centric Frontend Development Module of Code Institute
* Code from [W3schools.com][3] for making Column Cards and how to put a Navigation Bar on my Homepage image.

*I want to thank my mentor Brian Macharia for guiding me through the process of making my Portfolio Website.*



[1]: <https://sweetzia.github.io/Personal-Portfolio-Website/>
[CV]: <https://e9b8f684-5d41-46fc-b300-affb381be327.ws-eu01.gitpod.io/files/download/?id=7e3df4bc-2183-43c8-9364-911ec6e93c45>

[1a]: <https://github.com/Sweetzia/Personal-portfolio-website/blob/31421d60a047e4eef5cb25aebdeefed2674e2e13/wireframes/Home.png>
[1b]: <https://github.com/Sweetzia/Personal-portfolio-website/blob/31421d60a047e4eef5cb25aebdeefed2674e2e13/wireframes/About.png>
[1c]: <https://github.com/Sweetzia/Personal-portfolio-website/blob/31421d60a047e4eef5cb25aebdeefed2674e2e13/wireframes/Work.png>
[1d]: <https://github.com/Sweetzia/Personal-portfolio-website/blob/31421d60a047e4eef5cb25aebdeefed2674e2e13/wireframes/Skills.png>
[1e]: <https://github.com/Sweetzia/Personal-portfolio-website/blob/31421d60a047e4eef5cb25aebdeefed2674e2e13/wireframes/Contact.png>

[3]: <https://w3schools.com>
[4]: <https://unsplash.com/>
[5]: <https://www.haleyschafer.com/>
[5a]: <https://www.youtube.com/watch?v=JttTcnidSdQ&t=4s>
[6]: <https://codepen.io/marv117/pen/WvZdGV/>
[7]: <https://www.beingeorge.com/diya/>
[8]: <https://www.youtube.com/watch?v=Vef9bxTilCU>
[9]: <https://ajgreaves.github.io/portrait-artist/>
