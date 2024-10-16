# Ben Miles Rocks -  Testing

![The Ben Miles Rocks site shown on a variety of screen sizes](/assets/documentation/pages/home-1.png)

Visit the deployed site: [Ben Miles Rocks](https://benmilesrocks.github.io/1---Ben-Miles-Rocks/index.html)

- - -

## CONTENTS

* [AUTOMATED TESTING](#automated-testing)
  * [W3C Validator](#w3c-validator)
  * [Lighthouse](#lighthouse)
* [MANUAL TESTING](#manual-testing)
  * [Testing User Stories](#testing-user-stories)
  * [Full Testing](#full-testing)

Testing was ongoing throughout the entire build. I utilised Chrome developer tools whilst building to pinpoint and troubleshoot any issues as I went along.

During development I made use of Google developer tools to ensure everything was working correctly and to assist with troubleshooting when things were not working as expected.

I have gone through each page using Google Chrome developer tools & Microsoft Edge inspector tool to ensure that each page is responsive on a variety of different screen sizes and devices.

- - -

## AUTOMATED TESTING

### W3C Validator

**HTML Validation**

I used [W3C's HTML validator](https://validator.w3.org/) to check my code, and all the pages except music.html passed without issue. There was one result that I did not address intentionally:

- Error for using href attributes on button elements.

![music error 1](/assets/documentation/testing/music-err-1.png)

This code is part of the Bootstrap library, which alters how button elements work and allows the href attribute. Removing the href element would break the code and stop the buttons functioning properly. As a result I decided to leave this code as it is, as creating my own dropdown buttons would require JavaScript knowledge that falls outside the scope of this project.

**CSS Validation**

I used [W3C's Jigsaw Validator](https://jigsaw.w3.org/css-validator/) to test my site's CSS, which raised no issues.

![CSS Validation](/assets/documentation/testing/css-validation.png)

- - -

### Lighthouse

I used Lighthouse within the Chrome Developer Tools to test the performance, accessibility, best practices and SEO of the website.

**Index Page**

![Index Page Lighthouse](/assets/documentation/testing/index-lighthouse.png)

The best practices issues are being caused by Third Party Cookies from Google Fonts. The only resolution I could find for this would be hosting the fonts locally, but this could cause slow loading times for the site. As Google phases out the use of cookies on its site this is likely to be resolved, and so I decided not to take action at this stage.

![Index Page Lighthouse issues](/assets/documentation/testing/index-lighthouse-issues.png)

Developer tools also raised issues with Form Field elements not having a name or a label, but upon closer inspection this is code that applies to the embedded YouTube video player and as a result I did not take any action on this.

![Index Page Dev-Tools issues](/assets/documentation/testing/index-devtools-issues.png)

**Music Page**

![Music Page Lighthouse](/assets/documentation/testing/music-lighthouse.png)

The best practices issues are being caused by Third Party Cookies from Spotify. I was unable to find a resolution for this without removing the Spotify widget entirely. Given its utility I decided that this would not be suitable, as losing this feature would be a significant detriment to the site.

![Music Page Lighthouse issues](/assets/documentation/testing/music-lighthouse-issues.png)

Developer Tools also flagged an issue about a Depreciated Feature being used, but again this is part of the JavaScript for the embedded Spotify player.

![Music Page Dev-Tools issues](/assets/documentation/testing/music-devtools-issues.png)

**Contact Page**

![Contact Page Lighthouse](/assets/documentation/testing/contact-lighthouse.png)

Developer tools also recommended adding the Autocomplete attribute to the Name and Email fields on the contact form, which I updated.

**Message Sent Page**

![Message Sent Page Lighthouse](/assets/documentation/testing/message-sent-lighthouse.png)

- - -

## MANUAL TESTING

### Testing User Stories

**First Time Visitors**

| **Goals** | **How are they achieved?** |
| --- | --- |
| **I want to learn more about the artist Ben Miles**| |
| I want easy access to videos and music | Music Videos are placed prominently on the Home page, as well as being available on the Music page |
| I want information about live shows | Information about Live Shows is placed prominently on the Home page, making it clear when and where Ben Miles is playing next |
| I want links to social media sites where I can see and hear more | Social Media links are placed prominently in the Footer, which is pinned to the bottom of the page at all times |
| **I want the site to be responsive to my device**| The site was designed with responsiveness in mind, and has been tested on multiple devices to ensure functionality on all devices |
| **I want the site to be easy to navigate**| Navigation links are placed prominently in the page header, and the structure of the site has been kept as simple as possible for ease of use |

**Returning Visitors**

| **Goals** | **How are they achieved?** |
| --- | --- |
| **I want to find out when Ben Miles is next playing a show near me**| Information about Live Shows is placed prominently on the Home page, making it clear when and where Ben Miles is playing next |
| **I want to be able to purchase music and merchandise**| The Shop page is accessible from all points using the Navigation bar, as well as a clear call to action button on the Home page |
| **I want to contact the artist directly**| The Contact page has a simple form for users to complete, sending an email to the artist's inbox |

**Frequent Visitors**

| **Goals** | **How are they achieved?** |
| --- | --- |
| **I want to find out when Ben Miles is next playing a show near me**| Information about Live Shows is placed prominently on the Home page, making it clear when and where Ben Miles is playing next |
| **I want to be able to purchase music and merchandise**| The Shop page is accessible from all points using the Navigation bar, as well as a clear call to action button on the Home page |

- - -

### Full Testing

Full testing was performed on the following devices:

Desktop:
<ul><li>HP Envy All-in-one 32-a10</li></ul>

Mobile Devices:

<ul>
<li>Samsung Galaxy S20 FE</li>
<li>Samsung A20</li>
</ul>


Each device tested the site using the following browsers:

Google Chrome
Microsoft Edge
Firefox
Additional testing was taken by friends and family on a variety of devices and screen sizes. They reported no issues when using the site.


| **Feature** | **Expected Outcome** | **Testing Performed** | **Result** | **Pass/Fail** |
| --- | --- | ---- | --- | --- |
| **Navbar** | | | | |
| Home Button | Redirect to index.html | Clicked Home button on <ul><li>index.html</li> <li>music.html</li> <li>contact.html</li> <li>message-sent.html</li></ul> | Redirected to index.html | **PASS** |
| Music Button | Redirect to music.html | Clicked Music button on <ul><li>index.html</li> <li>music.html</li> <li>contact.html</li> <li>message-sent.html</li></ul> | Redirected to music.html | **PASS** |
| Contact Button | Redirect to contact.html | Clicked Contact button on <ul><li>index.html</li> <li>music.html</li> <li>contact.html</li> <li>message-sent.html</li></ul> | Redirected to contact.html | **PASS** |
| Shop Button | Redirect to [Big Cartel](https://benmilesrocks.bigcartel.com/) | Clicked Shop button on <ul><li>index.html</li> <li>music.html</li> <li>contact.html</li> <li>message-sent.html</li></ul> | Redirected to [Big Cartel](https://benmilesrocks.bigcartel.com/) | **PASS** |
| Navbar collapse | Navbar collapses on smaller screens | Shrank screen on <ul><li>index.html</li> <li>music.html</li> <li>contact.html</li> <li>message-sent.html</li></ul> clicked hamburger button & all links | Navbar collapsed, nav links worked as expected | **PASS** |
| **Footer** | | | | |
| Instagram Button | Redirect to [Facebook](https://www.instagram.com/benmilesrocks/) , open in a new tab | Clicked Instagram button on <ul><li>index.html</li> <li>music.html</li> <li>contact.html</li> <li>message-sent.html</li></ul> | Redirected to [Facebook](https://www.instagram.com/benmilesrocks/) , opened in a new tab | **PASS** |
| Facebook Button | Redirect to [Instagram](https://www.facebook.com/benmilesrocks) , open in a new tab | Clicked Instagram button on <ul><li>index.html</li> <li>music.html</li> <li>contact.html</li> <li>message-sent.html</li></ul> | Redirected to [Instagram](https://www.facebook.com/benmilesrocks) , opened in a new tab | **PASS** |
| YouTube Button | Redirect to [YouTube](https://www.youtube.com/user/benmilesrocks) , open in a new tab | Clicked Instagram button on <ul><li>index.html</li> <li>music.html</li> <li>contact.html</li> <li>message-sent.html</li></ul> | Redirected to [YouTube](https://www.youtube.com/user/benmilesrocks) , opened in a new tab | **PASS** |
| Spotify Button | Redirect to [Spotify](https://open.spotify.com/album/3jrzqHYCAxorthQZiSpANz?si=VbMDpkw7TYiBEDKZlp5-bg&nd=1&dlsi=33ec744ff523480c) , open in a new tab | Clicked Instagram button on index.html. music.html & contact.html | Redirected to [Spotify](https://open.spotify.com/album/3jrzqHYCAxorthQZiSpANz?si=VbMDpkw7TYiBEDKZlp5-bg&nd=1&dlsi=33ec744ff523480c) , opened in a new tab | **PASS** |
| **Home Page** | | | | |
| Call to Action Button | Redirect to Redirect to [Big Cartel](https://benmilesrocks.bigcartel.com/) | Clicked Call to Action button on index.html | Redirected to Redirect to [Big Cartel](https://benmilesrocks.bigcartel.com/) | **PASS** |
| Embedded Videos | Play video content | Clicked Play button on the three embedded videos | Video played from YouTube as expected | **PASS** |
| More Music link | Redirect to music.html | Clicked More Music link | Redirected to music.html | **PASS** |
| Responsive Elements | Medium screens should display two videos inline, remove border from hero image. Small screens should display two videos in blocks | Shrank screen size to 768px & 576px | At 768px hero image border removed, displayed 2 videos inline. At 576px displayed 2 videos in blocks. | **PASS** |
| **Music Page** | | | | |
| Embedded Videos | Play video content | Clicked Play button on the four embedded videos | Video played from YouTube as expected | **PASS** |
| Embedded Spotify Music | Play Music from Spotify, redirect to Spotify page with relevant links | Clicked: <ul><li>Play button</li> <li>Skip forward button</li><li>skip back button</li> <li>'Open in Spotify'</li> <li>'Save on Spotify'</li></ul> links. | Music played as expected, tracks skipped forward and back as expected. Links to Spotify opened artist page on Spotify. | **PASS** |
| Responsive Elements | Videos collapse on small screens, collapse buttons next to Videos and Music headers expand content | Shrank to small screen size, clicked collapse buttons next to Videos and Music headers & pressed space bar. | Content collapsed as expected. Buttons expanded and collapsed content correctly. | **PASS** |
| **Contact Page** | | | | |
| Contact Form | Should not submit unless all fields are completed | Tried submitting empty form, Name only, Email only, Message only, Name & Email, Name & Message, Email & Message | Would not submit | **PASS** |
| Contact Submit | Send message to veryloudrecords@mail.com using Web3Forms APIm redirect to message-sent.html | Sent message using Contact Form, clicked submit | Redirected to message-sent.html, mesage recieved by veryloudrecords@mail.com | **PASS** |   
| **Message Sent Page** | | | | |
| Home Button | Redirect to index.html | Clicked Home button | Redirected to index.html | **PASS** |

- - -