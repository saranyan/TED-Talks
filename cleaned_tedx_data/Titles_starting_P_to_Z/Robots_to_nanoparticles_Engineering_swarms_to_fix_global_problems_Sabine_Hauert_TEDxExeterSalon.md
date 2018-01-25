
birds can create these beautiful complex
dances in the sky
and there&#39;s no leader there&#39;s no one
bird telling every bird what to do in
that flock it&#39;s just the result of every
bird reacting to the birds within its
neighborhood following a simple set of
rules and there&#39;s there&#39;s many features
that I find interesting in these flocks
so for example if you keep adding birds
to the flock the flock continues to fly
so they can scale to very large numbers
if a bird falls from the sky the whole
flock doesn&#39;t fall to the ground so
they&#39;re very robust individual failures
and together they can do more than the
individual birds for example they&#39;re
much better at avoiding predators as a
flock than any of those individual birds
so these dances are really self
organized and emergent and there&#39;s many
examples of this so-called swarm
intelligence in nature so you might have
seen those annoying trails of ants that
lead up to your picnic table those are
self organized or you might have seen
bees that make decisions about the
location of their next nest site and the
one self-organized system that I&#39;m most
impressed by right now is our ability
just from two cells to self-organize a
fully functioning human being so as a
swarm engineer my puzzle the thing that
I try to solve is how do we engineer
these swarm behaviors and this is quite
challenging because very often I&#39;ll know
I want to do flocking or I want to
create trails or I want to do
decision-making but the challenge is in
understanding how you design those
individual rules and usually it&#39;s not
obvious at all just like if you were to
take a bird from the sky and look at it
that won&#39;t tell you how these flocks
operate and so to do that I use two
strategies the first strategy is
bioinspiration so we talked a lot with
biologists and they&#39;ve been studying
these swarms in nature for a very long
time and we asked them if they know what
the rules are if they have any ideas
about how these natural systems function
and then we can use that in our
artificial systems that we want to
engineer the other strategy if nature
doesn&#39;t have a good example is we need
to explore some of those local rules and
the way we explore sometimes a swarm
engineer like me is guessing so we&#39;re
behind our computer trying out lots of
different rules sometimes we use the
crowd so have the crowd help us explore
many different rules and some times and
this is really an approach that I love
we use machine learning so for example
we might want to engineer an neural
network controller for a robots that
gives you the desired swarm behavior and
we do that using machine learning so
that it&#39;s all automatic so that you can
automatically come up with those local
rules that give you a desired swarm
behavior so here&#39;s an example of how
we&#39;ve engineered a swarm of flying
robots to flock so focus on this robot
in the middle of that circle that robot
just looks at the other flying robots
within its local neighborhood and then
it needs to follow simple rules so for
example it&#39;s going to be attracted to
its neighboring robots that&#39;s just to
make sure that the flock as a whole
stays cohesive stays as a unit but it&#39;s
also repulsed by its neighbors because
otherwise all the robots would just
collide and they try to point in the
same direction now there&#39;s a fourth rule
that we add when it&#39;s an application and
that is we don&#39;t want our flock to just
fly away
so we add a migration point so that the
robots know where it is they&#39;re going
and you add up all those vectors and
that tells the robot in what direction
it should be moving and so every one of
the robots
within that flock is going to be
following those same sets of simple
rules and the exciting thing is once you
have the rules you can actually go and
deploy them in reality so here what you
see are ten of the flying robots that we
had in the Floriana lab at EPFL and we
could throw them in the air here they&#39;re
waiting to start a flocking experiments
sometimes you can spot a bird they&#39;re
about the same size and here are the GPS
trajectories of ten
these flying robots in the air you can
see it starts quite messy but over time
they create these circular dances and
this is exactly what we had predicted
using swarm engineering so that was ten
robots we&#39;ve also done work with a
hundred robots creating trails inspired
from how ants create trails to your
picnic table so here we&#39;re releasing
them and they&#39;re looking for that second
static robot and very quickly you can
see these trail forms these robots are
coin-sized so tiny little robots and
here what you&#39;re seeing are four hundred
robots making decisions so they&#39;re
making decisions between blue and red
and here&#39;s a little spoiler blue is the
better decision so they should very
quickly all become blue so we have tools
now that allow us to engineer swarm
behaviors for robots and typically these
behaviors work up to the thousands if
you&#39;re lucky that&#39;s really the max that
we can get to in the robot world and in
my mind swarms needed to work you know
thousands is great but what if they
could work in the ten thousands with a
hundred thousands or the millions and so
I got very excited by the field of nano
medicine and I spent three years in the
laboratory of Sangeeta Bhatia at MIT who
designs tiny nano particles that are
very interesting vehicles to deliver
drugs directly to tumors and what
fascinated me is that these
nanoparticles work in the 10 to the
power 13 so that&#39;s a one with 13 zero so
that&#39;s the huge number that I was
excited about and on top of that these
nanoparticles come in many different
flavors so you can change their size you
can change their shape this might be an
iron oxide nano worm for example you
could change their charge that changes
what they stick to you can change their
materials some of them can be activated
using magnetic fields or or lasers you
can decorate these nanoparticles with
molecules that allow them to go and
stick to cancer cells and you can load
them with drugs
that you can release in a more or less
controlled fashion so when you look at
it there&#39;s many knobs that you can turn
on the design of a nanoparticle so just
how would you make nano particle swarm
well you know the birds had a brain
which was probably controlling how they
reacted to the other birds in that flock
the flying robots had a program which is
something that I put on their computer
in the case of the nano particles
they&#39;re too tiny and so it&#39;s really
about how you turn those knobs how do
you change the design of the particle so
that when you inject them they do what
you want them to do as a collective and
here&#39;s an example of just two knobs that
we turn so for example the size changes
how quick these nano particles move and
then we change how sticky these nano
particles are to cancer cells so just
two knobs and actually if you&#39;re
bioengineer you might think it&#39;s a
brilliant idea to make a very sticky
nano particle because then it sticks to
the cancer cell cancer cell eats it up
it delivers the drug that cancer cell is
dead so that makes sense in terms of
looking at the individual but actually
when you have large numbers of these
particles and they&#39;re all so good what
happens is they leak out of the vessels
and they all stick to the same cancer
cells they encounter as soon as they&#39;ve
leaked up and so that means they&#39;re not
going deep into the tumor tissue and
they&#39;re not treating those deep-seated
tumour cells so actually the swarm
behavior the collective behavior is
quite poor so just turning those two
knobs shows how important is to think
about collective dynamics when you&#39;re
trying to make treatments better and we
need help turning those knobs so we also
have a game called nano dock to
crowdsource the design of these
nanoparticles so people can help us
essentially try lots of combinations and
then through our simulator you can see
what the group behavior is and you can
fine-tune that as you go and obviously
just like we threw the flying robots in
the air before we need to try these
things in reality and get our hands
dirty so here are some 3d printed
microfluidic devices that we design in
Bristol and
Green what you see are nanoparticles
that are really nanometer sized and in
red you have an artificial tumor tissue
and we look at how these nanoparticles
move through these tumor tissues so that
was a dive into the nano world into the
biomedical world and what I realized is
that actually swarm engineering can help
us across a number of biomedical
applications so why not use swarm
engineering to understand how millions
of cells go bad in the case of cancer
leave their primary tumors and are
recruited to to metastatic sites how can
we use swarm engineering to understand
how bacteria go bad in the millions and
become resistant to antibiotics or form
biofilms that are actually quite
difficult to treat can we use swarm
engineering again to understand how the
cells of the immune system work together
to reget to get recruited two areas of
infection and can we improve that in the
area of immunotherapy and the brain is
the result of billions of cells working
together can we understand these
self-organized systems in a way that&#39;s
meaningful for brain diseases and I
think that it&#39;s really beyond
understanding right swarm engineering
can help you understand but ultimately
what we want to be doing is controlling
this systems and we actually have
interesting tools now in in the
gene-editing world and synthetic biology
that could allow us to start engineering
the collective behavior in these
biomedical applications so that we can
ultimately improve treatments so I&#39;ve
showed you robots that were centimeter
sized that worked in the thousands and
I&#39;ve showed you nanoparticles that
worked in these huge numbers and I think
we need to bring together these two
worlds ideally I like to take the robot
world centimeter size but make those
work in the millions so those huge
numbers and the way we do that I think
is we need to make our robots behave
much closer to the way the Nano and
micro systems work so using very simple
behaviors that are on
random motion simple local interactions
with your with your immediate
neighborhood and here&#39;s just an example
of why I think this would be interesting
in robotics so here&#39;s a farm field
that&#39;s one kilometer by one kilometer
there&#39;s a hundred million seeds in this
farm fields and the way we would
currently go about making a robot to
plant seeds is to make a robot that
zigzags through that farm field and
plants them pretty much one by one 100
million is actually on the scale of
things that happened in the biology
world so why not make a hundred million
robot seeds that are safe and
biodegradable carry the nutrients and
actually deploy and plant themselves
could we be making robots to detect
pollutants and water sources could these
robots light up in a way that guides you
to the to the source of that pollutant
and ideally even cleans up that
pollutant and could we be designing
robots that work in those huge numbers
that are very rapidly able to deploy
over a disaster area create a
communication network and guide the
rescuers to the areas where victims
might be located so what I&#39;ve wanted to
show you today is that I think we&#39;re at
a stage where we can really start to
think about a unifying framework that
allows us to engineer swarms across
skills from the nanoparticle world to
the robot worlds but really focusing on
how we can make those huge numbers thank
you
[Applause]
