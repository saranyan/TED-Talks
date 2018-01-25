
okay well thank you so much so so so I
study the capabilities and also the
limits of quantum computers I like to
call it the study of what we can&#39;t do
even with computers that we don&#39;t have
so as a result I&#39;m sometimes asked say
by the person sitting next to me on the
plane you know so what is this quantum
computer so I say well it&#39;s a proposed
new kind of computer that would exploit
quantum mechanics so then we said well
why well you know quantum mechanics it&#39;s
sort of the basic operating system that
the rest of physics runs on as
application programs you know it&#39;s
hasn&#39;t changed at all since the 1920s
and it ought to let we think let us
solve certain problems dramatically
faster than we know how to solve them
with today&#39;s computers so then they say
well well why does quantum mechanics let
you solve things faster and you know it
is possible to explain that to a lay
audience right it&#39;s definitely the only
problem is that you know once you&#39;ve
really gotten started explaining it you
know by then the plane has already
landed okay so so it&#39;s no surprise that
for more than twenty years you know
almost every popular article that&#39;s ever
been written on this subject has taken
an easy way out you know and it&#39;s
described quantum computers in ways that
sound cool but are just kind of wrong
and you know I you know people correctly
recognize I think just you know how
important this is going to be for the
future of science and technology but
it&#39;s a sad way you know one of the the
most missed popularized topics in
science so I was delighted when I was
invited here to Dresden specifically to
talk about what quantum computing is not
okay so
the so the first thing that it&#39;s not I
guess is whatever this is when you when
you do a google image search for quantum
computer that&#39;s one of the first things
that come up now I&#39;m I&#39;m a theorist you
know I don&#39;t work in a lab but I don&#39;t
think that&#39;s what they look like so okay
but more to the point
people say well quantum means small so
how many times smaller is a quantum
computer than today&#39;s computers or well
it&#39;s supposed to be faster so how many
times faster is it okay but a quantum
computer is not just a smaller or faster
version of today&#39;s computers it
represents a fundamentally new way of
harnessing nature to do computation so
for certain problems you know adding up
numbers simulating the weather a quantum
computer may help you little or not at
all for other problems a quantum
computer could do things in seconds that
as far as we know would take any
existing computer longer than the age of
the universe okay so it all comes down
to asymptotics okay so you know what are
you know the famous examples of problems
where a quantum computer gives you these
huge speed ups or pretend well one of
them is simulating quantum mechanics
itself no surprise that a quantum
computer helps you there but you know I
think if we actually build one that that
may actually be the most important
economic application because you know
that is useful for designing new drugs
designing high-temperature
superconductors designing nano materials
you know better solar cells all kinds of
things
the second famous application is that a
quantum computer could efficiently find
the prime factors of an enormous
positive integer all right well who
cares about that well that and some
related problems would let you break
almost all of the cryptography that we
used to protect our data
online okay anytime your web browser you
know has that little padlock icon you
are using something that a quantum
computer could break okay you know there
are there are other codes that we don&#39;t
know how to break even with a quantum
computer but those are mostly not the
ones that we use today so so so you know
a you know if you want to factor you
know in an end digit number right the
best algorithms that we know with
classical computers use a number of
steps that increases exponentially with
n okay an exponential is a function like
this 1 2 to the N power which just kind
of shoots up and just goes off the slide
out of the building okay but you know
multiplying 2 n digit numbers is a lot
easier your computer can do that using
only about N squared steps or if you&#39;re
more clever even close to a linear and n
number of steps okay now what a quantum
computer would do is it would put
factoring into that easy class so
factoring also would only take about N
squared steps for an N digit number okay
so the advantage over a classical
computer is not by some fixed factor but
just becomes more and more enormous as
you go to larger and larger numbers
until there&#39;s just no comparison okay so
as I&#39;ve already indicated you know a
quantum computer is not this magic
bullet that just solves all problems
instantly you know it depends on the
problem okay so in computer science we
like to organize problems into a sort of
zoo so so at the bottom we&#39;ve got P that
stands for polynomial time you know
physicists give things much better names
okay
quark black hole but yeah ignore that
okay P is basically all of the problems
that are efficiently solvable by an
ordinary digital computer like the one
in your pocket ok n P stands for
non-deterministic polynomial time that&#39;s
the set of all the problems for which
you&#39;re a digital computer could at least
quickly wreck
nice an answer when given one okay but
finding the answer might require an
astronomical search okay
so P you know includes most of what we
do with our computers you know
multiplying sorting finding directions
with Google Maps NP has many many things
we would love to do and especially these
np-complete problems which are the
hardest problems in NP and that includes
you know almost everything and like
industrial optimization you know a
finance you know trying to predict the
stock market let&#39;s say trying to you
know uh optimize an airline schedule
playing Sudoku
so so you know one of the great unsolved
problems of mathematics in this century
you know is to formally prove that that
NP is larger than P okay you know if we
were physicists we would have just
called that a law of nature okay but you
know what physicists call a law you know
we in math have to call conjecture okay
so so now BQ P stands for bounded our
quantum polynomial time and that&#39;s the
class of all the problems that are
efficiently solvable by a quantum
computer so the quantum generalization
of P okay I drew it with this wavy
boundary because you know everything
quantum is spooky and weird and you know
so that so the so the big surprise was
that bqp contains a few problems like
factoring the special problems that are
not neither known nor believe to be in P
okay but as you can also see from this
picture you know bqp is not known or
believed to contain the np-complete
problems okay can we prove it doesn&#39;t
well no we can&#39;t even prove that P
doesn&#39;t contain them okay but that would
require a quantum algorithm radically
unlike any of the ones that we know okay
so for np-complete problems you know
quantum computers seem to give you some
advantage like a square root kind of
advantage but probably not an
exponential one okay so even quantum
computers have limits okay but where do
those
limits come from well you know if you
read almost any popular article on this
subject it&#39;ll say something like well
unlike a classical computer which just
has to try every possible answer one by
one a quantum computer just tries them
all in parallel in different parallel
universes and you know and well you know
that does sound pretty powerful right
you know that does sound like that would
crack the np-complete problems or
whatever else okay
the trouble is you know alas it&#39;s not
that simple okay and here&#39;s what the
issue is okay in quantum mechanics you
can actually quite easily create what we
call a quantum superposition over all
the possible answers to your problem
even if there are astronomically many of
them okay the trouble is if you want it
to be useful at some point you&#39;ve got to
observe your computer you know to read
an answer out okay and if you just
measure you know the superposition of
all answers not having done anything
else the laws of quantum mechanics say
that what you&#39;re going to see will be a
random answer okay well if you just
wanted a random answer then you could
have picked one yourself with a lot less
trouble okay
so so then you know when people hear
that they say oh well then it must be
that the quantum computer is just trying
one solution or the other one and we
simply don&#39;t know which until we look
okay like you know we&#39;ve you ever heard
about Schrodinger&#39;s cat right here&#39;s a
oh it&#39;s in a superposition of alive and
dead states in the Box you know until
you open the box and look and then it
collapses to one or the other right well
now you know any ten-year-old who hears
that right is gonna immediately ask well
why isn&#39;t that just a fancy pompous way
of saying well the cat is either alive
or it&#39;s dead and you don&#39;t know which so
then you open the box and you look and
then you do know you know so then what&#39;s
the big deal about quantum mechanics all
right well it&#39;s not that simple
so you know the central thing that
quantum mechanics says about the world
is that if you have an object that could
be in two different distinguishable
States it can also be in what we call a
superposition of those states a
superposition means I assign a number
an amplitude to each possible state now
in everyday life we could talk about the
probability of something happening right
but a probability is always a real
number from 0 to 1 right you never
there&#39;s never a negative 30% chance of
rain tomorrow that&#39;s just you know
stupid ok but amplitudes can be positive
or negative in fact they can even be
complex numbers ok and everything else
arises from that okay so in the famous
double slit experiment you have a photon
that could reach a certain spot on a
screen in two different ways okay but
one of those ways contributes a positive
amplitude and the other way contributes
a negative amplitude and the result is
that they interfere destructively and
cancel each other out so that the photon
has never seen there at all okay so you
know the amplitudes are used to
determine the probability that you&#39;ll
see something when you look but when you
don&#39;t look they can interfere okay so
and the with a quantum computation the
goal is always to choreograph things so
that for each wrong answer some of the
paths leading there have positive
amplitude and others have negative
amplitude so they cancel each other out
whereas the paths leading to the right
answer should reinforce you know be all
have the same sign you know and then
when you measure the right answer will
be seen with high probability so that&#39;s
the strange hammer that quantum
mechanics gives us and you know the goal
of quantum computing theorists is
basically to figure out what nails that
can hit okay so you know quantum
computing as you&#39;ve probably gathered by
now is not just some random buzzword to
be added like a seasoning onto whatever
is your tech startup idea you know it
helps a lot with certain things you know
and and less with others and you know
figuring out which is which has been a
you know a fascinating a challenge okay
but the other thing that quantum
computing is not is it&#39;s not science
fiction okay so what I&#39;ve shown here is
a
ship that recently was recently built by
a group at Google and this has a bunch
of very high quality interacting a
superconducting quantum bits or qubits
so systems that can be in a
superposition of states representing 0 &amp;
1
okay Google&#39;s current chip has about
twenty two qubits but they say that
within the next year they are planning
to scale up to 49 qubits
okay and there are other groups in
Innsbruck Austria and IBM in a Maryland
that are than have parallel efforts with
all kinds of physical platforms now 50
cubits is probably not enough yet to do
anything useful okay but it should be
enough we think to do something that at
least is classically hard okay so you
know so so already within a few years we
may achieve what I think of as the
number one application of quantum
computing which is just to disprove the
people who say that it&#39;s impossible okay
now you know could could it be
impossible for some deep reason that no
one has figured out yet well of course
but in some sense that&#39;s the more
exciting possibility okay because that&#39;s
the possibility that means that we have
to rewrite all the physics textbooks
okay at this point I think the idea that
yes eventually with enough money and
effort you could build a quantum
computer and it will work as this theory
says and give huge speed ups for certain
things that&#39;s the boring conservative
possibility okay that&#39;s the one that
doesn&#39;t require changing what we what we
already believe about physics okay
so embrace the future you know I&#39;m not
you know typically a huge fan of these
slogans that kind of everyone agrees
with but you know I&#39;m coming here from
the US I don&#39;t know if any of you have
been reading in news for the last year
or so but you know not everyone in the
US has been you know totally into
embracing the future which is kind of a
pity I
yeah I&#39;m sorry about that but I so I do
think that we should embrace the future
but if we want to do that I think a
crucial first step is to accurately
learn and report what&#39;s already known in
the present thank you
[Applause]
