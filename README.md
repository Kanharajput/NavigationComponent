# NavigationComponent
Moving between the destination using Jetpack Navigation Component, And pass the data using safe-args.
In this app: An activity can't get to know about the the fragment is doing in the space which is provided by this 
So we can't use any button which getting fragment data without pass by the fragment Normally we get data from any of the layout or fragment
when we calling another fragment after pressinga button but if we are not opening any other layout then we can't get that layouts data 
.....I think so so after applying this to any project research it to google.

About an Clickable images: to make an image clickable just add onclick method to it's code
image should only 113*113 pixels.
Copy image to drawables folder.

Transition can be added to action.
poUpTo is used to remove back stack for repeatness example Start dest from A then go to B then come back to A now if you wanna leave app then you have to press back butto 3 times A to B (1) , B to A (2), and last A to leave (3). using popUpTo B is remove from the back stack then you have to press for 2 times A to A->visited A (1) and last A to Leave.

Using popUpToInclusive, we can even remove visited A to stack then by only one click we will be out of the app.
