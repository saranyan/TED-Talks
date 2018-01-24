

(Laughter)


(Laughter)

That&#39;s SpotMini.
He&#39;ll be back in a little while.
I --

(Applause)

I love building robots.
And my long-term goal is to build robots
that can do what people and animals do.
And there&#39;s three things in particular
that we&#39;re interested in.
One is balance and dynamic mobility,
the second one is mobile manipulation,
and the third one is mobile perception.
So, dynamic mobility and balance --
I&#39;m going to do a demo for you.
I&#39;m standing here, balancing.
I can see you&#39;re not very impressed.
OK, how about now?

(Laughter)

How about now?

(Applause)

Those simple capabilities mean that people
can go almost anywhere on earth,
on any kind of terrain.
We want to capture that for robots.
What about manipulation?
I&#39;m holding this clicker in my hand;
I&#39;m not even looking at it,
and I can manipulate it
without any problem.
But even more important,
I can move my body while I hold
the manipulator, the clicker,
and stabilize and coordinate my body,
and I can even walk around.
And that means
I can move around in the world
and expand the range
of my arms and my hands
and really be able to handle
almost anything.
So that&#39;s mobile manipulation.
And all of you can do this.
Third is perception.
I&#39;m looking at a room
with over 1,000 people in it,
and my amazing visual system
can see every one of you --
you&#39;re all stable in space,
even when I move my head,
even when I move around.
That kind of mobile perception
is really important for robots
that are going to move and act
out in the world.
I&#39;m going to give you
a little status report
on where we are in developing robots
toward these ends.
The first three robots are all
dynamically stabilized robots.
This one goes back
a little over 10 years ago --
&quot;BigDog.&quot;
It&#39;s got a gyroscope
that helps stabilize it.
It&#39;s got sensors and a control computer.
Here&#39;s a Cheetah robot
that&#39;s running with a galloping gait,
where it recycles its energy,
it bounces on the ground,
and it&#39;s computing all the time
in order to keep itself
stabilized and propelled.
And here&#39;s a bigger robot
that&#39;s got such good
locomotion using its legs,
that it can go in deep snow.
This is about 10 inches deep,
and it doesn&#39;t really have any trouble.
This is Spot, a new generation of robot --
just slightly older than the one
that came out onstage.
And we&#39;ve been asking the question --

you&#39;ve all heard about drone delivery:
Can we deliver packages
to your houses with drones?
Well, what about plain old
legged-robot delivery?

(Laughter)

So we&#39;ve been taking our robot
to our employees&#39; homes
to see whether we could get in --

(Laughter)

the various access ways.
And believe me, in the Boston area,
there&#39;s every manner
of stairway twists and turns.
So it&#39;s a real challenge.
But we&#39;re doing very well,
about 70 percent of the way.
And here&#39;s mobile manipulation,
where we&#39;ve put an arm on the robot,
and it&#39;s finding its way through the door.
Now, one of the important things
about making autonomous robots
is to make them not do
just exactly what you say,
but make them deal with the uncertainty
of what happens in the real world.
So we have Steve there,
one of the engineers,
giving the robot a hard time.

(Laughter)

And the fact that the programming
still tolerates all that disturbance --
it does what it&#39;s supposed to.
Here&#39;s another example,
where Eric is tugging on the robot
as it goes up the stairs.
And believe me,
getting it to do what it&#39;s supposed to do
in those circumstances
is a real challenge,
but the result is something
that&#39;s going to generalize
and make robots much more autonomous
than they would be otherwise.
This is Atlas, a humanoid robot.
It&#39;s a third-generation humanoid
that we&#39;ve been building.
I&#39;ll tell you a little bit
about the hardware design later.

And we&#39;ve been saying:
How close to human levels
of performance and speed could we get
in an ordinary task,
like moving boxes around on a conveyor?
We&#39;re getting up to about two-thirds
of the speed that a human operates
on average.
And this robot is using both hands,
it&#39;s using its body,
it&#39;s stepping,
so it&#39;s really an example
of dynamic stability,
mobile manipulation
and mobile perception.
Here --

(Laughter)

We actually have two Atlases.

(Laughter)

Now, everything doesn&#39;t go exactly
the way it&#39;s supposed to.

(Laughter)


(Laughter)


(Laughter)

And here&#39;s our latest robot,
called &quot;Handle.&quot;
Handle is interesting,
because it&#39;s sort of half like an animal,
and it&#39;s half something else
with these leg-like things and wheels.
It&#39;s got its arms on
in kind of a funny way,
but it really does some remarkable things.
It can carry 100 pounds.
It&#39;s probably going to lift
more than that,
but so far we&#39;ve done 100.
It&#39;s got some pretty good
rough-terrain capability,
even though it has wheels.
And Handle loves to put on a show.

(Laughter)


(Applause)

I&#39;m going to give you
a little bit of robot religion.
A lot of people think that a robot
is a machine where there&#39;s a computer
that&#39;s telling it what to do,
and the computer is listening
through its sensors.
But that&#39;s really only half of the story.
The real story is
that the computer is on one side,
making suggestions to the robot,
and on the other side
are the physics of the world.
And that physics involves gravity,
friction, bouncing into things.
In order to have a successful robot,
my religion is that you have to do
a holistic design,
where you&#39;re designing the software,
the hardware and the behavior
all at one time,
and all these parts really intermesh
and cooperate with each other.
And when you get the perfect design,
you get a real harmony
between all those parts
interacting with each other.
So it&#39;s half software and half hardware,
plus the behavior.
We&#39;ve done some work lately
on the hardware, where we tried to go --
the picture on the left
is a conventional design,
where you have parts
that are all bolted together,
conductors, tubes, connectors.
And on the right
is a more integrated thing;
it&#39;s supposed to look like
an anatomy drawing.
Using the miracle of 3-D printing,
we&#39;re starting to build parts of robots
that look a lot more
like the anatomy of an animal.
So that&#39;s an upper-leg part
that has hydraulic pathways --
actuators, filters --
all embedded, all printed as one piece,
and the whole structure is developed
with a knowledge of what the loads
and behavior are going to be,
which is available from data
recorded from robots
and simulations and things like that.
So it&#39;s a data-driven hardware design.
And using processes like that,
not only the upper leg
but some other things,
we&#39;ve gotten our robots to go from big,
behemoth, bulky, slow, bad robots --
that one on the right,
weighing almost 400 pounds --
down to the one in the middle
which was just in the video,
weighs about 190 pounds,
just a little bit more than me,
and we have a new one,
which is working but I&#39;m not
going to show it to you yet,
on the left,
which weighs just 165 pounds,
with all the same
strength and capabilities.
So these things are really getting
better very quickly.
So it&#39;s time for Spot to come back out,
and we&#39;re going to demonstrate
a little bit of mobility,
dexterity and perception.
This is Seth Davis,
who&#39;s my robot wrangler today,
and he&#39;s giving Spot
some general direction
by steering it around,
but all the coordination
of the legs and the sensors
is done by the robot&#39;s computers on board.
The robot can walk
with a number of different gaits;
it&#39;s got a gyro,
or a solid-state gyro,
an IMU on board.
Obviously, it&#39;s got a battery,
and things like that.
One of the cool things
about a legged robot is,
it&#39;s omnidirectional.
In addition to going forward,
it can go sideways,
it can turn in place.
And this robot
is a little bit of a show-off.
It loves to use its dynamic gaits,
like running --

(Laughter)

And it&#39;s got one more.

(Laughter)

Now if it were really a show-off,
it would be hopping on one foot,
but, you know.
Now, Spot has a set of cameras
here, stereo cameras,
and we have a feed up in the center.
It&#39;s kind of dark out in the audience,
but it&#39;s going to use those cameras
in order to look at the terrain
right in front of it,
while it goes over
these obstacles back here.
For this demo, Seth is steering,
but the robot&#39;s doing
all its own terrain planning.
This is a terrain map,
where the data from the cameras
is being developed in real time,
showing the red spots,
which are where it doesn&#39;t want to step,
and the green spots are the good places.
And here it&#39;s treating
them like stepping-stones.
So it&#39;s trying to stay up on the blocks,
and it adjusts its stride,
and there&#39;s a ton of planning
that has to go into
an operation like that,
and it does all
that planning in real time,
where it adjusts the steps
a little bit longer
or a little bit shorter.
Now we&#39;re going to change it
into a different mode,
where it&#39;s just going to treat
the blocks like terrain
and decide whether to step up or down
as it goes.
So this is using dynamic balance
and mobile perception,
because it has to coordinate what it sees
along with how it&#39;s moving.
The other thing Spot has is a robot arm.
Some of you may see that
as a head and a neck,
but believe me, it&#39;s an arm.
Seth is driving it around.
He&#39;s actually driving the hand
and the body is following.
So the two are coordinated
in the way I was talking about before --
in the way people can do that.
In fact, one of the cool things
Spot can do we call, &quot;chicken-head mode,&quot;
and it keeps its head
in one place in space,
and it moves its body all around.
There&#39;s a variation of this
that&#39;s called &quot;twerking&quot; --

(Laughter)

but we&#39;re not going to use that today.

(Laughter)


So, Spot: I&#39;m feeling a little thirsty.
Could you get me a soda?
For this demo,
Seth is not doing any driving.
We have a LIDAR on the back of the robot,
and it&#39;s using these props
we&#39;ve put on the stage
to localize itself.
It&#39;s gone over to that location.
Now it&#39;s using a camera that&#39;s in its hand
to find the cup,
picks it up --
and again, Seth&#39;s not driving.
We&#39;ve planned out a path for it to go --
it looked like it was
going off the path --
and now Seth&#39;s going
to take over control again,
because I&#39;m a little bit chicken
about having it do this by itself.
Thank you, Spot.

(Applause)


So, Spot:
How do you feel about having just finished
your TED performance?

(Laughter)

Me, too!

(Laughter)

Thank you all,
and thanks to the team at Boston Dynamics,
who did all the hard work behind this.

(Applause)


Helen Walters: Marc,
come back in the middle.
Thank you so much.
Come over here, I have questions.
So, you mentioned the UPS
and the package delivery.
What are the other applications
that you see for your robots?

Marc Raibert: You know,
I think that robots
that have the capabilities
I&#39;ve been talking about
are going to be incredibly useful.
About a year ago, I went to Fukushima
to see what the situation was there,
and there&#39;s just a huge need
for machines that can go
into some of the dirty places
and help remediate that.
I think it won&#39;t be too long until
we have robots like this in our homes,
and one of the big needs
is to take care of the aging
and invalids.
I think that it won&#39;t be too long
till we&#39;re using robots
to help take care of our parents,
or probably more likely,
have our children help take care of us.
And there&#39;s a bunch of other things.
I think the sky&#39;s the limit.
Many of the ideas
we haven&#39;t thought of yet,
and people like you will help us
think of new applications.

HW: So what about the dark side?
What about the military?
Are they interested?

MR: Sure, the military has been
a big funder of robotics.
I don&#39;t think the military
is the dark side myself,
but I think, as with all
advanced technology,
it can be used for all kinds of things.

HW: Awesome. Thank you so much.

MR: OK, you&#39;re welcome.
Thank you.

(Applause)

