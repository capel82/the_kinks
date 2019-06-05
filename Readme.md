# The Kinks

## Introduction
The aim of this project is to promote a 1960s rock band called The Kinks to gain more accessibility to fans around the world and  to increase the sales from their newest music album, future tours and private hires.  This is a static front-end web development incorporating skills learned from HTML and CSS3 taught by Code Institute.

### A. Objectives
The objectives of creating this webpages are:
* to provide fans around the world with up-to-date information of their newest albums and future tours.  
* enable fans to purchase newly released album and tour tickets through third parties webpages.  
* it also promotes private hires in the contact page.

### B. Wireframes

[wireframe](Wireframes.pdf)

### C. User Stories
**Homepage**
As a fan that uses this website, the first thing that will catch my attention is when i lands on the landing page, it shows the band’s photo in Jumbotron. Coupling with navbar brand “The Kinks” clearly shown on the left end of navigation bar, it helps me to identify the correct webpage that i will be browsing through.

In the Jumbotron , I can see the shoutout of New Album Released which catches me to listen by clicking on the “Play Now” button to listen to one of the piece of music in the album. 

For people who are new to the band, they could read short reviews of fans on their previous albums to get a rough ideas of the popularity of their albums and values of them.

I am made aware of future tours of the band in terms of dates and venues as I scrolled down the page. I can buy tickets by clicking on “Buy Tickets” icon which will bring me to secure third party website *Ticketmaster* to purchase the tickets.

**About page**
 As fan, I could also easily find  general information about the band and if I wish to read more, I can just click on the *“Read more”* button.  As i scrolled down, i could also read about each of the members information and follow them on through their individual social medias shown by social icons beneth their descriptions.

**Media page**
I can listen as well as watch the new album by clicking on the iframes. If I wish to purchase I can just click on *“Buy Album ”* button that brings me to third party websites to purchase the album. If i want to listen more to their previous albums i can easily click on the *“Play Now”* button of albums shown.

**Gallery page**
I can view different photos of the group. If I am using mobile device, I know that I am in Gallery page with the heading "Gallery" as the Navbar collapses.

**Contact page**
I could see clear message that this band is also available for hire for special events and contact form is available to fill in or if I live locally, I can just give the admin office a call or email them directly.  These give me options which i like as a fan.

If I decide to navigate back to other pages like Home landing page, I can easily just click on the navigation bar which brings me to any pages that i will like to visit again.

###  D. FEATURES
-**Navbar** - This features uses Bootstrap Navbar toggles and collapsible features which allow when in smaller screen to toggle and collapse, featuring  like a dropdown for easier navigation. This is visible on all pages which allows users to switch between pages easily. 

-**Footer** - This is visible at the bottom of all pages with social icons that have hover effects and a copyright information. 

-**Home page** - The background image of The Kinks is responsive.  The heading helps to bring across new information of the group ie.New Album Released and the *"Play"* button with hover effect helped to catch user’s attention to sample the new music via youtube channel. For new fan or new user, they can read about reviews from previous albums showed with album cover images.   This page also features important information about future tours and option to purchase tour tickets by clicking on the *“Buy Ticket”* button with hover effect.

-**About page** - This page features on the top general information about the band together with their group photo and if user is kind to read more, they can click on “Read More” button with hover effect that linked to Wikipedia website.  Each column of the members used Bootstrap 4 card group component. User can also followed individual band members through their own social media websites by clicking on the social media icons at the bottom of each member information.

-**Media page** - This page allows users to sample one of the new song in their new released album either by audio clip via Spotify or watching their video via Youtube.  These are embedded to allow user to watch directly in current page without opening a new page. In addition, users can also buy the new album by clicking on the *“Buy Album”* button that bring them to third party websites for purchases.  Users can also listen to previous released albums by clicking on *“Play Now”* button.

-**Gallery page** - This page uses card group components from Bootstrap 4 which allow mix and match features of different sizes of photos. It is responsive to various media screens.

-**Contact page** - This page uses form features of bootstraps.  Users can choose either to fill in the form to be contacted back or they can choose to call or visit the admin office directly. Three fields of Your Name, Telephone number and E-mail are made as required fields so that if user not fill in any of the fields, message will appear to ask to fill in.

**_Features to implement in future_**

1.User can listen music in pop-up page whilst remaining on the current webpage.

2.Cookies to be implemented.

3.Contact form - to be able to incorporate GDPR consent and CAPTCHA.

### E.Technologies Used

**Adobe XD**
[Adobe](:https://www.adobe.com/ie/products/xd.html?promoid=PYPVQ3HN&mv=other/)

Why it is being used:  Recommeded by my mentor and it gives a good idea of wireframes even to the details of colours and images.

**Bootstrap v 4.3**

(https://getbootstrap.com/)

Why it is being used: As mobile digitals are increasing and so widely used, Bootstraps has been chosen for mobile first -approach for the design of the webpages so that it can be easily made responsive with many different features offered.

**Bootstrap own Javascript, jQuery and Popper.js**
(https://getbootstrap.com/docs/4.3/getting-started/introduction/)

 Why it is being used: As many of bootstrap v4.3 required use of Javascript, jQuery and Popper.js, these technologies were also incorporated into this project.    
     
**HTML5**
 
 Why it is being used: Using up-to-date features offered which is HTML5 through Cloud9 IDE for programming languages.

**CSS3**

Why is being used: Using the latest Cascading Style Sheets to support for responsive designs and styling.
 

[W3C Markup Validation Service](https://validator.w3.org/)
Why it is being used: to help to validate codes


[Spotify](http://www.spotify.com)
why it is being used: to host audio songs


[Youtube](http:www.youtube.com)
why it is being used: to host video of band’s performance

[google fonts](http://fonts.google.com)
why it is being used: use to style the fonts in all the pages


[Font awesome](https://fontawesome.bootstrapcheatsheets.com/)
why it is being used: to add social icons to website


### F. Testing
In the process of developing this project, Chrome Development Tool was used to assess responsiveness as well as designing and debugging.  HTML validator was used to validate the codes.

Browsers tested were Safari and Google Chrome.

The website also tested with my iPhone SE and MacAir.

##### **Manual testings:**
**Navbar** - clicking on all pages to ensure they are all properly linked to the right page.  I also reduced to smaller device screen to test for ability to toggle. In smaller screens, the menu showing "Home, About, Media, Gallery and Contact" appeared vertically on the left.  I have also tested the Navbar item is active of the correspondance page.  ie. When I was on About page, the "About" in Navbar appeared more prominently white color indicating that that was the About page.

**Buttons** - all manually tested with workable links. When i clicked on the buttons, background color and font-color changed indicating the hover effect worked.

**iframes** - all manually tested that can play the music or video.

**Social icons** - have hover effects and linked to social media websites. These include social icons in About page as well as in all Footers. ie. When I hovered a Facebook icon, it enlarged in size and when I clicked on it, it brought me to Facebook page.

**Footer** - checked with Chrome Development Tool that it is responsive and stayed at the bottom of the page.

**Contact Form** - checked by entering incorrect information ie wrong format emails will show the form is correctly validated. If required field not filled, error message will come out to ask to fill the field.

### G. Deployment
As introduced by Code Institute, I have used *Cloud9 IDE* which supports [Github](https://github.com/) and Git repositories as the main platform to develop my website.

Codes developed in Cloud 9 IDE were committed to Git with a repository created in Github beforehand. Then I pushed them to Github through in-built function of Cloud 9 IDE.

Then I signed into Github account and clicked on the **repository** with the name **‘Capel82/the_kinks’**

This showed the files, images, readme and assets.  

The current website is staged on Github pages.

### H.Credits

a. **Contents:** The contents about the band information and members profiles were taken from [Wikipedia](https://en.wikipedia.org/wiki/Main_Page) websites.

https://en.wikipedia.org/wiki/The_Kinks

https://en.wikipedia.org/wiki/Ray_Davies

https://en.wikipedia.org/wiki/Dave_Davies

https://en.wikipedia.org/wiki/Mick_Avory

https://en.wikipedia.org/wiki/Pete_Quaife

b. **Photos used:**  The photos used were taken from several sites as below:

*1.Wikipedia :*

https://en.wikipedia.org/wiki/The_Kinks

https://en.wikipedia.org/wiki/Ray_Davies

https://en.wikipedia.org/wiki/Dave_Davies

https://en.wikipedia.org/wiki/Mick_Avory

https://en.wikipedia.org/wiki/Pete_Quaife

https://en.wikipedia.org/wiki/Kinks_(album)

https://en.wikipedia.org/wiki/Low_Budget_(album)

https://en.wikipedia.org/wiki/Something_Else_by_The_Kinks

https://en.wikipedia.org/wiki/Face_to_Face_(The_Kinks_album)

https://en.wikipedia.org/wiki/Soap_Opera_(album)

https://en.wikipedia.org/wiki/Word_of_Mouth_(The_Kinks_album)

*2.Pitchfork*
https://pitchfork.com/news/ray-davies-says-the-kinks-are-reuniting/

*3.Rollingstone*
https://www.rollingstone.com/music/music-features/kinks-interview-ray-davies-dave-davies-village-green-preservation-society-747379/

*4.Rock and Roll Hall of Fame*
https://www.rockhall.com/inductees/kinks

*5.Evening Standard.*
https://www.standard.co.uk/go/london/arts/the-kinks-exhibition-village-green-a3947271.html

*6.Spotify*
https://images.app.goo.gl/DBs3xB7EzU8487qS9

*7.Jambase*
https://www.jambase.com/article/ray-davies-dave-davies-deny-a-the-kinks-reunion-is-in-the-works

*8.NME.com*
https://www.nme.com/news/music/the-kinks-50-1197380

*9.pastemagazine.com*
https://www.pastemagazine.com/blogs/lists/2011/04/the-15-best-kinks-songs-1.html

*10. Independent.co.uk*
https://www.independent.co.uk/arts-entertainment/music/features/dave-davies-interview-the-kinks-we-are-the-village-green-album-50th-anniversary-ray-reunion-a8557806.html

c. **Musics embedded:**

[Youtube](http://www.youtube.com)

[Spotify](http://www.spotify.com)

### I. Acknowledgement
A special thanks to my mentor **Maranatha Ilesanmi** who has very kindly encouraged, guided and taught me with so much patience towards me in finishing this first milestone project.

I also thanked my wonderful husband who has allowed me to have my protected time to complete this project by looking after my two young boys.

Not forget the tutor team in Code Institute and Slack communities.