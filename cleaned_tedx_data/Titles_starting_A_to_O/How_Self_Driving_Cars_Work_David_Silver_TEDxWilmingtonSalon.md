
hello I teach the self-driving car
engineer nano degree program at Udacity
which is a nine-month program that
trains software engineers to work on
autonomous vehicles before I was ever a
student at Udacity or an employee at
Udacity I was actually a student I was
for many years a normal Silicon Valley
web software engineer working in Ruby on
Rails and a few years ago I got really
excited about self-driving cars but I
didn&#39;t have any background in robotics
or system software or automotive
software so I started taking classes
online at Udacity and at other places to
learn how to become an autonomous
vehicle engineer I was hired onto the
autonomous vehicle team at Ford Motor
Company at their research and innovation
center in Palo Alto California and later
the team at Udacity asked me to come and
build out a program for people to do
essentially what I had done to learn to
become autonomous vehicle engineers at
Udacity we have our own self-driving car
her name is Carla and I&#39;d like to tell
you a little bit about how Carla works
and how most self-driving cars work
through the lens of some of the projects
that our students have done as part of
the nanodegree program so I think of
self-driving cars as having five core
components computer vision sensor fusion
localization path planning and control
computer vision is how we use camera
images to figure out what the world
around us looks like and sensor fusion
is how we incorporate data from other
sensors like lasers and radar to get a
richer understanding of our environment
once we&#39;ve built this deep understanding
of what the world around us is we use
localization to figure out precisely
where we are in that world and then once
we figure it out where we are in the
world and what the world looks like we
use path planning to chart a course
through the world to get us to where
we&#39;d like to go
and then the final step is control which
is how we actually turn the steering
wheel and hit the throttle and hit the
brake in order to execute the trajectory
that we built during path planning so
these are the five core components of
self-driving cars and I&#39;d like to
investigate each of them with you this
is computer vision this is a video that
Carla took driving up highway 280 in
Silicon Valley and this has work that
one of our students the Vecchia dab did
vivec is using computer vision so
looking for colors and edges and
gradients to find the lane on the road
and then he&#39;s trained a deep neural
network to draw bounding boxes around
the other vehicles on the road deep
neural networks or deep learning is an
exciting new part of machine learning
and artificial intelligence and it&#39;s a
way that computers can learn what cars
and other objects look like simply by
sending them lots and lots of data they
see lots of cars and they learn what
cars look like and you can see the deep
neural network is trying to figure out
is that one car is that two cars and as
they separate it sees that it&#39;s a couple
of cars and this is pretty similar to
what advanced driver assistance systems
do on the road today so once we know
what the world looks like through camera
images the next step is to augment that
understanding of the world using other
sensors so radar and lasers to get
measurements that are difficult for a
camera alone to understand so things
like the distance between us and other
cars and how fast other objects in the
environment are moving and what you see
here is data from a trip that Carla took
up El Camino Real which is the main
commercial street in Silicon Valley and
you see on the right the video feed of
what that drive looks like and the main
image here is the laser scan of what the
world around Carla looks like and you
can see this lidar which has an array of
lasers doing a 360 degree scan of the
world and seeing what the different
objects in that environment look like
and how they move so once we understand
both what the world looks like and how
to measure it and we incorporate those
understandings together to get a rich
picture of our surrounding environment
the next step is to local
ourselves in that environment and you
might think this is really
straightforward because we all have cell
phones today they all have GPS in them
we all know where we are all of the time
but in fact GPS is only accurate to
within about one to two meters and if
you think about how big one to two
meters is if a car is wrong about where
it is by one to two meters
it could be over here on the sidewalk
hitting things that would be really bad
so we have to use much more
sophisticated mathematical algorithms as
well as high-definition maps to localize
our vehicle precisely in its environment
to single-digit centimeter level
accuracy so this is work by one of our
students his name is Daniel Lopez Madrid
and what Daniel is doing is he is using
a particle filter which is a really
sophisticated type of triangulation and
as his blue vehicle moves through the
simulator it&#39;s measuring its distance
from various landmarks and it&#39;s figuring
out how far it is from these landmarks
and where it sees the landmarks and
comparing that to the map and using that
to figure out precisely where it is in
the world and this is how self-driving
cars localize in the real world those
landmarks might be things like street
lights or traffic signs or mailboxes or
even manhole covers so once we figured
out where we are in the world and what
the world around us looks like the next
step is to actually chart a path through
that world to figure out how to get
where we want to go and this is path
planning here you can see the work by
one of our students Kaz a hero Nakagawa
and what Kaz a hero has done is in our
Udacity highway simulator he&#39;s built a
path planner that predicts where the
other vehicles on the road are going to
go and then figures out what maneuver
his vehicle should take in response and
then finally builds a series of
waypoints those are those Green pearls
you see in the video for the car to
drive through that&#39;s the trajectory the
car should follow and you see when his
vehicle comes up on other traffic it has
to figure out should it slow down and
stay in its lane or should it shift
right or shift left and this is in fact
the type of decision that real
self-driving cars have to make all the
time subject to constraints like speed
limits and acceleration limit so the
ride is comfortable and you can imagine
this gets
more complicated and urban driving where
there are a lot more intersections and
different maneuvers you can make but in
principle the decisions are all the same
so once we figured out what the path we
want to take through this world is and
we know where we are in the world and we
know what the world looks like the final
step in the pipeline is control and
control is how we actually turn the
steering wheel and hit the throttle and
hit the brake
in order to execute that trajectory that
we built during path planning so this is
one of our students Emmy wow this is
Udacity z-- racetrack simulator and she
has a yellow line here that&#39;s the ideal
trajectory that her car should follow
and what you see is there&#39;s this green
line layered on top of the yellow line
in the Green Line is the trajectory that
her vehicle predicts it&#39;s going to
follow based on the steering wheel and
throttle and brake commands that it&#39;s
sending and what we love is for that
green line to be 100% aligned with the
yellow line but of course that&#39;s really
difficult and there&#39;s a human driver you
probably know this it&#39;s really difficult
particularly on tight turns to follow
the exact line through the middle of the
lane that you&#39;d like to follow but you
do pretty well with it you managed to
drive and in fact computers are really
really good at this and the distance
between the trajectory they&#39;d like to
follow and the trajectory they actually
follow is really really close so that&#39;s
how self-driving cars work at a high
level we use computer vision and sensor
fusion to get this rich picture of where
we are in the world we use localization
to nail down precisely our location in
that rich world we use path planning to
chart the course through the world to
get us where we&#39;d like to go and we use
control to turn the steering wheel and
hit the throttle and hit the brake to
execute that trajectory and ultimately
move the vehicle everything else
self-driving cars do are essentially
more sophisticated implementations of
these key functions and this is how
self-driving cars work it is a really
exciting time to work on self-driving
cars computers are getting better and
better at these tasks all of the time
and I hope you see self-driving cars on
a road near you soon my name is David
silver I teach self-driving cars at
Udacity thank you very much
you
you
