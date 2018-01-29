
thank you but they didn&#39;t unlock it for
me
okay so when we first started the
Photosynth project in 2007 it was really
with a very big idea in mind we wanted
to think about how to reinvent the whole
enterprise of photography for ordinary
people and in particular we were
thinking about how we might do that
using the tools of computer vision and
augmented reality computer vision is
very central to a lot of the different
kinds of demos that we&#39;ve seen in the
previous talks in this session and what
it really is about is enabling the
computer to understand images as spatial
temporal capture events as renditions of
the real world at a particular place and
moment in time and once the computer
understands those things then it becomes
possible to manipulate in all sorts of
ways that are not possible if one just
thinks about the pixels in a sort of
Photoshop style it&#39;s just a
two-dimensional grid of values so the
first really mainstream application of
photosynthetic Knology in in the kind of
consumer environment I think was the
Photosynth app that we released a couple
of years ago and what I&#39;m showing you
here now is essentially the same thing
it&#39;s the it&#39;s the Photosynth app but
it&#39;s now integrated into the next
version of Windows which is coming out
very shortly and I don&#39;t think I don&#39;t
think this has been shown in public
before it&#39;s something that I&#39;m very
proud of and it&#39;s one of the things that
makes it really fun for me to be working
at Microsoft because when we do things
it&#39;s possible for them to really reach a
very wide audience much much more than
if you are just releasing apps into an
app store somewhere so those
capabilities are now in the camera
itself and I&#39;ll show you I&#39;ll show you
what what that was just a capture that
my team and I did on on Friday and this
is the result so it&#39;s a full full
spherical capture
now in the meantime we&#39;ve been working
of course on on the next generations of
that technology and on what what happens
after we just think about the fusion of
images onto a sphere and two-dimensional
tracking which is what you just saw and
so what I&#39;m going to show you next is
what we have working in the lab today to
go beyond that two-dimensional capture
and we&#39;ll be releasing very shortly as
well this is another kind of panorama
and the thing that you might notice as I
rotate is that it&#39;s a three-dimensional
panorama the branches in the foreground
move with parallax they move at
different speeds from from the
background and in fact even the depth of
field changes you know you might notice
for example here that the the tree trunk
is a little bit blurry and as we rotate
it comes into focus and what&#39;s going on
here is in some sense a solution to the
problem of panorama capture which is
that when you&#39;re trying to fuse images
together onto a sphere you really need
to hold the device still in space and
only rotate because otherwise you
introduce parallax and then it becomes
very hard to create a stitch from a
consistent point of view but on the
other hand it&#39;s very difficult for
somebody to do that typically the the
normal action when somebody takes a
panorama is like this which is moving
both the it&#39;s both rotating and moving
the focal point at the same time but
here we&#39;re making lemonade out of that
in a way because the other thing that
happens when you move is that you have
enough information to reconstruct 3d
because if you hold the camera
completely still and only rotate then
you don&#39;t have the information to
reconstruct 3d so that&#39;s how you get the
three-dimensional effect and once you
have freed yourself from the constraint
to keep the camera fixed as you rotate
it around you can start to try other
sorts of things as well so
I&#39;ll show you kind of an odd an odd one
that was that was 34 photos by the way
that you just saw this is a planar
panorama but a planar three-dimensional
panorama that somebody took out the
window of plane and what&#39;s what&#39;s
interesting about this one is that you
can see the individual frame is the
individual captures of those of those
photos as we go and it creates this this
sort of vertiginous time-lapse II
impression that&#39;s very very different
from from an ordinary planar capture of
course because all these things have
been modeled and in 3d based on the
original images now let&#39;s get a little
bit crazier than just the sort of
outward panorama or the planar panorama
which are fairly standard for for doing
fused and panoramic imaging and let&#39;s
think about what happens if we take
those outward captures and we turn them
so that you are rotating around the
subject instead that&#39;s what you see here
all right so this is about 60 images of
our friend Noah and I can use this this
capture to give you to show you what&#39;s
going on behind the scenes so this is
the reconstructions of the positions of
the of the camera during each of the
original captures and you can see that
the scenes been broken apart
geometrically and Noah has been modeled
in 3d and so has the background and it&#39;s
essentially by projecting the image onto
that geometry that you can interpolate
that you can create alternate views that
aren&#39;t the view that the original image
was taken from and it&#39;s the process of
projecting the images onto that geometry
that allows you to morph into turn what
started off as a chain of independent
images into a continuous surface or a
continuous mesh of imagery I&#39;ll show you
one one more example that I that I shot
yesterday in Edinburgh in the in the
castle
let&#39;s see pick the right one this is
about a hundred pictures that I just I
shot in a different configuration this
time it&#39;s a walk so I&#39;m walking forward
it was a fairly long walk and what what
I think what I think is really quite
wonderful about this is that not only
have this set of a hundred or so images
turned into something continuous and
three-dimensional but when when we think
about our broader ambition to take these
individual pieces of social media and
start to stitch them together into
something collective we believe that
these continuum of images are the right
building blocks to use to do that and
you can you can sort of see that in
these in these three-dimensional
reconstruction buts this is a good part
of the of the top of the castle in in 3d
from that particular walk so I think I
should stop here Bruno since I&#39;m a
little bit over time thank you
