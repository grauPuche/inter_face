# README

This simple and hacked together experience is to demonstrate the idea that face tracking might be useful for other things other than giving you bunny ears.

For a while I wanted to try doing something with this kind of tech, but as said, I wanted to go away from the kind of applications that are being done at the moment. My interest was on using the face as an interface (heh..)

At first, the plan was to make a simple text-based narrative video game, where instead of writing what to do, you would have to give a specific expression. Although the idea is feasible, to do it in one day is not. specially when diving into a new technology.

So the obvious next step was to make something a bit more simple. So here we are.

The framework being used here is clmtrackr. This experience is build from the emotion detection example. I used the example due to it having already part of what I needed, and trying to make a whole new model for the a single eyebrow movement was not worth the time.
But this was not my first choice for a framework. The tracking is not very precise and it "jumps" a lot. My initial choice was brfv4, which is very precise and gives a lot of information, but the documentation is not very 'prototyping-in-one-day friendly' so I had to give it up. But for sure is going to be my 'go-to' next time I do a project with face tracking (it just requires a bit more time to use it).

What this ended up being, if you haven't tried it already, is a video recording experience. And the interactions is through the eyebrows, when they are raised, the recording starts, and captures 4.5 seconds of soundless footage, that pops up a save request.
To Record I am using RecordRTC. let's just say that it 'works'.

As expected this is very much a WIP and mainly a Proof of concept. Thank you for the opportunity and I hope I hear from Outernets very soon.

gP