# [Custom checkbox CSS](https://lebryere.github.io/Custom-checkbox-CSS/)

## Browser Support

![Chrome](https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Edge](https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![Firefox](https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Safari](https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png) | ![Samsung Internet](https://raw.githubusercontent.com/alrra/browser-logos/master/src/samsung-internet/samsung-internet_48x48.png)
--- | --- | --- | --- | --- | --- |
98+ ✔ | 98+ ✔ | 88+ ✔ | 82+ ✔ | 85+ ✔ | 75+ ✔ |

## Preview

**[View Live Preview](https://lebryere.github.io/Custom-checkbox-CSS/)**

## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-green?&style=plastic)](https://github.com/LeBryere/Custom-checkbox-CSS/blob/main/LICENSE)

## Usage

### Basic Usage

You can find the checkbox in the HTML code, which can give a unique style to your website if needed. Open the checked.svg file in the code editor, and replace the colors at <path ....... fill="#aa8354"> and border: 3.5px solid #aa8453; with your desired ones. You can customize it according to your preferences. Use it confidently and make your website stand out from the crowd! Simply paste the code into your own.

### THE POINT
```css
      input[type=checkbox] {
         visibility: hidden;
      }

      .checkbox_color input:checked~.marker:after {
         display: block;
      }

      .checkbox_color input:checked~.marker:before {
         display: none;
      }

      .marker::before {
         content: '';
         position: absolute;
         left: 0;
         top: 3px;
         width: 17.5px;
         height: 17.5px;
         display: block;
         border: 3.5px solid #aa8453;
         border-radius: 3px;
      }

      .marker:after {
         position: absolute;
         left: 0;
         top: 0;
         background-image: url(img/checked.svg);
         width: 35px;
         height: 35px;
         background-size: 30px;
         background-repeat: no-repeat;
         content: '';
         display: none;
      }
```

## Copyright and License

Copyright 2023 Lebryere. Code released under the[![GitHub license](https://img.shields.io/badge/license-MIT-green?&style=plastic)](https://github.com/LeBryere/Custom-checkbox-CSS/blob/main/LICENSE) license.
