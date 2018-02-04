Design is the creation of a plan or convention for the construction of an object, system or measurable human interaction; and Open Source refers to something people can modify and share because its design is publicly accessible.

So Open Source Design is the design whose design is publicly accessible? I believe it should be much more and I'm here to convince you about that.

I am Michael Demetriou, I'm involved in both open source and design for a good 10 years now and

**I believe that open source design should help users to exercise the freedoms that open source provides.**

Right now, design does not promote our freedom. I'd say it rather restricts it. The things around us are designed to keep users out, in the name of ease-of-use, security or beauty.

But the user that uses something most easily, the most secure user, the happiest user is the one that knows how that thing works. So making something automagically work will cause a few moments of delight initially but the effects in the long term are exactly the opposite.

I realized this when I showed the incredible advances in deep learning and neural image manipulation to friends and coworkers during the past few years. People that don't understand the complexity of the system involved are those that are the least impressed. Technology is magic after all, at least for them, and can do anything.

There's a story I read when I was little, which described a family dinner, during which one of the adults starts floating over the table. Despite what one would think, the children are the least amazed. They are used to seeing amazing new things all the time. Adults on the other hand know that floating over the table is impossible and are genuinely surprised.

<!-- I don't remember where I read this story but it stuck, if anyone does, please help me credit the author. -->

Trying to make technology look like magic helps keep our users childlike, which as good as it may sound, it's not. You might wonder why I mentioned fake news and clickbait in the description of this talk: it is because I believe that fake news, calls for universal back doors and conspiracy theories all stem from the inability of the crowd to distinguish between what is possible and what is impossible. The ability to do that improves with a firmer understanding of how things work.

But let's go back a little bit, to the design movements of yesteryear. Let's go back to Adolf Loos and Modernism, and his declaration that ornament is crime. Or to the Russian Constructivists who thought all art was political and that building the USSR was a great art project. To the bauhaus modernists that thought that art should adapt to the new era of the machine.[5] We can also go to today's advocates of emotionally durable design that aim to save the environment by designing things that we will love more as time passes. _Unfortunately I don't think that is really going anywhere, probably because it doesn't fit in with our consumption patterns._

All those guys and many many more in the history of art and design thought that they could change the world with their designs. They thought they could make the lives of people better, some by reinforcing social status, others by diminishing it, some by promoting technology and others mass consumption. I believe that today's design trends try to promote an easier life but fail, actually promoting blissful ignorance.

<!-- This failure is starting to show up: Apple tried to abstract the file system but they at last decided last year that it doesn't work. Google removed SD cards from their phones and they had the audacity to tell us in our faces that we're too stupid to understand where our stuff is saved. Fortunately that approach didn't catch up with other manufacturers. Microsoft also backed down from the extreme dumb-down that was Windows 8 and replaced them with Windows 10 -->
 <!-- a system that includes a robust command line, and a way to install complete GNU distributions on it, from the official store. -->

There are many more examples of how this approach does actually fail but the most spectacular manifestation of this failure is facebook's fake news problem. They tried to reduce the unlimited complexity of a thing called news to the presence or not of a little red flag, of all things, and managed exactly the opposite of what they intended. _And their new approach is to prioritize posts from friends because those friends are certainly more trustworthy than reputable news organizations._ It's deeply ingrained in silicon valley mentality: simplify anything down to an icon, or the push of a button.

And that brings us to why it fails. It fails because our world is complex. Complexity is there and it is inevitable. Our solutions to the problems caused by complexity usually involve adding even more complexity. In our effort to simplify things as designers we end up just hiding complexity behind user interfaces that make assumptions. By driving over the complexity with a road-paving roller machine of a UI we destroy all kinds of nuances people love to love. Just visit any kind of community that loves a certain something, be it coffee, tea, audio equipment, cars, whiskey, gaming keyboards, desktop environments, whatever and you will find that the discussion always gets down to the slight nuances that make each one's favorite thing unique, to the point, some times, of absurdity.

I think it's our duty as Open Source Design to have a political agenda, to actually do try and change the world. To be something more than automated operators of A/B studies and usability testing. To care not only whether our user will do the task quickly and effortlessly, not only if she is going to engage more with our item, but also if she will leave the interaction happier, wiser, more secure and why not, a better person.



We make the effort to build a million different options into our software and then painstakingly hide them behind a page that actually says, hey! I assume you're too stupid to change these settings, please don't. This doesn't mean that your app should have a 500 tab settings dialog, but why try hiding about:config so hard? And then there are the options that aren't even there:

On one hand we try to promote open source software as a tool that provides the user with freedoms, and then we turn around and and lock our users out of functionality "for their own good", because we know that they don't know how to recompile our software. If this isn't two-faced I don't know what is. (I know there are Mozilla guys in the audience).

--

It's not a coincidence that Eben Upton found that the computer skills of undergraduates dropped off between 1996 and 2006[1]. It's the period of Steve Jobs return to Apple and the dominance of "Just Works". The same period saw an almost religious purge of anything that resembled the command line, or programming. Computers now came without any hint of programmability, their former primary purpose. To be fair, this gave birth to excellent visual computer interactions that helped computers reach millions of people. And let's make it clear: I have nothing against that.

But we took it too far.

So what do I propose? To force everybody to code in assembler like REAL MEN? No, of course not. Technology must be accessible to everyone, it must have an easy on-ramp, and not be intimidating.

What I'm saying is that what we thought as an easy onramp, is not. It's just bad compromise that stifles learning. LaTeX might be intimidating but it requires you to invest the time to learn all about it. Word Processors promised to make this easy but in reality they never allowed the masses to produce work comparable to that of professional typesetters. Why?

Because typesetting is hard work. You have to know all about kerning and hinting and widows and orphans, and positive and negative space and no amount of nice buttons is gonna make that easier. _and a word processor does have nice buttons but it doesn't teach you all those things._ It just provides a false sense of competence so all the CV's I receive say "Excellent use of Microsoft Word" in the same paragraph in which they use spaces to right align a sentence.

Is there a middle ground? I think stackedit and markdown is a very good example of a middle ground. It doesn't look like hieroglyphics to an untrained eye, it is easy to learn, and a single row of buttons allows you to do most of the things you'd want to do in a document while at the same time you see exactly what the computer sees. After the first few presses of the B button on a markdown editor, if you are slightly interested, you'll understand that all it does is surround the word you're typing with double asterisks and you'll be able to do it, saving yourself a trip to the toolbar.
 <!-- Good luck learning what the shortcut for Bold Text is by pressing the button. -->

AutoCAD is another nice example. It's as point-and-click as MS paint but there's a nice little command line always visible and every click is accompanied with it's respective command on the bottom of the screen. After a few times you can easily learn the commands and stop searching for them with the mouse. There's also a nice predictable shortcut scheme which means you don't have to memorize shortcuts.

Do you know what's the biggest search term by volume on Google? Facebook. [4] Why? Because people can't distinguish a search term from a URL. And number 3 is Google. On Google. We have to fix this. It has huge security implications and it's clearly a failure of our design. We are trapped in our bubble and we've lost track of the real world results of our choices.

So what shall we do?

1. Teach! You know those "troubleshooters" that never work? Why not instead of "trying to fix the problem" you present your user with the steps he should take in order to understand why his printer, or his internet access doesn't work. Teach them the process of elimination and while you're doing that explain to them what DNS is and why it's probably the issue when you can't reach google.com but you can reach it's IP address.
<!-- 62.75.10.93 -->

2. Ask to teach. I'm pretty sure that there are millions of people that are actually curious about what happens between entering a letter in the URL bar and seeing the webpage they intended to see. So ask them, politely "Did you ever wonder what happens behind the scenes when you type here?". Not only you get to show off all the fancy things you do in every keystroke, but it also explains why you ask "Do you want to enable search suggestions?" and why the answer shouldn't be "Of course, why do you even ask?"

"Because I'll be sending your every keystroke to Big Brother, idiot!" btw, I've seen people pasting passwords there to see if they're correct!

3. Stop replacing "intimidating" jargon with "softer" words. It's confusing to those who know, it's different in every brand and it makes for an awful situation both trying to give or get help.
<!-- "You have to enable 4:4:4 color, you know go to the menu yeah it could be something like super-duper color, what's your TV brand, let me google it."  -->
[It's 4:4:4 color people, not UHD color nor HDMI Deep Colour. If you want to help clear the air write a helpful subtitle and get over with it. [This allows deeper color if your HDMI source supports it. Doesn't make a difference if you are using a DisplayPort cable]]

4. Don't be patronizing: [we've searched hard and couldn't find what you asked for]
This is *not* a good 404 page. I know, I'm guilty of it. I like the hip language but what this page is saying, is frankly, bullshit. You have to tell the user the truth. "There is no such page. Deal with it. There are no oompa loompas in the computer searching for your mistyped webpage, check the spelling or go to the wayback machine. Scram."

5. And because design isn't only software, make repairs easy: Include a repair manual, or link to disassembly videos. Don't use glue. Embrace wear and tear, stop cherishing smoothness and newness: scratches and marks show use and utility. Use that in your design.

6. Make it replaceable, interoperable, show it's inner workings. Reprap 3D printers are a very good example of what I'm talking about. You can see and learn exactly how they work, you can infinitely repair them, upgrade them with parts you can buy anywhere and then you can go and build your own. Contrast that to regular printers which are almost always cheaper to replace than to repair. Heck, some times it's cheaper to replace than buy new inks.

And because we know nothing about them they seem to never work as they should.

In all, this is what I think that Open Source design should mean. However I know that design principles are always controversial, as they should be so in order to avoid hijacking the term, I would like to call this approach, Transparencism. I invite you all to join me into creating example of transparent design, and to shape these ideas into concrete guidelines in order to influence the future of mankind.

I have created a gitlab organization where we can gather resources to show the world what transparent design is.

[1]: https://www.theguardian.com/technology/2012/nov/04/raspberry-pi-programming-jam-cern
[2]: https://danluu.com/input-lag/
[3]:http://www.alphr.com/news/education/375106/founder-no-raspberry-pi-for-every-student
[4]: https://www.mondovo.com/keywords/
[5]: http://bauhausinteriors.com/blog/the-bauhaus-movement/
