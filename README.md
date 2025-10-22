# Frontend Mentor - Testimonials grid section

I chose to continue doing this project from earlier as I was curious to see if bootstrap would make it easier or harder to complete the remainder of it. It did not seem to simplify things, but I am not sure it made it more difficult either. 

## Overview
I needed to take the given materials from Frontend Mentor, and recreate the website they gave as an example.


## Approach
I started by arranging the cards into the correct format. Then I arranged them for mobile view. I decided to do it this way because the mobile view would be much easier than the desktop view, in my opinion. Afterwards, I finished the first card, made sure it looked good and used that style to do all the other cards. 

## Difficulties

I had a really hard time figuring out how to make the long card at the end. I finally decided to make the other 4 cards their own div item and then use grid to add the long card as another div at the end. It worked, but then I had issues setting it up for mobile view. It kept being super long and skinny and/or not showing up completely. I had to manually set its size in css to get it to appear. I managed to figure out how to get it to appear correctly (mostly) in mobile view. It is slightly off to the side but no matter what I do I haven't figured out how to align it into the center. I tried justify-content-center in bootstrap as well as justify content: center in css. Niether has worked so far. 
I haven't figured out how to fix the headers for the other cards in mobile view, they hang off the edges and the images are not visible. The header on the long card is also messed up because when I tried to do to it what I did to the others, it caused the text not to wrap in the card and instead go off the page. Also, I originally tried making them component cards, but they wouldn't format correctly and kept adding lines between the content. I also couldn't figure out how to arrange them the same way as a div, so I used divs instead for the cards. Additionally, I was unable to figure out how to move the background image in the first card to the correct placement. Finally, I was unable to center all the content, similarly to the headers I have tried everything I know of and it just breaks the formatting completely or nothing happens. I am at a loss!

## Reflection
I encountered many challenges in this project. I had a lot of trouble with the long card on the end, as well as with the headers for the other cards. Centering content was also something I struggled with. Mobile view took a long time and still isn't perfect. If given more time, I would definitely figure out how to fix the headers on the cards in mobile view! 

### Link to Challenge

https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7

