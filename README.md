# Aloy: From Outcast to Heroine #
*And the importance of female playable characters in videogames.*

![Aloy](/wireframes/hero-image-aloy.jpg)

## Contents ##
---
* UX
    * Project Goals
    * User Goals
    * User Stories
    * Site Owner Goals
    * User Requirements and Expectations
    * Design Choices
        * Fonts
        * Icons
        * Colours
* Technologies
* Features
    * Features that have been developed
    * Features that will be implemented in the future
* Testing
* Bugs
* Deployment
* Credit

## UX (User Experience) ##
---
### Project Goals ### 

The **goal** for this project is to make people **aware** of the importance of **strong female playable characters in video games**, specifically about how **Aloy**, the playable female character from **Horizon Zero Dawn**, a video game launched in **2017**, has changed the landscape for female playable characters forever, at least for me!

### User Goals ###

* **Find information** about the **presence** of female playable characters in video games.
* **Find information** about the character of **Aloy**.
* **Images** of Aloy (fan art).
* **Send** an **email** to the **site owner**.
* **Contact the site owner** through options given with radio buttons for **clarification** on **why** a **user contacts** the **site owner**.
* Why it is important to have 'healthy' rolemodels instead of bare-naked ladies who have no storylines of any substance.

### User Stories ###

* As a **user**, I want an **attractive and informative website** so I will be **educated and entertained**.
* As a **user**, I want to **find information** about why having a **female playable character** in video games is **very important** for **female rolemodels**, so I can use this information for my **personal goals**, like **speaking engagements**.
* As a **user**, I want to be able to **contact the site owner** so I can **ask questions and/or suggest additional content**.
* As I **user**, I want to see **data** about the **presence of female playable characters in videogames**, so I can **use** the data for **personal goals**.

### Site Owner Goals ###

* As a **site owner**, I want to inform and educate my users about how important it is to have female playable characters in video games.
* As a **site owner**, I want to communicate y love for Aloy and the game **Horizon Zero Dawn** and make the **user aware** about the **vast differences** in appearances and storylines regarding **female playable characters** and particulary why **Aloy is the kick-ass heroin we all need!**
* As a **site owner**, I want to be able to **connect** with my **users** if they have any **questions or would like to talk about adding additional content**.

### User Requirements and Expectations ###

**Requirements**
* **Navigate** the website using the navbar.
* Be provided with **information** on various locations.
* Content displayed in a **visually appealing** manor.
* Having a working **contact form** with **radio buttons**.

**Expectations**
* Content is **visually satisfying** and **informative**.
* **Navigation** takes **user** to specific **parts** of the **website**.
* Working **Read More** buttons to **avoid** big **lumps** of clustered **text**.
* **Visually appealing** data from external sources.

### Design Choices ###
---
When **designing** this website, I looked for the **designs** used bij [Guerilla Games](https://www.guerrilla-games.com/) and added my **personal touch**. I wanted it to **breath** the look and feel of the [Horizon Zero Dawn](https://www.playstation.com/nl-nl/games/horizon-zero-dawn-ps4/) website, so it **feels familiar** for user who know the game and at the same time I wanted to try and **entice** other users to wanting to **play** the game **themselves**.

**Fonts**

I originally intended to use the **fonts** that **Guerilla games** used as well, but found out pretty quickly that those **fonts** where **designed specifically** for them. So I looked for **fonts** that had as **strong** as a **resemblance** to the **original fonts** as possible.
I picked [Quicksand](https://fonts.google.com/specimen/Quicksand?category=Sans+Serif&preview.text=&preview.text_type=custom&query=quick) for the headers and titels and [Raleway](https://fonts.google.com/specimen/Raleway?category=Sans+Serif&preview.text=&preview.text_type=custom&query=ralewa) for text.

**Icons**

**Icons** used where provided by [Font Awesome](https://fontawesome.com/), used in **moderation** and are self explanatory.

**Colours**

The **colours** that are used are mainly the **colours** that **Horizon Zero Dawn** uses. 

* For body text and some titles: Martinique #37343d;
* For some headers and titles: Cornflower Blue #5983ff;
* For body background: White #ffffff;
* For additional backgrounds: Desert Storm #eae8e5;

![Color Scheme](/wireframes/color-scheme.png)

## Wireframing ##
---
For **wireframing** I used [Pencil Prototyping](https://pencil.evolus.vn/). This produced some very **basic** wireframes, used to get an overall **feel** for what would go where and how things would look on different screensizes.

View my wireframes [here]("https://github.com/byIlsa/Aloy-from-outcast-to-heroin/tree/master/wireframes").
To be more precise:

*   [Desktop Wireframe]("https://github.com/byIlsa/Aloy-from-outcast-to-heroine/blob/master/wireframes/aloy-desktop.pdf")
*   [Tablet Wireframe]("https://github.com/byIlsa/Aloy-from-outcast-to-heroine/blob/master/wireframes/aloy-tablet.pdf")
*   [Mobile Wireframe]("https://github.com/byIlsa/Aloy-from-outcast-to-heroine/blob/master/wireframes/aloy-mobile.pdf")

Whilst building this **project**, I quickly **noticed** that my choice for a **multiple page site**, wasn't what my **demographic** wanted, so I decided to **divert** to a **landingpage structure** with **anchored links** and **sections**.

<details>
  <summary><strong>What didn't make the cut and why:</strong></summary>
As discussed earlier, my <strong>wireframes</strong> and the completed site are two different things. As this is my <strong>first project</strong> and I need to learn a lot about UI and UX, I quickly noticed that although things look nice in my mind and on paper,
that doesnt necessarily means it works on screens.

The main title became one word, as to help with making the navbar look more balanced when on smaller screens and to give some space to the anchor links.
So, taking the <strong>desktop</strong> one as a leading example, a lot has changed, since I've decided that I would use a <strong>landingpage structure</strong>. The home page became the main focus, where the other pages ive drawn in the wireframes, became sections. The jumbotron was originally
going to be in the right corner, but as I was building, I felt it would be more <strong>balanced</strong> if I made it centered.

At first I had a lot of problems wrapping my head around the <strong>mobile</strong> first perspective, which frustrated my core build in the beginning. Luckily thanks to a very patient mentor, I figured it out and things were a lot easier going forward.
The about Aloy section originally contained four image sections and three with text. This became one text section and a slider for three images. Reasons being, people dont want to read long stretches of text and the demographic usually want
to see more images then reading text. A <strong>Read More</strong> button gives the user the <strong>ability</strong> to visit a page that contains more (in depth) text about that section.

Keeping things smaller also ment it was easier on the eyes on smaller screens. So for the <strong>art section</strong> (with the cosplay and fan art) I decided to use <strong>less</strong> images, less text with a <strong>Read More</strong> button and decided to <strong>drop</strong> one image for
tablets and to <strong>stack</strong> the remaining image with the text on mobile devices.

**Female protagonist** became protagonists section, also with a lot less text on the main page and **Read More** buttons just like the other sections.
The <strong>contact</strong> form was place on the bottom of the page.
</details>

![Screens](assets/images/screens.jpeg)

## Features ##
---
**Features** that have been **implemented:**

* Easy to use **navigation** on all screen screensizes.
* Contact **form** with **radio buttons**.
* **Attractive** and **recognizable** design.
* Social media links

**Features** that will be **implemented** in the **future:**

* Video's
* Forum

## Technologies used ##
---
**Languages**

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [JS](https://nl.wikipedia.org/wiki/JavaScript)
* [JQuery](https://jquery.com/)
* [Popper](https://popper.js.org/)

**Tools & Libraries**

* [Git](https://git-scm.com/)
* [Bootstrap](https://getbootstrap.com/)
* [Font-Awesome](https://fontawesome.com/icons?d=gallery)
* [Google fonts](https://fonts.google.com/)
* [Gimp](https://www.gimp.org/)


## Testing ##
---
First time testing. I used an online tool called [Lambdatest](https://www.lambdatest.com/) and the chromium dev tools for testing. I made an spreadsheet containing test results.
You can find this [here](https://github.com/byIlsa/Aloy-from-outcast-to-heroin/blob/master/wireframes/testfile.png).

Ive tested the CSS with [CSS Validator](http://jigsaw.w3.org/css-validator/) which told me that all was **good**.

The HTML ive tested with [HTML Validator](https://validator.w3.org/) which gave me the following **results:**
* Warning:
    * Navbar section lacks heading
* Errors:
    * Attribute a not allowed on element a at this poin
    * Possible misuse of aria-label

* Fixes:
    * Changed section to div
    * Remove a Attribute
    * Moved aria-label to correct position

**Responsiveness**

* **Implementation**     Ive used **Bootstrap** throughout the project to ensure **maximum** responsibility. Ive tested with **devtools** and **Lambdatest**.

* **Results**   **Responsiveness** was as to be expected, except for the **navbar**, which didnt collapse on click, which in turn, covered a big portion of the content. I was not happy.
                Luckily my **mentor** gave me a **JavaScript** script, which **solved** the problem!

* **Verdict**    After **resolving** the navbar issue, everything is responsive and the test has **passed**.

**Design**

* **Implementation**   The **design** of the site was based on the design of the **Horizon Zero Dawn** website, using 'look-a-like' fonts, as the fonts used are custom for them. I used some of the colors and styles for a sense of familiarity for people who know the game
and would attract people who dont know the game yet.

* **Results** I feel the use of fonts and colors really add up to the **content** and make for a **well balanced** whole. I did change the opacity of the jumbotrons as some people told me the text was hard to read.

* **Verdict** Everything is working and looks good. So this test has **passed**.

**Contact form**

* **Implementation** The **contactform** is used to contact the site owner. I got this form from the **Bootstrap** site and **customized** it to my own **needs**. Form validation was **implemented** at the same time, so **users** need to put in a **value** into every form field, **before** being able to push the **Send** button.
As of now it is not possible to send the form, so for the time being there is no feedback.

* **Results** The contactform is working as intended, formfields are validated.

* **Verdict** Form validation works, so test **passed**.

## Bugs ##
---
Bugs, those **pesky** bugs

Here are some I encountered, with the solution.

**During development**

* Jumbotron overflow:
    * Removed margins and padding and added height in media query.
* Columns not nicely spaced:
    * Set margins on top and bottoms.
* Anchor link about ID not jumping to right place:
    * Still figuring that one out.
* Rows to close to each other:
    * Set margins and padding.
* Content not centering on mobile:
    * Set margin and padding.

**From validation/testing**

* Nav section didnt have a heading, got flagged by html validator.
    * Changed section tag for div, as nav doesnt need a heading per se.
* Double a tag on lines with links:
    * Removed a from target tag.
* Possible misuse of aria-label:
    * Moved aria-label and rel from the i tag to the a tag, where they belong.
* Navbar links not collapsing on click on mobile:
    * Trying some js for this.

**From peer code review**

* Overflow:
    * Changed margins and padding on multiple elements and removed hover effect on img to prevent overflow.
* Navbar not hiding on click:
    * js fixed the job :)
* Changed opacity on jumbotrons as some people found it hard to read.
* Images with hover effect where overlapping a bit.
    * Reduced the size of the hover.

## Deployment ##
---
Aloy: from Outcast to Heroine was **developed** on **GitPod**, using **git** and **GitHub** to host the repository.

When deploying Aloy: from Outcast to Heroine using **GitHub Pages** the following steps were made:

* Opened up **GitHub** in the **browser**.
* Signed in using **username** and **password**.
* Selected my **repositories**.
* Navigated to **byIlsa/Aloy-from-outcast-to-heroine**.
* In the top navigation clicked **settings**.
* Scrolled down to the **GitHub Pages** area.
* Selected **Master Branch** from the **Source** dropdown menu.
* Clicked to **confirm** my **selection**.
* Aloy: from Outcast tot Heroine now **live** on **GitHub Pages**.

**Running Aloy: from Outcast to Heroine Locally**

**Cloning** Aloy: from Outcast to Heroine from **GitHub**:

* Navigate to **byIlsa/Aloy-from-outcast-to-heroine**.
* Click the green **Clone or Download** button.
* **Copy** the url in the **dropdown box**.
* Using your **favourite IDE** open up your **preferred** terminal.
* **Navigate** to your **desired** file **location**.

**Copy** the following code and **input** it into your **terminal** to **clone Aloy: from Outcast tot Heroine**.

```git clone https://github.com/byIlsa/Aloy-from-outcast-to-heroine```

## Credits ##
---
**Credit for text used on this website**
* [Article](http://exclaim.ca/gaming/article/manic_pixel_dream_girls-on_importance_playable_female_characters) by  Joshua Ostroff.
* [Article]((https://levelskip.com/misc/do_we_need_more_playable_female_characters_in_video_games)) by j-u-i-c-e.
**Text about Aloy and Horizon Zero Dawn**
* Horizon Zero Dawn [Wikipedia](https://en.wikipedia.org/wiki/Horizon_Zero_Dawn)
* Horizon Zero Dawn [website](https://www.playstation.com/nl-nl/games/horizon-zero-dawn-ps4/)
* Text about [Aloy Cosplay](https://www.kamuicosplay.com/2017/09/15/aloy/)

**For spoiler tags in this file**
* [Source](https://gist.github.com/jbsulli/03df3cdce94ee97937ebda0ffef28287)

**Images used**

General:

* [Stormbird](https://www.besthdwallpaper.com/spellen/horizon-zero-dawn-video-game-aloy-boogschutter-meisje--dt_nl-20619.html)
* [Birds eye view](https://www.besthdwallpaper.com/spellen/horizon-zero-dawn-aloy-female-protagonist--dt_nl-20298.html)
* [Thunderjaw](https://www.besthdwallpaper.com/spellen/horizon-zero-dawn-aloy-en-de-dinosaurus-van-de-robot-dt_nl-19651.html)
* [Snapmaw](https://psmedia.playstation.com/is/image/psmedia/horizon-zero-dawn-screen-31-ps4-eu-20oct16?$MediaCarousel_Original$)
* [Frozen Wilds](https://i.kinja-img.com/gawker-media/image/upload/ncwwmdyfcvfhpqbskhnm.png)

Images for Art section:

* Fan Art:
    * [Nikusenpai](https://www.deviantart.com/nikusenpai/art/Horizon-Wallpaper-686563046)
    * [Kalasketch](https://www.deviantart.com/kalasketch/art/Aloy-Horizon-Zero-Dawn-673530134)

* Cosplay:
    * [Kamui Cosplay](https://www.kamuicosplay.com/2017/09/15/aloy/)
    * [Aurora Yulia](https://twitter.com/Aurora_Yulia/status/1146512824941842432/photo/1)

Images for Protagonists section:

The **hero image** used in the **protagonists** section was made by **myself** using [gimp](https://www.gimp.org/) and **contains**:

* Aloy; crops from images used on this site.
* [Amanda Ripley](https://www.avpgalaxy.net/wordpress/wp-content/uploads/2019/01/11.jpg)
* [Senua](https://static3.thegamerimages.com/wordpress/wp-content/uploads/2019/12/hellblade-hellblade-2-senua-s-saga-1-1.jpg)
* [Kassandra](https://twinfinite.net/wp-content/uploads/2018/09/ac-kassandra.jpg)
* [Claire Redfield](http://www.relyonhorror.com/wp-content/uploads/2012/05/CLAIRE_REDFIELD.jpg)
* [Heather Mason](https://i.pinimg.com/originals/9d/f1/bd/9df1bd25a6d6de50879f8956063fe06a.jpg)
* [Faith Connors](http://vignette1.wikia.nocookie.net/mirrorsedge/images/6/6c/Cropped-1280-1024-719167.jpg/revision/latest?cb=20160919164747)
* [Shiela](https://media.vandal.net/m/52273/bright-memory-2018123119171671_1.jpg)


**Special thanks**
* My Yoda-mentor [Simen Daehlin](https://github.com/Eventyret) for being there when I lost my way and didn't know how to get back. And for being the kick-ass person that he is (even though your a horde ;))
* [Geomint](https://github.com/Geomint), for his awesome README
* Everybody at Slack for their support, tips and humor!
* [Richard Williams](https://github.com/RichardWilliams) , for a second pair of eyes and his git knowledge.

For his undying love and support and always being there, my love, you know who you are ;)

**Site for educational purposes only!**