# product-preview-card-component-main

### Links

- Solution URL: https://github.com/Sebaplz/product-preview-card-component-main
- Live Site URL: https://sebaplz.github.io/product-preview-card-component-main/


Web width 1440px:
![image](https://user-images.githubusercontent.com/51845541/192427588-ff0a9104-47e0-4202-8b14-d6d4bd9abe63.png)


Mobile width 375px:

![image](https://user-images.githubusercontent.com/51845541/192427635-62c29662-b091-40e8-9fb8-b1b02209da2d.png)


- Semantic HTML5 markup
- CSS custom properties
- Bootstrap
- Flexbox

### What I learned
Cambiar imagenes según @media
```html
<picture>
  <source
    srcset="images/image-product-mobile.jpg"
    media="(max-width: 991px)"
    alt="Perfume"
  />
  <img
    src="images/image-product-desktop.jpg"
    class="img-change img-fluid"
    alt="Perfume"
  />
  </picture>

```


## Author
- Frontend Mentor - [@Sebaplz](https://www.frontendmentor.io/profile/Sebaplz)
