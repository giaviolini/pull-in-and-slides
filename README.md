# Pull-ins and Slides
## What I learned/Practiced
For this assignment, we followed an example from the HTML and CSS Bootcamp on Udemy. We also then had to change 5 things, to make it our own. Here are the major things I changed...

### Pull-in and Sliding columns 
For the Pull-in and Sliding columns, I had to use both CSS and JavaScript. I found a very easy-to-follow tutorial that helped me understand what I needed to do to make the pictures slide onto the page. I put each column into its own ```div```to be able to call them up individually and also get up a ```display: grid;```.  \
In my CSS for each column, the property ```transform``` to be able to have the column slide.   \
The full property looks like this ```transform: translateX(75%);```. The ```translateX``` property tells how far the columns need to move left or right.   \
The next step was adding keyframes, this would cause the columns to slide in at different times that I could control. This was a game of guess and check, but I finally found the correct values that I liked.   \
The next step was adding the animation to make the slide-in happen and move. I mostly followed the tutorial I found for this step, but you need four properties; Animation, animation-delay, animation iteration count, and animation fill mode. after selecting my columns mine looked like this (left collum)    \
ex. ```animation: left 2s, red 2s;```  \
    ```animation-delay: 0s, 4s;```  \
    ```animation-iteration-count: 1, 1;```  \
   ```animation-fill-mode: forwards;```  \
The animations show what direction (left or right) the column will move, and also for how long. The animation delay shows how long the computer needs to wait for each animation. The first value is the time for the left column and the second is the right. The iteration count tells the computer that there are 2, one on the left and right. The animation fill mode tells the computer I want the slide to come from the left and move forwards to the right side, or until the edge of the div container it is.  \

Speaking of divs, as I mentioned before, I put all the columns into different divs. This was mainly to help with the slides but also to help arrange the display. I continued to use ```display: grid``` for this project as well. Which I another thing I changed. 


### Page Hyperlinks 
I also wanted the Navigation bar to be useable so, I added hyperlinks to the sections of the website. The way to do this is very similar to adding pages but instead of the ```.../pages``` and ```#``` is used. 
ex. ```<a href="#about">About</a>```  \
This tells the computer that there is a property with a class of about further down the page and to scroll down to find it. 

### Nav Bar Sticky Version
A sticky Nav Bar stays at the top of the screen, at least in this case, no matter how far you scroll. The easier way to do this is to add the ```position: sticky;``` to the nav bar selector in your CSS.

I also changed some other things; like adding a picture, and changing the opacity on the hover over the different images, I found a [code pen](https://codepen.io/hugo/pen/krjgmB) that had an animated rainbow text, so I added that to the mailto input, which I used as well. 

[Visit Site Here](https://giaviolini.github.io/pull-in-and-slides/)
