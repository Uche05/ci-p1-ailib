# Testing

Return back to the [README.md](README.md) file.

## Table of Contents

<details>
<summary>Click here for Table of Contents</summary>

- [Code Validation](#code-validation)
  - [HTML](#html)
  - [CSS](#css)
  - [JavaScript](#javascript)

- [Browser Compatibility](#browser-compatibility)

- [Responsiveness](#responsiveness)

- [Accessibility](#accessibility)

- [Lighthouse Audit](#lighthouse-audit)

- [Defensive Programming](#defensive-programming)

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
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fboderg.github.io%2Fyour-weather%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | ![screenshot](documentation/validation/w3c-css-validator-results.png) | Pass: No Errors |

### JavaScript

I have used the recommended [JShint Validator](https://jshint.com) to validate all of my JS files.

| File | Screenshot | Notes |
| :---: | :---: | :---: |
| main.js | ![screenshot](documentation/validation/jshint-validation-warnings.png) | Missing semicolons |
| main.js | ![screenshot](documentation/validation/jshint-validation-pass.png) | Pass: No Errors |

## Browser Compatibility

I have tested Your Weather on the following browsers to check for compatibility issues.

| Browser | Main | About | Displayed °C | Displayed °F | Notes |
| :---: | :---: | :---: | :---: | :---: | :---: |
| [Chrome](https://www.google.com/chrome) | ![screenshot](documentation/browsers/chrome/chrome-main.png) | ![screenshot](documentation/browsers/chrome/chrome-modal.png) | ![screenshot](documentation/browsers/chrome/chrome-displayed-c.png) | ![screenshot](documentation/browsers/chrome/chrome-displayed-f.png) | Works as expected |
| [Firefox (Developer Edition)](https://www.mozilla.org/firefox/developer) | ![screenshot](documentation/browsers/firefox-dev/firefox-dev-main.png) | ![screenshot](documentation/browsers/firefox-dev/firefox-dev-modal.png) | ![screenshot](documentation/browsers/firefox-dev/firefox-dev-displayed-c.png) | ![screenshot](documentation/browsers/firefox-dev/firefox-dev-displayed-f.png) | Works as expected |
| [Edge](https://www.microsoft.com/edge)| ![screenshot](documentation/browsers/edge/edge-main.png) | ![screenshot](documentation/browsers/edge/edge-modal.png) | ![screenshot](documentation/browsers/edge/edge-displayed-c.png) | ![screenshot](documentation/browsers/edge/edge-displayed-f.png) | Works as expected |
| [Safari](https://support.apple.com/downloads/safari) | ![screenshot](documentation/browsers/safari/safari-main.png) | ![screenshot](documentation/browsers/safari/safari-modal.png) | ![screenshot](documentation/browsers/safari/safari-displayed-c.png) | ![screenshot](documentation/browsers/safari/safari-displayed-f.png) | Works as expected |
| [Brave](https://brave.com/download) | ![screenshot](documentation/browsers/brave/brave-main.png) | ![screenshot](documentation/browsers/brave/brave-modal.png) | ![screenshot](documentation/browsers/brave/brave-displayed-c.png) | ![screenshot](documentation/browsers/brave/brave-displayed-f.png) | Works as expected |

## Responsiveness

I have tested my deployed project on multiple devices to check for responsiveness issues.

<details>
<summary>Click for report</summary>

| Device | Main | About | Displayed °C | Displayed °F | Notes |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Mobile (DevTools - iPhone SE) | ![screenshot](documentation/responsiveness/mobile-dev-tools/mobile-dev-main.png) | ![screenshot](documentation/responsiveness/mobile-dev-tools/mobile-dev-modal.png) | ![screenshot](documentation/responsiveness/mobile-dev-tools/mobile-dev-c.png) | ![screenshot](documentation/responsiveness/mobile-dev-tools/mobile-dev-f.png) | Chrome dev tools were used, the site works as expected |
| Tablet (DevTools - iPad Air) | ![screenshot](documentation/responsiveness/tablet-dev-tools/tablet-main.png) | ![screenshot](documentation/responsiveness/tablet-dev-tools/tablet-modal.png) | ![screenshot](documentation/responsiveness/tablet-dev-tools/tablet-c.png) | ![screenshot](documentation/responsiveness/tablet-dev-tools/tablet-f.png) | Firefox dev tools were used, the site works as expected |
| 15" Laptop Mdpi | ![screenshot](documentation/responsiveness/15-inch-laptop/mdpi/laptop-main.png) | ![screenshot](documentation/responsiveness/15-inch-laptop/mdpi/laptop-modal.png) | ![screenshot](documentation/responsiveness/15-inch-laptop/mdpi/laptop-c.png) | ![screenshot](documentation/responsiveness/15-inch-laptop/mdpi/laptop-f.png) | Firefox was used, the site works as expected |
| 15" Laptop Hdpi | ![screenshot](documentation/responsiveness/15-inch-laptop/hdpi/laptop-main1.png) | ![screenshot](documentation/responsiveness/15-inch-laptop/hdpi/laptop-modal1.png) | ![screenshot](documentation/responsiveness/15-inch-laptop/hdpi/laptop-c1.png) | ![screenshot](documentation/responsiveness/15-inch-laptop/hdpi/laptop-f1.png) | Firefox (Developer Edition) was used, the site works as expected |
| 20" Desktop 1080p | ![screenshot](documentation/responsiveness/20-inch-desktop/safari-main.png) | ![screenshot](documentation/responsiveness/20-inch-desktop/safari-modal.png) | ![screenshot](documentation/responsiveness/20-inch-desktop/safari-displayed-c.png) | ![screenshot](documentation/responsiveness/20-inch-desktop/safari-displayed-f.png) | Safari was used, the site works as expected |
| 27" Desktop 1080p | ![screenshot](documentation/responsiveness/27-inch-desktop/edge-main.png) | ![screenshot](documentation/responsiveness/27-inch-desktop/edge-modal.png) | ![screenshot](documentation/responsiveness/27-inch-desktop/edge-displayed-c.png) | ![screenshot](documentation/responsiveness/27-inch-desktop/edge-displayed-f.png) | Edge was used, the site works as expected |
| 34" XL Monitor 1440p Ultrawide | ![screenshot](documentation/responsiveness/34-inch-desktop/34-desktop-main.png) | ![screenshot](documentation/responsiveness/34-inch-desktop/34-desktop-modal.png) | ![screenshot](documentation/responsiveness/34-inch-desktop/34-desktop-c.png) | ![screenshot](documentation/responsiveness/34-inch-desktop/34-desktop-f.png) | Firefox was used, the site works as expected |
| Samsung Galaxy S10 Plus | ![screenshot](documentation/responsiveness/galaxy-s10/chrome-main.jpg) | ![screenshot](documentation/responsiveness/galaxy-s10/firefox-dev-modal.jpg) | ![screenshot](documentation/responsiveness/galaxy-s10/edge-c.jpg) | ![screenshot](documentation/responsiveness/galaxy-s10/brave-forecast-f.jpg) | Chrome, Firefox (Developer Edition), Edge and Brave browsers were used, the site works as expected |

</details>

## Accessibility

I have tested my deployed project using the [WAVE](https://wave.webaim.org/) web accessibility evaluation tool to check for any accessibility issues.

| Page | Summary | Details | Contrast | Notes |
| :---: | :---: | :---: | :---: | :---: |
| Main | ![screenshot](documentation/wave/wave-summary.png) | ![screenshot](documentation/wave/wave-details.png) | ![screenshot](documentation/wave/wave-contrast.png) | A couple of minor notes about one label being missing from the search input field and a label missing from the search button, these were intentional as both items are titled and the input field has a placeholder. |

## Lighthouse Audit

I have tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| :---: | :---: | :---: | :---: |
| Main | ![screenshot](documentation/lighthouse/lighthouse-audit-mobile.png) | ![screenshot](documentation/lighthouse/lighthouse-audit-desktop.png) | Few minor warnings about load times on mobile |

- To improve the SEO score I have added a description meta tag to the HTML file.
- To improve the accessibility score I added titles to the buttons in the html file.

## Defensive Programming

Defensive programming was manually tested with the below user acceptance testing:

<details>
<summary>Click for report</summary>

| Page | Expectation | Test | Result | Fix | Screenshot |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Main | | | | | |
| | About Your Weather is expected to open a modal with information about the site when the user clicks on the About Your Weather button. | Tested the feature by clicking About Your Weather. | The feature behaved as expected, and it opened the modal. | Test concluded and passed. | ![screenshot](documentation/defensive/modal-open.png) |
| | An alert prompting the entry of a town or city name is expected to appear when the user clicks the search button while the input field is empty. | Tested the feature by clicking the search button with an empty input field | The feature behaved as expected, and activated an alert prompt. | Test concluded and passed. | ![screenshot](documentation/defensive/alert-prompt.png) |
| | The site is expected to fetch and display the weather data when the input field is populated and the search button is clicked. | Tested the feature by entering various city and town names and clicking the search button. | The feature behaved as expected. | Test concluded and passed. | ![screenshot](documentation/defensive/fetched-weather.png) |
| | The site is expected to fetch and display the weather data when the input field is populated and the 'Enter' key is pressed. | Tested the feature by entering various city and town names and pressing the 'Enter' key. | The feature did not respond to the 'Enter' key being pressed. | I added a keydown event listener for the 'Enter' key that would call the getWeather() function when pressed. | ![screenshot](documentation/defensive/enter-pressed.png) |
| | The Temperature toggle is expected to switch the weather data between metric and imperial measurements by calling the relevant api data. | Tested the feature by clicking on the toggle switch. | The feature behaved as expected. | Test concluded and passed | ![screenshot](documentation/defensive/metric.png) ![screenshot](documentation/defensive/imperial.png) |
| | The GitHub link in the footer is expected to open my main GitHub page in a new browser tab. | Tested the feature by clicking the link. | The feature behaved as expected. | Test concluded and passed. | ![screenshot](documentation/defensive/my-github.png) |
| About Modal | | | | | |
| | The GitHub repository link is expected to open the sites GitHub repository in a new browser tab when the user clicks the link. | Tested the feature by clicking the link. | The feature behaved as expected, and opened the sites GitHub repository on a new tab. | Test concluded and passed. | ![screenshot](documentation/defensive/repo-link-test.png) |
| | The Modal is expected to close when the user clicks on the 'x'. | Tested the feature by clciking on the 'x'. | The feature behaved as expected. | Test concluded and passed. | ![screenshot](documentation/defensive/modal-close.png) |
| |  The Modal is expected to close when the user clicks away from the modal. | Tested the feature by clicking away from the modal. | The feature behaved as expected. | Test concluded and passed. | ![screenshot](documentation/defensive/modal-close.png) |
| 404 Page | | | | | |
| | The 404 page is expected to appear if an incorrect page url is entered. | Tested the feature by enetering an extended url. | The feature behaved as expected. | Test concluded and passed. | ![screenshot](documentation/defensive/404-page.png) |
| | The Home button on the 404 page is expected to return the user to the main page. | Tested by clicking the Home button. | The feature did not return to the main page. | I fixed this by changing the link from internal to external and the feature now returns to the main page. | ![screenshot](documentation/defensive/return-main-error.png) ![screenshot](documentation/defensive/return-main.png) |

</details>

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

- Timezone displayed instead of city - The data being displayed was pulled from the timezone and not the city name.

| Original image | Bug fixed image |
| :---: | :---: |
| ![screenshot](documentation/bugs/miami-new-york-timezone.png) | ![screenshot](documentation/bugs/miami-city.png) |
| ![screenshot](documentation/bugs/hendon-london-timezone.png) | ![screenshot](documentation/bugs/hendon-town.png)

- To fix this I removed the const variable that was calling that data from the api enabling the HTML to use the place name from the input field instead.

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

| Error | Screenshot | Description |
| :---: | :---: | :---: |
| Permission policy error - Chrome devtools gives this google floc warning on the version that I am using. It appears to be a deprecated trial for data collection instead of using cookies. | ![screenshot](documentation/bugs/google-floc-warning.png) | I was unsuccessful at fixing this, however this does not affect the operation of the site and this trial operation is also blocked by GitHub as it breaks privacy policy. |
| The 404 page does not pick up the css if an error is created on the end of a .html url. | e.g. boderg.github.io/your-weather/index.html/data ![screenshot](documentation/bugs/html-error.png) | I was unable to fix this error but the 404 error does appear and the link button does work to return to the main page. I feel this is acceptable as it is an unlikely scenario to enter a url in this fashion. |

There are no remaining bugs that I am aware of.
