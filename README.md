# [AI Library](https://www.here.change.this.link "Click to view the deployed site")

- AI Library is a static site that shares basic knowledge about.
- The AI Library has been designed so that users at any level, who can read, write, and understand text (mainly in English), and have a drive to learn about AI, can easily comprehend its contents.
- AI Library is especially handy for those wish to learn more about AI and its history and state of the arts.
- AI Library showcases fundamental AI knowledge as well as advise to the generation where it has become more efficient.
- AI Library has ---.
- AI Library is the AI website  for everyone. The wikifandom website for just for knowing about AI.

## Table of Contents

<details>
<summary>Click here for Table of Contents</summary>

[Mockup Screenshots](#mockup-screenshots)

[UX](#ux)

- [Colour Scheme](#colour-scheme)
- [Typography](#typography)

[User Stories](#user-stories)

- [New site Users](#new-site-users)
- [Returning Site Users](#returning-site-users)

[Wireframes](#wireframes)

- [Mobile Wireframes](#mobile-wireframes)
- [Tablet Wireframes](#tablet-wireframes)
- [Desktop Wireframes](#desktop-wireframes)

[Features](#features)

- [Existing Features](#existing-features)
- [Future Features](#future-features)

[Testing](#testing)

[Deployment](#deployment)

- [Local Deployment](#local-deployment)

  - [Cloning](#cloning)
  - [Forking](#forking)

- [Local vs Deployment](#local-vs-deployment)

[Credits](#credits)

- [Content and Code](#content-and-code)

- [Media](#media)

- [Acknowledgments](#acknowledgements)

</details>

## Mockup Screenshots

Below are two mockup images of the AI Library website created using the "Am I Responsive" website <a href="https://ui.dev/">here</a>.

| Screenshot 1 | Screenshot 2 |
| :---: | :---: |
| ![screenshot](documentation/mockups/Am%20I%20Responsive1.png) | ![screenshot](documentation/mockups/Am%20I%20Responsive2.png) |

## UX

- The design for AI Library was created as a series of wireframes covering mobile, tablet and desktop to determine the initial design and layout of the site.
- AI Library site was designed with ease of use and simplicity in mind.
- A simple clean look was built so that all a user needs to do is enter their town or city name and click search.

### Colour Scheme

- The chosen colour scheme for AI Library is designed to be inviting and have a neutral aesthetic while giving a nice splash of colour.
- The colours used are as follows:-

- `#03045E` used for primary text.
- `#0077B6` used for primary highlights.
- `#` used for secondary text.
- `#fafafa` used for secondary highlights.
- `#7f0ffb and #c27b6f` combined to create a linear gradient background.
- `#000` used for box shadows and modal background.

I used [coolors.co](https://coolors.co/7f0ffb-c27b6f-9ecffa-fafafa-000000) to generate my colour palette.

<details>
<summary>Click for Coolors screenshot</summary>

![screenshot](documentation/ux/Create%20a%20Palette%20-%20Coolors.png)

</details><br>

I have used CSS `:root` variables to easily update the global colour scheme by changing only one value, instead of everywhere in the CSS file.

```css
:root {
  --display-background: linear-gradient(135deg, #7f0ffb, #c27b6f);
  --text-color: #9ecffa;
  --text-hover-color: #fafafa;
  --box-shadow-color: #000;
  --drop-shadow-color: #9ecffa;
  --modal-background: rgba(0, 0, 0, 0.4);
}
```

### Typography

- I used the Google Font called 'Play' for the AI Library site.
- I felt that this font had a nice modern style that is easy to read and that it fitted well with the AI Library site.

- [Play](https://fonts.google.com/specimen/Play) was used for all text within the site.

- [Font Awesome](https://fontawesome.com) icons were used in the AI Library site, for GitHub links in the footer and modal and for the search icon in the main weather card.

## User Stories

### New Site Users

- As a new site user, I would like to know what the site is about, so that I understand what the site does

### Returning Site Users

- As a returning site user, I would like to 
![screenshot](documentation/ux/Create%20a%20Palette%20-%20Coolors.png)

### Future Site Users

- As a future site user, I would like to

## Wireframes

I made use of pen and paper to make the wireframes of my website.


### Mobile Wireframes

| Main page | About modal | Displayed weather |
| :---: | :---: | :---: |
| ![screenshot](documentation/wireframes/mobile-main-page.png) | ![screenshot](documentation/wireframes/mobile-about-modal.png) | ![screenshot](documentation/wireframes/mobile-displayed-weather.png) |

### Tablet Wireframes

| Main page | About modal | Displayed weather |
| :---: | :---: | :---: |
| ![screenshot](documentation/wireframes/tablet-main-page.png) | ![screenshot](documentation/wireframes/tablet-about-modal.png) | ![screenshot](documentation/wireframes/tablet-displayed-weather.png) |

### Desktop Wireframes

| Main page | About modal | Displayed weather |
| :---: | :---: | :---: |
| ![screenshot](documentation/wireframes/desktop-main-page.png) | ![screenshot](documentation/wireframes/desktop-about-modal.png) | ![screenshot](documentation/wireframes/desktop-displayed-weather.png) |

## Features

### Existing Features

| Feature | Description | Screenshot |
| :---: | :---: | :---: |
| **About AI Library** | The 'About AI Library' button opens a modal that gives a little information about the site and it's creator. | ![screenshot](documentation/features/modal-button.png) |
| **About AI Library Modal** | The 'About AI Library Modal' displays what the site is about, what you can do on the site and why the site was created. It also contains links to the repository and where it is hosted. | ![screenshot](documentation/features/modal.png) ||
| **Footer** | The footer contains a link to the creators GitHub along with the project details. | ![screenshot](documentation/features/footer.png) |

### Future Features

- Comment Section so others can contribute and or ask questions which can also ne answered by other users.

## Tools & Technologies Used

- [HTML](https://en.wikipedia.org/wiki/HTML) used for the main site content.
- [CSS](https://en.wikipedia.org/wiki/CSS) used for the main site design and layout.
- [CSS :root variables](https://www.w3schools.com/css/css3_variables.asp) used for reusable styles throughout the site.
- [CSS Flexbox](https://www.w3schools.com/css/css3_flexbox.asp) used for an enhanced responsive layout.
- [Git](https://git-scm.com) used for version control. (`git add`, `git commit`, `git push`)
- [GitHub](https://github.com) used for secure online code storage.
- [GitHub Pages](https://pages.github.com) used for hosting the deployed front-end site.
- [VSCode](https://code.visualstudio.com/) used for local IDE for development.
- [Favicon.cc](https://www.favicon.cc/) used to create the favicon.
- [Google Fonts](https://fonts.google.com/) used to search a suitable font and obtain a download link for that font.
- [Font Awesome](https://fontawesome.com/) used to add GitHub icon to the footer and modal and search icon to the search button.

## Testing

- I tested my static site usong the following tools and here are the results.


## Deployment

The site was deployed to GitHub Pages. The steps to deploy are as follows:

- In the [GitHub repository](https://github.com/boderg/your-weather), navigate to the Settings tab.
- From the source section drop-down menu, select the **Main** Branch, then click "Save".
- The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://boderg.github.io/your-weather).

### Local Deployment

This project can be cloned or forked in order to make a local copy on your own system.

#### Cloning

You can clone the repository by following these steps:

1. Go to the [GitHub repository](https://github.com/boderg/your-weather).
2. Locate the Code button above the list of files and click it.
3. Select if you prefer to clone using HTTPS, SSH, or GitHub CLI and click the copy button to copy the URL to your clipboard.
4. Open Git Bash or Terminal.
5. Change the current working directory to the one where you want the cloned directory.
6. In your IDE Terminal, type the following command to clone my repository:
    - `git clone https://github.com/boderg/your-weather.git`
7. Press Enter to create your local clone.

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/boderg/your-weather).

Please note that in order to directly open the project in Gitpod, you need to have the browser extension installed.
A tutorial on how to do that can be found [here](https://www.gitpod.io/docs/configure/user-settings/browser-extension).

#### Forking

By forking the GitHub Repository, we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original owner's repository.
You can fork this repository by using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/boderg/your-weather).
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account.

### Local vs Deployment

There are no notable differences between my local developed site and the GitHub pages deployed site.

## Credits

The following are credits to various people and technologies that have directly or otherwise assisted in the creation of the AI Library site.

### Content and Code

| Source | Location | Notes |
| --- | --- | --- |
| [Markdown Builder](https://tim.2bn.dev/markdown-builder) | README and TESTING | tool to help generate the Markdown files |
| [W3Schools](https://www.w3schools.com/howto/howto_css_modals.asp) | Main page | interactive pop-up (modal) for the about section |
| [W3Schools](https://www.w3schools.com/howto/howto_css_switch.asp) | Main page | interactive toggle switch |
| [Wikipedia](https://en.wikipedia.org/wiki/List_of_short_place_names) | |  |

### Media

| Source | Location | Type | Notes |
| --- | --- | --- | --- |
| [Unsplash](https://source.unsplash.com/random?landscape) | Main changing background | image | Landscape image selection |

### Acknowledgements

- I would like to thank my Code Institute mentor, [Chris Quinn](https://github.com/10xOXR) for their support throughout the development of this project.
- I would like to thank [Code Institute](https://codeinstitute.net) for giving me the opportunity to complete the P1 course.
- I would like to thank the [Code Institute](https://codeinstitute.net) facilitator team [Iris Smok](https://github.com/Iris-Smok/Iris-Smok) and Irene Neville for their advice.
- I would like to thank the [Code Institute Slack community](https://code-institute-room.slack.com) for the moral support and general information that helps with my studies.
- I would like to thank my family, for their support and understanding, for believing in me, and allowing me to make this transition into software development.
