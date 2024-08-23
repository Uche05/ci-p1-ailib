# Testing

Return back to the [README.md](README.md) file.

## Table of Contents

<details>
<summary>Click here for Table of Contents</summary>

- [Code Validation](#code-validation)
  - [HTML](#html)
  - [CSS](#css)

- [Browser Compatibility](#browser-compatibility)

- [Responsiveness](#responsiveness)

- [Accessibility](#accessibility)

- [User Story Testing](#user-story-testing)

- [Bugs](#bugs)

- [Unfixed Bugs](#unfixed-bugs)

</details>

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Page | W3C URL | Screenshot | Notes |
| :---: | :---: | :---: | :---: |
| Main Page | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fboderg.github.io%2Fyour-weather%2F) | ![screenshot](documentation/validation/nu-html-checker-warnings.png) | Section lacks header h2-h6 warning |
| Main Page | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fboderg.github.io%2Fyour-weather%2F) | ![screenshot](documentation/validation/nu-html-checker-warnings.png) | Modal not allowed as child of body error |
| Main Page | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fboderg.github.io%2Fyour-weather%2F) | ![screenshot](documentation/validation/nu-html-checker-no-errors.png) | Fixed by adding an h1 heading and changing modal to div - Pass: No Errors or Warnings |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| File | Jigsaw URL | Screenshot | Notes |
| :---: | :---: | :---: | :---: |
| style.css | [Jigsaw](https://jigsa w.w3.org/css-validator/validator?uri=https%3A%2F%2Fboderg.github.io%2Fyour-weather%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | ![screenshot](https://github.com/Uche05/CI-PROJECTS-KUCJ/blob/main/documentation/testingshots/csscheck.png) | Pass: No Errors |

## Browser Compatibility

I have tested Your Weather on the following browsers to check for compatibility issues.

| Browser | Main | About | Displayed °C | Displayed °F | Notes |
| :---: | :---: | :---: | :---: | :---: | :---: |
| [Chrome](https://www.google.com/chrome) | ![screenshot](documentation/browsers/chrome/chrome-main.png) | ![screenshot](documentation/browsers/chrome/chrome-modal.png) | ![screenshot](documentation/browsers/chrome/chrome-displayed-c.png) | ![screenshot](documentation/browsers/chrome/chrome-displayed-f.png) | Works as expected |
| [Firefox (Developer Edition)](https://www.mozilla.org/firefox/developer) | ![screenshot](documentation/browsers/firefox-dev/firefox-dev-main.png) | ![screenshot](documentation/browsers/firefox-dev/firefox-dev-modal.png) | ![screenshot](documentation/browsers/firefox-dev/firefox-dev-displayed-c.png) | ![screenshot](documentation/browsers/firefox-dev/firefox-dev-displayed-f.png) | Works as expected |
| [Edge](https://www.microsoft.com/edge)| ![screenshot](documentation/browsers/edge/edge-main.png) | ![screenshot](documentation/browsers/edge/edge-modal.png) | ![screenshot](documentation/browsers/edge/edge-displayed-c.png) | ![screenshot](documentation/browsers/edge/edge-displayed-f.png) | Works as expected |

## Responsiveness

I have tested my deployed project on multiple devices to check for responsiveness issues.

<details>
<summary>Click for report</summary>

| Device | Main | About | Notes |
|---|---|---|---|

</details>

## Accessibility

I have tested my deployed project using the [WAVE](https://wave.webaim.org/) web accessibility evaluation tool to check for any accessibility issues.

| Page | Summary | Details | Contrast | Notes |
| :---: | :---: | :---: | :---: | :---: |
| Main | ![screenshot](documentation/wave/wave-summary.png) | ![screenshot](documentation/wave/wave-details.png) | ![screenshot](documentation/wave/wave-contrast.png) | Write on your problem faced from WAVE tool. |

## User Story Testing

| User Story | Screenshot |
| :---: | :---: |
| As a new site user, I would like to know what the site is about, so that I understand what the site does. | ![screenshot](documentation/features/modal.png) |
| As a new site user, I would like to search my local area, so that I can see what the weather is today. | ![screenshot](documentation/features/input-box.png) ![screenshot](documentation/features/search-button.png) |
| As a new site user, I would like to search my local area, so that I can see the forecast for the next few days. | ![screenshot](documentation/features/input-box.png) ![screenshot](documentation/features/search-button.png) |
| As a new site user, I would like to search other areas, so that I can see the weather in those areas. | ![screenshot](documentation/features/input-box.png) ![screenshot](documentation/features/search-button.png) |
| As a new site user, I would like to search other areas, so that I can se the forecast for those areas. | ![screenshot](documentation/features/input-box.png) ![screenshot](documentation/features/search-button.png) |
| As a returning site user, I would like to search a place I am visiting, so that I can see the weather and plan accordingly. | ![screenshot](documentation/features/input-box.png) ![screenshot](documentation/features/search-button.png) |
| As a returning site user, I would like to be able to change the format, so that I can view the weather in my native measurements. | ![screenshot](documentation/features/temp-toggle-f.png) ![screenshot](documentation/features/temp-toggle-c.png) |

## Bugs

The following are bugs that I have come across while creating the Your Weather site.
- Identified from using the HTML Validator to check my code intially, I made empty values for the id attribute in my nav-bar image element.
- From mr "Read Page" I made my 

***

- Initial Sunrise and Sunset times displayed as GMT timezone.

| Original image | Bug fixed image |
| :---: | :---: |
| ![screenshot](documentation/bugs/sunrise-set-gmt-date.png) | ![screenshot](documentation/bugs/sunrise-set-timezone-offset.png)

- To fix this I added a timezone offset and formatted the data to display only the time for the timezone of the city requested.

***

- Mixed content - This error prevented the deployed site from loading the weather data from the api.
- To fix this error I found he fix on MDN web docs and I edited all links that displayed as http:// to https://.

***

- Uncaught in promise error (network error) - This error was preventing the deployed site from fetching any data from the api but only while using Firefox, it was fine on other browsers.
- To fix this error I tried adding a catch to the geolocation api fetch but this broke the site. After a little research it turned out that by turning off the ad blocker extension I had on firefox the api was then able to fetch the data.
***

- Favicon would not display on GitHub pages deployed site, but would show locally.
- To fix this, I first tried changing the image, then changing the image name, but these did not fix the issue and after a little research it was noted that the link to where the image was located needed to have a '.' at the start of the link.

## Unfixed Bugs

There are no remaining bugs that I am aware of.
