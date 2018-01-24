
This is Pleurobot.
Pleurobot is a robot that we designed
to closely mimic a salamander species
called Pleurodeles waltl.
Pleurobot can walk, as you can see here,
and as you&#39;ll see later, it can also swim.
So you might ask,
why did we design this robot?
And in fact, this robot has been designed
as a scientific tool for neuroscience.
Indeed, we designed it
together with neurobiologists
to understand how animals move,
and especially how the spinal cord
controls locomotion.
But the more I work in biorobotics,
the more I&#39;m really impressed
by animal locomotion.
If you think of a dolphin swimming
or a cat running or jumping around,
or even us as humans,
when you go jogging or play tennis,
we do amazing things.
And in fact, our nervous system solves
a very, very complex control problem.
It has to coordinate
more or less 200 muscles perfectly,
because if the coordination is bad,
we fall over or we do bad locomotion.
And my goal is to understand
how this works.
There are four main components
behind animal locomotion.
The first component is just the body,
and in fact we should never underestimate
to what extent the biomechanics
already simplify locomotion in animals.
Then you have the spinal cord,
and in the spinal cord you find reflexes,
multiple reflexes that create
a sensorimotor coordination loop
between neural activity in the spinal cord
and mechanical activity.
A third component
are central pattern generators.
These are very interesting circuits
in the spinal cord of vertebrate animals
that can generate, by themselves,
very coordinated
rhythmic patterns of activity
while receiving
only very simple input signals.
And these input signals
coming from descending modulation
from higher parts of the brain,
like the motor cortex,
the cerebellum, the basal ganglia,
will all modulate activity
of the spinal cord
while we do locomotion.
But what&#39;s interesting is to what extent
just a low-level component,
the spinal cord, together with the body,
already solve a big part
of the locomotion problem.
You probably know it by the fact
that you can cut the head off a chicken,
it can still run for a while,
showing that just the lower part,
spinal cord and body,
already solve a big part of locomotion.
Now, understanding how this works
is very complex,
because first of all,
recording activity in the spinal cord
is very difficult.
It&#39;s much easier to implant electrodes
in the motor cortex
than in the spinal cord,
because it&#39;s protected by the vertebrae.
Especially in humans, very hard to do.
A second difficulty is that locomotion
is really due to a very complex
and very dynamic interaction
between these four components.
So it&#39;s very hard to find out
what&#39;s the role of each over time.
This is where biorobots like Pleurobot
and mathematical models
can really help.
So what&#39;s biorobotics?
Biorobotics is a very active field
of research in robotics
where people want to
take inspiration from animals
to make robots to go outdoors,
like service robots
or search and rescue robots
or field robots.
And the big goal here
is to take inspiration from animals
to make robots that can handle
complex terrain --
stairs, mountains, forests,
places where robots
still have difficulties
and where animals
can do a much better job.
The robot can be a wonderful
scientific tool as well.
There are some very nice projects
where robots are used,
like a scientific tool for neuroscience,
for biomechanics or for hydrodynamics.
And this is exactly
the purpose of Pleurobot.
So what we do in my lab
is to collaborate with neurobiologists
like Jean-Marie Cabelguen,
a neurobiologist in Bordeaux in France,
and we want to make spinal cord models
and validate them on robots.
And here we want to start simple.
So it&#39;s good to start with simple animals
like lampreys, which are
very primitive fish,
and then gradually
go toward more complex locomotion,
like in salamanders,
but also in cats and in humans,
in mammals.
And here, a robot becomes
an interesting tool
to validate our models.
And in fact, for me, Pleurobot
is a kind of dream becoming true.
Like, more or less 20 years ago
I was already working on a computer
making simulations of lamprey
and salamander locomotion
during my PhD.
But I always knew that my simulations
were just approximations.
Like, simulating the physics in water
or with mud or with complex ground,
it&#39;s very hard to simulate that
properly on a computer.
Why not have a real robot
and real physics?
So among all these animals,
one of my favorites is the salamander.
You might ask why,
and it&#39;s because as an amphibian,
it&#39;s a really key animal
from an evolutionary point of view.
It makes a wonderful link
between swimming,
as you find it in eels or fish,
and quadruped locomotion,
as you see in mammals, in cats and humans.
And in fact, the modern salamander
is very close to the first
terrestrial vertebrate,
so it&#39;s almost a living fossil,
which gives us access to our ancestor,
the ancestor to all terrestrial tetrapods.
So the salamander swims
by doing what&#39;s called
an anguilliform swimming gait,
so they propagate a nice traveling wave
of muscle activity from head to tail.
And if you place
the salamander on the ground,
it switches to what&#39;s called
a walking trot gait.
In this case, you have nice
periodic activation of the limbs
which are very nicely coordinated
with this standing wave
undulation of the body,
and that&#39;s exactly the gait
that you are seeing here on Pleurobot.
Now, one thing which is very surprising
and fascinating in fact
is the fact that all this can be generated
just by the spinal cord and the body.
So if you take
a decerebrated salamander --
it&#39;s not so nice
but you remove the head --
and if you electrically
stimulate the spinal cord,
at low level of stimulation
this will induce a walking-like gait.
If you stimulate a bit more,
the gait accelerates.
And at some point, there&#39;s a threshold,
and automatically,
the animal switches to swimming.
This is amazing.
Just changing the global drive,
as if you are pressing the gas pedal
of descending modulation
to your spinal cord,
makes a complete switch
between two very different gaits.
And in fact, the same
has been observed in cats.
If you stimulate the spinal cord of a cat,
you can switch between
walk, trot and gallop.
Or in birds, you can make a bird
switch between walking,
at a low level of stimulation,
and flapping its wings
at high-level stimulation.
And this really shows that the spinal cord
is a very sophisticated
locomotion controller.
So we studied salamander locomotion
in more detail,
and we had in fact access
to a very nice X-ray video machine
from Professor Martin Fischer
in Jena University in Germany.
And thanks to that,
you really have an amazing machine
to record all the bone motion
in great detail.
That&#39;s what we did.
So we basically figured out
which bones are important for us
and collected their motion in 3D.
And what we did is collect
a whole database of motions,
both on ground and in water,
to really collect a whole database
of motor behaviors
that a real animal can do.
And then our job as roboticists
was to replicate that in our robot.
So we did a whole optimization process
to find out the right structure,
where to place the motors,
how to connect them together,
to be able to replay
these motions as well as possible.
And this is how Pleurobot came to life.
So let&#39;s look at how close
it is to the real animal.
So what you see here
is almost a direct comparison
between the walking
of the real animal and the Pleurobot.
You can see that we have
almost a one-to-one exact replay
of the walking gait.
If you go backwards and slowly,
you see it even better.
But even better, we can do swimming.
So for that we have a dry suit
that we put all over the robot --

(Laughter)

and then we can go in water
and start replaying the swimming gaits.
And here, we were very happy,
because this is difficult to do.
The physics of interaction are complex.
Our robot is much bigger
than a small animal,
so we had to do what&#39;s called
dynamic scaling of the frequencies
to make sure we had
the same interaction physics.
But you see at the end,
we have a very close match,
and we were very, very happy with this.
So let&#39;s go to the spinal cord.
So here what we did
with Jean-Marie Cabelguen
is model the spinal cord circuits.
And what&#39;s interesting
is that the salamander
has kept a very primitive circuit,
which is very similar
to the one we find in the lamprey,
this primitive eel-like fish,
and it looks like during evolution,
new neural oscillators
have been added to control the limbs,
to do the leg locomotion.
And we know where
these neural oscillators are
but what we did was to make
a mathematical model
to see how they should be coupled
to allow this transition
between the two very different gaits.
And we tested that on board of a robot.
And this is how it looks.
So what you see here
is a previous version of Pleurobot
that&#39;s completely controlled
by our spinal cord model
programmed on board of the robot.
And the only thing we do
is send to the robot
through a remote control
the two descending signals
it normally should receive
from the upper part of the brain.
And what&#39;s interesting is,
by playing with these signals,
we can completely control
speed, heading and type of gait.
For instance,
when we stimulate at a low level,
we have the walking gait,
and at some point, if we stimulate a lot,
very rapidly it switches
to the swimming gait.
And finally, we can also
do turning very nicely
by just stimulating more one side
of the spinal cord than the other.
And I think it&#39;s really beautiful
how nature has distributed control
to really give a lot of responsibility
to the spinal cord
so that the upper part of the brain
doesn&#39;t need to worry about every muscle.
It just has to worry
about this high-level modulation,
and it&#39;s really the job of the spinal cord
to coordinate all the muscles.
So now let&#39;s go to cat locomotion
and the importance of biomechanics.
So this is another project
where we studied cat biomechanics,
and we wanted to see how much
the morphology helps locomotion.
And we found three important
criteria in the properties,
basically, of the limbs.
The first one is that a cat limb
more or less looks
like a pantograph-like structure.
So a pantograph is a mechanical structure
which keeps the upper segment
and the lower segments always parallel.
So a simple geometrical system
that kind of coordinates a bit
the internal movement of the segments.
A second property of cat limbs
is that they are very lightweight.
Most of the muscles are in the trunk,
which is a good idea,
because then the limbs have low inertia
and can be moved very rapidly.
The last final important property is this
very elastic behavior of the cat limb,
so to handle impacts and forces.
And this is how we designed Cheetah-Cub.
So let&#39;s invite Cheetah-Cub onstage.
So this is Peter Eckert,
who does his PhD on this robot,
and as you see, it&#39;s a cute little robot.
It looks a bit like a toy,
but it was really used
as a scientific tool
to investigate these properties
of the legs of the cat.
So you see, it&#39;s very compliant,
very lightweight,
and also very elastic,
so you can easily press it down
and it will not break.
It will just jump, in fact.
And this very elastic property
is also very important.
And you also see a bit these properties
of these three segments
of the leg as pantograph.
Now, what&#39;s interesting
is that this quite dynamic gait
is obtained purely in open loop,
meaning no sensors,
no complex feedback loops.
And that&#39;s interesting, because it means
that just the mechanics
already stabilized this quite rapid gait,
and that really good mechanics
already basically simplify locomotion.
To the extent that we can even
disturb a bit locomotion,
as you will see in the next video,
where we can for instance do some exercise
where we have the robot go down a step,
and the robot will not fall over,
which was a surprise for us.
This is a small perturbation.
I was expecting the robot
to immediately fall over,
because there are no sensors,
no fast feedback loop.
But no, just the mechanics
stabilized the gait,
and the robot doesn&#39;t fall over.
Obviously, if you make the step bigger,
and if you have obstacles,
you need the full control loops
and reflexes and everything.
But what&#39;s important here
is that just for small perturbation,
the mechanics are right.
And I think this is
a very important message
from biomechanics and robotics
to neuroscience,
saying don&#39;t underestimate to what extent
the body already helps locomotion.
Now, how does this relate
to human locomotion?
Clearly, human locomotion is more complex
than cat and salamander locomotion,
but at the same time, the nervous system
of humans is very similar
to that of other vertebrates.
And especially the spinal cord
is also the key controller
for locomotion in humans.
That&#39;s why, if there&#39;s a lesion
of the spinal cord,
this has dramatic effects.
The person can become
paraplegic or tetraplegic.
This is because the brain
loses this communication
with the spinal cord.
Especially, it loses
this descending modulation
to initiate and modulate locomotion.
So a big goal of neuroprosthetics
is to be able to reactivate
that communication
using electrical or chemical stimulations.
And there are several teams
in the world that do exactly that,
especially at EPFL.
My colleagues Grégoire Courtine
and Silvestro Micera,
with whom I collaborate.
But to do this properly,
it&#39;s very important to understand
how the spinal cord works,
how it interacts with the body,
and how the brain
communicates with the spinal cord.
This is where the robots
and models that I&#39;ve presented today
will hopefully play a key role
towards these very important goals.
Thank you.

(Applause)


Bruno Giussani: Auke, I&#39;ve seen
in your lab other robots
that do things like swim in pollution
and measure the pollution while they swim.
But for this one,
you mentioned in your talk,
like a side project,
search and rescue,
and it does have a camera on its nose.

Auke Ijspeert: Absolutely. So the robot --
We have some spin-off projects
where we would like to use the robots
to do search and rescue inspection,
so this robot is now seeing you.
And the big dream is to,
if you have a difficult situation
like a collapsed building
or a building that is flooded,
and this is very dangerous
for a rescue team or even rescue dogs,
why not send in a robot
that can crawl around, swim, walk,
with a camera onboard
to do inspection and identify survivors
and possibly create
a communication link with the survivor.

BG: Of course, assuming the survivors
don&#39;t get scared by the shape of this.

AI: Yeah, we should probably
change the appearance quite a bit,
because here I guess a survivor
might die of a heart attack
just of being worried
that this would feed on you.
But by changing the appearance
and it making it more robust,
I&#39;m sure we can make
a good tool out of it.

BG: Thank you very much.
Thank you and your team.
