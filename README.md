# Dungeon Squads

[View the deployed site here](https://adowlin.github.io/project-1-dungeons-dragons/)

Dungeon Squads is a website for an online "Dungeons and Dragons" gaming community. It will bring people together who are looking for a safe, social, gaming space.
The website was created for my first milestone project as part of the Diploma in Full Stack Software Development course with Code Institute. The website is responsive on all device sizes.

<img src="/readme-assets/dungeons-mockups.png" alt="color palette" style="width:600px;height:400px;">
 
## User Experience (UX)
 
With varying degrees of lockdowns due to the Coronavirus pandemic, it can be hard to make new friends, or keep in touch with existing friends. One could easily find themselves feeling isolated, 
even with the prevelance of social media.

This online community will advance the user's goals by providing them with an opportunity to connect with other gamers in a fun, safe environment, and by allowing them to easily learn the 
basics of the "Dungeons and Dragons" game. It will also advance the site owners goals of growing their community, and spreading knowledge of and enthusiasm for the "Dungeons and Dragons" game.

### User Stories
    
- As a first-time visitor I want to:
    
    1. Find information about how the online community works.
    2. Find out times of group meetups.
    3. Learn the basics of how to play "Dungeons & Dragons". 
    4. Quickly and easily sign up to the community.
    5. Find out how to get in contact with the site owners with any questions.

- As a returning visitor, I want to:
    
    1. Find information about when other groups meet.
    2. Sign up to a new group if my existing group's time no longer suits.
    3. Download the rulebook to refresh my knowledge.

### Design
    
- Colour Scheme

    <img src="/readme-assets/color-palette.png" alt="color palette" style="width:400px;height:300px;">

    - Colour palette was generated using [coolors.co](https://coolors.co/). I chose this palette as it offers nice contrasts, and the colours fit with the theme of the website.

- Typography

    - Using [Google Fonts](https://fonts.google.com/), I chose [Exo](https://fonts.google.com/specimen/Exo) for the website's main text, and [Montserrat](https://fonts.google.com/specimen/Montserrat) 
    for the website's headers.

### Wireframes

- Wireframes were created using [Balsamiq](https://balsamiq.com/):

    - [All wireframes PDF](/readme-assets/dungeon-squads-wireframes.pdf)

- Flowchart created using [draw.io](https://app.diagrams.net/):

    - [Flowchart PDF](/readme-assets/dungeons-sitemap.pdf)


## Features

### Existing Features

- Landing page with hero image: allows users to see the purpose of the website, most important information (such as how the community works, and benefits of joining), and call to action button, immediately upon visiting site.

- Navigation header: allows users to easily navigate between site pages, and return to the home page by clicking the logo, without relying on browser navigation buttons.

- Footer: allows users to navigate to Dungeon Squads' social media profiles.

- Sign up form modal: allows users to input their details to join the community, and allows the site owner to collect relevant information about the users who are signing up.

- Meetup Times page: allows users to easily find out what times each group meets, and where the groups are located, in the case where they would like to join a local group.

- How To Play page: allows first-time players to quickly learn about the basics of the "Dungeons & Dragons" game, and allows both first-time and experienced players to download the game rule book.

- Contact page: allows users to send any questions they might have to the site owners.

- Responsive: this website was developed with a "mobile-first" practise, allowing it to be responsive on all device sizes.

- Interactive elements: buttons and icons are desinged to elicit a positive emotional response from users, which will help advance the site owner's goals of increasing community sign ups.

### Features Left to Implement

- Download rule book and character sheets via links in Footer.
- Add a map to the Meetup Times page to portray locations of the groups.

## Technologies Used

- Languages Used
    
    - [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - [CSS3](https://en.wikipedia.org/wiki/CSS)

- Frameworks, Libraries, & Programs Used

    - [Bootstrap 4.5.3](https://getbootstrap.com/):
        - Used to help styling aspects of the site, and to help with the responsivness of the site.

    - [Google Fonts](https://fonts.google.com/):
        - Used to import Montserrat & Source Sans Pro fonts.

    - [Font Awesome](https://fontawesome.com/):
        - Used to add icons accross the site, to enhance the user experience.

    - [Git](https://git-scm.com/):
        - Used via the Gitpod terminal to make regular commits, and push to GitHub.

    - [GitHub](https://github.com/):
        - Used to store the site's code.

    - [GitHub Pages](https://pages.github.com/):
        - Used to host the deployed site.

## Testing

### Testing User Stories from User Experience (UX) section
- As a first-time visitor I want to:
    
    1. Find information about how the online community works.
        - Upon entering the site, users are immediately geeted with lead text which breifly describes the purpose of the site: "Find Dungeons & dragons groups in your local area" & "Sign up for free & start playing!"
        - On viewing the Hero section, users are prompted to scroll down the page by the visibility of the top portion of the card deck at the bottom of the viewport. Upon scrolling, users are presented with further details about how the community works.
        - The user has three options; click the "Meetup Times" button to find out infomration about when groups meet, click the "Sign Up" call to action button to provide their details and join the community, or click the "How To Play" button to find out more information about the game, "Dungeons & Dragons".
    2. Find out times of group meetups.
        - The user is presented with two intuitive options to navigate to the "Meetup Times" page within the site; in the navbar presented at the top of the page uppon entering the site, and in the "Steps" cards presented when the user scrolls down through the home page.
        - Upon visiting the "Meetup Times" page on the site, the user is presented with a visually pleasing image carousel. The user is also given an invitation to scroll further down the page, through the use of a section heading and partial visibility of card deck.
        - Upon scrolling down the page, the card deck provides the user with the relevant information for each "Dungeon Squad" group; location, day, and time.
        - The user is then invited once again to join the community, through the use of a call-to-action button, labelled "Start Playing!".
    3. Learn the basics of how to play "Dungeons & Dragons". 
        - The user is presented with two intuitive options to navigate to the "How To Play" page within the site; in the navbar presented at the top of the page uppon entering the site, and in the "Steps" cards presented when the user scrolls down through the home page.
        - Upon visiting the "How To Play" page within the site, the user is presented with an option to play an engaging video which explains the "Dungeons & Dragons" game. The user may also choose to read the "What is Dungeons & Dragons?" summary, and the "Character Creation" summaries further down the page.
        - With both media and text-based options, the user is presented with ample information to choose from, to learn the basics of how to play the "Dungeons & Dragons" game.
    4. Quickly and easily sign up to the community.
        - Upon visiting the home page of the site, the user is immediately presented with two intuitive option to sign up to the community; the call-to-action "Sign Up Now!" button underneath the lead text, and the "Sign Up" button within the navbar at the top of the page.
        - As the user navigates throughout the site, they are continuously presented with opportunities to sign up to the community, with the placement of call-to-action buttons, labelled "Sign Up" or "Start Playing" on each page of the site.
        - Upon clicking one of the sign-up buttons, the user sees with a neatly presented modal, which includes a short and easy to understand form for the user to submit to join the community.
    5. Find out how to get in contact with the site owners with any questions.
        - On each page of the site, the user is presented with two intuitive options to contact the site owners; the "Contact" link within the site's navbar, and the social media icons within the site's footer.
        - Upon visiting the "Contact" page of the site, the user will see a visually pleasing hero image, overlayed with text which explains how to contact the site owners. The user is directed to "use the form below to send us a message!", which invites them to scroll down the page, where they are presented with an intuitive form, to submit their question to the site owners.
        - Upon hovering over any of the social media icon links that are presented in the footer, the user is met with a satisfying hover effect. This should ellicit a positive emotional response in the user, to encourage them to follow the link to contact the site owners.

- As a returning visitor, I want to:
    
    1. Find information about when other groups meet.
        - Returning users can quickly navigate the group meetup times page by clicking the "Meetup Times" link contained within the site's navbar.
    2. Sign up to a new group if my existing group's time no longer suits.
        - Returning users are able to easily fill out the sign up form from any page within the site, most easily from one of the initial call-to-action buttons that are presented upon visiting the home page.
    3. Download the rulebook to refresh my knowledge.
        - Returning users can quickly find a link to download the "Dungeons & Dragons rulebook, by intuitively navigating to the "How To Play" page within the site. When viewing the "How To Play" page, the user is presented with a button to download the rulebook, which opens a PDF download in a new browser tab.

### Bugs Found
- In Bootstrap buttons that were intended to link to other site pages, or link to a PDF download, the buttons originally didn't work as links - when the button were clicked, nothing happened.
    - Cause: I found that the cause of this issue was the use of `button` html elements.
    - Fix: I changed the `button` elements to `a` elements with `role="button"`.

- When viewing the deployed site on an iOS device, the background image of the hero section in index.html did not display in the correct position. 
The image appeared to be fixed to the top left corner, meaning just that corner of the image was visible, and the main focus area of the image was not visible.
    - Cause: I found that this was caused by having `background-attachment:fixed;` set in the CSS code for the image. The `fixed` value for `background-attachment` is not supported by iOS.
    - Fix: I changed the `backgound-attachment` attribute on the image to `scroll`, which allows the image to scroll with the rest of the webpage, and allowed the image to be positioned correctly on iOS. Root cause & fix found [here](https://stackoverflow.com/questions/19795830/background-image-not-scaling-properly-on-ios/19798729).
    - Screenshot: </br>
<img src="/readme-assets/ios-image-bug.png" alt="iOS image bug" style="width:400px;height:812px;">

## Deployment

The project used the [GitPod](https://www.gitpod.io/) environment during development, and used Git to commit and push to GitHub, using the terminal feature within GitPod.

### GitHub Pages
The project was deployed to GitHub Pages following the below steps:

1. Log in to GitHub and locate the [Repository](https://github.com/adowlin/project-1-dungeons-dragons)
2. In the Repository's nav menu, click on the "Settings" button
3. Scroll down in the Settings page to the "GitHub Pages" section
4. Click the dropdown labelled "None" under "Source", and select the "Master" branch"
5. Click the "Save" button, the page will automatically refresh
6. Scroll down the page again to the "GitHub Pages" section to locate the now published [link](https://adowlin.github.io/project-1-dungeons-dragons/)


## Credits

### Content
- Used bootstrap boilerplate from [here](https://github.com/Eventyret/vscode-bcdn)
- Used README.md templates & inspiriation from [here](https://github.com/Code-Institute-Solutions/readme-template) and from [this sample](https://github.com/Code-Institute-Solutions/SampleREADME)
- Created images for responsive design mockups in README.md using [Am I Responsive](http://ami.responsivedesign.is/#)
- Adapted callout section styling from Wiskey Drop site [here](https://github.com/adowlin/bootstrap-intro), created during intro to Bootstrap coursework
- box-shadow CSS code used on Sign Up Info section cards found [here](https://codepen.io/sdthornton/pen/wBZdXq)
- Found inspiration for Benefits section content [here](https://www.hercampus.com/school/winona/game-gain-5-benefits-playing-dungeons-and-dragons)
- Adapted Work History timeline for benefits section & social media links Footer list from [coursework project](https://github.com/adowlin/ucd-resume/blob/master/resume.html)

### Media
- Site images taken from [Unsplash](https://unsplash.com/)
- Video in how-to.html found [here](https://dnd.wizards.com/dungeons-and-dragons/what-is-dd)
- Text content & rulebook PDF taken from [official D&D website](https://dnd.wizards.com/dungeons-and-dragons/what-is-dd), [D&D and Beyond](https://www.dndbeyond.com/essentials/creating-a-character) and [Wikipedia](https://en.wikipedia.org/wiki/Dungeons_%26_Dragons).

### Acknowledgements
- My mentor for their kind & helpful feedback & guidance throughout the course of the project's development.
- My sister for also providing helpful guidance & tips, "sanity checks", and inspiration for the project's topic.