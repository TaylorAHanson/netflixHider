# netflixHider
A Google Chrome Extension to add checkboxes to Netflix titles to hide them. Essentially, tell netflix "I never want to see that again"

after 20min of coding... 

The goal is to create an extension that gives the user "hide" buttons on the title cards on Netflix's browse page. 
While hiding the tiles using persistant cookie data is possible, netflix adds them right back in. If the hide function is binded to
domsubtreemodified, it locks the page up, probably because the function itself modifies the sub tree. Need to come up with a way to hide
the title cards and prevent netflix from injecting them right back in as they seem to do. 

Another issue is that it seems to eliminate only the first card, so if the same title is featured in another list it is still there. 

Also, would like to make the hide button expand with the title card, and add in a settings menu to clear all, list hidden, 
and maybe some sort/filter functionality to re enable something quickly. 

