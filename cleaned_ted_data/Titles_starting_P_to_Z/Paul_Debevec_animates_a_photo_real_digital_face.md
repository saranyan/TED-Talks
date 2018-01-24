
One of the biggest challenges in computer graphics
has been being able to create a photo-real,
digital human face.
And one of the reasons it is so difficult is that, unlike aliens and dinosaurs,
we look at human faces every day.
They are very important to how we communicate with each other.
As a result, we&#39;re tuned in to the subtlest things
that could possibly be wrong with a computer rendering,
in order to believe whether these things are realistic.
And what I&#39;m going to do in the next five minutes
is take you through a process
where we tried to create a reasonably photo-realistic computer-generated face,
using some computer graphics technology we&#39;ve developed,
and also some collaborators at a company called Image Metrics.
And we&#39;re going to try to do a photo-real face
of an actress named Emily O&#39;Brien, who is right there.
And that&#39;s actually a completely computer-generated rendering of her face.
By the end of the talk, we&#39;re going to see it move.
The way that we did this is we tried to start with Emily herself,
who was gracious enough to come to our laboratory
in Marina Del Rey, and sit for a session in Light Stage 5.
This is a face-scanning sphere, with 156 white LEDs all around
that allow us to photograph her
in a series of very controlled illumination conditions.
And the lighting that we use these days looks something like this.
We shoot all of these photographs in about three seconds.
And we basically capture enough information
with video projector patterns that drape over the contours of her face,
and different principle directions of light from the light stage,
to figure out both the coarse-scale
and the fine-scale detail of her face.
If we zoom in on this photograph right here,
we can see it&#39;s a really nice photograph to have of her,
because she is lit from absolutely everywhere at the same time
to get a nice image of her facial texture.
And in addition, we&#39;ve actually used polarizers on all the lights --
just like polarized sunglasses can block
the glare off of the road,
polarizers can block the shine off of the skin,
so we don&#39;t get all those specular reflections to take this map.
Now, if we turn the polarizers around just a little bit,
we can actually bring that specular reflection
of the skin back in,
and you can see she looks kind of shiny and oily at this point.
If you take the difference between these two images here,
you can get an image lit from the entire sphere of light
of just the shine off of Emily&#39;s skin.
I don&#39;t think any photograph like this had ever been taken
before we had done this.
And this is very important light to capture,
because this is the light that reflects off the first surface of the skin.
It doesn&#39;t get underneath the translucent
layers of the skin and blur out.
And, as a result, it&#39;s a very good cue
to the detailed shape of the skin-pore structure
and all of the fine wrinkles that all of us have,
the things that actually make us look like real humans.
So, if we use information that comes off of this specular reflection,
we can go from a traditional face scan
that might have the gross contours of the face and the basic shape,
and augment it with information
that puts in all of that skin pore structure and fine wrinkles.
And, even more importantly,
since this is a photometric process that only takes three seconds to capture,
we can shoot Emily
in just part of an afternoon,
in many different facial poses and facial expressions.
So, here you can see her moving her eyes around, moving her mouth around.
And these we&#39;re actually going to use to create a photo-real digital character.
If you take a look at these scans that we have of Emily,
you can see that the human face does an enormous amount of amazing things
as it goes into different facial expressions.
You can see things. Not only the face shape changes,
but all sorts of different skin buckling and skin wrinkling occurs.
You can see that the skin pore structure changes enormously
from stretched skin pores
to the regular skin texture.
You can see the furrows in the brow and how the microstructure changes there.
You can see muscles pulling down at flesh to bring her eyebrows down.
Her muscles bulging in her forehead when she winces like that.
In addition to this kind of high-resolution geometry,
since it&#39;s all captured with cameras, we&#39;ve got a great texture map to use for the face.
And by looking at how the different color channels of the illumination,
the red and the green and the blue,
diffuse the light differently,
we can come up with a way of shading the skin on the computer.
Then, instead of looking like a plaster mannequin,
it actually looks like it&#39;s made out of living human flesh.
And this is what we used
to give to the company Image Metrics
to create a rigged, digital version of Emily.
We&#39;re just seeing the coarse-scale geometry here.
But they basically created a digital puppet of her,
where you can pull on these various strings,
and it actually moves her face in ways that are
completely consistent with the scans that we took.
And, in addition to the coarse-scale geometry,
they also used all of that detail
to create a set of what are called &quot;displacement maps&quot;
that animate as well.
These are the displacement maps here.
And you can see those different wrinkles actually show up as she animates.
So the next process was then to animate her.
We actually used one of her own performances to provide the source data.
So, by analyzing this video with computer vision techniques,
they were able to drive the facial rig
with the computer-generated performance.
So what you&#39;re going to see now, after this,
is a completely photo-real digital face.
We can turn the volume up a little bit if that&#39;s available.

Emily: Image Metrics is a markerless, performance-driven animation company.
We specialize in high-quality facial animation
for video games and films.
Image Metrics is a markerless, performance-driven animation company.
We specialize in high quality facial animation
for video games and films.

Paul Debevec: So, if we break that down into layers, here&#39;s that diffuse component
we saw in the first slide.
Here is the specular component animating.
You can see all the wrinkles happening there.
And there is the underlying wireframe mesh.
And that is Emily herself.
Now, where are we going with this here?
We&#39;ve gone a little bit beyond Light Stage 5. This is Light Stage 6,
and we&#39;re looking at taking this technology
and applying it to whole human bodies.
This is Bruce Lawmen, one of our researchers in the group,
who graciously agreed to get captured running in the Light Stage.
And let&#39;s take a look at a computer-generated version
of Bruce, running in a new environment.
And thank you very much.

(Applause)

