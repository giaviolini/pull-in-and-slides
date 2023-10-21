# Pull ins and Slides
## What I learned/Practiced
This assignment we followed an example from the HTML and CSS Bootcamp on Udemy. We also then had to change 5 things, to make it our own. Here are the major things I changed...

### Pull in and Sliding collumns 
For the Pull in and Sliding collumn I had rto use both CSS and Java Script. I found a very easy to follow toutorial that helped me understand what I need to do to make the pictures slide onto the page. I put each collumn into its own ```div```to be able to call them up indivually and also get up a ```display: grid;```.  \
In my css for each collumn is used the property ```transform``` to be able to have the collumn slide.   \
The full property look like this ```transform: translateX(75%);```. The ```translateX``` property tells how far the collumns need to move left or right.   \
Next step was addng key frames, this would cause the collumns to slide in at different times that I could control. This was a game of guess and check, but I finally found the correct values that I liked.   \
The next step was adding the animation to make the slide in happen and move. I mostly followed the tourtial I found for this step, but you need four properties; Animation, animation-delay, animationa iteration count, and animation fill mode. after slecting my collumns mine looked like this (left collum)    \
ex. ```animation: left 2s, red 2s;```  \
    ```animation-delay: 0s, 4s;```  \
    ```animation-iteration-count: 1, 1;```  \
   ```animation-fill-mode: forwards;```  \
The animantions left what direct (left or right) the collumn will move, and also for how long. The animation delay shows how long the computer need to wait for each animation. The first value is the time for the left collumn and the second is the right. The iteration count tells the compter that there are 2, one on each the left and right. The the animation fill mode tells the computer I want the slide to come from the left and move forwards to the right side, or until the edge of the div container it is.  \

Speaking of divs, as I mention before, I put all the collumns into different divs. This was mainly to help with the slides, but also to help arrange the display. I continued to use ```display: grid``` for this project as well. Which I another thing I changed. 


### Page Hyperlinks 
I also wanted the Navigation bar to be useable so, I added hyper links to the sections of the website. The way to do this is very similar to adding pages but instead of the ```.../pages``` and ```#``` is used. 
ex. ```<a href="#about">About</a>```  \
This tell the computer that there is a property with a class of about further down the page and to scroll down to find it. 

### Nav Bar Sticky Version
A sticky Nav Bar stays at the top of the screen, at least in this case, no matter how far you scroll. The easier way to do this is add the ```position: sticky;``` to the nav bar selctor in your CSS.

I also changed a some other same things; like adding a picture, changing the opcaity on the hover over the different images, and I found a code pen that had an animated rainbow text, so I added that to the mailto input I used as well. 

[Visit Site Here](https://giaviolini.github.io/pull-in-and-slides/)
