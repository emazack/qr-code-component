# QR code component

This is a QR component card. This component expose a qr code image; It works in all viewport from 375 to 1440. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [License](#license)

## Overview

### Screenshot

![Sample scrennshot](/screenshot.png)

### Links

- Solution URL: [Github repo](https://github.com/emazack/qr-code-component)
- Live Site URL: [Live website](https://emazack.github.io/qr-code-component/)
- QR code to live solution ;) [Solution QR code website](/qrcode_emazack.github.io.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- [Google fonts](https://fonts.google.com)
- [Git](https://git-scm.com/)
- [Github Pages](https://pages.github.com/)
- [Visual studio code](https://code.visualstudio.com/)

### What I learned

- HTML5 structure
- CSS properties
- Images handling
- How to deploy a project with Github Pages

HTML5 landmark elements are used to improve navigation experience on your site for users of assistive technology.
```html
    <main>
        <img >
          <h3>
          </h3>
          <p>
          </p>
    </main>
```
The alternate text is needed on this image. The alternate text should indicate where the Qr code navigate the user like
```html
<img class="qr-code-image" src="../qr-code-component/images/image-qr-code.png" alt="QR code to frontend mentor">
```
Using rem and em units. They are flexible, specially for font size better to use rem. If your web content font sizes are set in absolute units, such as pixels, the user will not be able to re-size the text or control the font size based on their needs. Relative units “stretch” according to the screen size and/or user’s preferred font size, and work on a large range of devices

```css
.description { 
    font-size: 0.938rem;
    letter-spacing: 0.012rem;
}
```
Best practice is to use the simplest selector possible while maintaining the minimum required specificity. As a rule, if a selector will work without it being **nested** then do not nest it. That is to say, how quickly a browser can match the selectors your write in CSS up with the nodes it finds in the DOM.

**Layout**

- Mobile: 375px
- Desktop: 1440px

**Colors**

- White: hsl(0, 0%, 100%)
- Light gray: hsl(212, 45%, 89%)
- Grayish blue: hsl(220, 15%, 55%)
- Dark blue: hsl(218, 44%, 22%)

**Typography**

- Font size (paragraph): 15px
- Family: [Outfit](https://fonts.google.com/specimen/Outfit)
- Weights: 400, 700

### Continued development

The idea is to create a functionality able to expose a personalized QR code directly into the card

## Author


- Github - [emazack](https://github.com/emazack)
- Linkedin EN - [@emazack](https://www.linkedin.com/in/emazack/?locale=en_US)
- Linkedin IT - [@emazack](https://www.linkedin.com/in/emazack)
###### The project is made by me from the scratch without babysitting help of anyone; I did not follow any kind of tutorial or step by step guidance

## License

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).