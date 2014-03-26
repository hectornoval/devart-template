First Steps -

Define the size of the boxes an gave them a position on the screen.

a.html markup 
```
 <div id="surface">
    <div class="fig1"></div>
    <div class="fig2"></div>
    <div class="fig3"></div>
    <div class="fig4"></div>
    <div class="fig5"></div>
    <div class="fig6"></div>
    <div class="fig7"></div>
  </div>
```
b.I kept the same proportion and position in the canvas as Tinguely used to build his méta-malevich but instead of fixed units I used percentages in order to scale the figures depending of the screen and avoid the restraints of format.

```
.fig1 {
	background-color: white;
	width: 45.5%;
	height: 1.3%;
	top: 24.66%;
	left: 8.3%;
}
```

c. Then I make the rotation ... all at the same speed at the beginning - 

```
@keyframes rotate {
 from {
 transform: rotate(0deg);
}
to {
	transform: rotate(360deg);
}
}
.animated {
	animation: rotate 600s linear infinite;
}
```
![Shape](https://github.com/hectornoval/devart-template/blob/master/project_images/move_a.png "Shape")



