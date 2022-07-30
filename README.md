# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

## Overview

### Screenshot

Desktop view:

![2022-07-30 (2)](https://user-images.githubusercontent.com/94350356/181936609-f6825780-caff-4287-b1c7-372e704e8dad.png)


Mobile view:

![2022-07-30 (3)](https://user-images.githubusercontent.com/94350356/181936617-629f957b-07c2-462d-be4c-ad1cfb3774a6.png)


### Links

- Solution URL: [Solution](https://your-solution-url.com)
- Live Site URL: [Live](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex

### What I learned

This project was very usefull. I learnt a lot especially the position properties

```html
<div class="banner">
  <img src="/assets/image-qr-code.png" alt="" class="qr" />
  <div class="txt">
    <h1 class="header">Improve your front-end skills by building projects</h1>
    <p class="content">
      Scan the QR code to visit Frontend Mentor and take your coding skills to
      the next level
    </p>
  </div>
</div>
```

```css
.banner {
  height: 31rem;
  width: 20rem;
  background: white;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  position: relative;
  top: -2%;
  border-radius: 15px;
}

.qr {
  height: 18rem;
  width: 18rem;
  border-radius: 15px;
  position: absolute;
  top: 3.2%;
}
```

## Author

- Frontend Mentor - [@DEEPAK-tech40](https://www.frontendmentor.io/profile/DEEPAK-tech40)
