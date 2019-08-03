  <br>
    <img width="150" height="150" src="https://i.imgur.com/HCClYwF.png" />
  <br>
  <br>
  <br>
</p>

# Awesome Polyfills for the Browser
🛠️A curated list of awesome things related to browser polyfills
Polyfills help standardize the HTML, Javascript and CSS support across web browsers. 

## Contents
## Introduction
### Native Usage Score
The native usage score indicates how common this feature is supported natively. The score is based on caniuse.com and is quite strict by purpose. Please note, that this score has nothing to do with the polyfill itself. This doesn't indicate how good / bad the polyfill is, only how much it is needed. 
- ![#2aed11](https://placehold.it/12/2aed11/000000?text=+) `High Native Support` - Indicates that at least 90% of all browsers support this feature natively.
- ![#f0cb13](https://placehold.it/12/f0cb13/000000?text=+) `Moderate Native Support` - Indicates that at least 70% of all browsers support this feature natively.
- ![#fa3e00](https://placehold.it/12/fa3e00/000000?text=+) `Low Native Support` - Anything below.
- ![#fa3e00](https://placehold.it/12/fa3e00/000000?text=+) `Obsolete` - A feature that is obsoloted, and should not be used nor polyfilled.

### How Polyfills are picked
The main polyfill suggested is always the one that is the easiest to implement, the most stable and with the least depencencies. If there is another good / better option that requires a build tool or a framework, it might still be shown inside the polyfill description.
Labels:
- **Experimental** means that the project or the feature is still not quite production-ready.
- **Stable** indicates that the project is widely adopted and can be used in production.
- **No Dependencies** - the project has no third party dependencies (e.g jQuery).

Important note on the suggested Polyfills: The polyfills suggested just make things "work". Most solutions are not aimed at aestethics.

## HTML Polyfills
In almost all cases, Modern HTML tags do not require polyfills, with the exception of some few, relatively uncommon tags.

### New HTML Tags Polyfills
(Work in Progress!)
Polyfill for new HTML Tags that are not supported in old browsers. 
- <[Custom Elements](https://github.com/webcomponents/polyfills/tree/master/packages/webcomponentsjs)> (**Experimental, No Dependencies**) - ![#fa3e00](https://placehold.it/12/fa3e00/000000?text=+) `Low Native Support` This allows the developer to define new HTML tags (Web components). *Note: While there are other polyfills available, all of them, including the one suggested, are rather experimental.*

### Uncommon HTML Tags Polyfills
Polyfills for HTML tags that are not as common or not standardized across all major browsers.

 - <[details](https://github.com/rstacruz/details-polyfill)> (**Stable, No Dependencies**) - ![#2aed11](https://placehold.it/12/2aed11/000000?text=+) `High Native Support` The details tag specifies details that the user can view or hide on demand. 
 - <[dialog](https://github.com/rstacruz/details-polyfill)> (**Stable, No Dependencies**) - ![#f0cb13](https://placehold.it/12/f0cb13/000000?text=+) `Moderate Native Support` the dialog tag create a dialog box that can be displayed as a modal or a window to the user.

Old date and time related input types: (Most Polyfills are old and require old dependencies):
  - <[input type="datetime-local"](https://github.com/jonstipe/datetime-local-polyfill)> - ![#f0cb13](https://placehold.it/12/f0cb13/000000?text=+) `Moderate Native Support`.
   - <[input type="time"](https://github.com/jonstipe/time-polyfill)> Tag - ![#f0cb13](https://placehold.it/12/f0cb13/000000?text=+) `Moderate Native Support`.
   - <[input type="date"](https://github.com/liorwohl/html5-simple-date-input-polyfill)> - ![#f0cb13](https://placehold.it/12/f0cb13/000000?text=+) `Moderate Native Support`.
   - <[input type="month"](https://github.com/jonstipe/month-polyfill)> - ![#f0cb13](https://placehold.it/12/f0cb13/000000?text=+) `Moderate Native Support`.
   - <[datalist](https://github.com/mfranzke/datalist-polyfill)> - ![#f0cb13](https://placehold.it/12/f0cb13/000000?text=+) `Moderate Native Support`. A tag that offers the user to ener a custom value while still being able to pick a value from a defined list.
 
### Deprected HTML Tags Polyfills
Polyfills for deprected HTML tags that are no longer supported in modern browsers. 
*Please avoid using these tags*

 - <[Blink](https://github.com/contra/blink-polyfill)> - ![#fa3e00](https://placehold.it/12/fa3e00/000000?text=+) `Obsolete` The blink tag flashes the enclosed text. *Note: The polyfill utilize CSS to achieve the same effect.*
  - <[input type="datetime"](https://github.com/jonstipe/datetime-polyfill)> - ![#fa3e00](https://placehold.it/12/fa3e00/000000?text=+) `Obsolete` *Note: There is also a modern Polymer polyfill which includes some other features -[here](https://github.com/fooloomanzoo/datetime-picker)*

## CSS Polyfills

## New CSS Features Polyfills
Polyfills for features that were introduced in CSS3.
 - { display: grid }(https://github.com/FremyCompany/css-grid-polyfill/) (**Stable, No Dependencies**) - ![#2aed11](https://placehold.it/12/2aed11/000000?text=+) `High Native Support` *Note: There are other grid polyfills, but this one seems to be the most stable and maintained.*
 - { display: flex }(https://github.com/jonathantneal/flexibility) (**No Dependencies**) - ![#2aed11](https://placehold.it/12/2aed11/000000?text=+) `High Native Support` *Note: There are other flexbox polyfills. All of them seemed to have some limitations.*
  - <CSS Variables(https://github.com/aaronbarker/css-variables-polyfill)> (**No Dependencies**) - ![#2aed11](https://placehold.it/12/2aed11/000000?text=+) `High Native Support` *Note: There is another, younger project that only aims to polyfill IE11 [link](https://github.com/nuxodin/ie11CustomProperties)*

## Deprecated CSS Features Polyfills


