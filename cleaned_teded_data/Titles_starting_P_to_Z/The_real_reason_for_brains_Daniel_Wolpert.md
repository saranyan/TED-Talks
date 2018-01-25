
I&#39;m a neuroscientist and in neuroscience
we have to deal with many difficult
questions about the brain but I want to
start with the easiest question and the
question you really should have all
asked yourself at some point in your
life because it&#39;s a fundamental question
if we want to understand brain function
and that is why do we and other animals
have brains not all species of our
planet have brains so if we want to know
what the brain is for let&#39;s think about
why we evolved one
now you may reason that we have one to
perceive the world or to think and
that&#39;s completely wrong if you think
about this question for any length of
time it&#39;s blindingly obvious why we have
a brain with a brain for one reason and
one reason only and that&#39;s to produce
adaptable and complex movements there is
no other reason to have a brain think
about it
movement is the only way you have of
affecting the world around you that&#39;s
not quite true there&#39;s one other way and
that&#39;s through sweating but apart from
that everything else goes through
contraptions of muscles you think about
communication speech gestures writing
sign language they&#39;re all mediated
through contractions of your muscles so
it&#39;s really important to remember that
sensory memory and cognitive processes
are all important but they&#39;re only
important to either drive or suppress
future movements there can be no
evolutionary advantage to laying down
memories of childhood or perceiving the
color of a rose if it doesn&#39;t affect the
way you&#39;re going to move later in life
now for those who didn&#39;t believe this
argument we have trees and grass and our
planet without the brain but that
clinching evidence is this animal here
the humble cease were rudimentary animal
has a nervous system swims around in the
ocean in its juvenile life and on some
point of its life it implants on a rock
and the first thing it does in and
planting on that rock which it never
leaves is to digest its own brain and
nervous system for food so once you
don&#39;t need to move you don&#39;t need the
luxury of that brain and this is often
this animals often taking as an analogy
to what happens universities when
professors get tenure but that&#39;s as
so I am a movement chauvinist I believe
movement is the most important function
in the brain that anyone tell you that&#39;s
not true
now if movement is so important how well
are we doing understanding how the brain
controls movement and the answers we&#39;re
doing extremely poor is a very hard
problem but we can look at how well
we&#39;re doing by thinking about how well
we&#39;re doing building machines what you
can do what humans can do think about
the game of chess how what are we doing
determining what piece to move where if
we pick garry kasparov here when he&#39;s
not in jail against IBM&#39;s deep blue well
the answer is IBM&#39;s deep blue will
occasionally win and I think that IBM&#39;s
deeply played probably anyone in this
room it would win every time that
problem is solved what about the problem
of picking up a chess piece dextrous
they manipulating and putting that back
down on the board if we put a five year
old Charles dexterity against the best
robots of the day the answers very
simple the child wins easily there&#39;s no
competition at all now why is that top
problem so easy in the bottom problem so
hard one of the reasons is a very smart
five law could tell you the algorithm
for that top problem look at all
possible moves to the end of the game
and choose the one that makes you win so
it&#39;s a very simple algorithm now of
course a lot of moves but with fast
computers as an approximation become
close to the optimal solution when it
comes to being dexterous it&#39;s not even
clear where the algorithm is you have to
solve to be dexterous and we&#39;ll see you
after both deceive and act on the world
which has a lot of problems but let me
show you cutting-edge robotics now a lot
of robotics is very impressive but
manipulation robotics is really some the
dark ages so this is the end of a PhD
project from one of the best robotics
institutes and the student is trained
this robot to pour this water into a
glass is a hard problem because the
water slosh is about but it can do it
but it doesn&#39;t do it with any fact the
agility of a human now if you want this
robot to do a different task that&#39;s
another three-year PhD program there is
no
no generalization at all from one task
to another in robotics now we can
compare this to cutting-edge human
performance so what I&#39;m gonna share is
Emily Fox within the world record for
cup staffing now the Americans in the
audience will know all about cup
stacking it&#39;s a high school sport where
you have 12 cups you have to stack and
unstack against the clock in a
prescribed order and this is her getting
the world record in real time
and she&#39;s pretty happy we have no idea
what is going on inside her brain when
she does that and that&#39;s what we&#39;d like
to know so in my group what we try to do
is reverse engineer how humans control
movement and it sounds like an easy
problem you send a command down it
causes muscles to contract your arm or
body moves and you get sensory feedback
from vision from the skin from muscles
and so on
the trouble is these signals are not the
beautiful signals you want them to be so
one thing that makes controlling
movement difficult is for example
sensory feedback is extremely noisy now
by noise I do not mean sound we&#39;re using
the engineering on neuroscience sense
meaning a random noise corrupting a
signal so the old days before digital
radio when you were tuning in your radio
and you heard on the station you wanted
to hear that was the noise but it more
generally this noise is something to
corrupts the signal so if example if you
put your hand under a table and try to
localize it with your other hand you can
be off by several centimeters due to the
noise in sensory feedback similarly when
you put motor output on movement output
it&#39;s extremely noisy forget if I try to
hit the bull&#39;s eye and ask just aim for
the same spot over and over again you
have a huge spread due to movement
variability and more than that the
outside world or task was both ambiguous
and variable that teapot could be full
it could be empty it changes over time
so we work a whole sensory movement
tasks soup of noise now this noise is so
great that society places a huge premium
on those of us you can reduce the
consequences of noise so if you&#39;re lucky
enough to be able to knock a small white
ball into a hole several hundred yards
away using a long metal stick our
society will willing to reward you with
hundreds of millions of dollars
now what I want to convince you is the
brain also goes to a lot of effort to
reduce the negative consequences of this
sort of noise and variability and to do
that I&#39;m gonna tell you about a
framework which is very popular in
statistics and machine learning of the
last 50 years called Bayesian decision
theory and it&#39;s more recently a unifying
way to think about how the brain deals
with uncertainty and the fundamental
idea is you want to make inferences and
then take actions so let&#39;s think about
the inference you want to generate
beliefs about the world so what a
beliefs beliefs could be but where are
my arms and space am I looking at a cat
or a fox but we&#39;re gonna represent
beliefs with probabilities so we&#39;re
gonna rips into belief with a number
between 0 &amp; 1 0 meaning I do not believe
it at all 1 means that AB see certain
and numbers in between gives you the
gray levels of uncertainty and the key
idea to Bayesian inference is you have
two sources of information from which to
make your inference you have data and
data in neuroscience is sensory input so
I have sensory input which I can take in
to make beliefs but there&#39;s another
source of information and that&#39;s
effectively prior knowledge your cue leg
knowledge throughout your life in
memories and the point about Bayesian
decision theory is it gives you the
mathematics of the optimal way to
combine your prior knowledge with
sensory evidence to generate new beliefs
and I put the formula up there I&#39;m not
gonna explain to you what that formulas
but it&#39;s very beautiful and it has real
beauty and real explanatory power and
what it really says is what want to
estimate is the probability of different
beliefs given your sensory input so let
me give you an intuitive example imagine
you&#39;re playing tennis live play tennis
and you want to decide where the ball is
going to bounce as it comes over the net
towards you there are two sources of
information based rule tells you there&#39;s
sin through evidence you can use visual
information auditory information and
that might tell you it&#39;s real and that
red spot but you know that your senses
are not perfect and therefore there&#39;s
some variability where it&#39;s going to
land shown by that cloud of red
representing numbers between 0.5 and
maybe 0.1
sad information is available on the
current shot but there&#39;s another source
of information not available on the
current shot but only available by
repeated experience in the game of
tennis and that&#39;s what the ball doesn&#39;t
bounce with equal
for the court during the match if you&#39;re
playing against a very good opponent
they may distribute that green area
which is the prior distribution making
it hard for you to return now both these
sources of information
carry important information and what
Bayes rule says they should mark are the
numbers in the red by the numbers and
the green to get the numbers in the
yellow which have the ellipsis and
that&#39;s my belief so it&#39;s the optimal way
of combining information now I wouldn&#39;t
tell you all this if it wasn&#39;t a few
years ago we should exactly what people
do when they learn new movement skills
what it means is we really are Bayesian
inference machines as we go around we
learn about statistics of the world and
lay that down but we also learn about
how noisy our own sensory apparatus is
and then combine those in a real
Bayesian way now a key part to the
Bayesian is this part of the formula and
what this part really says is I have to
predict the probability of different
sensory feedbacks given my beliefs so
that really means I have to make
predictions of the future and I want to
convince you the brain does make
predictions of the sensory feedback its
going to get and moreover it profoundly
changes your perceptions by what you do
and to do it I&#39;ll tell you about how the
brain deals with Cynthia so you send a
command out you get sensory feedback
back and that transformation is governed
by the physics of your body and your
sensory apparatus but you can imagine
looking inside the brain and his inside
the brain you might have a little
predictor a neural simulator of the
physics of your body in your senses so
as you send the movie command down you
tap a copy of that off and run it into
your neural simulator to anticipate the
sensory consequences of reaction so as I
shake this ketchup bottle I get some
true sensory feedback as a function of
time on the bottom row and if I&#39;ve got a
good predictor it predicts the same
thing well why would I bother doing that
I&#39;m gonna get the Cynthia feedback
anyway well there&#39;s good reasons imagine
as I shake the ketchup bottle someone
very kindly comes up with me and taps it
on the back for me now I get an extra
source of sensory information due to the
external act so I get to sources I get
you
tapping on it and I get me shaking it
but for my senses point of view that is
combined together into one source of
information now the good reason to
believe that you would want to be able
to distinguish external events from
internal events because external events
are actually much more behaviour elevant
than feeding everything that&#39;s going on
inside my body so one way to reconstruct
that is to compare the prediction which
is only based on your movie commands
with the reality and any discrepancy
should hopefully be external so as I go
around the world I&#39;m making predictions
of what I should get subtract them off
everything leftover is external to me
what evidence is there for this well
there&#39;s one very clear example where a
sensation directed by myself feels very
different than though generated by
another person and so we decided the
most obvious case of start was with
tickling it&#39;s been known for a long time
you can&#39;t tickle yourself as well as
other people can but it hasn&#39;t really
been shown it&#39;s because you have a
neural simulator simulating your own
body and subtracting off that sense so
we can bring the experiments in the 21st
century by applying robotic technology
for this problem and effective what we
have is some sort of stick in one hand
attached to a robot and they&#39;re going to
move that back and forward and then
we&#39;re going to crack that with a
computer and use it to control another
robot which is going to tickle their
palm with another stick and we&#39;re gonna
ask them to rape a bunch of things
including pictures actually just one
part of our study and here I&#39;ve taken
away the robots but basically people
move with their right arm sinusoidal
back and forward and we replay that to
the other hand with a time delay either
no time delay in which case light would
just dip in your palm or with a time
delay over ten to ten or three tenths of
a second so the important point here is
the right hand always does the same
thing sinusoidal movement the left hand
always its same input sinusoidal tickle
all playing with is a temporal causality
and as we go from naught to point one
second it becomes more ticklish as we&#39;re
from point one to point two it becomes
more tips again and by 0.2 of a second
it&#39;s equivalently ticklish to the robot
just typically without you doing
anything so whatever is responsible for
this pencil ation is extremely tightly
coupled a temporal causality and based
on this other studies we really
convinced ourselves in the field that
the brain is making precise
predictions and subtracting them off
from the sensations now I have to admit
these are the worst studies my lab has
ever run because the tickle session the
palm comes engaged with large numbers of
subjects at these stars making them
significant so we were looking for a
much more objective way to assess this
phenomena and in the intervening years I
had two daughters and once the news
about children on back seats of cars on
long journeys
they&#39;ve get into fights which started
with one limiting something to the other
the other than retaliation that quickly
escalates and children can&#39;t identify
its which escalate in terms of force now
when I scream at my children to stop
sometimes they would both say to me the
other person hit them harder now I
happen to know my children don&#39;t lie so
I thought was a nurse and it was
important how can I explain how they
were telling inconsistent truths and we
had pot size based on the tickling study
that when one child hits another they
generate the movement command they
predict the sensory consequences and
subtract it off so they actually think
they fit the person less hard than they
have rather liked the tickling where&#39;s
the passive recipient doesn&#39;t make the
prediction fuels the full blow so if
they retaliate with the same force the
first place more thinkers mean escalated
so we decided to test this in the lab
now we we don&#39;t work with children we
don&#39;t work with hitting but the concept
is identical we bring in two adults and
we tell them they&#39;re gonna play a game
and so his player 1 and player 2 sitting
opposite each other and the game is very
simple we started with a motor with a
little leave and little force transducer
and we use this motor to apply a force
down to the player ones fingers for
three seconds and then it stops and
that&#39;s players being told remember the
experience with that force and use your
other finger to apply the same force
down to the other subjects finger
through a force transducer and they do
that and player two&#39;s been told remember
the experience of that force use your
other hand to apply the falls back down
and so they take it in turns to apply
the force they&#39;ve just experienced back
and forward but critically they&#39;re
briefed about the rules of the game and
separate rooms so they don&#39;t know the
rule that other person is playing by and
what we measure is the force as a
function of turns and if we look at what
we start with a quarter of a Newton
there a number of turns
perfect would be that red line and
we see in all pairs of subjects is this
a 70% escalation and force on each go so
it really suggests when you&#39;re doing
this basically studying others we&#39;ve
done that the brain is canceling the
sensory consequences and under
estimating the force its producing so
release shows the brain makes
predictions and fundamental changes for
persons so we&#39;ve made inferences we&#39;ve
done predictions now we have to generate
actions and what Bayes rule says has
given my beliefs the action some sense
be optimal but we&#39;ve got a problem
tasks a symbolic I want a drink I want a
dance
but the movement system has to contract
600 muscles in particular sequence and
there&#39;s a big gap between the task and
the movement system so it can be briefed
and infinitely may different ways to
think about just the point the point
movement I could choose these two paths
and have infinite number of paths having
chosen a particular path I can hold my
hand on that path was instantly made
different joint configurations and I can
hold my arm to particular joint
integration but they&#39;re very stiff or
very relaxed so I have a huge amount of
choice to make now it turns out we are
extremely stereotypical we all move the
same way pretty much and so it turns out
we&#39;re so stereotypical our brains have
got dedicated neural circuitry to decode
this therapy so if I take some dots and
set them in motion with biological
motion your brains have circularly doing
understand instantly what&#39;s going on now
this is a bunch of dots moving you will
know what this person is doing with a
happy sad old yarn a huge amount of
information if these dots were cars
going on a racing circuit you would have
actually no idea what&#39;s going on so why
is it we move the particular ways we do
well let&#39;s think about what really
happens maybe we don&#39;t all quite move
the same way maybe there&#39;s variation in
the population and maybe those who move
better than others have got more chance
in your children into the next
generation so an eeveelution rescales
movements get better
perhaps through life movements get
better through learning
so what is it about a moon which is good
or bad imagine I want to intercept this
ball here are two possible paths to that
ball well if I choose the left-hand path
I can work out the forces required in
one of my muscles of the function of
time but there&#39;s noise added to this so
what I actually get basically the lovely
smooth desired force it&#39;s a very noisy
version so I played the same command
through many times I will get a
different noisy version each time
because noise changes each time so what
I can show you here is how the
variability the movement will evolve if
I choose that way if I choose a
different way of moving on the right for
example then I&#39;ll have a different
command different noise playing through
a nonlinear system very complicated all
we can be sure us is the variability
will be different if I move in this
particular way I end up with a smaller
variability across many movements so if
I choose between those two I would
choose the right one because it&#39;s less
variable and the fundamental idea is you
want to plan your movement so as to
minimize the negative consequence of the
noise and one intuition to get is that
actually the amount of noise or
variability as I show here gets a bigger
as the force gets bigger so you want to
avoid big forces as one principle so
we&#39;ve shown that using this we can
expend a huge amount of data that
exactly people are going about their
lives planning movements so as to
minimize negative consequences of noise
so I hope I&#39;ve given to you brain is
there and evolved to control movement
and it&#39;s an intellectual challenge to
understand how we do that but it also is
relevant for disease and rehabilitation
there are many diseases which affect
movement and hopefully if we understand
how we control movement we can apply
that to robotic technology and finally I
want to remind you when you see animals
do what I look like very simple tasks
the actual complexity of what&#39;s going on
aside their brain is really quite
dramatic thank you very much
question two though so you&#39;re you&#39;re a
movement chauvinist
does that mean that you think that the
other things that we think our brains
about the kind of the dreaming the
yearning the falling in love and all
these things are a kind of sideshow and
accident never accident I think they&#39;re
all important to drive the right movie
behavior to get reproduction of them so
I think I think people who study
sensation or memory without realizing
why you&#39;re laying down memories of
childhood that&#39;s that we forget most of
our childhood for example it&#39;s probably
fine cuz it doesn&#39;t affect our movements
later in life you only just store things
which are really gonna affect movement
so you think that people thinking about
the brain and consciousness generally
could get real insight by saying where
does movement play and you&#39;re scared so
people have found out for example that
the studying vision and the absence of
realizing why you have vision is a
mistake you have to study a vision with
the rise ation of how the movement
system is going to use vision and it
uses it very differently once you think
of it that way well that was quite
fascinating thank you very much indeed
