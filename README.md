# Grades-Hack
Change your HAC grades.
## Bookmarklet
Put the code below in a bookmark as the URL. Change the foos and bars to grades. Use a space for classes like lunch or duplicates so no grade shows up.
```javascript
javascript:function%20myFunction(){var%20Elements=document.getElementsByClassName("sg-font-larger-average");var%20i;for%20(i=0;i<Elements.length;i++){if%20(i==0){Elements[i].textContent="foo"}if%20(i==1){Elements[i].textContent="bar"}if%20(i==2){Elements[i].textContent="foo"}if%20(i==3){Elements[i].textContent="bar"}if%20(i==4){Elements[i].textContent="foo"}if(i==5){Elements[i].textContent="bar"}if%20(i==6){Elements[i].textContent="foo"}if%20(i==7){Elements[i].textContent="bar"}if%20(i==8){Elements[i].textContent="foo"}if%20(i==9){Elements[i].textContent="bar"}}}myFunction();
```
