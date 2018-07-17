# README

To deploy just create a local server and open `index.html`

The way **I** do it is `python -m SimpleHTTPServer portNumberHere`

### this is better read at the rendered index.html

This is **inter-face,** the whole point of it is to explore the idea of making face tracking an interface instead of a gimmick that Instagram has. The said gimmick is great, it works and attracts people to it, but that has been very well explored, and in my opinion, this tech can be used for other things. One of them is as an interface.

Using it is very simple. The app records **4.5-second video-clips**. and it does so when you **raise your eyebrows**. In this case, the movement is linked to a threshold value, that once exceeded starts recording and then pops up a request to save it.

This particular experience is **not finished**, it has plenty of problems but the **main point** that I am trying to get across **is clear**.
If it were to be made a **full-fledged experience**. Issues like the permissions wouldn't be there, and the video, instead of being just saved into the system, it would be used for **something more exciting**.
The camera would not need to be right on top of the screen, or would **not even need to be the same camera** that is the one doing the face tracking, getting this way a more interesting shot.

This is **just one example** of what can be done with faces being used as an interface. When I started to create this, I just **wanted to explore** a concept that I thought might have **potential**. This app uses only the eyebrows. But you could decide to **use more** parts of the face or even use only the **orientation** of it. And here the output is only a video, but so much more can be done; making the face orientation a mouse, triggering different things depending on what expression you do, **playing pong by looking up and down**.
Basically, you have this new input that does not require any kind of physical contact and that can be used by pretty much anyone (there are always exceptions). **And you only need a camera, no specialized equipment**.

---

The **framework** being used to track the face is [clmtrackr](https://github.com/auduno/clmtrackr). This experience is built from the **emotion detection** [example](https://www.auduno.com/clmtrackr/examples/clm_emotiondetection.html). I used the example due to it having already part of **what I needed**, and trying to make a whole new model for a single eyebrow movement was a big hassle. This was **not my first choice** for a framework. The tracking is **not very precise** and it "jumps" a lot.
My **initial choice** was [brfv4](https://tastenkunst.github.io/brfv4_javascript_examples/), which is very precise and gives a **lot of information**, but the documentation is not very 'prototyping-in-one-day friendly' so I had to give it up. But for sure is going to be my 'go-to' next time I do a project with face tracking (it just requires a bit more time to use it).

To **record** I am using [RecordRTC](https://www.webrtc-experiment.com/RecordRTC/). let's just say that it 'works'.
