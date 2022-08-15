# apex-img-size
apex-img-size (apex v19.1, v19.2, v20.1)

Page property --> CSS --> Inline , put this :
```
img {
   width:;
   height:120px;
}
```
and adjust the width / height value.

For making a circle image from square image:
```
img {
   width:;
   height:120px;
   border-radius:50%;
   object-fit:cover;
}
```
sample output:
<img src="a.png">
