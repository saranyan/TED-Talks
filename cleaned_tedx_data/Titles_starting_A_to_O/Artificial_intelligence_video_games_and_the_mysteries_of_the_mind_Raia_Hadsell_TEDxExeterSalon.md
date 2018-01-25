
artificial intelligence will change our
world
machines that can think like humans yet
crunch through massive amounts of data
in a very inhuman way may be exactly the
tool we need to solve our biggest
problems AI may also unlock the
remaining mysteries of the human mind
and this is what intrigues me the most
I&#39;m not a neuroscientist but as a
computer scientist I write programs that
can learn learn from their experience
and change and adapt some of my first
experiments were with a robot that
needed to avoid obstacles outdoors and I
still remember the amazement that I felt
when the robot stopped running into
trees and instead drove around the trees
and down the winding forest trail
without me changing a single line of
code but because the robots program had
learned from its experience and changed
its own behavior
a decade later I&#39;m still writing
programs that can learn from experience
and change and adapt and I&#39;m still
amazed to be clear we have not yet
created true artificial intelligence and
it may be decades more before we do but
we are making progress so let me tell
you about machines that can learn to
play video games solve mazes and run
through an obstacle course the programs
that I write use a learning algorithm
called reinforcement learning we start
with what we call an agent and this is
the part of the algorithm that learns
and takes actions and that&#39;s why we call
it an agent because it has agency an
autonomy the agent interacts with an
environment it sees observations it
takes actions and it gets reward both
both positive and negative
this idea of reinforcement learning is
simple and powerful it&#39;s based on the
the same way that a dog learns how to
sit or we encourage a child to practice
piano through strategically given M&amp;Ms
let&#39;s go a little bit deeper the agent
that I&#39;m talking about is a mathematical
model and at deep mind we&#39;ve been very
successful in using deep neural networks
with many layers of neurons and millions
of connections between those neurons as
the agent
thus merging the fields of deep learning
and reinforcement learning as for the
environment we mainly use games at deep
mind why is that well games are very
very useful because we can readily
evaluate how well the agent does by
pitting it against a human player for
example or comparing its score to other
agents but more importantly we can think
of games as being like a microcosm of
human ability because they are so
diverse and so ubiquitous across human
culture so they&#39;re incredibly valuable
if what we want is to both develop and
demonstrate artificial intelligence at
deep mind we&#39;ve trained agents to play
everything from simple video games to
incredibly complex games such as go and
chess one particular game I can show to
you is this game it&#39;s an Atari game
called break out those of you that are a
child of the 70s or 80s may remember it
very well
may be new to others of you and the way
an agent learns to play this game is by
seeing the pixels on the screen then
making mathematical calculations which
propagate through those millions of
connections layer by layer in the
network producing an action which is a
command on the joystick now if that
action is good and results in the agent
getting more points more reward then the
learning algorithm reinforces that
action by adjusting ever-so-slightly
all of the millions of connections in
that neural network we can see how the
behavior of the agent changes over time
with its experience of the game so at
first even after a hundred games of
experience it&#39;s still pretty rubbish it
misses the ball all too often but if it
keeps on playing after a few hours the
300 games then it gets better and better
at this point it&#39;s it about human
ability can return the ball keep keep
alive for a long time if we let it keep
on learning then after a few more hours
and a lot of play and a lot of games of
experience then it gets really good it
gets better than a human because it
learns how to how to do this trick
called tunneling that is systematically
send the ball to the sides of the wall
so that it bounces around on top and the
agent has less work and more reward the
learning algorithm doesn&#39;t just work on
breakout it works on most of the 57
games that we&#39;ve tried it on and
achieves superhuman level of play at
most of them but not all some are still
a challenge so if we look at the bottom
of this list we see a game called
Montezuma&#39;s Revenge where the agent gets
a score of zero which is zero percent
relative to a human player why&#39;s
Montezuma&#39;s Revenge hard well when I
look at this game I immediately infer
that my actions are going to control the
little dude in the middle with the hat
that ropes are for swinging and ladders
for climbing that the skull at the
bottom is probably a probably bad and
the the key especially since its golden
is probably good in other words I apply
concepts high-level concepts that I&#39;ve
learned in a lifetime to this game and
immediately understand it an agent
however that learns only from the pixels
on the screen is never going to get to
this high level of concept my colleague
sasha avez nevets had the insight that
this game could be solved if we could
break it into simpler problems for
instance if we could say jump across the
gap get to the ladder get past the skull
and pick up the key then maybe this
would be a solvable problem and if you
think about it that&#39;s what a teacher
does a good teacher breaks down a hard
problem into simpler problems that a
student can learn so we developed an
architecture that involves training to
neural networks to agents at the same
I&#39;m from the same game one of them we
call it the teacher produces those
subproblems learns what good subproblems
are and sends them to the student the
student actually takes the actions
controls the joystick tries to maximize
reward in the game but also tries to do
what the teacher tells it to and even
though these two agents are only trained
from those same pixels on the screen and
with no other information the structure
allows strategy and communication to
emerge over time and we end up being
able to learn how to play the game if we
look at how the agent plays now it&#39;s
still not as good as a human my 10 year
old son would not be impressed I think
but it is managing to move around the
screen it&#39;s managing to get through it
even manages to pick up the sword
important piece before dying so we are
making progress
let me tell you about another challenge
for our learning algorithms for these
agents and that&#39;s the problem of
learning multiple games one after the
other we human that humans have a
seemingly limitless capacity to learn
games one after the other we learn to
play piano we learn to play poker we
learn to play ping pong all without
forgetting how to learn how to ride the
bike that we learn before any of those
but agents that we train have a very
hard time learning just two games one
after the other this is because when we
learn on the first game then we saturate
the neural connections the millions of
neural connections they&#39;ll get saturated
with knowledge of how to play that first
game and when we move on to play the
second game all of those neural
connections are overwritten obliterated
with the second game thus producing the
phenomenon known as catastrophic
forgetting which is well known for
neural networks we can see this
happening in the simple game of pong so
this is a trained pong agent it&#39;s
superhuman better than any of us because
it can methodically get to a score of
twenty to zero the agent is controlling
the green paddle on the right and it
will go through methodically win with a
score of twenty to zero on every game
that it plays against the computer
opponent here what happens when we make
a very small change to the input all
we&#39;re going to do is change the paddle
and the score of the opponent from
orange to black and now we see that the
agent controlling the green paddle still
still moves around but it&#39;s missing the
point and missing the ball as well and
it loses with a score of zero to twenty
everytime catastrophic failure so in
order to solve this we took some
inspiration from neuroscience in the
mouse brain and presumably in our own as
well there&#39;s a process called synaptic
consolidation that protects only neural
connections that are formed when a
particular new skill is learned and we
developed an algorithm where after
training on a game we
automatically identify and protect only
the neural connections that are most
important for that skill on that game
this means that when we move on to
playing the second game that there are
spare neurons that can be used to learn
the new game and we&#39;ve preserved the
knowledge of how to play the old game
thus preventing forgetting this is
called elastic weight consolidation and
when we apply it to our agents then we
find that they can learn ten games one
after the other without forgetting and
all at superhuman level all right so
let&#39;s move on from video games and let&#39;s
take a look at a more complex
environment this maze so consider this
maze it&#39;s not too hard to solve
from this perspective clearly but if we
are in the maze looking at it from this
perspective it becomes very hard for
both agents and for humans alike this is
because as we move through this maze
then we need to both remember where we
have been and also where we are going to
go to and that requires memory and the
neural networks that have shown you so
far don&#39;t have memory so what we did in
order to solve this game was we
developed a neural network that has one
layer in it that is composed of neural
memory units and those persist over time
so that as the agent explores the maze
and tries to find that orange and red
object that you see there at the bottom
it can retain memory of where it saw it
where that location was in the maze and
then as it continues to move through the
maze then that memory layer persists
over time and enables the agent to find
that goal again more efficiently and
just to be clear this neural memory is
not given for free the agent has to
learn to use it just like it has to
learn to use all of the rest of their
neural network but it does work so we
can see how the agent after training
manages to find its way through this
maze zooms around the maze picking up
apples along the way those are worth one
point in this game that that I made and
it searches the whole maze to find where
the goal is
note that without memory it wouldn&#39;t
even be able to search the maze
effectively it would just run in circles
because it wouldn&#39;t be able to remember
where it had searched once it finds the
goal object it has to find it again and
again and again in this maze that it had
not seen before and we can look at how
long it takes to get back to the goal
each successive time and see that it
gets lower each time meaning that the
agent is using its memory to improve its
performance and get back to the goal
again and again I&#39;ll tell you about one
last challenge for our learning agents
today and that&#39;s the challenge of
controlling a humanoid figure like our
own this is challenging for us think
about how long it takes a baby to learn
to take those first few steps alone and
it&#39;s an interesting problem my colleague
Nicolas he&#39;s trained an agent to control
this simulated humanoid figure instead
of the neural network producing a single
joystick command the network produces a
set of 21 different actions continuous
values one for each of the different
joints in this simulated humanoid figure
and then the agent trains learns how to
control the humanoid so that it can run
through an obstacle course which can
have random walls placed or can have
gaps of increasing size let&#39;s take a
look at the video of how it does
all right so clearly this is not the
most sophisticated running agent that
you&#39;ve ever seen and you may think that
it is awkward or inhuman like or simply
funny the way it controls the body and
particularly those arms but keep in mind
that this agent has never been asked to
do anything with its arms like juggle or
carry a full pint glass nor has it ever
seen any human examples to emulate nor
has it undergone the merciless scrutiny
of its peers it&#39;s simply trying to use
its arms to do the task better so it&#39;s
using them for momentum and for balance
so it&#39;s clearly going to be a little
while before we can use this technology
in order to control complex robots on
real-world tasks but it is a very
interesting research path that we&#39;re
going down with a lot of potential and
where you may ask is this path actually
going to lead us and why are we trying
to solve artificial intelligence at deep
mind I can give you three reasons
personally so the first reason as a
computer scientist I just am fascinated
by the challenge of how we write
programs that can actually learn and
change themselves and gain intelligence
through interactions with a complex
world the second reason is as a human I
am deeply curious about how we work
an AI may be exactly the platform we
need to probe those mysteries of how
does a baby learn to stand up and walk
how does a 10 year old master a
videogame how does a 40 year old
navigate through a urban maze day after
day without getting lost how does an 80
year old remember a lifetime of
experiences and lastly as a human on
this planet like all of us I am
incredibly optimistic that artificial
intelligence may be the powerful tool
that we need
to solve our problems to cure disease to
ease inequality or to save a warming
planet thank you
[Applause]
[Music]
