
I want to talk to you about one thing
and just one thing only,
and this has to do with when people ask me,
what do you do?
To which I usually respond,
I do computer music.
Now, a number of people
just stop talking to me right then and there,
and the rest who are left usually have
this blank look in their eye,
as if to say, what does that mean?
And I feel like I&#39;m actually depriving them
of information by telling them this,
at which point I usually panic
and spit out the first thing that comes to my mind,
which is, I have no idea what I&#39;m doing.
Which is true.
That&#39;s usually followed by a second thought,
which is, whatever it is that I&#39;m doing,
I love it.
And today, I want to, well,
share with you something I love,
and also why.

And I think we&#39;ll begin with just this question:
What is computer music?
And I&#39;m going to try to do my
best to provide a definition,
maybe by telling you a story
that goes through some of the stuff
I&#39;ve been working on.
And the first thing, I think, in our story
is going to be something called ChucK.
Now, ChucK is a programming language for music,
and it&#39;s open-source, it&#39;s freely available,
and I like to think that it crashes equally well
on all modern operating systems.
And instead of telling you more about it,
I&#39;m just going to give you a demo.
By the way, I&#39;m just going to nerd out
for just a few minutes here,
so I would say, don&#39;t freak out.
In fact, I would invite all of you to join me
in just geeking out.
If you&#39;ve never written a line
of code before in your life,
do not worry.
I&#39;ll bet you&#39;ll be able to come along on this.
First thing I&#39;m going to do is to make
a sine wave oscillator,
and we&#39;re going to called the sine wave generator
&quot;Ge.&quot;
And then we&#39;re going to connect &quot;Ge&quot; to the DAC.
Now this is kind of the abstraction
for the sound output on my computer. Okay?
So I&#39;ve connected myself into the speaker.
Next, I&#39;m going to say my frequency
is 440 hertz,
and I&#39;m going to let time advance
by two seconds through this operation.
All right, so if I were to play this --
(Tone) —
you would hear a sine wave
at 440 hertz for two seconds.
Okay, great. Now I&#39;m going to copy and paste this,
and then just change some of these numbers,
220.5, 440 I shall leave it as that,
and .5 and 880.
By doubling the frequency,
we&#39;re actually going up in successive octaves,
and then we have this sequence --
(Tones) — of tones.
Okay, great, now I can imagine creating
all kinds of really horrible
single sine wave pieces of music with this,
but I&#39;m going to do something
that computers are really good at,
which is repetition.
I&#39;m going to put this all in a while loop,
and you actually don&#39;t need to indent,
but this is purely for aesthetic reasons.
It&#39;s good practice.
And when we do this —
(Tones) —
that&#39;s going to go on for a while.
In fact, it&#39;s probably not going to stop
until this computer disintegrates.
And I can&#39;t really empirically prove that to you,
but I hope you&#39;ll believe me when I say that.
Next, I&#39;m going to replace this 220
by math.random2f.
I&#39;m going to generate a random number
between 30 and 1,000 and send that
to the frequency of me.
And I&#39;m going to do this every half a second.
(Tones)
Let&#39;s do this every 200 milliseconds.
(Tones)
One hundred.
(Tones)
All right.
At this point, we&#39;ve reached something
that I would like to think of as
the canonical computer music.
This is, to me, the sound that mainframes
are supposed to be making
when they&#39;re thinking really hard.
It&#39;s this sound, it&#39;s like,
the square root of five million.
So is this computer music?
Yeah, I guess by definition,
it&#39;s kind of computer music.
It&#39;s probably not the kind of music you would listen to
cruising down the highway,
but it&#39;s a foundation of computer-generated music,
and using ChucK,
we&#39;ve actually been building instruments
in the Stanford Laptop Orchestra,
based right here at Stanford Center for
Computer Research in Music and Acoustics.
Now the Laptop Orchestra is an ensemble of laptops,
humans and special hemispherical speaker arrays.
Now the reason we have these
is so that for the instruments that we create
out of the laptop, we want the sound to come
out of somewhere near the instrument
and the performer,
kind of much like a traditional, acoustic instrument.
Like, if I were to play a violin here,
the sound would naturally not come out of
the P.A. system, but from the artifact itself.
So these speakers are meant to emulate that.
In fact, I&#39;m going to show you
how we actually built them.
The first step is to go to IKEA
and buy a salad bowl.
This is an 11-inch Blanda Matt.
That&#39;s the actual name,
and I actually use one of these
to make salad at home as well, I kid you not.
And the first step is you turn it upside down,
and then you drill holes in them,
six holes per hemi,
and then make a base plate,
put car speaker drivers in them
along with amplifiers in the enclosure,
and you put that all together and you have
these hemispherical speaker arrays.
Add people, add laptops,
you have a laptop orchestra.
And what might a laptop orchestra sound like?
Well, let me give you a demonstration
of about 200 instruments we&#39;ve created so far
for the Laptop Orchestra.
And what I&#39;m going to do is
actually come over to this thing.
This thing I have in front of me
actually used to be a commodity gaming controller
called a Gametrak.
This thing actually has a glove
you can put on your hands.
It&#39;s tethered to the base,
and this will track the position of your hands
in real time.
It was originally designed as a golfing controller
to detect the motion of your swing.
That turned out to be a rather large
commercial non-success,
at which point they slashed prices to 10 dollars,
at which point computer music researchers
said, &quot;This is awesome!
We can prototype instruments out of this.&quot;
So let me show you one instrument we&#39;ve created,
one of many, and this instrument
is called &quot;Twilight,&quot;
and it&#39;s meant to go with this metaphor
of pulling a sound out of the ground.
So let me see if this will work.
(Music)
And put it back.
And then if you go to the left,
right,
it sounds like an elephant in pain.
This is a slightly metallic sound.
Turn it just a bit.
(Music)
It&#39;s like a hovering car.
Okay.
This third one is a ratchet-like interaction, so
let me turn it up.
(Music)
So it&#39;s a slightly different interaction.
The fourth one is a drone.
(Music)
And finally, let&#39;s see,
this is a totally different interaction,
and I think you have to imagine that there&#39;s
this giant invisible drum sitting right here on stage,
and I&#39;m going to bang it.
(Drum)

(Laughter)

So there we go, so that&#39;s one of many instruments
in the Laptop Orchestra.

(Applause)

Thank you.
And when you put that together,
you get something that sounds like this.
(Music)
Okay, and so, I think from the experience
of building a lot of instruments
for the Laptop Orchestra,
and I think from the curiosity of wondering,
what if we took these
hopefully expressive instruments
and we brought it to a lot of people,
plus then a healthy bout of insanity —
put those three things together —
led to me actually co-founding a startup company
in 2008 called Smule.
Now Smule&#39;s mission is to create
expressive, mobile music things,
and one of the first musical instruments
we created is called Ocarina.
And I&#39;m going to just demo this for you real quick.
So Ocarina —
(Music) —
is based on this ancient flute-like instrument
called the ocarina,
and this one is the four-hole
English pendant configuration,
and you&#39;re literally blowing into the microphone
to make the sound.
And there&#39;s actually a little ChucK script
running in here that&#39;s detecting
the strength of your blowing
and also synthesizing the sound.
(Music)
And vibrato is mapped to the accelerometer,
so you can get —
(Music)
All right. So let me play a little ditty for you,
a little Bach.
And here, you&#39;ll hear a little
accompaniment with the melody.
The accompaniment actually follows the melody,
not the other way around.
(Music)
And this was designed
to let you take your time
and figure out where your expressive space is,
and you can just hang out here
for a while, for a really
dramatic effect, if you want,
and whenever you&#39;re ready —
(Music)
And on these longer notes,
I&#39;m going to use more vibrato
towards the end of the notes
to give it a little bit more of an expressive quality.
(Music)
Huh, that&#39;s a nice chord to end this excerpt on.

(Applause)

Thank you.
So I think a good question to ask about Ocarina is,
is this a toy or it an instrument? Maybe it&#39;s both,
but for me, I think the more important question is,
is it expressive?
And at the same time, I think
creating these types of instruments
asks a question about the role of technology,
and its place for how we make music.
Apparently, for example,
not that long ago, like only a hundred years ago —
that&#39;s not that long in the course of human history —
families back then
used to make music together
as a common form of entertainment.
I don&#39;t think that&#39;s really happening
that much anymore.
You know, this is before radio, before recording.
In the last hundred years, with all this technology,
we now have more access to music
as listeners and consumers,
but somehow, I think we&#39;re making less music
than ever before.
I&#39;m not sure why that would be.
Maybe it&#39;s because it&#39;s too easy just to hit play.
And while listening to music is wonderful,
there&#39;s a special joy to making music
that&#39;s all its own.
And I think that&#39;s one part
of the goal of why I do what I do
is kind of to take us back to the past a little bit. Right?
Now, if that&#39;s one goal, the other goal
is to look to the future and think about
what kind of new musical things can we make
that we don&#39;t perhaps yet have names for
that&#39;s enabled by technology, but ultimately
might change the way that humans make music.
And I&#39;ll just give you one example here,
and this is Ocarina&#39;s other feature.
This is a globe,
and here you&#39;re actually listening
to other users of Ocarina
blow into their iPhones to play something.
This is &quot;G.I.R.&quot; from Texas,
&quot;R.I.K.&quot; I don&#39;t know why it&#39;s these
three-letter names today, Los Angeles.
They&#39;re all playing pretty,
somewhat minimal music here.
(Music)
And the idea with this is that, well,
technology should not be foregrounded here,
and — 
(Laughter)
 —
we&#39;ve actually opened this up.
The first thought is that, hey, you know
there&#39;s somebody somewhere out there
playing some music,
and this is a small but I think important
human connection to make
that perhaps the technology affords.
As a final example,
and perhaps my favorite example,
is that in the wake of the 2011 earthquake
and tsunami disaster in Japan,
a woman reached out in one of our singing apps
to try to get people to join in to sing with her
on a version of &quot;Lean on Me.&quot;
Now, in these apps, there&#39;s this thing that allows
any user to add their voice
to an existing performance by any other user
or group of users,
so in some sense, she&#39;s created this kind of
global ad hoc corral of strangers,
and within weeks, thousands of people
joined in on this,
and you can kind of see people
coming from all around the world
and all these lines converging on the origin
where the first rendition of the song was sung,
and that&#39;s in Tokyo.
And this is what it sounds like 
when there&#39;s 1,000 people.
This is 1,000 voices.
(Recording) ♪ Sometimes in our lives ♪
♪ We all have pain, we all have sorrow ♪
♪ But if we are wise ♪
♪ We know that there&#39;s always tomorrow ♪
♪ Lean on me ♪
♪ When you&#39;re not strong ♪
♪ And I&#39;ll be your friend ♪
♪ I&#39;ll help you carry on ♪
♪ For it won&#39;t be long ♪
♪ Till I&#39;m gonna need ♪
♪ Somebody to lean on ♪
♪ Just lean on — ♪
Is this computer music?

(Applause)

Was that computer music?
Yeah, I guess so; it&#39;s something that you really
couldn&#39;t have done without computers.
But at the same time, it&#39;s also just human,
and I think what I&#39;ve essentially answered so far
is maybe why I do the stuff that I do,

and let&#39;s just finally return to the first question:
What is computer music?
And I think that the catch here is that,
at least to me, computer music
isn&#39;t really about computers.
It is about people.
It&#39;s about how we can use technology
to change the way we think
and do and make music,
and maybe even add to how we can
connect with each other through music.
And with that, I want to say,
this is computer music, and thank you for listening.

(Applause)

