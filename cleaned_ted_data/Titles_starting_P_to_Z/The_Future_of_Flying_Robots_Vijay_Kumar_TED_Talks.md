
In my lab, we build
autonomous aerial robots
like the one you see flying here.
Unlike the commercially available drones
that you can buy today,
this robot doesn&#39;t have any GPS on board.
So without GPS,
it&#39;s hard for robots like this
to determine their position.
This robot uses onboard sensors,
cameras and laser scanners,
to scan the environment.
It detects features from the environment,
and it determines where it is
relative to those features,
using a method of triangulation.
And then it can assemble
all these features into a map,
like you see behind me.
And this map then allows the robot
to understand where the obstacles are
and navigate in a collision-free manner.
What I want to show you next
is a set of experiments
we did inside our laboratory,
where this robot was able
to go for longer distances.
So here you&#39;ll see, on the top right,
what the robot sees with the camera.
And on the main screen --
and of course this is sped up
by a factor of four --
on the main screen you&#39;ll see
the map that it&#39;s building.
So this is a high-resolution map
of the corridor around our laboratory.
And in a minute
you&#39;ll see it enter our lab,
which is recognizable
by the clutter that you see.

(Laughter)

But the main point I want to convey to you
is that these robots are capable
of building high-resolution maps
at five centimeters resolution,
allowing somebody who is outside the lab,
or outside the building
to deploy these
without actually going inside,
and trying to infer
what happens inside the building.
Now there&#39;s one problem
with robots like this.
The first problem is it&#39;s pretty big.
Because it&#39;s big, it&#39;s heavy.
And these robots consume
about 100 watts per pound.
And this makes for
a very short mission life.
The second problem
is that these robots have onboard sensors
that end up being very expensive --
a laser scanner, a camera
and the processors.
That drives up the cost of this robot.

So we asked ourselves a question:
what consumer product
can you buy in an electronics store
that is inexpensive, that&#39;s lightweight,
that has sensing onboard and computation?
And we invented the flying phone.

(Laughter)

So this robot uses a Samsung Galaxy
smartphone that you can buy off the shelf,
and all you need is an app that you
can download from our app store.
And you can see this robot
reading the letters, &quot;TED&quot; in this case,
looking at the corners
of the &quot;T&quot; and the &quot;E&quot;
and then triangulating off of that,
flying autonomously.
That joystick is just there
to make sure if the robot goes crazy,
Giuseppe can kill it.

(Laughter)

In addition to building
these small robots,
we also experiment with aggressive
behaviors, like you see here.
So this robot is now traveling
at two to three meters per second,
pitching and rolling aggressively
as it changes direction.
The main point is we can have
smaller robots that can go faster
and then travel in these
very unstructured environments.
And in this next video,
just like you see this bird, an eagle,
gracefully coordinating its wings,
its eyes and feet
to grab prey out of the water,
our robot can go fishing, too.

(Laughter)

In this case, this is a Philly cheesesteak
hoagie that it&#39;s grabbing out of thin air.

(Laughter)

So you can see this robot
going at about three meters per second,
which is faster than walking speed,
coordinating its arms, its claws
and its flight with split-second timing
to achieve this maneuver.
In another experiment,
I want to show you
how the robot adapts its flight
to control its suspended payload,
whose length is actually larger
than the width of the window.
So in order to accomplish this,
it actually has to pitch
and adjust the altitude
and swing the payload through.
But of course we want
to make these even smaller,
and we&#39;re inspired
in particular by honeybees.
So if you look at honeybees,
and this is a slowed down video,
they&#39;re so small,
the inertia is so lightweight --

(Laughter)

that they don&#39;t care --
they bounce off my hand, for example.
This is a little robot
that mimics the honeybee behavior.
And smaller is better,
because along with the small size
you get lower inertia.
Along with lower inertia --
(Robot buzzing, laughter)
along with lower inertia,
you&#39;re resistant to collisions.
And that makes you more robust.
So just like these honeybees,
we build small robots.
And this particular one
is only 25 grams in weight.
It consumes only six watts of power.
And it can travel
up to six meters per second.
So if I normalize that to its size,
it&#39;s like a Boeing 787 traveling
ten times the speed of sound.

(Laughter)

And I want to show you an example.
This is probably the first planned mid-air
collision, at one-twentieth normal speed.
These are going at a relative speed
of two meters per second,
and this illustrates the basic principle.
The two-gram carbon fiber cage around it
prevents the propellers from entangling,
but essentially the collision is absorbed
and the robot responds to the collisions.
And so small also means safe.
In my lab, as we developed these robots,
we start off with these big robots
and then now we&#39;re down
to these small robots.
And if you plot a histogram
of the number of Band-Aids we&#39;ve ordered
in the past, that sort of tailed off now.
Because these robots are really safe.
The small size has some disadvantages,
and nature has found a number of ways
to compensate for these disadvantages.
The basic idea is they aggregate
to form large groups, or swarms.
So, similarly, in our lab,
we try to create artificial robot swarms.
And this is quite challenging
because now you have to think
about networks of robots.
And within each robot,
you have to think about the interplay
of sensing, communication, computation --
and this network then becomes
quite difficult to control and manage.
So from nature we take away
three organizing principles
that essentially allow us
to develop our algorithms.
The first idea is that robots
need to be aware of their neighbors.
They need to be able to sense
and communicate with their neighbors.
So this video illustrates the basic idea.
You have four robots --
one of the robots has actually been
hijacked by a human operator, literally.
But because the robots
interact with each other,
they sense their neighbors,
they essentially follow.
And here there&#39;s a single person
able to lead this network of followers.
So again, it&#39;s not because all the robots
know where they&#39;re supposed to go.
It&#39;s because they&#39;re just reacting
to the positions of their neighbors.

(Laughter)

So the next experiment illustrates
the second organizing principle.
And this principle has to do
with the principle of anonymity.
Here the key idea is that
the robots are agnostic
to the identities of their neighbors.
They&#39;re asked to form a circular shape,
and no matter how many robots
you introduce into the formation,
or how many robots you pull out,
each robot is simply
reacting to its neighbor.
It&#39;s aware of the fact that it needs
to form the circular shape,
but collaborating with its neighbors
it forms the shape
without central coordination.
Now if you put these ideas together,
the third idea is that we
essentially give these robots
mathematical descriptions
of the shape they need to execute.
And these shapes can be varying
as a function of time,
and you&#39;ll see these robots
start from a circular formation,
change into a rectangular formation,
stretch into a straight line,
back into an ellipse.
And they do this with the same
kind of split-second coordination
that you see in natural swarms, in nature.
So why work with swarms?
Let me tell you about two applications
that we are very interested in.
The first one has to do with agriculture,
which is probably the biggest problem
that we&#39;re facing worldwide.
As you well know,
one in every seven persons
in this earth is malnourished.
Most of the land that we can cultivate
has already been cultivated.
And the efficiency of most systems
in the world is improving,
but our production system
efficiency is actually declining.
And that&#39;s mostly because of water
shortage, crop diseases, climate change
and a couple of other things.
So what can robots do?
Well, we adopt an approach that&#39;s
called Precision Farming in the community.
And the basic idea is that we fly
aerial robots through orchards,
and then we build
precision models of individual plants.
So just like personalized medicine,
while you might imagine wanting
to treat every patient individually,
what we&#39;d like to do is build
models of individual plants
and then tell the farmer
what kind of inputs every plant needs --
the inputs in this case being water,
fertilizer and pesticide.
Here you&#39;ll see robots
traveling through an apple orchard,
and in a minute you&#39;ll see
two of its companions
doing the same thing on the left side.
And what they&#39;re doing is essentially
building a map of the orchard.
Within the map is a map
of every plant in this orchard.
(Robot buzzing)
Let&#39;s see what those maps look like.
In the next video, you&#39;ll see the cameras
that are being used on this robot.
On the top-left is essentially
a standard color camera.
On the left-center is an infrared camera.
And on the bottom-left
is a thermal camera.
And on the main panel, you&#39;re seeing
a three-dimensional reconstruction
of every tree in the orchard
as the sensors fly right past the trees.
Armed with information like this,
we can do several things.
The first and possibly the most important

thing we can do is very simple:
count the number of fruits on every tree.
By doing this, you tell the farmer
how many fruits she has in every tree
and allow her to estimate
the yield in the orchard,
optimizing the production
chain downstream.
The second thing we can do
is take models of plants, construct
three-dimensional reconstructions,
and from that estimate the canopy size,
and then correlate the canopy size
to the amount of leaf area on every plant.
And this is called the leaf area index.
So if you know this leaf area index,
you essentially have a measure of how much
photosynthesis is possible in every plant,
which again tells you
how healthy each plant is.
By combining visual
and infrared information,
we can also compute indices such as NDVI.
And in this particular case,
you can essentially see
there are some crops that are
not doing as well as other crops.
This is easily discernible from imagery,
not just visual imagery but combining
both visual imagery and infrared imagery.
And then lastly,
one thing we&#39;re interested in doing is
detecting the early onset of chlorosis --
and this is an orange tree --
which is essentially seen
by yellowing of leaves.
But robots flying overhead
can easily spot this autonomously
and then report to the farmer
that he or she has a problem
in this section of the orchard.
Systems like this can really help,
and we&#39;re projecting yields
that can improve by about ten percent
and, more importantly, decrease
the amount of inputs such as water
by 25 percent by using
aerial robot swarms.
Lastly, I want you to applaud
the people who actually create the future,
Yash Mulgaonkar, Sikang Liu
and Giuseppe Loianno,
who are responsible for the three
demonstrations that you saw.
Thank you.

(Applause)

