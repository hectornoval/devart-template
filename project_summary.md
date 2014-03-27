# Méta-Méta-Malevich
Undeterminated surface box with seven geometric shapes in pure white

## Author
Héctor Noval - [noval](github.com/hectornoval "noval")


## Description

Homage to Jean Tinguely homage to Kasimir Malevich. Undeterminated surface box with seven geometric shapes in pure white. 
The elements rotate at different speeds producing an ongoing series of new compositions. Each image is new and virtually unrepeatable. 

Art evolves through technology. Jean Tinguely rethought Malevich's paint with 'movement' so it would become infinite. Based on his principles I redid the 'méta' but without the constraints of format. You can view it either projected or reflected, in a small or big screen without losing the primary concept. 


## Link to Prototype

[méta méta malevich](http://hectornoval.com/experiment/metametamalevich.html "méta méta malevich")

## Example Code

a.surface box 
```
.fig1 {
	position: absolute;
	background-color: white;
	width: 45.5%;
	height: 1.3%;
	top: 24.66%;
	left: 8.3%;
	display: inline-block;
	box-shadow: 0px 45px 19px rgba(0, 0, 0, 0.54);
}
```
b. box rotation 
```
@keyframes rotate {
from {
 transform: rotate(0deg);
}
to {
 transform: rotate(360deg);
}
```
c. box animation 
```
.animated {
animation: rotate 600s linear infinite;
}
```

## Images & Videos

![cover image](project_images/cover.jpg?raw=true "cover image")


