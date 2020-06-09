# Aloy: From Outcast to Heroin #  
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

## **UX (User Experience):** ##  
---
### Project Goals: ### 

<p>The goal for this project is to make people aware of the importance of strong female playable characters in video games, specifically about how Aloy, the playable female character from 'Horizon Zero Dawn', a video game launched in 2017, has changed the landscape for female playable characters forever, at least for me!

### User Goals: ###

* Find information about the presence of female playable characters in video games.
* Find information about the character of Aloy.
* Images of Aloy (fan art).
* Send an email to the site owner.
* Contact the site owner through options given with radio buttons for clarification on why a user contacts the site owner.
* Why it is important to have 'healthy' rolemodels instead of bare-naked ladies who have no storylines of any substance.

### User Stories: ###

* As a user, I want an attractive and informative website so I will be educated and entertained.

* As a user, I want to find information about why having a female playable character in video games is very important for female rolemodels, so I can use this information for my personal goals, like speaking engagements.

* As a user, I want to be able to contact the site owner so I can ask questions and/or suggest additional content.

* As I user, I want to see data about the presence of female playable characters in videogames, so I can use the data for personal goals.

### Site Owner Goals: ###

* As a site owner, I want to inform and educate my users about how important it is to have female playable characters in video games. My love for Aloy and the game 'Horizon Zero Dawn' will make the user aware about the vast differences in appearances and storylines regarding female playable characters and particulary why Aloy is the kick-ass heroin we all need!

* I want to be able to connect with my users if they have any questions or would like to talk about adding additional content.

### User Requirements and Expectations: ###

**Requirements:**
* Navigate the website using the navbar.
* Be provided with information on various locations.
* Content displayed in a visually appealing manor.
* Having a working contact form with radio buttons.

**Expectations:**
* Content is visually satisfying and informative.
* Navigation takes user to specific parts of the website.
* Working 'Read More' buttons to avoid big lumps of clustered text.
* Visually appealing data from external sources.

### Design Choices: ###
---
When designing this website, I looked for the designs used bij Guerilla Games and added my personal touch. I wanted it to breath the look and feel of the [Horizon Zero Dawn](https://www.playstation.com/nl-nl/games/horizon-zero-dawn-ps4/) website, so it feels familiar for user who know the game and at the same time I wanted to try and entice other users to wanting to play the game themselves.

**Fonts:**

I originally intended to use the fonts that Guerilla games used as well, but found out pretty quickly that those fonts where designed specifically for them. So I looked for fonts that had as strong as a resemblance to the original fonts as possible.
I picked [Quicksand](https://fonts.google.com/specimen/Quicksand?category=Sans+Serif&preview.text=&preview.text_type=custom&query=quick) for the headers and titels and [Raleway](https://fonts.google.com/specimen/Raleway?category=Sans+Serif&preview.text=&preview.text_type=custom&query=ralewa) for text.

**Icons:**

Icons used where provided by [Font Awesome](https://fontawesome.com/), used in moderation and are self explanatory.

**Colours:**

The colours that are used are mainly the colours that Horizon Zero Dawn uses. 

* For body text and some titles: Martinique #37343d;
* For some headers and titles: Cornflower Blue #5983ff;
* For body background: White #ffffff;
* For additional backgrounds: Desert Storm #eae8e5;

![Color Scheme](/wireframes/color-scheme.png)


## Wireframing: ##
---
For wireframing I used [Pencil Prototyping](https://pencil.evolus.vn/). This produced some very basis mock ups, used to get an overall 'feel' for what would go where and how things would look on different screensizes.

<p>View my wireframes <a href="https://github.com/byIlsa/Aloy-from-outcast-to-heroin/tree/master/wireframes">here.</a></p>

Whilst building this project, I quickly noticed that my choice for multiple menu links, wasn't what my demographic wanted, so I decided to divert to a landingpage structure with only two menu links.



## Features: ##
---
**Features** that have been **implemented:**

* Easy to use navigation on all screen screensizes.
* Contact form with radio buttons.
* Attractive and recognizable design.
* Social media links

**Features** that will be **implemented** in the **future:**

* Video's
* Forum

## Technologies used: ##
---
**Languages:**

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

**Tools & Libraries:**

* [Git](https://git-scm.com/)
* [Bootstrap](https://getbootstrap.com/)
* [Font-Awesome](https://fontawesome.com/icons?d=gallery)
* [Google fonts](https://fonts.google.com/) 

## Testing: ##
---
First time testing. I used an online tool and the chromium dev tools for testing. I made an spreadsheet containing test results.
You can find this [here](https://github.com/byIlsa/Aloy-from-outcast-to-heroin/blob/master/wireframes/Screenshot%20from%202020-06-09%2010-58-17.png).

## Bugs: ##
---
Bugs, those pesky bugs:

Here are some I encountered, with the solution.

**During development:**
* Jumbotron overflow:
    * Removed margins and padding and added height in media querie.
* Columns not nicely spaced:
    * Set margins on top and bottoms.
* Anchor link about ID not jumping to right place:
    * Still figuring that one out.
* Rows to close to each other:
    * Set margins and padding.
* Content not centering on mobile:
    * Margin and padding (not completely resolved).      


**From validation/testing**

* Nav section didnt have a heading, got flagged by html validator.
    * Changed section tag for div, as nav doesnt need a heading per se.
* Double a tag on lines with links: 
    * Removed a from target tag.
* Possible misuse of aria-label:
    * Moved aria-label and rel from the i tag to the a tag, where they belong.
* Navbar links not collapsing on click on mobile:
    * Trying some js for this.
    
## Deployment: ##
---
Aloy: from Outcast to Heroin was developed on GitPod, using git and GitHub to host the repository.

When deploying Aloy: from Outcast to Heroin using GitHub Pages the following steps were made:

* Opened up GitHub in the browser.
* Signed in using username and password.
* Selected my repositories.
* Navigated to 'byIlsa/Aloy-from-outcast-to-heroin'.
* In the top navigation clicked 'settings'.
* Scrolled down to the GitHub Pages area.
* Selected 'Master Branch' from the 'Source' dropdown menu.
* Clicked to confirm my selection.
* Aloy: from Outcast tot Heroin now live on GitHub Pages.

**Running Aloy: from Outcast to Heroin Locally**

Cloning Aloy: from Outcast to Heroin from GitHub:

* Navigate to 'byIlsa/Aloy-from-outcast-to-heroin'.
* Click the green 'Clone or Download' button.
* Copy the url in the dropdown box.
* Using your favourite IDE open up your preferred terminal.
* Navigate to your desired file location.

Copy the following code and input it into your terminal to clone Aloy: from Outcast tot Heroin.

```git clone https://github.com/byIlsa/Aloy-from-outcast-to-hero```

## Credits ##
---
**Credit for text used on this website:**
* Article by  Joshua Ostroff, original posted on: [link](http://exclaim.ca/gaming/article/manic_pixel_dream_girls-on_importance_playable_female_characters)
* Article by j-u-i-c-e, original posted on: [link](https://levelskip.com/misc/do_we_need_more_playable_female_characters_in_video_games)

**Text about Aloy and Horizon Zero Dawn:**
* Horizon Zero Dawn Wikipedia: [link](https://en.wikipedia.org/wiki/Horizon_Zero_Dawn)
* Horizon Zero Dawn website: [link](https://www.playstation.com/nl-nl/games/horizon-zero-dawn-ps4/)
* Text about Aloy Cosplay: [link](https://www.kamuicosplay.com/2017/09/15/aloy/)

**Special thanks:**
* My Yoda-mentor [Simen Daehlin](https://github.com/Eventyret) for being there when I lost my way and didnt know how to get back and for showing me a README file I actually understood and could use (Geomint; you rock!) and just the kick-ass person he is! (even tho you are horde!).

* Everybody at Slack for their support, tips and humor!

* [Richard Williams](https://github.com/RichardWilliams) , for a second pair of eyes and his git knowledge.

For his undying love and support and always being there, my love, you know who you are ;) 