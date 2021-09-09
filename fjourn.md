# Formative Assessment Journal

## Experimentations

I spent a while considering what to do my fansite on. It was a toss up between the Final Fantasy series, or a Cyberpunk themed site - possibly for the CP2077 game, or just a kind of fansite for the genre itself, maybe have some kind of interactivity going on. I delayed it for a bit cause I wanted the URL to be appropriate relative to what the content was. So in the end I went with cyberpunk purely because I have a lot more ideas for what I could do, and creating the appropriate aesthetic would be easier for me than a Final Fantasy based one.

The things I most struggled with in this was getting the layout to sit where I wanted it. I usually kinda cheat and just margins to set things in place on a fullscreen desktop website, but that method catches you out whe you go to make the layout responsive, and things can overlap and just look weird when shorted down to a mobile viewpoint. So I spent a good day at least trying to place everything correctly while making sure it still looked fine without any overlap or unwanted behaviour on a mobile layout as well.

choosing body font, between:  
![exo](/assets/font-exo.png)
and  
![ox](/assets/font-oxanium.png)
browsing fonts for titles and headings is always fun cause you get to find some whack looking stuff.. went with this as it fits the theme really well  
![neolat](/assets/font-neolatina.png)


I've also been struggling on content, like how could I make a fansite, what sort of things should go on it. Having major creative block, I went around the web and looked at the official site, and other kinda of fansites, to see the kind of content they have and take ideas for myself.

I love the colour palette of this site as these are some of my favourite colours used in combination with each other. For everything in the site, I took hex codes from the background image.

![palette](/assets/website-palette.png)

I've been experimenting a bit with the background, and decided that it would look better blurred. The way the CSS works with that is that the body, html, and bg div height has to be set to 100% or it won't show up properly. This caused issues with the main column divs that were originally on the front page. The entire body would blur itself instead of the background image like I wanted. Upon a lot of review, I figured that since we technically have to create a splash page, I could do that and have just a basic splash when you first arrive on the page, and then the content could be displayed after going into the site properly, and I would remove the scanlines and complicated css that was messing it up after. So with this change, the background on the site is nicely blurred to give more focus to the main content.
Another thing I was focusing on was experimenting with different content in my splash page. At first, the main page had the content on it that you now see once you have clicked the enter button. I then changed it to having the enter button and all the effects and such, but it looked very empty, especially on a large screen. I played around with different things like text or even css animations, and just moving the enter to be the very center of the screen but still felt like it needed something more. I asked a friend to have a look at the website and if he had any feedback or suggestions about it, and it was helpful hearing an outside observation. One of the points was that you don't know what the website is even for when you arrive at the page, you just see a background and an enter button. So I decided after that to just add the CP logo to kinda show what the website was about.

After finalizing that, I moved the previous content over to the inside of the site and went from there.


## Formative Professional Pratices 
summarise an area of professional pratice in approx 300 words, use imagery if appropirate, you must use credible academic references and cite your statements. you are welcome ot give your thoughts, however you must have your statements backed up by credible research

you are free to select any area of professional pratice you would like to investigate further, it can include what i have shown you in our professional practice lesson or somethin additional you have an interest in
note: this is a draft for your fromative assessment, you will submit a final copy in your summative assessment

## Inspiration
Rather than be inspired by live websites, i usually look through codepen or deviantart or something. where codepen has a lot of css on it you can use which has some really amazing effects that you never thought were possible with css only, some of them are very very advanced and have served as inspiration for my development. As well as deviantart having lots of art images of things like interfaces and HUDs.

Here are some links to pens and websites that I have been inspired by, though there isn't really any elements from these examples that I actually used with mine.

https://codepen.io/aderaaij/pen/amqoVJ

The colour theme here and animated style of the background inspire me. The classic outrun style always attracts me, something about the grid and the colour scheme. It made me want to do some kind of animated background, but maybe not so basic as what was shown here. Something like the background I had chosen but with a few parts animated such as a wind blowing or neon lights flickering would have been cool, but also would probably have had to create something myself which would have taken too much effort that I didn't have time to sink in.

---

https://codepen.io/hussard/details/ExgbXMP

This is a redesign of a social app using the same interface as what's in the actual cyberpunk game. You have a messaging system in your menu, so it gave me some ideas around incorporating elements from the game's interface in my website. The thing is I didn't have any ideas for content that I could put in that could use anything like that.

---

https://codepen.io/kimwhy/details/zYroKXr

This mockuip of a website is very well made, basically a template for a fansite. I like the way you scroll down the page and everything comes in sort of modeules, with the text next to the images and section after section. I would have liked to design a similar page but positioning like that is the bane of my existence when trying to design websites. I guess it's just a matter of a lottt of different divs, and them making sure everything comes together and sits perfectly when responsive, it just takes too much time and fiddling around to get right. So with the time I had I had to come up with a more basic design, plus I didn't want to straight up just copy something like this

---

https://codepen.io/marcc24k/details/gRPygo

Not quite sure what this one is but it looks really beautiful, and the colours attract me a lot, the soft neons and the opacity of the middle div and the animations it does as well are just so smooth. It looks kinda like a screen from a web based game of some kind. I could not incorporate anything from this into my own design but I liked it a lot so thought it worth mentioning as inspiration.

---

https://codepen.io/summercodes/details/jOmbZLW

This mockup website really amazed me, the fact it comes with its own splash page sort of entrance thats part of the homepage itself, and you can just scroll down to view the content, and the way the frame is placed around the page as well, it looks like pretty advanced css, I had a look at the code and played around with it a bit but that kind of things far beyond my level at the moment. It just looked super cool how it was laid out, the colours it used as well. I would have liked to do a vertical side menu kind of thing like that if I had more content to put in my site.

---

https://codepen.io/ltrademark/pen/xpgprZ

This is an error page I found and it just looked so damn cool. The glowing and glitching as well as japanese text with monocode font fits perfectly for the genre. I would have changed the colour of course, and the opacent kind of background I admired a lot as well. I think i've said in the videos of the walkthrough that drop shadowing and opacity were some of my favourite things to do on a site and it instantly makes it look 10x cooler when you add those to divs.

---

https://www.cyberpunk.net/nz/en/

The official website for the CP2077 game. I like the imagery and the frames around them, as well as the way the website flows out when you scroll downwards. The main colours of yellow and blue fits the theme as the game's official colours on all their game boxes, their logos, and in the game itself as interfaces. Thee yellow and blue also fits thematically within the cyberpunk genre itself as it is built on the 80s neon colour aesthetic.


## Development of Splash Page

Grabbed a multi column layout from w3 schools, ive used it a lot in previous work so its handy just having all the code as the template, then you can make whatever changes you want. customizing the headers and buttons and such to have cool effects. i tried messing around with a blurred background but something in the css was mucking it up and as soon as i put it in, the background would disappear entirely. because it had to be its own div, but when you have all these other divs all doing stuff to the page.. i tried to isolate the problem for about 20 minutes before giving up, couldn't figure it out, but it wasn't too much of a problem.. more something i just wanted to see if it looked good or not. having the background less busy. alternatively i can fill up the columns with content and have the opacent which is what im going with at the moment, so the background will be less prevalent. overall loving the colours so far.

This was what I had written in the first few weeks when I started development and not sure really what else to say at the risk of repeating myself of what i've said in the experimentation, which I kinda wrote a lot about the development in there. Basically switched around a lot of parts of the site. The splash page ended up being quite basic with only a few elements on it, but I guess you expect that of a splash page. I wanted a bit more stuff so the last thing I did was add the custom cursors and have the music playing in the background. Apparently its not so good practice to have autoplaying music on websites anymore but maybe its the part of me that lived through the internet in the late 90s/early 2000s that holds a bit of sentimental value towards old school kind of ideals like that, so I put it in anyway. The music I used was from the official soundtrack of CP2077: Marcin Przybylowicz - Corposeduction


## Final Splash Page

![splash](/assets/splash.png)

## Evaluation of your Splash Page
I think it looks beautiful. Im happy with how it turned out especially with the responsitivity. It looks so cute when resized. The slight blurred border around the background image makes it pop out of your screen as well, like it looks like it has rounded edges like a curved phone screen with zero bezels.

## Development of Fansite
Once I had finished doing the splash I basically just slapped a bunch of content on there, and used all the formatting for divs and headers and text etc into that. It didn't take too long because I had already done all the css and placed everything and made sure it was working to be responsive. I had written before in the experimentation that I had problems with positioning stuff but thinking back I can barely remember it now and it seems so easy when youre just looking at a finished product that works the way you want it.


## Final Fansite

### Video walkthroughs
https://streamable.com/tpu4o4

https://streamable.com/n2ta21

![index](/assets/index.png)


## Evaluation of your Fansite
One thing that bothered me, as I also talked about in the walkthrough was the logo on the content page. At the time of filming you can see how it looked, and since filming that and now i've made a new logo and replaced the old one and i'm much happier with it now. You can see that on the live website. In other areas, What I think could be improved on was having more content, or perhaps laying out the website in a way that one of my inspirations had, instead of one long scrolling div with everything in it, the background could stay fixed on screen and the different sections of the site could be smaller and have more spacing, more pictures between them, and overall more professional looking when scrolling through it.


## References

tutorials used:   
http://aleclownes.com/2017/02/01/crt-display.html

(unused) asset:  
by jose ciceraro  
https://dribbble.com/shots/1807804-Ratchet-and-Clank-battle-arena-screen/attachments/298724

css glitching:  
https://codepen.io/mattgrosswork/details/VwprebG

content:  
https://www.cyberpunk.net/artbook/en/

https://cyberpunk.fandom.com/wiki/Cyberpunk_Wiki
