# font

***use this link into your head tag***
```
<link rel="preload" as="font" type="font/woff" crossorigin href="https://parswebdesigners.github.io/font/iransansxv.woff" />
<link rel="preload" as="font" type="font/woff2" crossorigin href="https://parswebdesigners.github.io/font/iransansxv.woff2" />  
<link rel="preload" as="font" type="font/ttf" crossorigin href="https://parswebdesigners.github.io/font/hack.ttf" />
<link rel="preload" as="font" type="font/woff" crossorigin href="https://parswebdesigners.github.io/font/staticfonts/iransansx-bold.woff" />
<link rel="preload" as="font" type="font/woff" crossorigin href="https://parswebdesigners.github.io/font/staticfonts/iransansx-regular.woff" />
<link rel="stylesheet" href="https://parswebdesigners.github.io/font/font.css"/>
```
***use mixin in sass for bold***
```
@mixin bold {
  font-weight: 900;
  font-variation-settings: "wght" 900, "dots" 7;
}
```
