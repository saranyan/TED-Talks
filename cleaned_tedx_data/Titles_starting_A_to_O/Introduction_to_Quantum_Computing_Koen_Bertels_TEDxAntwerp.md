
the wonderful world of quantum computing
that&#39;s basically what I would like to
talk about and if I can yeah use this
device would be would be great what you
see is
I&#39;m cheap that we&#39;ve started developing
in India no okay sorry in Delft with my
colleague Leo DeCarlo
he sounds Italian but it&#39;s actually
Argentinean and with whom I&#39;m working
very intensively with the two teams that
we have to actually build a first
prototype of a quantum computer and I
will hopefully explain a little bit in
detail what we understand by that so
let&#39;s let&#39;s start by looking at a
classical machine yeah and here we see a
diagram which which is being drawn by by
someone where we have memory and
processor and we have instructions in
memory residing and of course we
transport now instruction after
instruction into the processor and we we
decode the instruction which is an
addition then we get the operands so
that 3 and the 6 in this case from
memory and we put them again in the
local register we compute the result and
we write back you know the result which
again in this place will be in the same
location as where I retrieved the 3
because that&#39;s what my instruction is
actually telling me how it should be
done so this is how in principle every
single computer yeah what size and and
when it was built basically works and I
will try to explain a little bit what
happened also let&#39;s say in the last 22
maybe even 50 years and it&#39;s it we see a
clear trend in downsizing of the
technology so that it&#39;s yep
yeah as long I have to look around
because I don&#39;t know what you know it&#39;s
already then I&#39;m sorry for this so I see
I see that my scale is going up to the
nanometer cell so 1 1 nanometer is 10 to
the minus 9 divided by 1 meter so that
that&#39;s pretty small and we see here that
the compute power which we hold in our
hands which can be an iPad or or your
smartphone or whatever has more compute
power than let&#39;s say supercomputers 20
30 years ago so that&#39;s kind of the trend
we see in technology happening still
today yeah we all know about Moore&#39;s law
that&#39;s gonna end I will not explain
about that but Intel says no it&#39;s not
going to end it will end when we don&#39;t
have any ideas anymore and that&#39;s
basically what we try to explain
today so at the far right you see Adams
and that&#39;s indeed the scale at which
we&#39;re using technology these days this
is the scale at which we are developing
things and even in quantum computing I
will tell a little bit more later on
yeah we&#39;re using single electrons for
instance to represent one which we call
a qubit but I will explain that in in a
couple of minutes so where is this what
kind of philosophy or yeah scientific
discipline are we are we basing
ourselves on is there evidently physics
and I see here I show here three
prominent physicists that you may well
for sure you you&#39;ve recognized Einstein
because he already mentioned once or
twice I think in previous talks yeah and
we see the guy on the right which is
Niels Bohr he says he&#39;s a Danish
physicist and he lived more or less in
the same time period as Einstein and but
the scale at which they were reasoning
the phenomena that they were looking at
is completely different so I&#39;m Stein you
had the relativity theory and those
kinds of things is about gravity and
interaction between planets or large
large scale phenomenon and Niels Bohr
was more let&#39;s say at the sub atomic
scale and he said but those those
concepts do are not applicable yeah at
that level and because quantum and
that&#39;s quantum physics there is a
fundamental principle which is
randomness and I will I will explain a
little bit later on and that&#39;s also why
Einstein says now God does not play dice
because he could not he could not
imagine that if there is something like
a god yeah that he would he would assume
that there is some random behavior in in
nature yeah and therefore also in in
human in human beings and the third
person at the bottom is Richard Feynman
and he&#39;s he&#39;s an American he was one of
the the most brilliant physicist that
died I think that lived at least in the
20th century and there were quite a
number yeah off of them and he is
actually the initiator he was the one
who formulated in 1982 so that&#39;s
basically around six years before he
died he said we should build a quantum
computer which is based on this quantum
phenomena that we want to understand in
a very deep way and therefore he he was
proposing that
we should look at the technology and
think about how to build a a device a
computational device and I will I will
explain those those concepts a bit more
if I can switch to the next light which
I can yeah
so what is what makes quantum computer
so special and I and I hope to give you
at least an intuition a profound
understanding that&#39;s maybe very
difficult because I still have to find
actually the first person that really
understands at that level yeah how it
works so we are more intuitive in into
in intuitive reasoning rather than very
analytical so what makes these these
quantum computers so so special well
again let&#39;s let&#39;s go back to how
machines that we have in our daily life
that are filled in your car yeah that
you have on your on your on your wrist
most likely or in your pocket your
smartphone or whatever it is they are
all based on bits zeros and ones and
then we can combine these bits in
multiple sequences so that we can
represent bigger numbers yeah or we can
represent like huge text on which we can
then apply all kinds of algorithms and
algorithms are like the standard
protocols or their little programs yet
that describe what should be done at
each step in the in in the algorithm so
that&#39;s what what classical bits are now
when we move into the into a completely
different world namely the quantum
physical world we have to look at
completely different phenomena and I&#39;m
just mentioning here the three that are
really key and really fundamental and
extremely difficult to make on a large
scale and I will maybe not explain
everything but this is this is really a
big challenge so it&#39;s super position
measurement and entanglement and I will
explain those three in the next coming
minutes so here you have a little
animation from it a kinetic where I have
let&#39;s say an electron that is now in the
ground state and now it&#39;s in an excited
state so you see the energy levels they
move discretely between low and high and
now it&#39;s in the super positions because
you see the two levels are activated and
indeed this electron in this is in these
two states at the same time now I have
an observation and there&#39;s
so when the eye opens one of those two
superposition states actually disappears
and that&#39;s actually where the randomness
comes from yeah and this is really key
because that means that when you build a
quantum computer you basically move away
from what we what we know classically
which is very deterministic very
classical when you do the same algorithm
and the same data you execute it a
thousand times you will get thousand
times exactly the same results in
quantum this is not true and I will
explain that in in a couple of minutes
so we use qubits as I already said so we
don&#39;t use these classical bits because
they don&#39;t have this superposition and
entanglement property that we need in
order to to compute so we have these
qubits which can be in a combined state
so it can be 0 and 1 at the same time so
classically it&#39;s either a 0 or a 1 or
any combination of those but it&#39;s always
in an exhaustive yeah state of a of one
single combination of zeros and ones in
quantum physics you know this is
absolutely not true
so what I see here is on the left the 0
part which is let&#39;s say the right arrow
the the red arrow is pointing above and
the 1 state is the the red arrow
pointing pointing below and then you can
have any position in between which is
the superposition state and then
depending on what I&#39;m going to how my
algorithm is computing what it actually
is doing it is manipulating what I&#39;m
showing you know is from behind it that
the projection shows I&#39;m sorry so what
it what we do in in a quantum algorithm
is that we influence the alphas that we
see there that alpha 0 in the alpha 1
and in principle what it means is that
alpha 0 in a way represents the
probability when I do the measurement
then the superposition disappears then
at what with what probability am I going
to get a 0 and with what probability do
I get a 1 that&#39;s what those alphas
actually mean and so all of the quantum
algorithms and so now I will show you
that it can be the 1 so that the Alpha 1
is bigger than the alpha 0 yeah then you
will when you measure it you will
measure the 1
results now assume that I have here 80%
white and 20% black so that means I have
to execute my algorithm multiple times
so that then I can aggregate all of the
results and then I can simply count what
result gives me most is computed in most
of the cases and that&#39;s going to be the
final result of your quantum algorithm
and that&#39;s why we call it it&#39;s a non
deterministic computing reverse due to
classical computing so I will briefly
say something then about the the two
other phenomena which is measurement as
I already explained it basically means
that when I when I&#39;m in a superposition
state yeah and I will measure it I&#39;m
gonna force it into either the 0 or in
the 1 state always we have not yet
figured out a way to overcome that and
maybe in 20 30 40 50 years maybe we will
but for now we don&#39;t yeah so that is
that is that is where this
non-deterministic element comes from and
then the third property is entanglement
and that&#39;s also a very crucial way of
combining these qubits because the qubit
that is in the superposition state
basically has two states as two values
namely the 0 and the 1 and if it&#39;s 50/50
then then it can you can you can get any
kind of result at any point in time by
measuring but you can never predict when
it&#39;s 8020 then you know that in 80% of
the cases you will get the 0 and the 0
case it for instance this case so the
entanglement is again I&#39;m combining two
qubits they&#39;re in a superposition here
yeah so I basically have when I combine
two qubits I have four positions and if
I have 3 it&#39;s 2 to the power 3 I cannot
show that with my with my fingers yeah
but you have eight different states
that&#39;s what 2 to the power 3 so 2 by 2
by 2 right means so this and then the
entanglement is a way of combining them
and then when you when you apply
whatever quantum algorithm on such an
entangled state then you apply it at all
of those combinations at the same time
yeah it&#39;s not only about the
entanglement there but this is this is
really key so I will briefly show you
yet to give you a little bit of an idea
where the compute power now possibly
comes from because yeah sure now that
depends on how many qubits you will have
and whatever it is yeah but if I give me
five five or ten supercomputers I can do
the same well this is not true and I&#39;ll
give you an example later on so here I
plot the graph of having two three up to
ten cubits combined and then you see
here these are 10 yeah 2 to the power 10
combinations so parallel States and what
quantum physics is giving me is giving
me massive parallelism for free and the
for free should be taking a little bit
of yeah salt because there&#39;s no free
lunch here either but that&#39;s that&#39;s the
principle idea that we&#39;re that we&#39;re
using and why is that important because
if I didn&#39;t execute any quantum gate and
I will show one simple example on those
on this matrix I am I apply all that
particular gate on all of those states
at the same time in one shot whereas in
a classical machine I would have to do
it sequentially yeah and two to the
power 100 that&#39;s already a big number so
it&#39;s sequential versus massively
parallel that&#39;s what it that&#39;s what it
means that also implies that if I&#39;m
actually building a new machine and I
want to build said okay I&#39;m gonna make
it more powerful because I need to have
more data that I need to process what I
need to do is simply add one more qubit
because b by adding one more qubit it&#39;s
2 to the 2 to the 3 to the 4 to the n n
plus 1 I each time double the entire
number of superposition states that I
can manipulate at any point in time so
that&#39;s what the the theory of course
tells us right in the and we have to
work on building a machine which is
capable if we&#39;re if I have let&#39;s say 300
which was the point on the far right of
this graph if I have 300 of those let&#39;s
say perfect qubits I can represent more
data than there are atoms in the known
universe just just think about how big
such such a huge amount of data would be
so that&#39;s why I showed this this little
yeah universe picture
now let&#39;s let&#39;s start and talk a little
bit about how to build a a quantum
machine so just like classically we have
to build transistors yeah and the
transistors we combine yeah in
particular ways well we have to do the
same thing physically we have to work on
making those qubits and we have to make
sure that these qubits are stable and
live long enough in time yeah because
we&#39;re here yeah there&#39;s this one
Austrian and Italian working in
Australia and he was capable of making
one qubit yeah in silicon 20 in 28
silicon whatever that is and it could
live for five seconds it was incredible
and how can you make to know maybe three
no okay so he doesn&#39;t know it has no
clue how to scale this up and most
likely that&#39;s the direction that we are
basically not looking at so in Delft
yeah because I&#39;m I&#39;m Flemish but I work
already for quite some time in in the
Netherlands yeah we were basically on
quantum dots NV centers semiconductors
and superconductor kind of technology we
do not work on on ion traps which was
very popular and is still very popular
especially in the US but we don&#39;t we
don&#39;t have anybody in Delft doing that
and I personally am more on the quantum
dots and and the superconducting qubits
now how do you start doing such a work
because I&#39;m a classical engineer yeah
I&#39;m a computer engineer so I&#39;m used to
building machines and and then we had we
had the the the request from the rector
yeah of our university said yeah but we
start anew if we start a new research
center called qt you have quantum
technology whatever is in the name yeah
and I want I want you from that faculty
from the electrical engineering faculty
to be responsible for yeah making the
architecture actually ok quantum physics
yeah do I know anything yeah the basic
principles like I just explained and
then then I started looking at ok I have
to start somewhere and the first drawing
I made was actually this one was not
that that sophisticated as I was it here
right it was just with pen and on paper
and this is a system stack of a
classical machine and I said well if I
simply write the Q in front of each
layer maybe
good enough yeah well turns out so far
this is the case yeah this is the case
yeah well we can be proven wrong yeah
and then I will come here and say I was
completely wrong excuse me for that yeah
but for now this really seems to be yeah
the keypad and turns out yeah just it&#39;s
a little bit of off of no I don&#39;t know
so turns out that Intel was at some
point every four five years this
American that you most likely know yeah
revises its roadmap technology roadmap
and quantum was always out there&#39;s an
added sewer that is too early yeah we&#39;re
absolutely not interested yeah it hasn&#39;t
it hasn&#39;t matured in any particular way
yeah until until the last time and this
was like three years ago there was a guy
Jim Clark yeah I can mention his name
now right he was traveling all over the
world literally all over the world
visiting every single research lab
working on quantum technology quantum
computing and that means you know the
Ivy League universities in India Wes
right from MIT Princeton Stanford those
kind of things to Australia to Canada
all over Europe and he also came at some
point to TU delft and they asked me
together with my colleague around the
shop oh hey can&#39;t you guys say something
about quantum computing now happens to
be this is a little bit of interior
information three weeks before we were
completely killed because of this idea
by our my own rector by by a physicist
say like what I helped are you doing go
back to your office and think again and
come back so we say that what sorry
we&#39;re gonna sorry gonna bring to Intel
and I said you know what
we don&#39;t know anything else we&#39;ll just
give this one yeah
and remember what happens they said no I
was gonna say dirty word survivor I have
to filter myself sometimes right said
like we are we have never heard this
story I&#39;ve been traveling to every
single research lab in the u.s. in
Canada in Australia in Europe and this
is the only place where I get a
systematic and a coherent view on how to
build a quantum computer language so and
that was a start that was a start now
I&#39;ll show you yeah vanity of course has
its price so I&#39;ll show a little picture
yeah where we started actually working
with with the Intel people so again the
system stack we have and then you have
to again start at the lowest bottom so
the dark blue the point that you saw was
basically where all the physicists
anywhere in the world are working yeah
okay time is out okay so this is a this
is a this is a quantum circuit so on the
right you see yes you&#39;re right yeah you
see a quantum circuit consisting of a
couple of operations that classically
you do not really use and that&#39;s fine we
know how to use them and that&#39;s I think
for now the most important part then we
came up
this was also a drawing that I showed
this Intel person I said yeah I think we
need all of these things and again the
little box the pink box on the on the
right is where the physicists are so
that&#39;s 99% of the people that are
working on it or in just this this pink
box box at the at the right and we do
everything else yeah and and well
actually that&#39;s that&#39;s a team in in
Delft that that is working on that and
so you have to define also you need to
you need to have programming languages
you need to have algorithms of course so
you need a language you need a compiler
you need you need to build all these
things you need to have a
microarchitecture and again as you can
see we&#39;re working on three different
kinds that I&#39;m currently working on all
three different kinds of physical
technologies and so we have prototypes
at least this year for the for the spin
qubits and the trans months
yeah we&#39;re not so good in making
publicity so maybe being here today is a
good is a good exercise yeah and this is
my team that works on all of these
aspects that I&#39;ve been that I&#39;ve been
telling you the people at the bottom are
our PhD students at the top are our
postdocs or assistant professors and and
and the old guy on the left is that
that&#39;s me yeah and then who else is
working on as I said already it&#39;s it&#39;s
huge it&#39;s a pretty big field these days
and so yeah on the right you see the
American companies we know Microsoft was
on if you if you read the red except in
ba I don&#39;t know whether you do that yeah
I do that from time to time
and when they were thirsty much like
Microsoft is busy announcing the big
quantum computer uh-huh
yes it like we&#39;re running behind it&#39;s
absolutely not true right
so the most famous one is maybe d-wave
which is a Canadian company and they
claim to have already more than 2000
cubits is it in a powerful no my laptop
run smarter than there than their
quantum machine oh and here you do see
the picture of Intel when we started
yeah that&#39;s I&#39;ll just now what are we
yeah yeah I&#39;m running a bit late but I
think that&#39;s fine right
because the people listening to me said
yeah but you have to talk much more
about what are you gonna do with it so
this is the part that I will insist on a
little bit right so what why do you need
quantum computers yeah I will no of
course the compute power now allow yeah
we believe you yeah sure that&#39;s
fantastic but how are we gonna use that
yeah my my the language that you develop
wow great yeah but what kind of problems
and then you see an entire domain yeah
and the big data is a big is a big field
right I mean big data they slap us
around the years with big data every day
yeah and and and we don&#39;t have solutions
for that well wait until we have a
quantum computer of course yeah now what
I personally believe and I will not go
into too much detail but I personally
believe and we start working it we
started working on this already now is
working on what is in the top left you
know what is in the in chemical in
chemical applications and mostly yeah
what we what we start now is on genome
sequencing genome sequencing what I feel
you&#39;re talking about physics and now
it&#39;s only biology again right but genome
sequences is the future of medicine so
whatever is going to happen let&#39;s say in
ten years when you go to your physical
doctor yeah it&#39;s gonna take a bit of
blood or whatever and he will send you
through a such a such a sequencing
machine and then it needs to be analyzed
now this is billions billions of bytes
that you need to process so it takes for
one person yeah it takes a very very
powerful computer network for more than
a week for one person to do one analysis
so that&#39;s that&#39;s one one thing that we
think is is an important application
domain so just to give you another
example in then I will really wrap it up
yeah is is is this one is about
factoring a large number and that this
is something that we all use on a daily
basis whenever you contact your bank
yeah it&#39;s basically in an encrypted way
so that means that the day that you
don&#39;t send zeros and ones you send them
in an encrypted way and the encryption
basically boils down to decode finding
the the prime numbers yeah when you
multiply all those prime numbers it
gives you your big number and that&#39;s
kind of the key
yeah to do it so again if I&#39;m assuming
that I have the most powerful
supercomputer which is Chinese by the
way right at the chancre here and I can
build a data center the size of Germany
and the Netherlands so that&#39;s around
four hundred thousand square kilometers
yeah and just assume that every single
meter is filled with this the
supercomputer it&#39;s still gonna take me
let&#39;s say about a hundred years a
trillion euros and basically it can
never work but it&#39;s going to consume so
much power that the earth is running out
of energy in one month so that&#39;s not
something you can actually see as a
realistic approach now if I can build a
quantum computer yeah and look at the
five billion cubits
you know the physicists they&#39;re very
proud they&#39;re at 7 and 17 yeah so going
to five billion is still quite a way to
go but in principle at that size with
the factoring the Shor&#39;s factoring
algorithm it should be done in a bit
more than a day so just to give you an
example from 100 years yeah which is in
consumer with in consumable amounts of
energy you can downsize it to two to one
day and it really uses much much less
energy I did not insist on that yeah
because I am already running out of time
I will be very short here in the
conclusion yeah that of course there are
a number of huge challenges that we
still need to overcome and and scaling
it up is actually the biggest one yeah I
can I can for maybe I can make seven
cubits nine cubits 17 yeah and they&#39;re
always like odd numbers so don&#39;t ask me
about those odd numbers but yes they are
all odd numbers yeah but yeah the the
potential benefits of building such a
machine are so huge that I personally
think in many people you know that the
investment is really worth worth the
effort thank you very much
[Applause]
