
one of the biggest challenges and
computer graphics has been able to
create a photo real digital human face
and one of the reasons that&#39;s so
difficult is that unlike aliens and
dinosaurs we look at human faces
everyday they&#39;re very important to how
we communicate with each other and as a
result we&#39;re tuned into the subtlest
things that could possibly be wrong with
the computer rendering in order to
believe whether these things are
realistic and what I&#39;m going to do in
the next five minutes is take you
through a process where we tried to
create a reasonably photorealistic
computer-generated face using some
computer graphics technology we&#39;ve
developed and also some collaborators at
a company called image metrics we&#39;re
gonna try to do a photo real face of an
actress named Emily O&#39;Brien who&#39;s right
there and that&#39;s actually a completely
computer-generated rendering of her face
and by the end of the talk we&#39;re gonna
see it move the way that we did this is
we tried to start with Emily herself who
was gracious enough to come to our
laboratory in Marina del Rey and sit for
a session in Light Stage five this is a
face scanning sphere with 156 white LEDs
all around that allow us to photograph
her in a series of very controlled
illumination conditions and the lighting
that we use these days looks something
like this we shoot all of these
photographs in about three seconds
and we basically capture enough
information with video projector
patterns that drape over the contours of
her face in different principal
directions of light from the light stage
to figure out both the course scale and
the fine scale detail of her face if we
zoom in on this photograph right here
you can see it&#39;s a really nice
photograph to have a fur because she&#39;s
lit from absolutely everywhere at the
same time to get a nice image of her
facial texture and in addition we&#39;ve
actually used polarisers on all the
lights just like polarized sunglasses
can block the glare off of the road
polarisers can block the shine off of
the skin so we don&#39;t get all those
specular reflections to take this map
now if we turn the polarisers around
just a little bit we can actually bring
that specular reflection of the skin
back in and you can see she looks kind
of shiny and oily at this point and if
you take the difference between these
two images here you can get an image lit
from the entire sphere of light of just
the shine off of Emily&#39;s skin I don&#39;t
think any photograph like this had ever
been taken before we&#39;ve done this and
this is very important light to capture
because this is the light that reflects
off of the first sir
the skin doesn&#39;t get underneath the
translucent layers of the skin and blur
out and as a result it&#39;s a very good cue
to the detailed shape of the skin pore
structure and all the fine wrinkles that
all of us have the things that actually
make us look like real humans so if we
use information that comes off of the
specular reflection we can go from a
traditional face scan that might have
the gross contours of the face and the
basic shape and augment it with
information that puts in all of that
skin pore structure and fine wrinkles
and even more importantly since this is
a photometric process that only takes
three seconds to capture we can shoot
Emily in just part of an afternoon in
many different facial poses and
different facial expressions so here you
can see her moving your eyes around
moving her mouth around and these were
actually going to use to create a photo
real digital character so if you take a
look at these scans that we have of
Emily you can see that the human face
does an enormous amount of amazing
things as it goes into different facial
expressions you can see things not only
the base shape changes but all sorts of
different skin buckling and skin
wrinkling occurs you can see that the
skin pore structure changes enormous Lee
from stretched skin pores to the regular
skin texture you can see the furrows in
the brow and how the microstructure
changes there you can see muscles
pulling down it flesh to bring our
eyebrows down our muscles bulging in her
forehead when she winces like that in
addition to this kind of high-resolution
geometry since it&#39;s all captured with
cameras we get a great texture map to
use for the face and by looking at how
the different color channels of the
illumination the red and the green and
the blue diffused the light differently
we can come up with a way of conveying
the skin and the computer that instead
of looking like plaster mannequin
actually looks like it&#39;s made out of
living human flesh
and this is what we used to give to the
company image metrics to create a rigged
digital version of Emily we&#39;re just
seeing the coarse scale geometry here
but they basically created a digital
puppet of her where you can pull on
these various strings and it actually
moves her face in ways that are
completely consistent with the scans
that we took in addition to the coarse
scale geometry they also use all of that
detail to create a set of what are
called displacement maps that animate as
well these are the displacement maps
here and you can
see those different wrinkles actually
show up as she animates so the next
process was then to animate her we
actually used one of her own
performances to provide the source data
so by analyzing this video with computer
vision techniques they were able to
drive the facial rig with the
computer-generated performance so what
you&#39;re gonna see now after this is a
completely photo real digital face we
can turn the volume up a little bit if
that&#39;s available which metrics is a
marvelous performance driven animation
company we specialize in high quality
facial animation for video games and
films image metrics is a markerless
performance driven animation company we
specialize in high quality facial
animation for video games and films so
if we break that down into layers here&#39;s
that diffuse component we saw in the
first slide here&#39;s the specular
component animating you can see all the
wrinkles happening there and there&#39;s the
underlying wireframe mesh and that&#39;s
Emily herself now where are we going
with this here we&#39;ve actually gone and
gone a little bit before beyond light
Stage five this is light stage six and
we&#39;re looking at taking this technology
and applying it to whole human bodies
this is Bruce LOM and one of our
researchers in the group who graciously
agreed to get captured running in the
light stage and let&#39;s take a look at a
computer-generated version of Bruce
running in a new environment
and thank you very much
