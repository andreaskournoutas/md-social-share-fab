# Material Design (2/3) based, social share FAB component

## Usage

### 1. Include the script in your HTML file, using the code below:

`<script src="https://andreaskournoutas.github.io/md-social-share-fab/button.js"></script>`

### 2. Include the code below in your HTML file, either in the <head> or before the </body>

`
mdSocialShareFab({
  container: "String, the ID of the HTML element that will contain the button, <body> if null",
  materialDesignVersion: "2 | 3",
  verticalPosition: "top | middle | bottom",
  verticalDistance: "In px, rem etc. (does not apply on 'middle' position option)",
  horizontalPosition: "left | center | right",
  horizontalDistance: "In px, rem etc. (does not apply on 'center' position option)",
  extendedBeforeScroll: "true | false",
  label: "String (Optional, applies only if extendedBeforeScroll is true, 'Share' if null",
  languageCode: "en, el etc."
});
`
