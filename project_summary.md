# Project Title
Méta-Méta-Malevich

## Author
Héctor Noval - github.com/hectornoval

## Description

Homage to Jean Tinguely homage to Kasimir Malevich. Undeterminated surface box with seven geometric shapes in pure white. 
The elements rotate at different speeds producing an ongoing series of new compositions. Each image is new and virtually unrepeatable. 

Art evolves trough technology. Jean Tinguely redid Malevich paint with 'movement' so it would become infinite. I updated his work with our technology so it wouldn't have the constraints of format.


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
## Links to External Libraries
 NOTE: You can also use this space to link to external libraries or Github repositories you used on your project.

[Example Link](http://www.google.com "Example Link")

## Images & Videos
NOTE: For additional images you can either use a relative link to an image on this repo or an absolute link to an externally hosted image.

![cover image](project_images/cover.jpg?raw=true "cover image")


