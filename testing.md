# M&H DIstributons -  Testing Documentation

![M&H Distributions site shown on multiple screen sizes](assets/images/readme/web-responsiveness.png)

Visit the deployed site: [M&H Distribution](https://mubashirgit1.github.io/mhdistribution/)

- - -

## CONTENTS

* [AUTOMATED TESTING](#AUTOMATED-TESTING)
  * [W3C Validator](#W3C-Validator)
  * [W3C CSS MarkUP Validator ](#W3C-CSS-Validator)
  * [Lighthouse](#Lighthouse)
* [MANUAL TESTING](#MANUAL-TESTING)
  * [Testing User Stories](#Testing-User-Stories)
  * [Full Testing](#Full-Testing)

Testing was ongoing throughout the entire build. We utilised Chrome developer tools whilst building to pinpoint and troubleshoot any issues as we went along.

Each page has been inspected using google chrome developer tools & Firefox inspector tool to ensure that each page is fully responsive on a variety of different screen sizes and devices. We have also physically tested the responsiveness of the site on a number of different devices.

- - -

## AUTOMATED TESTING

### W3C Validator

[W3C](https://validator.w3.org/) was used to validate the HTML on all pages of the website. It was also used to validate the CSS.

A warning relating to the use of the aria-label in the `<i>` tag was flagged as being a possible misuse of the label. This is due to the bootstrap class for the icons to allow the icons to be accessible friendly (taken from the documentation for bootstrap5), and can therefore be ignored.
__Update April 2025__
Further research into this matter suggests that moving the aria-label into the parent `<a>` tag will remove the above error relating to the misuse of the label.
An Error to remove pixel unit from width and height of img attritbute from our project 
* [Index Page W3C HTML Validation](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmubashirgit1.github.io%2Fmhdistribution%2F) - Pass
* [About US W3C HTML Validation](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmubashirgit1.github.io%2Fmhdistribution%2Fabout.html) - Pass
* [Contact US Page W3C HTML Validation](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmubashirgit1.github.io%2Fmhdistribution%2Fcontact.html) - Pass
* [All threads Page W3C HTML Validation](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmubashirgit1.github.io%2Fmhdistribution%2Fthanks.html%3F) - Pass


- - -

### W3 CSS Validator

[jigsaw.w3](https://jigsaw.w3.org/css-validator) was used to validate the Cascading styling sheet.

* [style.css CSS Validation](assets//testing/css-validation.png) - Pass

- - -

### Lighthouse

I used Lighthouse within the Chrome Developer Tools to test the performance, accessibility, best practices and SEO of the website.

### Desktop Results

* Index Page
  ![Index Page lighthouse testing desktop](documentation/testing/lighhouse-index-dp.png)

* About Page
  ![ABout Page Lighthouse testing desktop](documentation/testing/lighthouse-about-dp.png)
  
* Contact Page
  ![Contact Page Lighthouse testing desktop](documentation/testing/lighthouse-contact-dp.png)
  
* Thank you Page
  ![Thanks you page lighthouse testing desktop](documentation/testing/lighthouse-thanks-dp.png)

### Mobile Results

* Index Page
  ![Index Page lighthouse testing Mobile](documentation/testing/lighthouse-index-mobile.png)

* About Page
  ![ABout Page Lighthouse testing Mobile](documentation/testing/lighthouse-about-dp.png)
  
* Contact Page
  ![Contact Page Lighthouse testing Mobile](documentation/testing/lighthouse-contact-mobile.png)
  
* Thank you Page
  ![Thanks you page lighthouse testing Mobile](documentation/testing/lighthouse-thanks-mobile.png)

- - -

## MANUAL TESTING

### Testing User Stories
