# how to add fonts to css file .(font are locally located ):  
###### defining new font:  
```
@font-face {
	font-family: 'PTSans';
	src: url('fonts/PT-Sans.eot');
    	src: url('fonts/PT-Sans.eot?#iefix') format('embedded-opentype'),
        url('fonts/PT-Sans.woff') format('woff'),
        url('fonts/PT-Sans.ttf') format('truetype'),
        url('fonts/PT-Sans.svg#pt_sansregular') format('svg');
	font-weight: normal;
	font-style: normal;
}

```
###### then pick the name of your own font name and put it here :  
```
body {
  font-family: 'name-of-font'
}
```
