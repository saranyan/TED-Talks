
Most of us think of motion
as a very visual thing.
If I walk across this stage
or gesture with my hands while I speak,
that motion is something that you can see.
But there&#39;s a world of important motion
that&#39;s too subtle for the human eye,
and over the past few years,
we&#39;ve started to find that cameras
can often see this motion
even when humans can&#39;t.
So let me show you what I mean.
On the left here, you see video
of a person&#39;s wrist,
and on the right, you see video
of a sleeping infant,
but if I didn&#39;t tell you
that these were videos,
you might assume that you were looking
at two regular images,
because in both cases,
these videos appear to be
almost completely still.
But there&#39;s actually a lot
of subtle motion going on here,
and if you were to touch
the wrist on the left,
you would feel a pulse,
and if you were to hold
the infant on the right,
you would feel the rise
and fall of her chest
as she took each breath.
And these motions carry
a lot of significance,
but they&#39;re usually
too subtle for us to see,
so instead, we have to observe them
through direct contact, through touch.
But a few years ago,
my colleagues at MIT developed
what they call a motion microscope,
which is software that finds
these subtle motions in video
and amplifies them so that they
become large enough for us to see.
And so, if we use their software
on the left video,
it lets us see the pulse in this wrist,
and if we were to count that pulse,
we could even figure out
this person&#39;s heart rate.
And if we used the same software
on the right video,
it lets us see each breath
that this infant takes,
and we can use this as a contact-free way
to monitor her breathing.
And so this technology is really powerful
because it takes these phenomena
that we normally have
to experience through touch
and it lets us capture them visually
and non-invasively.
So a couple years ago, I started working
with the folks that created that software,
and we decided to pursue a crazy idea.
We thought, it&#39;s cool
that we can use software
to visualize tiny motions like this,
and you can almost think of it
as a way to extend our sense of touch.
But what if we could do the same thing
with our ability to hear?
What if we could use video
to capture the vibrations of sound,
which are just another kind of motion,
and turn everything that we see
into a microphone?
Now, this is a bit of a strange idea,
so let me try to put it
in perspective for you.
Traditional microphones
work by converting the motion
of an internal diaphragm
into an electrical signal,
and that diaphragm is designed
to move readily with sound
so that its motion can be recorded
and interpreted as audio.
But sound causes all objects to vibrate.
Those vibrations are just usually
too subtle and too fast for us to see.
So what if we record them
with a high-speed camera
and then use software
to extract tiny motions
from our high-speed video,
and analyze those motions to figure out
what sounds created them?
This would let us turn visible objects
into visual microphones from a distance.
And so we tried this out,
and here&#39;s one of our experiments,
where we took this potted plant
that you see on the right
and we filmed it with a high-speed camera
while a nearby loudspeaker
played this sound.

(Music: &quot;Mary Had a Little Lamb&quot;)
And so here&#39;s the video that we recorded,
and we recorded it at thousands
of frames per second,
but even if you look very closely,
all you&#39;ll see are some leaves
that are pretty much
just sitting there doing nothing,
because our sound only moved those leaves
by about a micrometer.
That&#39;s one ten-thousandth of a centimeter,
which spans somewhere between
a hundredth and a thousandth
of a pixel in this image.
So you can squint all you want,
but motion that small is pretty much
perceptually invisible.
But it turns out that something
can be perceptually invisible
and still be numerically significant,
because with the right algorithms,
we can take this silent,
seemingly still video
and we can recover this sound.

(Music: &quot;Mary Had a Little Lamb&quot;)

(Applause)

So how is this possible?
How can we get so much information
out of so little motion?
Well, let&#39;s say that those leaves
move by just a single micrometer,
and let&#39;s say that that shifts our image
by just a thousandth of a pixel.
That may not seem like much,
but a single frame of video
may have hundreds of thousands
of pixels in it,
and so if we combine all
of the tiny motions that we see
from across that entire image,
then suddenly a thousandth of a pixel
can start to add up
to something pretty significant.
On a personal note, we were pretty psyched
when we figured this out.

(Laughter)

But even with the right algorithm,
we were still missing
a pretty important piece of the puzzle.
You see, there are a lot of factors
that affect when and how well
this technique will work.
There&#39;s the object and how far away it is;
there&#39;s the camera
and the lens that you use;
how much light is shining on the object
and how loud your sound is.
And even with the right algorithm,
we had to be very careful
with our early experiments,
because if we got
any of these factors wrong,
there was no way to tell
what the problem was.
We would just get noise back.
And so a lot of our early
experiments looked like this.
And so here I am,
and on the bottom left, you can kind of
see our high-speed camera,
which is pointed at a bag of chips,
and the whole thing is lit
by these bright lamps.
And like I said, we had to be
very careful in these early experiments,
so this is how it went down.

(Video) Abe Davis: Three, two, one, go.
Mary had a little lamb!
Little lamb! Little lamb!

(Laughter)


AD: So this experiment
looks completely ridiculous.

(Laughter)

I mean, I&#39;m screaming at a bag of chips --

(Laughter)
 --
and we&#39;re blasting it with so much light,
we literally melted the first bag
we tried this on. 
(Laughter)

But ridiculous as this experiment looks,
it was actually really important,
because we were able
to recover this sound.
(Audio) Mary had a little lamb!
Little lamb! Little lamb!

(Applause)


AD: And this was really significant,
because it was the first time
we recovered intelligible human speech
from silent video of an object.
And so it gave us this point of reference,
and gradually we could start
to modify the experiment,
using different objects
or moving the object further away,
using less light or quieter sounds.
And we analyzed all of these experiments
until we really understood
the limits of our technique,
because once we understood those limits,
we could figure out how to push them.
And that led to experiments like this one,
where again, I&#39;m going to speak
to a bag of chips,
but this time we&#39;ve moved our camera
about 15 feet away,
outside, behind a soundproof window,
and the whole thing is lit
by only natural sunlight.
And so here&#39;s the video that we captured.
And this is what things sounded like
from inside, next to the bag of chips.
(Audio) Mary had a little lamb
whose fleece was white as snow,
and everywhere that Mary went,
that lamb was sure to go.

AD: And here&#39;s what we were able
to recover from our silent video
captured outside behind that window.
(Audio) Mary had a little lamb
whose fleece was white as snow,
and everywhere that Mary went,
that lamb was sure to go.

(Applause)


AD: And there are other ways
that we can push these limits as well.
So here&#39;s a quieter experiment
where we filmed some earphones
plugged into a laptop computer,
and in this case, our goal was to recover
the music that was playing on that laptop
from just silent video
of these two little plastic earphones,
and we were able to do this so well
that I could even Shazam our results.

(Laughter)


(Music: &quot;Under Pressure&quot; by Queen)

(Applause)

And we can also push things
by changing the hardware that we use.
Because the experiments
I&#39;ve shown you so far
were done with a camera,
a high-speed camera,
that can record video
about a 100 times faster
than most cell phones,
but we&#39;ve also found a way
to use this technique
with more regular cameras,
and we do that by taking advantage
of what&#39;s called a rolling shutter.
You see, most cameras
record images one row at a time,
and so if an object moves
during the recording of a single image,
there&#39;s a slight time delay
between each row,
and this causes slight artifacts
that get coded into each frame of a video.
And so what we found
is that by analyzing these artifacts,
we can actually recover sound
using a modified version of our algorithm.
So here&#39;s an experiment we did
where we filmed a bag of candy
while a nearby loudspeaker played
the same &quot;Mary Had a Little Lamb&quot;
music from before,
but this time, we used just a regular
store-bought camera,
and so in a second, I&#39;ll play for you
the sound that we recovered,
and it&#39;s going to sound
distorted this time,
but listen and see if you can still
recognize the music.

(Audio: &quot;Mary Had a Little Lamb&quot;)
And so, again, that sounds distorted,
but what&#39;s really amazing here
is that we were able to do this
with something
that you could literally run out
and pick up at a Best Buy.
So at this point,
a lot of people see this work,
and they immediately think
about surveillance.
And to be fair,
it&#39;s not hard to imagine how you might use
this technology to spy on someone.
But keep in mind that there&#39;s already
a lot of very mature technology
out there for surveillance.
In fact, people have been using lasers
to eavesdrop on objects
from a distance for decades.
But what&#39;s really new here,
what&#39;s really different,
is that now we have a way
to picture the vibrations of an object,
which gives us a new lens
through which to look at the world,
and we can use that lens
to learn not just about forces like sound
that cause an object to vibrate,
but also about the object itself.
And so I want to take a step back
and think about how that might change
the ways that we use video,
because we usually use video
to look at things,
and I&#39;ve just shown you how we can use it
to listen to things.
But there&#39;s another important way

that we learn about the world:
that&#39;s by interacting with it.
We push and pull and poke and prod things.
We shake things and see what happens.
And that&#39;s something that video
still won&#39;t let us do,
at least not traditionally.
So I want to show you some new work,
and this is based on an idea I had
just a few months ago,
so this is actually the first time
I&#39;ve shown it to a public audience.
And the basic idea is that we&#39;re going
to use the vibrations in a video
to capture objects in a way
that will let us interact with them
and see how they react to us.
So here&#39;s an object,
and in this case, it&#39;s a wire figure
in the shape of a human,
and we&#39;re going to film that object
with just a regular camera.
So there&#39;s nothing special
about this camera.
In fact, I&#39;ve actually done this
with my cell phone before.
But we do want to see the object vibrate,
so to make that happen,
we&#39;re just going to bang a little bit
on the surface where it&#39;s resting
while we record this video.

So that&#39;s it: just five seconds
of regular video,
while we bang on this surface,
and we&#39;re going to use
the vibrations in that video
to learn about the structural
and material properties of our object,
and we&#39;re going to use that information
to create something new and interactive.
And so here&#39;s what we&#39;ve created.
And it looks like a regular image,
but this isn&#39;t an image,
and it&#39;s not a video,
because now I can take my mouse
and I can start interacting
with the object.
And so what you see here
is a simulation of how this object
would respond to new forces
that we&#39;ve never seen before,
and we created it from just
five seconds of regular video.

(Applause)

And so this is a really powerful
way to look at the world,
because it lets us predict
how objects will respond
to new situations,
and you could imagine, for instance,
looking at an old bridge
and wondering what would happen,
how would that bridge hold up
if I were to drive my car across it.
And that&#39;s a question
that you probably want to answer
before you start driving
across that bridge.
And of course, there are going to be
limitations to this technique,
just like there were
with the visual microphone,
but we found that it works
in a lot of situations
that you might not expect,
especially if you give it longer videos.
So for example,
here&#39;s a video that I captured
of a bush outside of my apartment,
and I didn&#39;t do anything to this bush,
but by capturing a minute-long video,
a gentle breeze caused enough vibrations
that we could learn enough about this bush
to create this simulation.

(Applause)

And so you could imagine giving this
to a film director,
and letting him control, say,
the strength and direction of wind
in a shot after it&#39;s been recorded.
Or, in this case, we pointed our camera
at a hanging curtain,
and you can&#39;t even see
any motion in this video,
but by recording a two-minute-long video,
natural air currents in this room
created enough subtle,
imperceptible motions and vibrations
that we could learn enough
to create this simulation.
And ironically,
we&#39;re kind of used to having
this kind of interactivity
when it comes to virtual objects,
when it comes to video games
and 3D models,
but to be able to capture this information
from real objects in the real world
using just simple, regular video,
is something new that has
a lot of potential.
So here are the amazing people
who worked with me on these projects.

(Applause)

And what I&#39;ve shown you today
is only the beginning.
We&#39;ve just started to scratch the surface
of what you can do
with this kind of imaging,
because it gives us a new way
to capture our surroundings
with common, accessible technology.
And so looking to the future,
it&#39;s going to be
really exciting to explore
what this can tell us about the world.
Thank you.

(Applause)

