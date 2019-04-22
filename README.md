# __Rockanrolla Band Website__

*__This is my very first Website Project.__*

It is based on all the learnings acquired through the initial three modules or the Fullstack Web Developer (Code Institute).

It is about an imaginary rock band from California from the 70's and the user can review their albums, past and future events and videoclips. It also allows the user to keep in contact with the band providing their feedback via mail and, if interested, buy event tickets or hire the band for private events.

This site is simulating all the previous features and all its content is pure fiction. Everything has been researched and collected from many different sites around the WWW.


## __UX__
---

This website is aim to be visited by music and rock fans, more especifically those ones that grown up listening those beats during the 70's an 80's. This site shows the progress of the band from then till these actual days. 

__*Average visitor should probably be:*__

* Between 30 and 70 year old.

* music / Rock and roll lover.

* Curious about rock history.

* Engaged with concerts and live events.

__*Most of the visitors to this site are probably looking for:*__

* Valuable information about the band that made them dance and feel like no other during a single concert or an event.

* New ways to keep in touch with their favourite music band 

__*This site could help them to feel part of the crowd again:*__

* The easy menu allows visitors to navigate between the site pages

* Many other music bands overload the sites with sponsors. That takes visitor's attention to different things. On this site, the band is the main sponsor

* Some past events are included and displayed in a time line. This should encourage visitors to update their experiences when attending to a concert not displayed on site.

__*Visitors experiences:*__

  1. As a new visitor to this page I would like to navigate throug the contents in a easy way.

  2. As a new visitor to this page I would like to find some pictures of previous and future events of this band.

  3. As a new visitor to this page I would like to listen to some music from this band.

  4. As a fan of this band I would like to be able to give some feedback about my feelings during a concert I attended.

  5. As a fan of this band I would like to buy a ticket for a concert.

  6. As a fan of this band I would like to follow the band through social media sites.
  
__*Wireframes mockups:*__

  + [Mobile Approach wireframe 01](project_docs/Wireframes/2018.06.29_rockandrollband_prj_wireframe_01.jpg)

  + [Mobile Approach wireframe 02](project_docs/Wireframes/2018.06.29_rockandrollband_prj_wireframe_02.jpg)

  + [Balsamiq Project wireframe](project_docs/Wireframes/Balsamiq_wireframe_Rockanrolla_project.pdf)

## __Features__
---

The site works on 5 Html pages styles using Flexbox and customized CSS properties to feature a responsive design. 

On each page the next elements are displayed:

  1. A __*header*__ containing a band logo, a title and a navigational menu between pages.

  2. A *__section__* with two columns displaying *[specific contents](###specific-section-contents)* attending to the page selected.

  3. A __*footer*__ that links the user to this developer and to the band via social media.

  4. A __*back to top button*__ that allows the visitor to go back to the header 

### __*Specific Section contents*__

__*Home:*__

+ The contents displayed in the first column of this section are about all the band's albums. A carrousel containing seven slides with the album cover and some of the song titles should help the visitor to meet the band's discography.

+ The contents displayed in the second column are about the beginnig of the band's history. In a simple article element containing a header and two paragraphs, the visitor should be able to learn about the beginning of the band and why, after all this time, they are still together.

__*Pictures:*__

+ The contents displayed on the first column of this section are about the band's concerts. A gallery displays nine cards, every one containing an image and some information about a concert in a world venue. This cards are ordered by year to show the visitor the band progress through the years.  

+ The contents displayed on the second column are about feedback from events provided by fans that attended some of the concerts of the band.

__*Clips:*__

+ The contents displayed on the first column of this section are about the band's concert song recordings. A gallery displays four cards, every one containing the song name and a videoclip. Hovering or clicking on the card should start playing the clip. 

+ The contents displayed on the second column are about an specific videoclip. This is the first video recorded by the band and here is displayed when the visitor clicks on the text link or hover on the clip card. 

__*Events:*__

+ The contents displayed on the first column of this section are about the future events of the band. A carrousel is available with eight slides, each one containing information about a future event date, city, country, venue and tickets availability. This should help the fans to take a decision about which should be the best concert to attend.

+ The contents displayed on the second column are related to the purchase of concerts tickets. A link is diplayed that should link the visitors to an external site where tickets can be bought.

__*Contact:*__

*Section contents*

+ The contents displayed on the first column of this section are about the form available for the visitor to give any kind of feedback about the band, their concerts, etc. A validated email is neccesary to send the feedback so this would give the band crew to give back a response, increasing the confidence between the musicians and the fans.

+ The contents displayed on the second column are about the chance given to any fan to hire the band for music events. This is managed through an external company so the visitor is offer a link to it if this is their desire.

### Existing features

+ __*Header:*__ Exist on every page and it is a key feature for the visitor experience when navigating through the site. It is responsive and displayed in a very simple way.
  
  - *Band Logo*. A simple picture showing the band in its best cheerfuk moment.

  - *Band Name*. A title displaying the band name.

  - *Responsive navigation menu*. It adapts to the different devices used by the visitor to display the site.

+ __*Section:*__  Exist on every page and it is a key feature for the visitor experience when looking for contents the site. Every different page uses different features as:

  - *Slider*. A simple way to display cards with images and/or information about the band. The interaction with the screen make it particularly valuable on the Mobile Approach due to its quickness

  - *Gallery*. Another simple way to display cards with images and/or information about the band. This way looks better on Tablets and Laptops with bigger screens and the chance to have more space avilable to display more cards than in the Mobile approach. 


+ __*Footer:*__ Exist on every page and it is a key feature for the visitor experience when connecting to the band in different social media platforms. It is responsive and displayed in a very simple way.

  - *Band PO box*. A box showing the PO address of the band to allow visitors to write mail letters to the band. This is a vintage feature added to the site. Some fans still rely on written old-style feedback, as the band itself.
  
  - *Developer link*. An image that rotates when clicked links the visitor to the developer's resume. This is only a special feature that is included in every project designed by [danmtt](https://danmtt.github.io/ucd-resume/index.html).

  - *Social media platform's icons*. A box containing three links to connect the visitor to the different social media profiles of the band. This way they should receive current news and posts, increading the chances to interact with the band.

+ __*Back to top button:*__ A button that only exist on Mobile approach helps the customer to navigate back to the page header to easily link to anothe page of the site.


### Features Left to Implement

+ __*Landing page:*__ As shown in [Balsamiq Project wireframe](project_docs/Wireframes/Balsamiq_wireframe_Rockanrolla_project.pdf), the project was originally planned over 6 Html pages. A landing page should be the perfect way to introduce images of the band as also some random song from their extended repertoire.

+ __*Ticket / Band Hiring managment:*__ Actually the band use external companies to manage this features. A challenge for every band is to manage this so no external control over them is impossed by the ticketing industry. 

## Technologies Used
---

The site has been developed using programming languages as HTML5 with semantic tags and CSS3 with Flexbox properties:

+ __*Fonts Research:*__ This site uses [Google Fonts](https://fonts.google.com/) to style its fonts. Some font mockups have been created using [Our own thing](http://www.ourownthing.co.uk/fontpairing/):

  + [Font mockup 01](project_docs/Font_selection_research/01_Blue_White_Monoton.jpg)

  + [Font mockup 02](project_docs/Font_selection_research/01_Blue_White_Ranchers.jpg)

  + [Font mockup 03](project_docs/Font_selection_research/02_Yellow_Black_Monoton.jpg)

  + [Font mockup 04](project_docs/Font_selection_research/02_Yellow_Black_Ranchers.jpg)

  + [Font mockup 05](project_docs/Font_selection_research/03_Black_White_Monoton.jpg)

  + [Font mockup 06](project_docs/Font_selection_research/03_Black_White_Ranchers.jpg)

  + [Font mockup 07](project_docs/Font_selection_research/04_Black_White_Monoton_Ranchers_Combo.jpg)

  + [Font mockup 08](project_docs/Font_selection_research/04_White_Black_Monoton_Ranchers_Combo.jpg)
 
+ __*Flexbox:*__ 'How to' documentation has been researched and coding examples edited from this sites:

  - [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  
  - [w3school - CSS Flexbox](https://www.w3schools.com/css/css3_flexbox.asp)

  - [Scrimba - Flexbox](https://scrimba.com/g/gflexbox)

  A Complete Guide to Flexbox
  
+ __*Sliders:*__ 'How to' documentation has been researched and coding examples edited from this sites:

  - [Slider with just HTML and CSS](https://css-tricks.com/can-get-pretty-far-making-slider-just-html-css/)

  - [Image Slider Using HTML And CSS Only](http://qnimate.com/creating-a-slider-using-html-and-css-only/)

  After various attemps to implement the slider / carousel only with Html and Css, it  became an horrendous feature for the project so I decided to implement a generic example from Bootstrap and adapt its code to make it functional for the site. This feature has been implemented to index.html("The Albums"), pict.html ("The concerts"), events.html ("Upcoming Events")

  - [Bootstrap Carousel with javascript](https://getbootstrap.com/docs/3.4/javascript/#carousel-examples)

+ __*Back to top button:*__ 'How to' documentation has been researched and coding examples edited from this site:

  - [Back to top button using css and html only](https://stackoverflow.com/questions/32102747/how-to-make-a-back-to-top-button-using-css-and-html-only)

+ __*Code editors:*__ Two different editors have been used along the development of this project.

  - [Cloud9](https://aws.amazon.com/es/cloud9/?origin=c9io)

  - [Visual studio code](https://code.visualstudio.com/)

## Testing
---

All the tests run on this project can be found on these two different markdown files:

  + [Code Validation tests](Code_Validation_Tests.md)

  + [UX tests](UX_Tests.md)


## Deployment
---

This project was developed and stored in git using initially Cloud9 and Visual Studio Code after.

The project was staged, commited and pushed frequently to a GitHub repository  named [Rockanrolla Project](https://github.com/danmtt/rockanrolla). It is published to [GitHub pages](https://pages.github.com/) using the GitHub settings.

[Click here to visit the site](https://danmtt.github.io/rockanrolla)


## Credits
---

### Content

The band I selected to be simulated on this site was "The Guess Who". I decided to change its name to "The Invasors" to make the site a bit different. I implemented the band history and the fans feedbacks reading and then editing some of the texts contained in these links:

  + [Fans stories](https://www.vanmorrison.com/fans)

  + [A rock musical project](https://en.wikipedia.org/wiki/The_Brian_Jonestown_Massacre)

  + [A rock band example](https://consequenceofsound.net/aux-out/book-club-our-band-could-be-your-life/)

  + [Rock music survival](https://www.theguardian.com/commentisfree/2018/oct/23/rock-music-survive-testosterone-guitar-female)

  + [A good band bio](http://www.alandmoore.com/blog/how-to-write-a-good-band-bio/)

  + [A music video 30 years later](https://metalinjection.net/video/guns-n-roses-unveil-its-so-easy-music-video-30-years-later)


### Media

Most of the site media content is related to "The Guess Who":

  + [The Guess Who Song Research](https://www.taringa.net/+musicadelos6070/the-guess-who-discografia-1965-2004_12v27z)

  + [The Guess Who Video Research](https://www.google.co.uk/search?rlz=1C1CHBF_esGB786GB786&biw=1745&bih=843&tbm=vid&ei=Z1vGW_6vL4uVgAapyY6oDA&q=THE+GUESS+WHO+VIDEOS&oq=THE+GUESS+WHO+VIDEOS&gs_l=psy-ab.3..0l2.19951.25843.0.29252.20.17.0.3.3.0.89.1244.17.17.0....0...1c.1.64.psy-ab..0.20.1237...0i8i30k1j0i8i10i30k1.0.3lJQ5jf22Og)

The image research process has been done navigating through these sites:

  + [Logo Research](https://www.manitobamusicmuseum.com/theguesswho.htm)

  + [Background Research](https://wallpapers-house.com/group/band-backgrounds/index.php)

  + [Random concerts and events images](https://www.google.com/search?q=concerts&rlz=1C1CHBF_esGB786GB786&source=lnms&tbm=isch&sa=X&ved=0ahUKEwiOwLyM_uHhAhVdRBUIHaAAA74Q_AUIDigB&biw=1280&bih=615)


The background, logo images displayed on the different project pages have been selected and edited from:
  
  + [Logo Image](https://manitobamusicmuseum.webs.com/The%20Guess%20Who%201972-74.jpg)

  + [Background Image](https://wallpapers-house.com/data/out/8/wallpaper2you_268116.jpg)


### Acknowledgements

- "Takk!" to my mentor [Simen Daehlin](http://simen.dehlin.info/#home) and 
"Bedankt!" to student [Anna Greaves](https://github.com/AJGreaves) for all the help, patience and examples shown. Their help through different channels has been key to this project development! "Gracias!"







