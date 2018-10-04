# CSS

Actually, I use SCSS often than CSS.

But, there is few difference, so I'm gonna tell you based on CSS.

Here is my style.

```css
.div {
  /* Layout properties */
  display: block;
  margin: 0px;
  border: 1px solid gray;
  border-radius: 5px;
  
  /* Simple appearance properties */
  color: white;
  background-color: black;
  text-shadow: 2px 2px #ff0000;
  
  /* other properties like transition or somethin' */
  transition: 0.1s all;
}
```

## 수치 관련 설정

* `em` is used for typogrpahy.
* `px` is used for detailed settings like `border-size`, `border-radius` etc.
* `rem` is used for except above all.
* I prefer to set the color in hex. ex) `#c0ffee`
    * But, if I have to do with transparency, I prefer `rgba` than 8-digit hex.
