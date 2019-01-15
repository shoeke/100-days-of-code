# 100 Days Of Code - Log

### Day 14: January 14, 2019

**Today's Progress**: Back to UnPlugged. I went through and validated html. Turns out that html5 is a bit fussy about the comments. So wherever I had a line of hypens to make a comment stand out (ex: <!------------------- HEADER --------------> ) it would flag it. I used spaces instead so now they look like this ( <!--          HEADER        -->). Also found out that the css validator doesn't like css variables, even though they are accepted across the board on browsers. Turns out this had been a know issue for over a year. Online advice was just to ignor the parse error message as long as the browser read it correctly. 
**Thoughts** Still left on unplugged, I need to test in different browsers. I want to try and clean up the css for the .content-wrappers. Made a chart of all the variations of width in each section in each media query. I think I can set one standard width per query and just have one or two sections vary to reduce the repeating code. 

### Day 13: January 13, 2019

**Today's Progress**: Cool! I worked on my first pure css image. I got stuck for the longest time not understanding why the z-index was not working! Turned out I forgot the . to make my class selector in css. Duh!! Set up my first little animal css in codepen. Also my first time using that tool. I think I like it. It's especially good for css illustrations since you can preview as you work. Would like to do the challenge everyday, but I think that might be too too much for girl!! 
**Thoughts** I would love to focus on what I think is referred to as creative css and animations. Besides these tuts which I can access through coding-artist.teachable.com, there is a nice tut in Lynda.com and I'm sure some on SkillShare. I'll try to work them in! 

### Day 12: January 12, 2019

**Today's Progress**: Better session today. Put in the font awesome officially. I had roughly figured it out before so I could preview the layout with real images. Had most of it right except did not place them inside a container. SC suggested using the <p> tag. I think with the features icons I had them in a figure. In the social icons they were wrapped in an anchor tag. After some playing around I nested the <a> and <i> tags each inside a div. That way I was able to make a round circle background for each icon. Was forced to give exact width and height to use border radius and make the circles. Otherwise they accomodate the shape of each icon. 
**Thoughts** There was a way to layer 2 fontawesome icons but it looked messier than just formatting the parent div. 
  PS. Want to work on creative css soon!! 
  
### Day 11: January 11, 2019

**Today's Progress**: Shorter day today. Did work on Unplugged - honestly forgot to write down what I did and now can't quite remember. I played with the map iframe because it didn't look quite right. Adjusted a few things. 
**Thoughts** There seems to be a weird lag when I load the page with the map embedded. Especially if I'm using the Dev tools, makes it really hard to scroll down and see the whole page. 

### Day 10: January 10, 2019

**Today's Progress**: Continued on Unplugged. Got all images (except icons) in and sized. Had to adjust many things for the media queries after changes were made to some images I had had as placeholders. 
**Thoughts** Learned for img tags to be responsive, you can place them inside a figure tag. The img can be set at 100% and the size of the container (figure) can be adjusted). This is what messed up some of my flex boxes, I had to insert a figure element where there was none before and the flex layout got disturbed. I've left a lot of commented out code behind, and probably some repetitive code as well. Will remove and clean at the very end. Should get the icons from fontawesome in next. 

### Day 9: January 9, 2019

**Today's Progress**: Working on the font styles for Unplugged. Still trying to use variables for at least the two main fonts so future projects might use variables for main colors and fonts to ease in switching out. 
**Thoughts** Still messed up trying to find em sizes coming out of PS comps. Measuring the fonts in PS should be accuarate, but doesn't seem to be. I think we know that the px font sizes in PS are not accurate (read somewhere that the px in graphics programs don't quite correlate to web browsers?). In any case suing the measuements to get started and then adjusting by eye. Also the font weights look slightly off as well. Still not quite understanding why we want to use ems and not rems. Maybe I will ask that in the Slack channel.

### Day 8: January 8, 2019

**Today's Progress**: Finished up the responsive layouts for tablet and desktop on the unplugged project. Starting to get the hang of it. Did the quiz at the end of the section. Not satisfied with the answers. Esp. how should you organize your CSS. The official answer was by section top to bottom, but I swear that they suggested layout, colors, fonts, etc.. Also didn't know know 400 was a normal breakpoint. Oh well. 
**Thoughts** Moving forward to fonts and colors on the unplugged project tommorow. Since I incorporated background colors and most fonts colors as white already, I'm hoping this should go smoothly. Once the fonts are correct and I can put in font sizes — they layout should hopefully start looking right. Might need to adjust margins and paddings once those are in. By then again, should probably wait until after the images are correctly in place too. 

### Day 7: January 7, 2019

**Today's Progress**: Instead of working on Skillcrush, I set up a simple webpage to practice specific tasks. Today I set up a 6 block responsive section with flex box.Intend to continue to add specific sections to practice coding. 
**Thoughts** Add images to make them responsive over the next few days.  

### Day 5: January 5, 2019

### Day 6: January 6, 2019

**Today's Progress**: Worked on Unplugged. First had to work with git to separate out just the unplugged files into their own repo (instead of the whole responsive 206 group I had it in). Was able to clone it to my local drive, initiate a new repo locally, and then init the remote repo (yeah!!) The problem after that was I was missing some CSS work on the media queries. I was able to figure out (eventually) that I had somehow swapped css files. Worked with flex groups in the tablet layout and got a rough layout going (again — eventually). 
**Thoughts** My code is probably a mess, but at least I am problem solving step by step.  

### Day 5: January 5, 2019

**Today's Progress**: NO ACTUAL CODING TODAY
**Thoughts** Slack meeting with the group. Incorporating #100 days into our slack group. Also began Learning how to Learn class through Coursera. 


### Day 4: January 4, 2019

**Today's Progress**: Treehouse workshop on CSS variables. Worked on CSS for layout on Unplugged. I was able to incorporate the css variables for background color dark and background color light.

**Thoughts** Still having issues matching the layout BUT not sure if it's because not all the objects are in yet or whether I just made mistakes earlier on. 

### Day 3: January 3, 2019

**Today's Progress**: Worked a little further on UnPlugged project in 206 Skillcrush. Figured out how to include fontawesome icons. Added in some rough flex layout with a few margins and padding. Need to do the same for the about page and the faq page.

**Thoughts** I find it difficult to exactly replicate how Skillcrush has the code written. Makes more sense if I imitate it in a way that makes sense to me but I'm worried it will further confuse the issue if I need help down the road. 

### Day 2: January 2, 2019

**Today's Progress**: Working on Skillcrush 206, building CSS for the layout, adding display:flex and beginning to set widths and margins for Unplugged site

**Thoughts**: Really confused at least with how Skillcrush has you go through it. Trying to add in images and backgrounds so I can see what I'm doing in the browser. Had to check out Font Awesome, and have the download code I need to link and test out how it works for the icons on the main page.

**Link(s) to work**: www.fontawesome.com

### Day 1: January 1, 2019

**Today's Progress**: Worked through Treehouse, Web Design Track, CSS Grid, final section on using Firefox developer tools with Grid, and did a Practice grid layout

**Thoughts:** Need more practice but makes good sense.






