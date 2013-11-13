# Day 1
I've been thinking a lot about impermanence when it comes to text... About how a text can be altered, or maybe about the fluidity of meaning. My thoughts are all over the place, but here are some ideas. Some take a route towards historical revisionism (myth), other look at textual impermanence [*I've got to find a better phrase for that] formally: what a text looks like when it is changed or destroyed.

**OR** devising ways to hide the fact that a text has been changed.

**OR** embracing that a text can change (perhaps without notice or evidence) and creating a typeface that helps the modifier do so. I suppose this typeface would be a hand-written style.
- This seems quite foolish, though. The real ephemerality of text comes into play with digital text.
	* A wiki is changed
	* A hacker defaces a website
	* A purposefully sensational post on a political subreddit is changed *after* users comment/support, making the users look like fools or radicals
		- → Mirrors or snapshots are create to visualize this change, or at least provide a record of its past

I am also interested in version control, like Git. Edits are "nondestructive" because the past versions are all recoverable. Changes are ultra-visible. Git would have been a great art project. Part of me feels, though, that if I make work about version control, it would be pigeonholed into "transparency protest". 

Have I become so jaded that "creating the world we envision" seems hackneyed? 

# Day 2, RE: Handwriting vs Digital Text
I may be overlooking something interesting in the impermanence of written text, but truthfully my instinct is to do something digital. Maybe this is because my comfort-zone is in the digital realm, but it feels more appropriate to focus here. 

It does seem to be "more interesting"—I guess—to look at historical revisionism through digital capabilities: what does technology allow us to do to our past? On one hand, it is easy to remark how there is a file on everything, a record or evidence. We will likely continue down that path. But my interest, I think, at the point anyway, is in how all those traces are digital and therefore editable. Of course, there are permissions and digital signatures, but overall it seems like technology has given us a way to **forge history**. It's less about removing bits as much as it is changing what's there and **adding more** (saturating the market). 

I think what I really want to do is learn to be a hacker. I want to be able to upload my own files to the Library of Congress, or at least make a file look like it's coming from there. I want to create a data packet from scratch, to fake a digital signature. 

Maybe in overlooking written text, I am overlooking a huge vulnerability that could be exploited. Maybe so much time and energy is being put towards digital security that a physical change is more likely to go unnoticed. Using America as an example, though, this seems unlikely. The U.S. spends all of its money on a digital offensive but leaves its digital defenses weak. In that case, a digital change is perhaps "stealthier". 

- Drawings of digital "seals"

Another something-or-other I've been sitting on comes from summer 2012 when I was working at Munich Reinsurance. I am interested (and this falls outside of the textual impermanence thing) in the act of creating work within a place and the ownership of that work. What I create at work is under my authorship but not my ownership. 
> *"I created it, I own it*
> *VS*
> *I created it, you own the tool, you own it*
> *VS*
> *I created it, I own the tool, you own the subject, you own it*
> *VS*
> *I created it, I own the tool, you bought the subject, I could buy the subject, I could own something similar* 
> *VS*
> *I created it, you own it, fuck you"*

Partially, I think my interest in this comes from the idea of containers → something I have not worked out in the slighted. Literally, I am interested in things that are built to contain other things. 
1. Because it automatically assumes a position/role of power and hierarchy
2. Because it continues infinitely: this contains this, which contains this, which contains this, which ... ... ...
3. There is often one direction of flow (of information, of command, of power, etc.)

Maybe I'm more interested in containers as a symbol to incorporate into later works, like a stupid painter using ants. 

I think there are often interesting relationships between the container and the contents. Like how the container can stand **to represent the contents**, but not always the reverse. Or perhaps the idea of synecdoche in general. 

I also like the idea of an empty container, but I'm not if my interest in trying to be subversive or nihilistic. I mean, I'm not sure if I want to deceive people by **exploiting their expectation for a container to have relevant and appropriate contents**, or if I am expressing a perpetual dissatisfaction with discovering new containers in a descending chain, or that containers on different scopes may contradict one another. I.E. that it is hopeless (well... maybe not hopeless, but never-ending) to explore a chain of containers because you will never reach an end. Part of me finds this idea exciting, though (and this is perhaps how it ties into my interest in horizontality and the internet). Certainly the first idea is more interesting.

## Steganography
There's something interesting about "the art and science of encoding hidden messages in such a way that no one, apart from the sender and intended recipient, suspects the existence the message." 
> *"It is a form of security through obscurity"*
> *"The advantage of steganography over cryptography alone is that the intended secret message does not attract attention to itself as an object of scrutiny."*
- A little more about containers... If the container can veil the contents... 

## Ok let's get to some practical planning
#### About the left-align/center-align revisions
*What would this look like?*
Fuck it, let's just start building!
#### First Draft
- Ok looking good! In its current state, it is a toggle. On first load, the text "Left-aligned text" is displayed from the DOM. Immediately, Javascript appends a new `<p>` "is easier to edit than center-aligned text". The start of the appended paragraph is aligned correctly to the end of the first paragraph. When clicked, the body text switches from "Left-align text" to "Center-aligned text," and it is indeed center-aligned. Again, immediately Javascript appends a new `<p>` "is harder to edit than left-aligned text"
- I think maybe I can drop the comparison, so that it says "is easier to edit." and "is harder to edit."
- By mistake, initially both sentences said they were "easier" than the other. I might actually enjoy this contradiction.
- Something interesting might happen if instead of _replacing_ the  last sentence, the new one was appended.
- RE: fonts... Maybe something with serifs? Referencing an older document? I could have the initial be serif and the appendage be sans serif.
- One thing I do like about this is it that the initial text will get highlighted if the user toggles fast enough. Maybe it should be highlighted from the start? Maybe it should fade in?
#### Second Draft

#### Print Sketches
- Experimenting with showing the bounding boxes
- Maybe this should be a video that documents editing the text without editing the initial text.
- Should this be accompanied by a manifesto championing center-aligned text. That could be really funny. 
- I'm thinking a three-column presentation: 1 for the changing/appending text, 1 for a visual presentation of the containers (maybe a live DOM, maybe something that relates it to steganography or radio imaging that reveals paintings beneath paintings), and 1 for a written manifesto championing center-aligned center (or maybe left-aligned. yet to be decided).
- One way or another, though, it's clear this needs to be more than a webpage. It's not really interesting in this form, and it doesn't really make any sense.
- One thing to figure out is whether I am in favor of changing texts or against... Maybe I don't have to decide. Maybe I can just make an observation/point out an exploit that center-aligned text is an added layer of defense. Like, bringing a tool to the people so they may use it in any way they see fit. All the same, exposing it to "bad people" and people at the top of power systems. Luckily, the idea is so fucking stupid that they would never even try.
- This *is* sort of the same vain of Hito's "How Not To Be Seen: A Fucking Didactic Educational .MOV File"—I think.. I haven't seen it yet. **Maybe it would be good to have the left-align/center-align argument be one piece in a larger body of work of tools to aid/disrupt the impermanence of text.**
-- I need to see this piece to really make a judgement about whether or not I'm shooting for it. I'm worried about... What am I worried about? Something about her title makes me think that she's tired of these "fucking didactic educational videos" that propose solutions. But you know, maybe I am too. I mean, why am I suggesting center-aligned type? It's like scratching the bottom of the barrel of trying to take hold of history. A collection of last-ditch efforts. Do I really feel that defeated? Well, kind of. In Cooper-related terms, I feel pretty defeated about the history and legacy of the place. I feel like the battle is pretty much lost. But I'm looking forward to distilling some of the influences it had on me, and creating my own institution to reflect those ideals. That's not so defeated. Where is the essence of moving forward in this project? Don't you get tired of people complaining *all the time*?

## After seeing Hito's "How Not To Be Seen: A Fucking Didactic Educational .MOV File"
The piece was amazing, for what it's worth. The discussion surrounding it was _okay_ but not particularly inspiring. That is, with the exception of one question (or remark rather). Paraphrased:
> Q: This seems to be your most hopeless piece. None of the solutions proposed would really work. Is it hopeless to try to be invisible?
> A: I totally disagree. This piece is humorous, I guess, but I am dead serious. I think these methods can work. In image-mediated world, if you can have the power to affect those images, you can affect the world. You can write your own reality if you can affect the images. I'm being dead serious. Yes, these are half-solutions, but they are solutions nonetheless.
That was really helpful for me. I'm projecting here, but I think what she's saying that although it is farcical, the conversation is still serious. Having a hand in image-mediation is intensely powerful, and these are genuinely ways you can do it. They are fantastic and sometimes outlandish, but their underlying concepts _make sense_. So long as your methods for rewriting history or editing text have a concept rooted in reality, it doesn't necessarily matter that the actual methods are outlandish.
