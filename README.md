# Grades-Hack
Change your HAC grades.
## Bookmarklet
Put the code below in a bookmark as the URL. Change the foos and bars to grades. Use a space for classes like lunch or duplicates so no grade shows up.
```javascript
javascript:function myFunction(){ 
var Elements = document.getElementsByClassName("sg-font-larger-average"); var i;for (i = 0; i < Elements.length; i++){if (i==0){Elements[i].textContent = "foo"}if (i==1){Elements[i].textContent = "bar"}if (i==2){Elements[i].textContent = "foo"}if (i==3){Elements[i].textContent = "bar"}if (i==4){Elements[i].textContent = "foo"}if (i==5){Elements[i].textContent = "bar"}if (i==6){Elements[i].textContent = "foo"}if (i==7){Elements[i].textContent = "bar"}if (i==8){Elements[i].textContent = "foo"}if (i==9){Elements[i].textContent = "bar"}}}myFunction();
```
