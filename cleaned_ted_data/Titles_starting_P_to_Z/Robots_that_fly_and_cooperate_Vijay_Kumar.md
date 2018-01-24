
Good morning.
I&#39;m here today to talk
about autonomous flying beach balls.

(Laughter)

No, agile aerial robots like this one.
I&#39;d like to tell you a little bit
about the challenges in building these,
and some of the terrific opportunities
for applying this technology.
So these robots are related
to unmanned aerial vehicles.
However, the vehicles
you see here are big.
They weigh thousands of pounds,
are not by any means agile.
They&#39;re not even autonomous.
In fact, many of these vehicles
are operated by flight crews
that can include multiple pilots,
operators of sensors,
and mission coordinators.
What we&#39;re interested in
is developing robots like this --
and here are two other pictures --
of robots that you can buy off the shelf.
So these are helicopters with four rotors,
and they&#39;re roughly
a meter or so in scale,
and weigh several pounds.
And so we retrofit these
with sensors and processors,
and these robots can fly indoors.
Without GPS.
The robot I&#39;m holding in my hand
is this one,
and it&#39;s been created by two students,
Alex and Daniel.
So this weighs a little more
than a tenth of a pound.
It consumes about 15 watts of power.
And as you can see,
it&#39;s about eight inches in diameter.
So let me give you
just a very quick tutorial
on how these robots work.
So it has four rotors.
If you spin these rotors
at the same speed,
the robot hovers.
If you increase the speed
of each of these rotors,
then the robot flies up,
it accelerates up.
Of course, if the robot were tilted,
inclined to the horizontal,
then it would accelerate
in this direction.
So to get it to tilt,
there&#39;s one of two ways of doing it.
So in this picture, you see
that rotor four is spinning faster
and rotor two is spinning slower.
And when that happens,
there&#39;s a moment that causes
this robot to roll.
And the other way around,
if you increase the speed of rotor three
and decrease the speed of rotor one,
then the robot pitches forward.
And then finally,
if you spin opposite pairs of rotors
faster than the other pair,
then the robot yaws
about the vertical axis.
So an on-board processor
essentially looks at what motions
need to be executed
and combines these motions,
and figures out what commands
to send to the motors --
600 times a second.
That&#39;s basically how this thing operates.
So one of the advantages of this design
is when you scale things down,
the robot naturally becomes agile.
So here, R is the characteristic
length of the robot.
It&#39;s actually half the diameter.
And there are lots of physical parameters
that change as you reduce R.
The one that&#39;s most important
is the inertia,
or the resistance to motion.
So it turns out the inertia,
which governs angular motion,
scales as a fifth power of R.
So the smaller you make R,
the more dramatically the inertia reduces.
So as a result, the angular acceleration,
denoted by the Greek letter alpha here,
goes as 1 over R.
It&#39;s inversely proportional to R.
The smaller you make it,
the more quickly you can turn.
So this should be clear in these videos.
On the bottom right, you see a robot
performing a 360-degree flip
in less than half a second.
Multiple flips, a little more time.
So here the processes on board
are getting feedback from accelerometers
and gyros on board,
and calculating, like I said before,
commands at 600 times a second,
to stabilize this robot.
So on the left, you see Daniel
throwing this robot up into the air,
and it shows you
how robust the control is.
No matter how you throw it,
the robot recovers and comes back to him.
So why build robots like this?
Well, robots like this
have many applications.
You can send them
inside buildings like this,
as first responders to look for intruders,
maybe look for biochemical leaks,
gaseous leaks.
You can also use them
for applications like construction.
So here are robots carrying beams, columns
and assembling cube-like structures.
I&#39;ll tell you a little bit
more about this.
The robots can be used
for transporting cargo.
So one of the problems
with these small robots
is their payload-carrying capacity.
So you might want to have
multiple robots carry payloads.
This is a picture of a recent
experiment we did --
actually not so recent anymore --
in Sendai, shortly after the earthquake.
So robots like this could be sent
into collapsed buildings,
to assess the damage
after natural disasters,
or sent into reactor buildings,
to map radiation levels.
So one fundamental problem
that the robots have to solve
if they are to be autonomous,
is essentially figuring out how to get
from point A to point B.
So this gets a little challenging,
because the dynamics of this robot
are quite complicated.
In fact, they live
in a 12-dimensional space.
So we use a little trick.
We take this curved 12-dimensional space,
and transform it into a flat,
four-dimensional space.
And that four-dimensional space
consists of X, Y, Z,
and then the yaw angle.
And so what the robot does,
is it plans what we call
a minimum-snap trajectory.

So to remind you of physics:
You have position, derivative, velocity;
then acceleration;
and then comes jerk,
and then comes snap.
So this robot minimizes snap.
So what that effectively does,
is produce a smooth and graceful motion.
And it does that avoiding obstacles.
So these minimum-snap trajectories
in this flat space are then transformed
back into this complicated
12-dimensional space,
which the robot must do
for control and then execution.
So let me show you some examples
of what these minimum-snap
trajectories look like.
And in the first video,
you&#39;ll see the robot going
from point A to point B,
through an intermediate point.
(Whirring noise)
So the robot is obviously capable
of executing any curve trajectory.
So these are circular trajectories,
where the robot pulls about two G&#39;s.
Here you have overhead
motion capture cameras on the top
that tell the robot where it is
100 times a second.
It also tells the robot
where these obstacles are.
And the obstacles can be moving.
And here, you&#39;ll see Daniel
throw this hoop into the air,
while the robot is calculating
the position of the hoop,
and trying to figure out how to best
go through the hoop.
So as an academic,
we&#39;re always trained to be able
to jump through hoops
to raise funding for our labs,
and we get our robots to do that.

(Applause)

So another thing the robot can do
is it remembers pieces of trajectory
that it learns or is pre-programmed.
So here, you see the robot combining
a motion that builds up momentum,
and then changes its orientation
and then recovers.
So it has to do this
because this gap in the window
is only slightly larger
than the width of the robot.
So just like a diver
stands on a springboard
and then jumps off it to gain momentum,
and then does this pirouette,
this two and a half somersault through
and then gracefully recovers,
this robot is basically doing that.
So it knows how to combine
little bits and pieces of trajectories
to do these fairly difficult tasks.
So I want change gears.
So one of the disadvantages
of these small robots is its size.
And I told you earlier
that we may want to employ
lots and lots of robots
to overcome the limitations of size.

So one difficulty is:
How do you coordinate
lots of these robots?
And so here, we looked to nature.
So I want to show you a clip
of Aphaenogaster desert ants,
in Professor Stephen Pratt&#39;s lab,
carrying an object.
So this is actually a piece of fig.
Actually you take any object
coated with fig juice,
and the ants will carry it
back to the nest.
So these ants don&#39;t have
any central coordinator.
They sense their neighbors.
There&#39;s no explicit communication.
But because they sense the neighbors
and because they sense the object,
they have implicit coordination
across the group.
So this is the kind of coordination
we want our robots to have.
So when we have a robot
which is surrounded by neighbors --
and let&#39;s look at robot I and robot J --
what we want the robots to do,
is to monitor the separation between them,
as they fly in formation.
And then you want to make sure
that this separation
is within acceptable levels.
So again, the robots monitor this error
and calculate the control commands
100 times a second,
which then translates into motor commands,
600 times a second.
So this also has to be done
in a decentralized way.
Again, if you have
lots and lots of robots,
it&#39;s impossible to coordinate
all this information centrally
fast enough in order for the robots
to accomplish the task.
Plus, the robots have to base
their actions only on local information --
what they sense from their neighbors.
And then finally,
we insist that the robots be agnostic
to who their neighbors are.
So this is what we call anonymity.
So what I want to show you next
is a video of 20 of these little robots,
flying in formation.
They&#39;re monitoring
their neighbors&#39; positions.
They&#39;re maintaining formation.
The formations can change.
They can be planar formations,
they can be three-dimensional formations.
As you can see here,
they collapse from a three-dimensional
formation into planar formation.
And to fly through obstacles,
they can adapt the formations on the fly.
So again, these robots come
really close together.
As you can see
in this figure-eight flight,
they come within inches of each other.
And despite the aerodynamic interactions
with these propeller blades,
they&#39;re able to maintain stable flight.

(Applause)

So once you know how to fly in formation,
you can actually pick up
objects cooperatively.
So this just shows that we can
double, triple, quadruple
the robots&#39; strength,
by just getting them to team
with neighbors, as you can see here.
One of the disadvantages of doing that is,
as you scale things up --
so if you have lots of robots
carrying the same thing,
you&#39;re essentially increasing the inertia,
and therefore you pay a price;
they&#39;re not as agile.
But you do gain in terms
of payload-carrying capacity.
Another application I want to show you --
again, this is in our lab.
This is work done by Quentin Lindsey,
who&#39;s a graduate student.
So his algorithm essentially
tells these robots
how to autonomously build cubic structures
from truss-like elements.
So his algorithm tells the robot
what part to pick up,
when, and where to place it.
So in this video you see --
and it&#39;s sped up 10, 14 times --
you see three different structures
being built by these robots.
And again, everything is autonomous,
and all Quentin has to do
is to give them a blueprint
of the design that he wants to build.
So all these experiments
you&#39;ve seen thus far,
all these demonstrations,
have been done with the help
of motion-capture systems.
So what happens when you leave your lab,
and you go outside into the real world?
And what if there&#39;s no GPS?
So this robot is actually
equipped with a camera,
and a laser rangefinder, laser scanner.
And it uses these sensors
to build a map of the environment.
What that map consists of are features --
like doorways, windows,
people, furniture --
and it then figures out
where its position is,
with respect to the features.
So there is no global coordinate system.
The coordinate system
is defined based on the robot,
where it is and what it&#39;s looking at.
And it navigates with respect
to those features.
So I want to show you a clip
of algorithms developed by Frank Shen
and Professor Nathan Michael,
that shows this robot entering
a building for the very first time,
and creating this map on the fly.
So the robot then figures out
what the features are,
it builds the map,
it figures out where it is
with respect to the features,
and then estimates its position
100 times a second,
allowing us to use the control algorithms
that I described to you earlier.
So this robot is actually being
commanded remotely by Frank,
but the robot can also figure out
where to go on its own.
So suppose I were to send
this into a building,
and I had no idea
what this building looked like.
I can ask this robot to go in,
create a map,
and then come back and tell me
what the building looks like.
So here, the robot is not
only solving the problem
of how to go from point A
to point B in this map,
but it&#39;s figuring out what the best
point B is at every time.
So essentially it knows where to go
to look for places that have
the least information,
and that&#39;s how it populates this map.
So I want to leave you
with one last application.
And there are many applications
of this technology.
I&#39;m a professor, and we&#39;re
passionate about education.
Robots like this can really change
the way we do K-12 education.
But we&#39;re in Southern California,
close to Los Angeles,
so I have to conclude with something
focused on entertainment.
I want to conclude with a music video.
I want to introduce the creators,
Alex and Daniel, who created this video.

(Applause)

So before I play this video,
I want to tell you that they created it
in the last three days,
after getting a call from Chris.
And the robots that play in the video
are completely autonomous.
You will see nine robots
play six different instruments.
And of course, it&#39;s made
exclusively for TED 2012.
Let&#39;s watch.
(Sound of air escaping from valve)
(Music)
(Whirring sound)
(Music)

(Applause)
 (Cheers)
