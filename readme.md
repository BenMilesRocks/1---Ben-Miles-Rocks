# Ben Miles Rocks



## Project Goals

This project is to create a website for blues musician Ben Miles.

[The deployed version of the site is available here](https://benmilesrocks.github.io/1---Ben-Miles-Rocks/)

The main priority for this website is to make it easier for fans to purchase merchandise directly from the artist. They already have a [Big Cartel](https://benmilesrocks.bigcartel.com/products) store in place, so links to this should be prominent at multiple points in the website.

A secondary goal is to act as a showcase for both new fans and people interested in booking Ben for live shows and Radio / TV appearances. This means embedding music and video into the page is a high priority, which is made easier by their previous work being readily available on YouTube and Spotify. 

Thirdly there is also the need to drive new fans to Ben's existing social media pages, so links to these will need to be promiently placed.

Finally, there is a strong drive to make this website easy to use on mobile devices. As a result the whole site will need to be responsive, resizing elements to best fit the screen they are being displayed on.


## Contents

* [User Experience](#user-experience)
    - [User Stories](#user-stories)
* [Design](#design)
    - [Color Scheme](#color-scheme)
    - [Typography](#typography)
    - [Imagery](#imagery)
    - [Wireframe](#wireframe#)
* [Features](#features)
* [Accessibility](#accessibility)
* [Credits](#credits)
* [Technologies Used](#technologies-used)
    - [Languages Used](#languages-used)
    - [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)
* [Deployment and Local Development](#deployment-and-local-development)
    - [Deployment](#deployment)
    - [Local Development](#local-development)
* [Testing](#testing)
    - [Solved Bugs](#solved-bugs)
    - [Known Bugs](#known-bugs)
* [Credits](#credits)
    - [Code Used](#code-used)
    - [Media](#media)
    - [Acknowledgements](#acknowledgements)


## User Experience (UX)


### User Stories

**First Time Visitor Goals**

* I want to learn more about the artist Ben Miles.
    - I want easy access to videos and music.
    - I want information about shows.
    - I want links to social media sites where I can see and hear more.
* I want the site to be responsive to my device.
* I want the site to be easy to navigate.

**Returning Visitor Goals**

* I want to find out when Ben Miles is next playing a show near me.
* I want to be able to purchase music and merchandise.
* I want to contact the artist directly.

**Frequent Visitor Goals**

* I want to keep up to date with live shows that are happening near me.
* I want to purchase music and merchandise.


## Design

### Color Scheme

The color palette was chosen with colours picked from the Hero Image on index.htmtl. The intention was to create a visual style that was cohesive and tied the Hero Image with the rest of the site, giving it an aesthetic continuity.

![Hero Image](/assets/images/hero-image.webp)


![Color Palette](/assets/documentation/color-palette.png)


The color palette was put together using [coolors.co](https://coolors.co/fafafa-0d1512-0a3342-c4c5c4-1f565d), using the color picker tool on the hero image to identify color hex values.

### Typography

Typography posed an interesting challenge in this site, as I wanted to maintain a simple, easy to read style whilst making it visually interesting and evocative at the same time.

All fonts were sourced through [Google Fonts](https://fonts.google.com/) not only for ease of use but also for reliability and stability.

I used the [Lato](https://fonts.google.com/specimen/Lato?query=lato) font for menu and body text, as this is a clear and simple san-serif font ideal for communicating information clearly.

![Lato Font](/assets/documentation/fonts/lato.png)

For the page Logo I used [Ultra](https://fonts.google.com/specimen/Ultra?query=ultra), which is a very bold serif font. This also is quite evocotive of old western movies which ties in nicely with the americana-influenced music that the page is showcasing, giving users a visual indication of the style of music that the artist plays.

![Ultra Font](/assets/documentation/fonts/ultra.png)

For the section headers I used [Diplomata SC](https://fonts.google.com/specimen/Diplomata+SC?query=Diplomata+SC), a bold serif font which is capitalised. Much like Ultra this is quite evocotive of old western movies, playing into the americana theme and giving the page a distinctive style that ties in with the music of the artist.

![Diplomata SC Font](/assets/documentation/fonts/diplomata-sc.png)

### Imagery

The Hero Image on index.html is a live photograph of the artist in concert, which was chosen to evoke the energy and tone of the live shows. Not only does this keep the subject of the site clear in the user's mind, but also helps create interest and communicates the type of music you would hear from this artist.

The other source of imagery is the video thumbnails found on index.html and music.html, which are very bright and colourful to tie in with the energy of the artist's music. Relying on these to convey imagery not only makes the site more engaging (as a video with music is going to hold the user's attention more than a still image) but it also plays into the site's philosophy of "let the music do the talking". It helps communicate the music of the artist in a clear and obvious manner without the need for excessive text that might bore visitors to the site.

### Wireframe

Wireframes were created for Mobile, Tablet and Desktop using Wireframe.cc .

**Homepage**

*Desktop*

![Homepage Wireframe - Desktop](/assets/documentation/wireframe/home/home-desktop.png)

*Tablet*

![Homepage Wireframe - Tablet](/assets/documentation/wireframe/home/home-tablet.png)

*Mobile*

![Homepage Wireframe - Mobile](/assets/documentation/wireframe/home/home-mobile.png)

**Music Page**

*Desktop*

![Music Page Wireframe - Desktop](/assets/documentation/wireframe/music/music-desktop.png)

*Mobile*

![Music Page Wireframe - Mobile](/assets/documentation/wireframe/music/music-mobile.png)

**Contact Page**

*Desktop*

![Contact Page Wireframe - Desktop](/assets/documentation/wireframe/contact/contact-desktop.png)

*Mobile*

![Contact Page Wireframe - Mobile](/assets/documentation/wireframe/contact/contact-mobile.png)

As you can see these wireframes have a navigation bar and social media links on the top and bottom of the site for Desktop and Tablet, which I changed during development to have the navigation at the top and the social media links in the footer. Not only was this clearer for the user to follow but it was more visually appealing as well.

I also added a drop-down menu for the navbar on Tablet, as this made the navigation menu easier to read on medium sized screens.

### Features

The website is comprised of a home page, music page, contact page and a message sent page.

All the pages are responsive and have

- a favicon in the browser tab

![Favicon](/assets/documentation/pages/favicon.png)

- a navigation bar and a logo, with the logo linking back to the home page

![Navbar](/assets/documentation/pages/navbar.png)

- a footer with social media links

![Footer](/assets/documentation/pages/footer.png)

**Home Page**

The Home Page displays the Hero Image of the artist and a call to action button linking to the artist's Big Cartel store.

In line with the brief from the client, this site uses minimal text to convey its message. The embedded YouTube videos make sure the artist's music is front and center, ensuring first time visitors are able to easily access music and hear more from the artist.

![Home Page](/assets/documentation/pages/home-1.png)

The site also displays a list of live dates, and links to where the user can purchase tickets. The [Live Nation Homepage](https://www.livenation.co.uk/) was used to test this facility, but in a full deployment this would link to tickets for the show advertised.

![Home Page](/assets/documentation/pages/home-2.png)


**Music Page**

The music page has more videos from the artist, which are also embedded from YouTube:

![Music Page](/assets/documentation/pages/music-1.png)

and also has a widget from Spotify to allow the user to listen to their full album:

![Music Page](/assets/documentation/pages/music-2.png)

As promoting the artist's social media accounts was one of the project's goals, it made more sense to use embedded video and music links rather than host this content locally. This way the user has the option to open this content in their YouTube or Spotify app directly, increasing the likelyhood that the user will listen to the music more as well as making the content easier to access for the user.

**Contact Page**

The contact form is fully functional, and will email a message directly to the artist's inbox using an API from [Web3Forms](https://web3forms.com/).

![Contact Page](/assets/documentation/pages/contact.png)

Once a message has been successfully sent, the form redirects them to a seperate landing page where they can go to another part of the site.

![Message Sent Page](/assets/documentation/pages/message-sent.png)

**Future Implementations**

In future implementations I would like to:

1. Add a portal for the site owner to add and remove live dates from the Homepage, allowing the site owner to keep this section updated without the need for a web developer.
2. Add a functioning Store page to the site, removing the need for users to purchase merchandise through the Big Cartel store and keeping the styling of the website for consistent user experience.
3. Create my own API for the contact page rather than relying on Web3Forms for this functionality.

These features fell outside the scope of this current project, but I do plan on revisiting this at a later date to add these features.

### Accessibility

I have worked hard to ensure the website is as easy to navigate and as accessible to disabled people as possible. To achieve this I:

- Used semantic HTML elements
- Added Aria tags to all links, buttons and content to ensure Screen Readers are able to comprehend it
- Used a San-Serif font for site navigation, to make it as easy to read as possible
- Used as little text as possible, to make sure the site is accessible to people who do not speak or read English
- Ensured contrasting colors were used throughout the site to keep elements easily idenitfiable and readable.

I also tested the site with the Chrome extension [Web Disability Simulator](https://chromewebstore.google.com/detail/web-disability-simulator/olioanlbgbpmdlgjnnampnnlohigkjla) to ensure the user experience was friendly to those with color blindness, parkinsons and dyslexia.

**Yellow-Blue Colorblindness**

![Yellow-Blue Colorblindness](/assets/documentation/pages/yellow-blue-colorblind.png)

**Red-Green Colorblindness**

![Red-Green Colorblindness](/assets/documentation/pages/red-green-colorblind.png)


## Technologies Used

### Languages Used

This website is built with HTML 5 and styled using CSS.

There are also JavaScript elements, but these are provided by external libraries (in particular [Boostrap](https://getbootstrap.com/) and [Web3Forms](https://web3forms.com/)).

### Frameworks, Libraries & Programs Used

I used [Bootstrap 5](https://getbootstrap.com/) framework to make use of its responsive elements, and [Web3Forms](https://web3forms.com/) for the API on the Contact page.

[Google Fonts](https://fonts.google.com/) and [Font Awesome](https://fontawesome.com/) icons for the Social Media links. 

[Favicon.io](https://favicon.io/) used to create the site's Favicon.

To edit my code I used Visual Studio, and I used Git for version control.

## Deployment and Local Development

### Deployment

The site is deployed using GitHub Pages - [Ben Miles Rocks](https://benmilesrocks.github.io/1---Ben-Miles-Rocks/)

To Deploy the site using GitHub Pages:

1. Login (or signup) to Github.
2. Go to the repository for this project, [BenMilesRocks/1---Ben-Miles-Rocks](https://github.com/BenMilesRocks/1---Ben-Miles-Rocks).
3. Click the settings button.
4. Select pages in the left hand navigation menu.
5. From the source dropdown select main branch and press save.
6. The site has now been deployed, please note that this process may take a few minutes before the site goes live.

### Local Development

**How to fork**

To fork the repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, [BenMilesRocks/1---Ben-Miles-Rocks](https://github.com/BenMilesRocks/1---Ben-Miles-Rocks).
3. Click the Fork button in the top right corner.

**How to clone**

To clone the repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, [BenMilesRocks/1---Ben-Miles-Rocks](https://github.com/BenMilesRocks/1---Ben-Miles-Rocks).
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

## Testing

Please refer to [testing.md](/assets/documentation/testing.md) for my manual testing logs.

### Solved Bugs

| **No.** | **Bug** | **How I Solved The Issue** |
|:--------|:-------:|:--------------------------:|
| 1 | Header was not reaching the full width of the screen on index.html and music.html | Removed gutters on Hero Image and Video containers |
| 2 | Contact form accepting whitespace validation | Added ' pattern=".*\S+.*" ' to name input field, preventing whitespace validation |

### Known Bugs

Whilst I was able to resolve the issue of whitespace validation on the Name field of the contact form, there is no way to apply this to the <textarea> element using HTML. As a result the form will still accept whitespace as a message. 

## Credits

### Code used

- I used code from [This post on Stack Overflow](https://stackoverflow.com/questions/13766015/is-it-possible-to-configure-a-required-field-to-ignore-white-space) to help resolve the issue of the contact form accepting whitespace validation.

- I used code from [This YouTube Video](https://www.youtube.com/watch?v=K8YrX15e31s) to prevent "Related Videos" coming up when videos are paused, improving user experience.

For site optimization I took a number of best practices from [web.dev](https://web.dev/), including

- This post about [Third Party Embedds](https://web.dev/articles/embed-best-practices)

- This post about [LCP](https://web.dev/articles/optimize-lcp)

### Media

The Hero Image on index.html is (C) Haluk Gurer 2018. 

Come Together written by John Lennon / Paul McCartney, video (C) Ben Miles 2014. Video shot and edited by [Snow Elk Productions](https://snowelkproductions.co.uk/).

King of the Road written by Ben Miles, video (C) Ben Miles 2017. Video shot and edited by [Loki Films](https://www.lokifilms.co.uk/).

What your Mamma Don't Know written by Ben Miles, video (C) Ben Miles 2019. Video shot and edited by [Nathan Bailey Producer](https://www.instagram.com/nathanbaileyproducer/?hl=en).

Lawman written by Ben Miles, video (C) Ben Miles 2014. Video shot and edited by [Lock Up Studios](https://www.instagram.com/lockupstudios/).

The album Great Unknown written by Ben Miles (except I Just Want to Make Love to You, written by Willie Dixon), (C) Ben Miles 2017. Recorded at [Electric Bear Studios](https://electricbearstudios.co.uk/book-now/) by Phil Wilbraham.

### Acknowledgements

I would like to acknowledge the following people

- Jubril Akolade - my Code Institute mentor

- Mia Edris for helping with the Media sources

- The Code Institute Slack channel Peer Code Review - thank you to everyone who tested the site and offered feedback