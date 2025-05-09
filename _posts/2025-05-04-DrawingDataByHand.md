---
title: "drawing data by hand"
date: 2025-05-04
---
![Class Quilt](/post_images/drawing%20data%20by%20hand/class_quilt.png "Class Quilt")

*The class quilt. Each square represents a member of the course and each feature of a square —background color, main symbol, border, etc.— represents an answer to a personal question such as: what's your favorite texture to feel in spring?*

Last May I took a digital art class. It was about trying stuff, creating and, surprisingly, learning about myself.

Drawing Data by Hand is a class offered by SFPC (Society for Poetic Computation) that explores data visualizations through sketching, daily life exploration and introspection. 

When I stumbled upon SFPC by recommendation of a friend, I first saw HTTPoetics and thought it was one of the coolest things I had seen. But when browsing through the available courses, Drawing Data by Hand really caught my eye — I do data visualization as part of my engineering work and this course offered me a path to a new perspective on something that had become mundane.

First of all, I recommend this class one hundred million percent (as a qualified engineer I am allowed to use such expression). For that reason, I won't be going over the details of the class or its content, because they belong to the class and, also, I would be spoiling the whole experience. 

However, I do wanna do the show-and-tell part of the things that I took home: stuff I made in class and the lessons that came with it.
## i data me

These are some of the things I made - each tied to a prompt, an idea, or an encouraged personal project. Most of them are quick, playful sketches that have personal perception embedded into the data they portray. That’s why I cherish them—improvised creation is one of the ways I feel closest to art, regardless of the result (not me soft-launching that I do improv).
###### my personal history of condiments

![Condiments](/post_images/drawing%20data%20by%20hand/condiments.jpg "Condiments Through Time")

*prompt: draw your condiments from your childhood home vs now* 

I was surprised at how much I liked hand-drawn histograms better over the ones I usually produce with Python. A quick ChatGPT query helped me with the title and the "felt history" stuck with me. I usually feel guilty of my recounting of stories because I tend to add condiments for the sake of the plot. However, disclosing it in the title as _felt_ history, i.e., how I feel it was, provided me the peace of mind of being honest, and understanding how the re-telling of something is almost always biased and that's okay too.

###### the history of my family

![family map starter](/post_images/drawing%20data%20by%20hand/family_map_1.png "The first visualization of my family")

![family map final](/post_images/drawing%20data%20by%20hand/family_map_2.png "Final abstract visualization")
- Black dots represent birth
- Black squares represent remains
- Thick lines represent immigration
- Thick lines represent travel for visit, could be relatives or a person who immigrated

*prompt: draw a visualization of the history of your family* 

Any visualization type was encouraged, but having played with maps during class — you guessed it, I started with a map. My family history **is** about immigration, so to be fair, a map does offer good proxy for movement. However, led by my desire to escape literalness I abstracted from the geographical references to focus on the flow and let the lines speak for themselves. Where our family's remains lie is also a big part of our history, it reflects belonging and deep connection with cultures that may or may not be where they were born. 

This was nice. I got to think about my family, especially those who are not with me. Gave me a big picture of how interestingly varied my family is, which I usually tend to forget about. In addition, it led to a really nice conversation with my grandma which are rare these days, especially as a tired adult (me).

###### a map to a friend's house

![edus house](/post_images/drawing%20data%20by%20hand/edus_house.png "Map to Edu's House")

*prompt: draw a map from memory to your friend's house*

I'd never really thought about or noticed personal perception embedded in maps before. It was nice learning that many maps that had struck me in the past had this as a core characteristic. 

###### `reminders_of_decay.envelope`

The final project consisted of creating a visualization of any personal dataset explored during class, I chose my unread WhatsApp messages from the last 4 years. 

I was greatly influenced by [Sarah GHP](https://sarahghp.com/bio)'s *Timeline of Neglect*, where the artist visualized their unread book collection based on the days that passed since acquiring them. I loved how she was able to represent something intangible —such as neglect— using a clever proxy like time. 

Another influence in this work was  [Félix González-Torres](https://en.wikipedia.org/wiki/F%C3%A9lix_Gonz%C3%A1lez-Torres "Félix González-Torres")'s  *"Untitled" (Portrait of Ross in L.A.)*, where a pile of candies represented the ideal weight of the artist’s partner, who at the time was dealing with a deteriorating condition. This exhibition struck me with its connection with loss and eternity, and how meaning can be embedded in material choices.

I sorted my messages on a very-late-night Tuesday, which I regret it because I didn't get to collect all the things I wanted from this dataset. However, I did include some interesting parameters that helped me in my creative process:
- my relationship status with sender at the time of receiving the message
- my current relationship status with sender
- do I regret not responding?
- is it too late to respond?
- do I miss that person?

![final project structured data](/post_images/drawing%20data%20by%20hand/structured_data.png "Structured Data Unread Whatsapp Messages")

After staring at the spreadsheet for a while looking for patterns, I realized that the *change* of my relationship could be a proxy for the consequences of ghosting. And like that, my journey to represent relationship decay and its connection with ghosting began.

Initially I wanted to draw, since it was my newly-learned tool for representing data, so I played with some data-viz that, at the moment, didn't quite make the cut but I now kinda dig. 

![doodle 1](/post_images/drawing%20data%20by%20hand/doodle_1.png "Before and After Ghosting")

![doodle 2](/post_images/drawing%20data%20by%20hand/doodle_2.png "Before and After Ghosting Fluvial Map")

Thinking about Felix's work (and other artists explored in class) I looked out of traditional graphs and thought about material representations. I settled on using envelopes because of:
1. Their clear relationship with unread messages
2. I liked how they looked and felt
3. The dimensions they offered: envelopes can vary shape, size and color. 

![reminders of decay](/post_images/drawing%20data%20by%20hand/reminders_of_decay.png "reminders of decay.envelope")

And so, after a trip to my local stationary, `reminders_of_decay.envelope` came to be.

- Unread messages from 2021-2025 (31).
- Sorted in the stack by date.
- Each envelope _should_ (maybe in the future) contain a copy of the message preview.
- Colors represent relationship decay:
	- White indicates no change in the relationship status with sender.
	- Red indicates decay in the relationship, e.g. friend -> acquaintance or acquaintance -> stranger.
	- Black indicates a decay from friend to stranger, symbolizing the loss of something precious.
	- Yellow indicates decay in relationship, just like yellow, but it is not too late to respond, and possibly, amend this change.

![reminders of decay 2](/post_images/drawing%20data%20by%20hand/reminders_of_decay_2.png "reminders of decay.envelope")

Poetically, the stack sits by my desk and, surprisingly, I still ignore it. However, I now get a tangible sense of what my ghosting habits lead to. 

My classmates noted two things I hadn't realized before sharing this work:

There is only one yellow envelope, and it sticks out. It made me think about them—about our relationship—and why haven't I responded if I still had time to. I guess, as we drew apart, that unread message became a kind of hope: that maybe we haven’t really changed, that we’re still the same people who used to be friends. And maybe I prefer holding onto that possibility over confirming we’re not anymore.
 
I based my work on the premise that I knew whether it was too late to respond or not. A classmate asked me how I knew such a thing; I couldn't think of a good answer. 
 
I guess they were on the right track — it made me realize that maybe, it is never *too* late to respond. 
