
[Music]
I&#39;d like to tell you about my kids not
just because I&#39;m a proud dad but also
because I think their early experiences
provide an interesting perspective on
the different ways that we&#39;ve thought
about creating intelligent systems so so
max when he was a baby we decided at one
point that he was old enough to graduate
from his crib to a big-boy bed so we
swapped out the crib we put the bed in
we put him to sleep in the crib and the
next morning he called to us to ask us
to you know take him out of the bed so
that he could start his day and so we
went in and we explained to him okay
look this is how a bed works
you&#39;re only this many inches off the
floor just sit down on the bed put your
feet on the floor you&#39;re good to go so
we never had to tell him again but it
wasn&#39;t something that he came up with on
his own and this was kind of a typical
property of Max that he would follow
rules in some cases very complex rules
but he tended not to discover the rules
on his own now contrast this with Molly
you know Molly when Molly was a baby
at one point we just found her wandering
in the morning around the entire
apartment she had gotten somehow her
tiny little body over the barrier of the
crib into the room got out the door
somehow and was just going about her
business at which point we decided okay
well I guess she&#39;s ready for a big-girl
bed and that was kind of a property of
Molly pretty frequently what she would
tend to do is create her own rules she
would look at the environment understand
the patterns that were going around and
decided for herself what to do and this
was great this was very powerful we had
there was less that we had to tell her
about what to do on the other hand it
made her somewhat uninstructed ball so
if we wanted her to do something it was
difficult to tell her what to do because
she kind of already had her own idea of
what needed to be done and so these same
descriptions actually apply to the two
main ways of making AI systems so go
physis terms are good old-fashioned AI
is when we build intelligent systems by
programmers people writing down lots of
rules giving them to the system and then
having the system do inference and
problem solving to actually use those
rules to decide what to do in contrast
machine learning is a method for
creating intelligent
systems where what we do is we create a
program and then we dump tons and tons
and tons of data on it at which point it
extracts patterns if it finds
regularities in that data and then it
applies what it learned to solve the
problem that it was originally set out
to solve and these are both very
powerful and very very useful ways of
solving problems but I want to argue
that there&#39;s still something missing
there&#39;s still something about these that
doesn&#39;t really get us all the way there
and to try to get this idea across let
me give you a scenario so let&#39;s say that
you what you&#39;d really like in your life
is to have a robot that will bring you
coffee in the morning now I use this
example in particular because I&#39;ve
watched a lot of movies and I&#39;m pretty
sure that what Hollywood wants us to do
is to make robots that bring us coffee
in the morning anytime there&#39;s a movie
with an inventor in it if it&#39;s back to
the future or pee-wee&#39;s big adventure
there&#39;s always an inventor in end that
inventor always is inventing ways of
getting us our coffee in the morning so
so I assume that that&#39;s what we&#39;re here
for as AI system creators and I accept
that responsibility so so let&#39;s say that
that&#39;s what we want to do we want to get
you your coffee in the morning so you
decide ok this is what I need to do I&#39;m
gonna I&#39;m gonna create such a robotic
system the first thing you realize is
that you&#39;re gonna need some kind of
physical robot so you go down to your
local home robot store and from all the
different robots that are available you
decide to pick one out and let&#39;s say yum
that&#39;s a very nice robot I will name him
Jeff and I will bring him to my house so
you go home with Jeff and now Jeff is
ready to help you but Jeff doesn&#39;t know
what you want and so you now have to
create some kind of program some kind of
AI system that&#39;s going to drive Jeff to
solve the problem that you want to solve
which is getting you your coffee so you
being a say a ngo5 person nearly I&#39;m
gonna create a good old-fashioned AI
system I&#39;m gonna write a program that
the robot will follow and by following
that program will solve my problem and
what you discover very early on even
though you&#39;re a great programmer
programming robots is actually really
different from programming other kinds
of systems it&#39;s very complicated you
have to handle lots of weird corner
cases the programs themselves become
very very complex very difficult to
maintain so maybe you get frustrated
you&#39;re like you know what no more with
the go fie I&#39;m going to switch
- over to machine learning I heard
that&#39;s very good you discover right
right away that this actually does seem
to be a lot better instead of having to
tell the robot what to do in every gift
given possible situation you have to
define an objective function you have to
define what the rules are that it should
try to follow and the rules are you
should have I should have coffee at some
point in the morning you shouldn&#39;t break
any mugs on the way to do that and don&#39;t
make too much noise when you&#39;re making
coffee because that but that wakes me up
and you can define that as a series of
kind of costs and then you say to the
robot great this is these are your
instructions now make it so and what you
discover is that even though it started
off as a pretty easy thing from your
perspective it&#39;s still pretty
frustrating because the robot doesn&#39;t
figure it all out instantaneously it has
to learn and what you find is at some
point the robot you know weeks later
after you&#39;ve been waiting for your
coffee the robot has discovered that
it&#39;s wandering the house it maybe
doesn&#39;t know about coffee mugs but it&#39;s
got a potted plant and it&#39;s not really
bringing coffee to you in your bedroom
it&#39;s kind of hanging out in the bathroom
for some reason with a cat and it&#39;s not
even your cat like what is going on with
this you know your patient until you
wait in a few more weeks later the robot
is getting will say better it&#39;s got a
coffee mug now and it&#39;s in the kitchen
so that seems relevant it still got that
cat though
so so you&#39;ve become frustrated and
probably what you would do probably what
I would do in that situation is try to
intervene in some way it&#39;s like yeah it
would be great if it could just
spontaneously invent all the things that
I needed to invent but it would save a
lot of time if I could just tell it what
I wanted it to do
and so that&#39;s the essence of the idea
that I want to put forward the notion of
cooperative artificial intelligence
cooperative AI is supposed to have in it
the strengths of the two other ways of
creating artificial intelligence systems
like machine learning it&#39;s embodied in
the world the robot is in the world
experiencing things and it can ground
its experiences in the tasks that it&#39;s
actually trying to carry out but like go
Phi we as the programmers are we as the
people in the system get to actually
define the task that we want it to carry
out so we get to help the system do what
it should do to help us so the basic
idea here is that the human trainer the
person actually becomes a really central
component in the
creating of the AI system and what the
person&#39;s doing is providing feedback on
desirable behavior the person is guiding
the learners attention so of all the
zillions of things it might pay
attention to it pays attention to the
stuff that matters and then finally the
human trainer has the opportunity to
give the robot certain kinds of
experiences in a certain kind of order
that help it build up the conceptual
structure that it&#39;s going to need to
solve the problem and that part I think
is really neat and very much
underappreciated in the field so let me
focus in on that idea a little bit so
when we&#39;re training a robot in this
model we are presenting it with a series
of tasks and those tasks need to be
selected in a certain way the learning
challenges should be introduced so that
they&#39;re neither too big of a step and
therefore may be too difficult to solve
for the system nor too small of a step
that is to say not making enough
progress towards ultimately what you&#39;re
trying to teach the tasks themselves
need to be you know relevant and
unambiguous and useful so the robot
should be paying attention to what
you&#39;re telling it and ultimately if
these things work the competence of the
robotic system comes from climbing up
this ladder of competence by solving
each of the individual tasks that you
set for the robot it&#39;s going to get
better at what it is that it&#39;s supposed
to do now I call this the portal theory
of intelligence it maybe has gone by
some other names oh ok so Jeff is
pointing out that in fact the
psychologists and education Pyrrhus know
this as the zone of proximal development
the idea that you&#39;re always teaching a
little bit outside the current
competence of the learner now I didn&#39;t
know that term when I start first
started working on this I didn&#39;t spend a
lot of time reading the educational
literature which I probably should have
in fact I was spending a lot of time
playing video games which maybe I
shouldn&#39;t have portal if you don&#39;t know
about it is a video game that&#39;s really
cool and I&#39;m going to tell you a little
bit about it because I think it&#39;s
actually useful in this particular
context so portal is a first-person
shooter but you don&#39;t shoot bullets
you&#39;re not killing things you&#39;re
actually shooting doorways at surfaces
when those doorways exist it actually
connects points in space and lets you
pass through them hence the name portal
it&#39;s a little bit hard to see in the
first-person view point so let me just
show you one of the challenges in a
schematic way so here you are in the
world trying to get out of the world
trying to get to the big red button
which is going to let you out and what
you notice very quickly is that the
Shelf the barrier before the button is a
little bit too hard to climb up a little
bit too high
but what you&#39;ve learned over a course of
a series of levels is that you have this
portal gun and you can use it to shoot
doorways at things and in fact if you
shoot a doorway where you&#39;re standing
and one close to the button those two
places in space become connected and
then all you have to do is walk through
one of them and you appear out the other
one and you get to where you&#39;re going so
this is actually a really nice trick it
would be very fun if we could do this in
the real world but in this artificial
world you can totally do that and you
need this to be able to solve the
problems that are posed and this isn&#39;t
the only way to use a portal there&#39;s
other ways to use portals so let me give
you another example so let&#39;s take the
same scenario except now the wall next
to the button is gone so you can&#39;t shoot
a portal there you can&#39;t come out next
to the button what are you gonna do so
what happens is the designers of the
game have created a series of levels
that introduce all the ideas that you&#39;re
gonna need and just leave you right on
the edge of putting those ideas together
to solve the problem and what you
realize when you think about this for a
while is wait a second if I put a portal
on the floor and one on the wall high
above me and then jump off the shelf
into the hole I will fly out of the
other hole with the same momentum that I
went into the hole with jumping over the
ledge and landing on the button tada all
right so this is a really neat trick and
again it doesn&#39;t happen this way in the
real world but in this artificial world
you get to learn how to use these
particular kinds of tools and the game
designers teach this to you and create
this competence in you by introducing
you to this series of levels it&#39;s really
a very beautiful idea and it&#39;s very
similar to things that you might think
about doing in the real world as well so
for example let&#39;s imagine that you have
a dog if you want that dog to clean up
its own toys if you guys if you go
online and search for that as a task
you&#39;ll find instructions for the things
that you need to teach the dog the
portal levels that you need to expose
the dog to to get it to solve this task
it&#39;s not a matter of just holding a
treat and saying clean up your toys
right you have to kind of get the dog to
that point same thing happens with say
teaching a kid to swim you don&#39;t want to
just take a kid and throw the kid into
the ocean this is how my dad taught my
cousin to swim and it&#39;s not recommended
really what you want to do is work up to
it in a series of challenges and so
again I went online and these are the
instructions for learning to swim if you
want to learn advanced mathematics again
you want to start and build up from
there and it&#39;s not just for kids or
animals either
if you want to become a CEO you can go
online and in wiki how it tells you just
how to do it there&#39;s a series of levels
to it like portal levels and each one is
you know relatively easy given the ones
below it and the end see you now I
haven&#39;t tried this one out but I you
know I&#39;m tempted to at some point so so
let&#39;s take this idea and bring it back
to the problem of bringing coffee
because you know those other problems
we&#39;re not really as important so the
coffee problem to solve the problem of
the robot bringing coffee one thing that
it&#39;s going to need to be able to do is
recognize your coffee machine your
coffee maker and so this is this can be
set up as a supervised learning problem
so supervised learning is the machine
learning problem of being able to
recognize patterns and classify things
as being positive or negative instances
of a giving concept so if I want to
train my robot by supervised learning
what I need is a giant database of
images most of which I label as not the
coffee machine and some of which I label
as a coffee machine and then it would
have to go through that data and and
work out a concept that would correctly
separate coffee machines from non coffee
machines and this actually is a problem
that&#39;s fairly well solved today so
convolutional neural nets are a very
powerful computational tool that if you
dump tons of data on them like this they
will probably learn to recognize coffee
machines and if you crack open you know
the container and look inside to see
what they&#39;re doing they basically
discover portal levels so the way that
these systems actually recognize complex
objects is by recognizing straight lines
and using that to recognize curved lines
to recognize textures to recognize
object parts and ultimately to recognize
the objects that you&#39;re interested in
which is really kind of amazing and very
powerful now you might be tempted at
this point to think okay well this is
great this is a solved problem anything
that I want I could just get enough data
and and apply it it turns out though
that we&#39;ve known since the 90s that it&#39;s
a computationally intractable problem to
train neural nets or machine learners in
general in the worst case I mean lots of
problems they solve really well but
others you know they&#39;re gonna struggle
on it turns out the problem if you could
solve it effectively you could use that
same system to break cryptographic codes
like the kinds of things that protect
our money in the banks so we&#39;re
expecting at least the bankers I guess
are expecting that this is a hard
problem and unlikely to be one that we
could solve well my students and I have
figured out is that in fact
you as a teacher can break down the
learning problem into portal levels if
you will you can actually train any task
no matter how complicated its in such a
way that the learner is never having to
work too hard each of the levels that it
solves are simple combinations of the
things that it&#39;s already seen this works
for supervised learning it turns out
also works for reinforcement learning
which is the problem of actually
following a path to get to to a goal to
execute a sequence of commands in the
world - in this particular case go from
the charger to the to the kitchen to my
bedroom to deliver coffee this problem
is also intractable for a completely
autonomous system we just give it the
task you just say go for it it&#39;s going
to take essentially forever but we can
break it down into smaller problems and
we can solve it that way it&#39;s not easy
to know how to break it down but there
is a community of scientists who think
about this the the behavior analysts
these are the people who think about how
to train animals how do you train a
chicken how do you train a dog how do
you train a hippopotamus and what
they&#39;re what they do is they teach
people how to break complicated tasks
into smaller pieces and one of the
challenge problems that they&#39;ll give is
ok train a chicken to walk a
figure-eight and it turns out it&#39;s
actually not that hard if you break the
problem down the right way so my
colleagues and I were reading about this
and thought this is really amazing we
should totally do this with a robot so
we built a robot that you could give
positive and negative feedback to like a
chicken and we gave it things to walk
around in a figure-eight and trained it
just the way that the behavior analysts
would tell us to and it worked we got a
robot that we could then run around into
a figure eight it was really neat it was
almost as if robots were following in
the chickens footsteps so this notion of
cooperative AI to me is it&#39;s a very
powerful idea that is is really our best
hope to creating intelligent systems and
I think one of the reasons I&#39;m so
optimistic about this as a path forward
is because it acknowledges an important
fact about intelligence that I think is
underappreciated and that is the
intelligence system that we know the
most about namely people we don&#39;t invent
we don&#39;t solve SuperDuper hard problems
always on our own if we need to use
something complex like language we
invent language together if we need to
use advanced mathematics like calculus
we learn this together even the
inventors of calculus
didn&#39;t invent this completely alone
right so both Newton and Leibnitz
created calculus at around the same time
and around the same way but they were
both building on the notations that were
available at the time though the
problems that people thought were
interesting the concepts that were
available and they came up with
something very similar to each other in
fact Newton even said if I can see so
much further than others it&#39;s because
I&#39;m standing on the shoulders of giants
right I&#39;m getting benefit from working
with other people so we really do get to
be smarter by working together in this
way but smartness is not the only thing
we care about what we&#39;re building AI
systems we really want them to be
helpful we want them to do what we need
them to do and this cooperative approach
to artificial intelligence is maybe
problematic in that regard it really
puts the onus back on us as teachers to
teach the system&#39;s the right things we
don&#39;t want all of our robots to grow up
to be I don&#39;t know racist Twitter bots
cuz this happens sometimes and so you
want to avoid that so we really have to
pay attention to what we&#39;re asking our
robots to do we need to teach them well
but I think the benefits of doing so are
really important well in the near term
we&#39;ll have systems that are more
personalized to this the problems that
we&#39;re actually facing in the longer term
will be sharing the world with
intelligent agents that that kind of get
us they understand the things that we
understand they break down the world the
way that we break down the world will
understand what they&#39;re doing they&#39;ll
understand what we&#39;re doing and I think
that&#39;s really important because in the
coming AI revolution each of us has an
important role to play we&#39;re not going
to be sitting on the sidelines we&#39;re
going to be putting a bit of ourselves
into these systems that are so
powerfully going to influence our lives
and our futures thanks very much
you
