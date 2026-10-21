First time building a web page "on my own" following HTML Fundamentals
(IspringLearn)

Adding some more elements to the web page. Just learned that <br> is a line break.
<br><br> effectively makes 2 line breaks.
Started implementing organizational changes and experimenting with placement of different "functions"
(Not sure if function is proper terminology here)
Attempting to creat classes for elements so I can customize them with CSS.

Day2:
Just learned about absolute and relative links. Going to create a Pages folder for my relative links to keep it organized, then I'll implement the links.
<a> is an anchor point. I know they can be used for links.</a>
Learned that entering a ! will give an option to auto fill the basic info, which speeds up the work flow a lot. Give's me a good standard to work off of.
Learned target="_blank" makes the link open into a new tab. It goes after the href (hyperlinkreference) from my understanding.
 <a href="./Pages/about.html">About</a> for a better connection to the relative file, telling the system that its a relative file by using ./Pages
 It is possible to do Pages/about.html but aparently the system can malfuction like that, so good practice for relative files is ./ before the directory
 I also noticed the color of the links change on the live preview from dark purple to brighter blue, seemingly signifying the link working properly.

Day3:
 I can use changelog.md for an AI agent to update changes made in my files in real time with references to them and examples and insights. May try it here.

Day5:

Learned about inline, internal and external css.

Day6: Going to try and link the stylesheet to eliminate the inline css for grey background for all pages.
(Haven't figured it out yet. Maybe I have to put the <link> in every section? Do I have to make a section for the background color, and link that section? LOST)

Just figured it out. 

Next challenge is to get a button to go back to the home page, from both contact and about pages.
Trying to get the button linked to the index.html is giving me trouble.

Just learned about <button></button> needing javascript attributes, it cannot use href, which is HTML.
I can make the link with HTML just fine, then STYLE it to LOOK like a button. I'm going to attempt that so I can get the hang of html and css.
I'm pretty sure in order to do that I have to designate a class for all the buttons (can do inline css but, no) and style them in class.css.
(Future reference I think it's best to name is styles.css not class.css).
I had class spelt incorrectly...
Ok I got it sorted out. Made the links look like buttons with some style.
I had to go into every <a> and clasify it as a button. INSIDE its <>.
-example-
<a href="/index.html>" class="button">Home</a>
                                    ^^^ see. Class goes inside the <a>
Will be customizing the buttons a bit more. Next challenge will be to put the image into some kind of 
container. Maybe I'll add a slew of fish pics to challenge myself with hover abilities and different css styles.
(raw. No templates! or outside source styles!)