
So I want to talk today about an idea. It&#39;s a big idea.
Actually, I think it&#39;ll eventually
be seen as probably the single biggest idea
that&#39;s emerged in the past century.
It&#39;s the idea of computation.
Now, of course, that idea has brought us
all of the computer technology we have today and so on.
But there&#39;s actually a lot more to computation than that.
It&#39;s really a very deep, very powerful, very fundamental idea,
whose effects we&#39;ve only just begun to see.
Well, I myself have spent the past 30 years of my life
working on three large projects
that really try to take the idea of computation seriously.
So I started off at a young age as a physicist
using computers as tools.
Then, I started drilling down,
thinking about the computations I might want to do,
trying to figure out what primitives they could be built up from
and how they could be automated as much as possible.
Eventually, I created a whole structure
based on symbolic programming and so on
that let me build Mathematica.
And for the past 23 years, at an increasing rate,
we&#39;ve been pouring more and more ideas
and capabilities and so on into Mathematica,
and I&#39;m happy to say that that&#39;s led to many good things
in R &amp; D and education,
lots of other areas.
Well, I have to admit, actually,

that I also had a very selfish reason for building Mathematica:
I wanted to use it myself,
a bit like Galileo got to use his telescope
400 years ago.
But I wanted to look not at the astronomical universe,
but at the computational universe.
So we normally think of programs as being
complicated things that we build
for very specific purposes.
But what about the space of all possible programs?
Here&#39;s a representation of a really simple program.
So, if we run this program,
this is what we get.
Very simple.
So let&#39;s try changing the rule
for this program a little bit.
Now we get another result,
still very simple.
Try changing it again.
You get something a little bit more complicated.
But if we keep running this for a while,
we find out that although the pattern we get is very intricate,
it has a very regular structure.

So the question is: Can anything else happen?
Well, we can do a little experiment.
Let&#39;s just do a little mathematical experiment, try and find out.
Let&#39;s just run all possible programs
of the particular type that we&#39;re looking at.
They&#39;re called cellular automata.
You can see a lot of diversity in the behavior here.
Most of them do very simple things,
but if you look along all these different pictures,
at rule number 30,
you start to see something interesting going on.
So let&#39;s take a closer look
at rule number 30 here.
So here it is.
We&#39;re just following this very simple rule at the bottom here,
but we&#39;re getting all this amazing stuff.
It&#39;s not at all what we&#39;re used to,
and I must say that, when I first saw this,
it came as a huge shock to my intuition.
And, in fact, to understand it,
I eventually had to create
a whole new kind of science.

(Laughter)

This science is different, more general,
than the mathematics-based science that we&#39;ve had
for the past 300 or so years.

You know, it&#39;s always seemed like a big mystery:
how nature, seemingly so effortlessly,
manages to produce so much
that seems to us so complex.

Well, I think we&#39;ve found its secret:
It&#39;s just sampling what&#39;s out there in the computational universe
and quite often getting things like Rule 30
or like this.
And knowing that starts to explain
a lot of long-standing mysteries in science.
It also brings up new issues, though,
like computational irreducibility.
I mean, we&#39;re used to having science let us predict things,
but something like this
is fundamentally irreducible.
The only way to find its outcome
is, effectively, just to watch it evolve.
It&#39;s connected to, what I call,
the principle of computational equivalence,
which tells us that even incredibly simple systems
can do computations as sophisticated as anything.
It doesn&#39;t take lots of technology or biological evolution
to be able to do arbitrary computation;
just something that happens, naturally,
all over the place.
Things with rules as simple as these can do it.
Well, this has deep implications
about the limits of science,
about predictability and controllability
of things like biological processes or economies,
about intelligence in the universe,
about questions like free will
and about creating technology.
You know, in working on this science for many years,
I kept wondering,
&quot;What will be its first killer app?&quot;
Well, ever since I was a kid,
I&#39;d been thinking about systematizing knowledge
and somehow making it computable.
People like Leibniz had wondered about that too
300 years earlier.
But I&#39;d always assumed that to make progress,
I&#39;d essentially have to replicate a whole brain.

Well, then I got to thinking:
This scientific paradigm of mine suggests something different --
and, by the way, I&#39;ve now got
huge computation capabilities in Mathematica,
and I&#39;m a CEO with some worldly resources
to do large, seemingly crazy, projects --
So I decided to just try to see
how much of the systematic knowledge that&#39;s out there in the world
we could make computable.
So, it&#39;s been a big, very complex project,
which I was not sure was going to work at all.
But I&#39;m happy to say it&#39;s actually going really well.
And last year we were able
to release the first website version
of Wolfram Alpha.
Its purpose is to be a serious knowledge engine
that computes answers to questions.
So let&#39;s give it a try.
Let&#39;s start off with something really easy.
Hope for the best.
Very good. Okay.
So far so good.

(Laughter)

Let&#39;s try something a little bit harder.
Let&#39;s do
some mathy thing,
and with luck it&#39;ll work out the answer
and try and tell us some interesting things
things about related math.
We could ask it something about the real world.
Let&#39;s say -- I don&#39;t know --
what&#39;s the GDP of Spain?
And it should be able to tell us that.
Now we could compute something related to this,
let&#39;s say ... the GDP of Spain
divided by, I don&#39;t know,
the -- hmmm ...
let&#39;s say the revenue of Microsoft.

(Laughter)

The idea is that we can just type this in,
this kind of question in, however we think of it.
So let&#39;s try asking a question,
like a health related question.
So let&#39;s say we have a lab finding that ...
you know, we have an LDL level of 140
for a male aged 50.
So let&#39;s type that in, and now Wolfram Alpha
will go and use available public health data
and try and figure out
what part of the population that corresponds to and so on.
Or let&#39;s try asking about, I don&#39;t know,
the International Space Station.
And what&#39;s happening here is that
Wolfram Alpha is not just looking up something;
it&#39;s computing, in real time,
where the International Space Station is right now at this moment,
how fast it&#39;s going, and so on.
So Wolfram Alpha knows about lots and lots of kinds of things.
It&#39;s got, by now,
pretty good coverage of everything you might find
in a standard reference library.
But the goal is to go much further
and, very broadly, to democratize
all of this knowledge,
and to try and be an authoritative
source in all areas.
To be able to compute answers to specific questions that people have,
not by searching what other people
may have written down before,
but by using built in knowledge
to compute fresh new answers to specific questions.
Now, of course, Wolfram Alpha
is a monumentally huge, long-term project
with lots and lots of challenges.
For a start, one has to curate a zillion
different sources of facts and data,
and we built quite a pipeline of Mathematica automation
and human domain experts for doing this.
But that&#39;s just the beginning.
Given raw facts or data
to actually answer questions,

one has to compute:
one has to implement all those methods and models
and algorithms and so on
that science and other areas have built up over the centuries.
Well, even starting from Mathematica,
this is still a huge amount of work.
So far, there are about 8 million lines
of Mathematica code in Wolfram Alpha
built by experts from many, many different fields.
Well, a crucial idea of Wolfram Alpha
is that you can just ask it questions
using ordinary human language,
which means that we&#39;ve got to be able to take
all those strange utterances that people type into the input field
and understand them.
And I must say that I thought that step
might just be plain impossible.

Two big things happened:
First, a bunch of new ideas about linguistics
that came from studying the computational universe;
and second, the realization that having actual computable knowledge
completely changes how one can
set about understanding language.
And, of course, now
with Wolfram Alpha actually out in the wild,
we can learn from its actual usage.
And, in fact, there&#39;s been
an interesting coevolution that&#39;s been going on
between Wolfram Alpha
and its human users,
and it&#39;s really encouraging.
Right now, if we look at web queries,
more than 80 percent of them get handled successfully the first time.
And if you look at things like the iPhone app,
the fraction is considerably larger.
So, I&#39;m pretty pleased with it all.
But, in many ways,
we&#39;re still at the very beginning with Wolfram Alpha.
I mean, everything is scaling up very nicely
and we&#39;re getting more confident.
You can expect to see Wolfram Alpha technology
showing up in more and more places,
working both with this kind of public data, like on the website,
and with private knowledge
for people and companies and so on.
You know, I&#39;ve realized that Wolfram Alpha actually gives one
a whole new kind of computing
that one can call knowledge-based computing,
in which one&#39;s starting not just from raw computation,
but from a vast amount of built-in knowledge.
And when one does that, one really changes
the economics of delivering computational things,
whether it&#39;s on the web or elsewhere.
You know, we have a fairly interesting situation right now.
On the one hand, we have Mathematica,
with its sort of precise, formal language
and a huge network
of carefully designed capabilities
able to get a lot done in just a few lines.
Let me show you a couple of examples here.
So here&#39;s a trivial piece of Mathematica programming.
Here&#39;s something where we&#39;re sort of
integrating a bunch of different capabilities here.
Here we&#39;ll just create, in this line,
a little user interface that allows us to
do something fun there.
If you go on, that&#39;s a slightly more complicated program
that&#39;s now doing all sorts of algorithmic things
and creating user interface and so on.
But it&#39;s something that is very precise stuff.
It&#39;s a precise specification with a precise formal language
that causes Mathematica to know what to do here.
Then on the other hand, we have Wolfram Alpha,
with all the messiness of the world
and human language and so on built into it.
So what happens when you put these things together?
I think it&#39;s actually rather wonderful.
With Wolfram Alpha inside Mathematica,
you can, for example, make precise programs
that call on real world data.
Here&#39;s a real simple example.
You can also just sort of give vague input
and then try and have Wolfram Alpha
figure out what you&#39;re talking about.
Let&#39;s try this here.
But actually I think the most exciting thing about this
is that it really gives one the chance
to democratize programming.
I mean, anyone will be able to say what they want in plain language.
Then, the idea is that Wolfram Alpha will be able to figure out
what precise pieces of code
can do what they&#39;re asking for
and then show them examples that will let them pick what they need
to build up bigger and bigger, precise programs.
So, sometimes, Wolfram Alpha
will be able to do the whole thing immediately
and just give back a whole big program that you can then compute with.
Here&#39;s a big website
where we&#39;ve been collecting lots of educational
and other demonstrations about lots of kinds of things.
I&#39;ll show you one example here.
This is just an example of one of these computable documents.
This is probably a fairly small
piece of Mathematica code
that&#39;s able to be run here.
Okay. Let&#39;s zoom out again.
So, given our new kind of science,
is there a general way to use it to make technology?
So, with physical materials,
we&#39;re used to going around the world
and discovering that particular materials
are useful for particular
technological purposes.
Well, it turns out we can do very much the same kind of thing
in the computational universe.
There&#39;s an inexhaustible supply of programs out there.
The challenge is to see how to
harness them for human purposes.
Something like Rule 30, for example,
turns out to be a really good randomness generator.
Other simple programs are good models
for processes in the natural or social world.
And, for example, Wolfram Alpha and Mathematica
are actually now full of algorithms
that we discovered by searching the computational universe.
And, for example, this -- if we go back here --
this has become surprisingly popular
among composers
finding musical forms by searching the computational universe.
In a sense, we can use the computational universe
to get mass customized creativity.
I&#39;m hoping we can, for example,
use that even to get Wolfram Alpha
to routinely do invention and discovery on the fly,
and to find all sorts of wonderful stuff
that no engineer
and no process of incremental evolution would ever come up with.

Well, so, that leads to kind of an ultimate question:
Could it be that someplace out there in the computational universe
we might find our physical universe?
Perhaps there&#39;s even some quite simple rule,
some simple program for our universe.
Well, the history of physics would have us believe
that the rule for the universe must be pretty complicated.
But in the computational universe,
we&#39;ve now seen how rules that are incredibly simple
can produce incredibly rich and complex behavior.
So could that be what&#39;s going on with our whole universe?
If the rules for the universe are simple,
it&#39;s kind of inevitable that they have to be
very abstract and very low level;
operating, for example, far below
the level of space or time,
which makes it hard to represent things.
But in at least a large class of cases,
one can think of the universe as being
like some kind of network,
which, when it gets big enough,
behaves like continuous space
in much the same way as having lots of molecules
can behave like a continuous fluid.
Well, then the universe has to evolve by applying
little rules that progressively update this network.
And each possible rule, in a sense,
corresponds to a candidate universe.
Actually, I haven&#39;t shown these before,
but here are a few of the candidate universes
that I&#39;ve looked at.
Some of these are hopeless universes,
completely sterile,
with other kinds of pathologies like no notion of space,
no notion of time, no matter,
other problems like that.
But the exciting thing that I&#39;ve found in the last few years
is that you actually don&#39;t have to go very far
in the computational universe
before you start finding candidate universes
that aren&#39;t obviously not our universe.

Here&#39;s the problem:
Any serious candidate for our universe
is inevitably full of computational irreducibility.
Which means that it is irreducibly difficult
to find out how it will really behave,
and whether it matches our physical universe.
A few years ago, I was pretty excited to discover
that there are candidate universes with incredibly simple rules
that successfully reproduce special relativity,
and even general relativity and gravitation,
and at least give hints of quantum mechanics.
So, will we find the whole of physics?
I don&#39;t know for sure,
but I think at this point it&#39;s sort of
almost embarrassing not to at least try.
Not an easy project.
One&#39;s got to build a lot of technology.
One&#39;s got to build a structure that&#39;s probably
at least as deep as existing physics.
And I&#39;m not sure what the best way to organize the whole thing is.
Build a team, open it up, offer prizes and so on.
But I&#39;ll tell you, here today,
that I&#39;m committed to seeing this project done,
to see if, within this decade,
we can finally hold in our hands
the rule for our universe
and know where our universe lies
in the space of all possible universes ...
and be able to type into Wolfram Alpha, &quot;the theory of the universe,&quot;
and have it tell us.

(Laughter)

So I&#39;ve been working on the idea of computation
now for more than 30 years,
building tools and methods and turning intellectual ideas
into millions of lines of code
and grist for server farms and so on.
With every passing year,
I realize how much more powerful
the idea of computation really is.
It&#39;s taken us a long way already,
but there&#39;s so much more to come.
From the foundations of science
to the limits of technology
to the very definition of the human condition,
I think computation is destined to be
the defining idea of our future.
Thank you.

(Applause)


Chris Anderson: That was astonishing.
Stay here. I&#39;ve got a question.

(Applause)

So, that was, fair to say, an astonishing talk.
Are you able to say in a sentence or two
how this type of thinking
could integrate at some point
to things like string theory or the kind of things that people think of
as the fundamental explanations of the universe?

Stephen Wolfram: Well, the parts of physics
that we kind of know to be true,

things like the standard model of physics:
what I&#39;m trying to do better reproduce the standard model of physics
or it&#39;s simply wrong.
The things that people have tried to do in the last 25 years or so
with string theory and so on
have been an interesting exploration
that has tried to get back to the standard model,
but hasn&#39;t quite gotten there.
My guess is that some great simplifications of what I&#39;m doing
may actually have considerable resonance
with what&#39;s been done in string theory,
but that&#39;s a complicated math thing
that I don&#39;t yet know how it&#39;s going to work out.

CA: Benoit Mandelbrot is in the audience.
He also has shown how complexity
can arise out of a simple start.
Does your work relate to his?

SW: I think so.
I view Benoit Mandelbrot&#39;s work
as one of the founding contributions
to this kind of area.
Benoit has been particularly interested
in nested patterns, in fractals and so on,
where the structure is something
that&#39;s kind of tree-like,
and where there&#39;s sort of a big branch that makes little branches
and even smaller branches and so on.
That&#39;s one of the ways
that you get towards true complexity.
I think things like the Rule 30 cellular automaton
get us to a different level.
In fact, in a very precise way, they get us to a different level
because they seem to be things that are
capable of complexity
that&#39;s sort of as great as complexity can ever get ...
I could go on about this at great length, but I won&#39;t. 
(Laughter)
 
(Applause)


CA: Stephen Wolfram, thank you.

(Applause)

