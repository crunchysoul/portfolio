# Chen's Portfolio Website
self-explanatory

# Aim
Simple. Simple. Simple
- Too many websites homogeneous, espcially portfolio websites
- Suit my personalities, down to business with unique daring aesthetic
- Simplicity has became a trendy and cheap commodity, losing it's soul
- Anti/Break rules
- Organic, minimise decoration images
- Magic, browsing it should not feel like browing website
- Zen, it can be left open in the screen as an art
- Loosen imagination 
- Every elements serves for funtionality purpose

# My inspiration comes from:
- Ceiling above me
- Truth is: I wasn't really turned on about the idea of design, and at the beginning of this project, My feeling was wasting time. So I decided if I'm going to do this, I will only do it to not follow the rules and common trend.

# Design Stage One: Imagine
- Plan structures and form factors in mobile viewport
- Mobile first thinking
- Thinking about operation flow on mobile viewport

# Design Stage Two: Mobile Design

This is the starting point of the protfolio project:

![iPhoneSE_00](./md-img/iPhoneSE00.png "iPhoneSE_00")

Only structure and initial color combination, took about no more than 10 minutes to create in Figma, but lead to one whole week's dedication and one literally sleepless weekend, btw, by now, it is about on the mark of 48 hours, still holding up pretty good.

Second is the same design with matching font:

![iPhoneSE_00_type](./md-img/iPhoneSE00_typexs.png "iPhoneSE_00_type")

Notice: names for each section's name is not the same as the final web, but they are important, as this structure of inner to outer(from a human (later changed to soul) to an individual's archievement showcase website).

Nothing fancy, randomly chose a font from 'Google Fonts' within seconds, and really happy with it, "Wire One", really not the most pleasant font to read, which can be used for title or short reading.

Here is what the "Wire One" font in a glimpse:

![wire_one](./md-img/wire_one.png "wire_one.png")

Obeviously it's too slim, not really useful for many situations, but fit into the this portfolio's non-main stream dreamy color scheme and very symmetrical and artificial form factor, Which is good plus, later Ruegen enlighten me with quite eye opening knowledge, that this font is actually belong to once glorious but short lived Art Deco design genre, in fact the whole initail design itself reminisce Art Deco unintentionally, always learn from others and always discovery within.

# Design Stage Three: Larger Viewport

No special arrangement need to apply the design to computer, Squares are very portable to all different shapes and sizes, beauty of fundamental geometric shapes, they exist everywhere and suitable for all occasions, only limitation is imagination.

# Technical challanges
- I was struglling to place all the frames in a place I want. However I start to have understanding of what `relative` or `fixed`, `absolute` does, although I still tend to choose one hoping for the best.
- Text rotation to vertical. Some texts flied to nowhere when all I did was just rotating it.
- z-index. Apparently it all has to belong `position: relative`?
- Keeping it DRY (don't repeat yourself) ― I noticed I repeat some elements too many times in my CSS, such as `font-family` and `font-weight`. It still works but I didn't like it so I spent extra time cleaning up several lines.
- Implementing animation. I took Ruegen's feedback and decided to implement animation. What I knew I wanted to do is that it only swings or rotates once, when you scroll down and the object is visible in the screen (apparently it's called viewpoint).
I researched a bit and there was this handy plugin called [CSS3 Animate It](http://jackonthe.net/css3animateit/examples/), which helped me a lot saving my time.
I also learnt how to implement jQuery in your html.
- Not quite sure how to use svg. Svg's I created with Vectr get blurry as I zoom in..?????

# Lessons learnt:
- Preparation is (almost) everything.
I was recalling myself Abraham Lincoln's quote, which goes as follows:
> **_"Give me six hours to chop down a tree and I will spend the first four sharpening the axe."_** 

This was so true, I spent majority of hours desiging in Figma and the actual coding part was pretty smooth.
- **Edit your file in local unless you know what you are doing!!!** <br>
This was my official effed up moment.  
I once wiped out my 5-hour work of `readme.md` because there was a conflict between local file and remote. And I force overwrote my latest one saved in the remote with the old one saved in the local by doing `git push -f`. <br>
This happened because I kept editing my `readme.md` in remote repository directly.  
I did create `.gitignore` in my local to exclude any `.md` files but it wasn't working for some reasons and thus `readme.mb` was pushed to remote when I only meant to push other files. Screw me.  
- Try getting a big picture ― there were a few instances where I had to do repeat my work because the images I prepared weren't big enough, so when it's zoomed in it became looking a bit ugly.
- Name your classes wisely ― I realised it's quite easy to get lost in your own coding if the classes are poorly named. I named a bunch of links at the top page "link" which later I ended up investigating what that means.
I changed it to "menu" which is much more self-explanatory.


# Ok here is the website.
### https://tomomioki.netlify.com/
