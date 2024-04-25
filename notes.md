Certainly! Let's break down the @keyframes fadeFromBottom animation:

@keyframes fadeFromBottom: This declares a new keyframe animation named fadeFromBottom. Keyframe animations allow you to specify a sequence of
styles to be applied to an element over a specified duration.
0%: This represents the starting point of the animation, where the element's properties will be defined at 0% of the animation duration.
opacity: 0;: At the beginning (0% of the animation), the element will have an opacity of 0, meaning it will be completely transparent and invisible.
transform: translateX(100%);: At the beginning, the element will be translated (moved) horizontally by 100% of its own width to the right.
This means it will start off-screen to the right, outside the viewport.
100%: This represents the ending point of the animation, where the element's properties will be defined at 100% of the animation duration.
opacity: 1;: At the end (100% of the animation), the element will have an opacity of 1, meaning it will be fully opaque and visible.
transform: translateX(0);: At the end, the element will have no horizontal translation (0%), meaning it will be in its original position horizontally.
So, the fadeFromBottom animation gradually transitions the opacity of the element from 0 to 1, making it fade in from completely transparent to fully opaque,
while simultaneously translating it horizontally from outside the viewport to its original position. This creates an effect where the element fades in from the bottom to top while moving horizontally onto the screen.



So to set images  to the inputs inside first in css we target the input itself and then the first class that will be the actual input and here we set the background image (the icon) then we target the input and the second calss thats the actual icon that we going to pass the no prepeat propery and paddings :)

input.icon-profile{
    
    padding-left: 30px; /* Adjust this value according to your icon size */
   
    background-repeat: no-repeat;
    background-position: 5px center; /* Adjust the position of the icon horizontally */
    background-size: 40px 40px; /* Adjust the size of the icon */

}

input.name {
    background-image: url("images/icon-profile\ is.svg");
}



input.icon-email{
    padding-left: 30px; /* Adjust this value according to your icon size */
   
    background-repeat: no-repeat;
    background-position: 5px center; /* Adjust the position of the icon horizontally */
    background-size: 40px 40px; /* Adjust the size of the icon */
}


input.email{
    background-image: url("images/icon-msg\ is.svg");
}



Also for the images first we enter the img tag itself and then the class to resize it

img.js,
img.html{
    width: 100px;
}

img.css{
    width: 130px;
}

img.react{
    width: 100px;
}
