---
layout: post
title: "Because Mr. Eco was right"
excerpt: "Why I really need to slow down and take my time learning..."
tags: [learning]
---

This week seems to be my week for coding mistakes (in as much as I can call it coding, that is[^1]). I am still relying a great deal too much on the viewing format of something and not enough on what the code is telling me about how something will look.

I sat down this week and work and renamed in excess of 200 image files to a more consistent format. Sadly it wasn't a case where I could beg one of my awesome cow-orkers to wave a magic scripting wand. The files really did require human eyes to look at the content of the image and say "Well obviously 'screenshot01.png' isn't going to cut it here." We were aiming for a loose BEM-style naming scheme[^2].

Of course then I had to commit the changes. Everything looked great in the [Markdown previewer](https://github.com/atom/markdown-preview) I use with the [Atom text editor](https://atom.io/). Except not so much on the accuracy upstream. When I got everything the way I thought it should look, I ran everything through our linter and ... nada. No complaints. That alone made me suspicious. I mean, at the very least I make some boneheaded typo or forget to prepend a URL with a slash or something. But this time? Nothing. Not a peep.

<img src="/images/i-might-be-a-wizard.gif" alt="I Might Be A Wizard animated gif" style="float:right;PADDING-LEFT: 10px;PADDING-BOTTOM: 10px">After confessing to my work Wonder Twin, [Uberfuzzy the Great and Powerful](https://github.com/uberfuzzy)[^3], that I basically felt like I was [rolling my face around on the keyboard](http://www.urbandictionary.com/define.php?term=faceroll), we set about fixing things[^4]. Lots of things. Like extra spaces that needed adding, double-editing files that were renamed multiple times in different commits, unused files that weren't removed. Sure there were the edge-casey typos that our linter seemed to usher on through with nary a complaint. But for the most part everything was fixable and avoidable if I HAD JUST PAID ATTENTION.

For all my self-professed love of pedantic little logic-y fiddly bits and bobs, I just don't understand why these little details escape me right now. Am I avoiding them? Is my brain deliberately ignoring them? Am I simply rushing through hoping to complete things quickly? I have no idea. Probably a combination of all these reasons.

Maybe I need a giant sticky note on the side of my monitor that says "HEY DUMMY!" and lists out the things I need to review manually that the linter simply won't find. At least until the review steps become second nature like editing text. I think it may save my life[^5]. In fact, the more I think about it, the more I like that idea a lot.

>"We like lists because we don't want to die." ~ Umberto Eco[^6]

[^1]: Because really, when it comes right down to it, it's formatting.
[^2]: Sort of like "Bob's Rules of Order" instead of "Robert's Rules of Order" in a way.
[^3]: Whenever I talk about my ever-patient cow-orkers, he heads the list. Always.
[^4]: Read: He fixed it all and I just sat there twiddling my thumbs.
[^5]: I'm not sure how long Uberfuzzy's patience is going to hold before he gets really stabby about these things. I think I owe him more than one bottle of his favorite umbrella drink booze in thanks for all the assists.
[^6]: Beyer, Susan, and Lothar Gorris. ["SPIEGEL Interview with Umberto Eco: 'We Like Lists Because We Don't Want to Die'"](http://www.spiegel.de/international/zeitgeist/spiegel-interview-with-umberto-eco-we-like-lists-because-we-don-t-want-to-die-a-659577.html) Spiegel Online. November 11, 2009. Accessed March 14, 2015.
