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

|

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.



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

The following are bugs that I have come across while creating the AI Lib Site.

### HTML

- Bad value for attribute id on element img as by the HTML Validator, An ID must not be the empty string.
- To resolve this, I simply removed any id attribute to the img element(s).

- No alt attribute in an img element.
- This was resolved as it was the image element of the navbar and I simply gave it the alternative name, "menu".

- Text inserted directly in the "details" element as by HTML Validator, Text not allowed in element details in this context.
- I simply used the paragraph element, "p" to nest all text used in the details element(s).

- Text inserted directly in the "ol" element as by HTML Validator, Text not allowed in element ol in this context. (3)
- I used appropriate list elements to subdue the naked texts.

- Br used as child of "ol" as by HTML Validator, Element br not allowed as child of element ol in this context.
- I removed all br elements in my code.

- Certain elements were misplaced as stated by HTML Validator, "No li element in scope but a li end tag seen".
- I located such element and deleted the excesses.

- Text inserted directly into summary element, as stated by HTML Validator, "Text not allowed in element ___ in this context."
- To first fix this I made use of the p element to nest the text, however it still resulted in an error,
so I checked the W3C document recommended and used ChatGPT to provide me aid to this problem and I needed to use an inline element to wrap naked text unto
for a summary element.
I ended up using the "em" element but replaced it with the "span" element as the "em" made the 'overall look too much boldening to see'.

- Summary element at the wrong position inside the details element. This resulted in two errors thus stating,
"Element details is missing a required instance of child element summary."
,"Element summary not allowed as child of element details in this context."
- To fix this error I placed the summary element before the text rather than after.

- Used \ instead of / in creating paths for file documents.
- Simply used the forward slash characher(/) to put relative file paths.

- When making a button for the contact form, I nested a button element in an "a" element.
- I simply removed the button element and styled the "a" element to look like a button instead.

- <b>NOTE</b>: I made use of a W3C Validator Extension to make the testing process smoothier and faster. Note I still used the validation website afterwards!

### CSS

- Favicon would not display on GitHub pages deployed site, but would show locally.
- To fix this, I first tried changing the image, then changing the image name, but these did not fix the issue and after a little research it was noted that the link to where the image was located needed to have a '.' at the start of the link.

## Unfixed Bugs

There are no remaining bugs that I am aware of.
