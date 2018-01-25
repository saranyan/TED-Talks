
the human eye is one of nature&#39;s finest
marvels with sensitivity to just three
colors red green and blue the eye is
able to make pictures as wondrous as
this rainbow as spectacular as the
Northern Lights and as picturesque as
sunset in Boston now as beautiful as
these images are they raise a question
how can we get machines to perceive this
visual world how can we teach machines
how to see this is one of the core
challenges in artificial intelligence AI
and it&#39;s a hard one if I were to show
this picture to you to any of you in the
audience you could probably tell me that
there are two cars sitting in a parking
lot maybe even near a Burger King but
when a machine is asked to label this
image to draw boxes around the object
that sees it miss identifies the
reflections in the car as belonging to
cyclists and pedestrians to overcome
this problem the self-driving car
industry uses spinning rigs mounted on
top of their cars known as lidar lidar
is a new way to see the world it&#39;s a way
to see the world different from how
humans do
but despite seeing the world in
different ways these cars are still not
fully autonomous these light our cars
need something else but this has not
stopped artists designers scientists and
engineers from imagining the
possibilities in this simulation we can
see a car as it smoothly avoids
pedestrians by using the echoes of light
from lidar to take concepts like this
into reality our lab at MIT tries to
build superhuman eyes
to enable superhuman driving
we&#39;ve started along this path many years
ago five years ago we had a paper from
our group that tried to capture light in
motion light as it moves through this
coke bottle half a million dollars of
equipment on an optical table and we
were able to get images like this the
following year I and my team we built a
prototype a benchtop prototype that
scaled this idea to a $500 device when
industry labs and academia and even the
popular press heard about our device
they wanted to come by to check it out I
guess we were in some ways successful
when BBC came by for a live demo they
liked it enough that they put it on
their homepage but we knew that despite
this warm reception there was a way to
go there was a ways to go in order to
take this to the next level
so I&#39;m back on the stage here in 2017 to
present a new technique for lidar and
our invention is to essentially tag
light at every micrometer that&#39;s
one-tenth the width of a human hair to
explain the significance of this
invention let me start with the way
things are done today lidar light
detection and ranging a vehicle sends a
packet of photons at a pedestrian that
it wants to avoid and measures the
echoes of light that reflects back we
know from our basic high school classes
distance equals velocity times time
since we know the speed of light if we
can measure the echo time we can
estimate the distance the concept is
simple but it&#39;s taken decades and
decades to realize this in practice
because there&#39;s a core culprit here and
that&#39;s that the speed of light is very
very fastest the fastest thing in the
universe in one nanosecond in one
billionth of a second light travels one
foot so even if you had a billion frames
per second camera you would only be
accurate to one foot the industry has
done a wonderful job in making cameras
that are even faster so that we can tag
light not at 1 foot but at 5 millimeters
a 5 millimeter light tag for example if
I wanted to scan the
object this einstein bus would give you
a reconstruction of the object that
looks something like this the
reconstruction you can make out barely a
face but the details are lost in
situations for mission-critical
applications like self-driving cars we
want the best image quality possible and
that&#39;s our invention we call it
heterodyne lidar which were trying to
tag light not at five millimeters but at
two micrometers one-tenth the width of a
human hair
the core idea the way we&#39;re able to
solve this is not by building faster and
faster cameras the way we solve this is
by exploiting the natural physics of
light when I take this laser pointer and
eischeid it on the floor so I don&#39;t
blind you when I shot it on the floor we
often think of this abstraction as a
laser beam a green beam of light just
pointing towards the floor but light is
far more complex and rich than that
light is a wave it&#39;s oscillating
trillions and trillions of times a
second up and down up and down and by by
exploiting these natural oscillations of
light we&#39;re able to realize very high
path length tagging very high resolution
so the idea is to send a beam of light
and this wave model at us target so we
send photons and wave fronts at a target
to enable two micrometer light tagging
which makes that Einstein statue look
much more photorealistic now you can see
the wrinkles in the face the lines in
the clothing and even the hair in the
mustache of course the key idea is very
specialized to my community of optics
and so that detail is one left best left
unsaid but the nice thing is that this
implementation does not need to be as
specialized as optical implementations
it&#39;s something that can be prototyped
on a bench top on a regular work desk
and so when we took this prototype and
built it we want to test it against the
industry metrics what the lidar industry
uses today which is long range trying to
achieve half a kilometer target
avoidance evaluating low-power operation
by
Russians beat notes stability and all
the metrics that the latter
intra-industry is traditionally
interested in and speaking of the light
our industry it&#39;s one of the hottest
spaces in technology today Kwon ergy all
these devices are of successful
companies Kwon ergy the company making
solid state light ours is a technology
unicorn meaning it&#39;s valued at more than
a billion dollars strobe and way mo are
now subsidiaries of Google and GM but
all these successful implementations in
our world they&#39;re light tagging at
millimetre precision and so the MIT
proposal is to take this idea to
micrometers 1/10 the width of a human
hair
in doing so doctors might be able to
discriminate light paths within human
body for example to see through the body
without x-rays airplanes are equipped
with light ARS but with micrometer path
length separation an airplane flying
over a fruit orchard might not just be
able to map out a topology but tell you
if the fruits are ripe and finally
autonomous driving maybe we can have
vehicles that can drive smoothly through
fog taking a dangerous road condition
like this and making it appear as if the
road was clear these problems are being
studied in our group and of course the
technology details can be found on
various web URLs but I&#39;d like to wrap
this idea back to the motivation and
that&#39;s the beauty of nature&#39;s eyes the
human eye with sensitivity to three
colors is a magical device but it&#39;s not
as well known that there are animals in
the kingdom with far superior eyes alien
eyes this is a mantis shrimp perhaps
some of you who are food connoisseurs
might know it as a menu item in Japan or
Korea but its visual system is able to
pick up 16 bands of colors only three of
which humans can see so one can only
imagine one can literally only imagine
how an animal like this would perceive
and it&#39;s these sort of motivations from
biology bioinspiration
that encouraged us to build the
artificial eye for machines of the
future
thank you
[Applause]
