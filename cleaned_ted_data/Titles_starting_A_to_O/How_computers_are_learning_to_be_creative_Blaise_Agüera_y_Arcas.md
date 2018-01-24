
So, I lead a team at Google
that works on machine intelligence;
in other words, the engineering discipline
of making computers and devices
able to do some of the things
that brains do.
And this makes us
interested in real brains
and neuroscience as well,
and especially interested
in the things that our brains do
that are still far superior
to the performance of computers.
Historically, one of those areas
has been perception,
the process by which things
out there in the world --
sounds and images --
can turn into concepts in the mind.
This is essential for our own brains,
and it&#39;s also pretty useful on a computer.
The machine perception algorithms,
for example, that our team makes,
are what enable your pictures
on Google Photos to become searchable,
based on what&#39;s in them.

The flip side of perception is creativity:
turning a concept into something
out there into the world.
So over the past year,
our work on machine perception
has also unexpectedly connected
with the world of machine creativity
and machine art.
I think Michelangelo
had a penetrating insight
into to this dual relationship
between perception and creativity.

This is a famous quote of his:
&quot;Every block of stone
has a statue inside of it,
and the job of the sculptor
is to discover it.&quot;
So I think that what
Michelangelo was getting at
is that we create by perceiving,
and that perception itself
is an act of imagination
and is the stuff of creativity.
The organ that does all the thinking
and perceiving and imagining,
of course, is the brain.
And I&#39;d like to begin
with a brief bit of history
about what we know about brains.
Because unlike, say,
the heart or the intestines,
you really can&#39;t say very much
about a brain by just looking at it,
at least with the naked eye.
The early anatomists who looked at brains
gave the superficial structures
of this thing all kinds of fanciful names,
like hippocampus, meaning &quot;little shrimp.&quot;
But of course that sort of thing
doesn&#39;t tell us very much
about what&#39;s actually going on inside.
The first person who, I think, really
developed some kind of insight
into what was going on in the brain
was the great Spanish neuroanatomist,
Santiago Ramón y Cajal,
in the 19th century,
who used microscopy and special stains
that could selectively fill in
or render in very high contrast
the individual cells in the brain,
in order to start to understand
their morphologies.
And these are the kinds of drawings
that he made of neurons
in the 19th century.
This is from a bird brain.
And you see this incredible variety
of different sorts of cells,
even the cellular theory itself
was quite new at this point.
And these structures,
these cells that have these arborizations,
these branches that can go
very, very long distances --
this was very novel at the time.
They&#39;re reminiscent, of course, of wires.
That might have been obvious
to some people in the 19th century;
the revolutions of wiring and electricity
were just getting underway.
But in many ways,
these microanatomical drawings
of Ramón y Cajal&#39;s, like this one,
they&#39;re still in some ways unsurpassed.
We&#39;re still more than a century later,
trying to finish the job
that Ramón y Cajal started.
These are raw data from our collaborators
at the Max Planck Institute
of Neuroscience.
And what our collaborators have done
is to image little pieces of brain tissue.
The entire sample here
is about one cubic millimeter in size,
and I&#39;m showing you a very,
very small piece of it here.
That bar on the left is about one micron.
The structures you see are mitochondria
that are the size of bacteria.
And these are consecutive slices
through this very, very
tiny block of tissue.
Just for comparison&#39;s sake,
the diameter of an average strand
of hair is about 100 microns.
So we&#39;re looking at something
much, much smaller
than a single strand of hair.
And from these kinds of serial
electron microscopy slices,
one can start to make reconstructions
in 3D of neurons that look like these.
So these are sort of in the same
style as Ramón y Cajal.
Only a few neurons lit up,
because otherwise we wouldn&#39;t
be able to see anything here.
It would be so crowded,
so full of structure,
of wiring all connecting
one neuron to another.
So Ramón y Cajal was a little bit
ahead of his time,
and progress on understanding the brain
proceeded slowly
over the next few decades.
But we knew that neurons used electricity,
and by World War II, our technology
was advanced enough
to start doing real electrical
experiments on live neurons
to better understand how they worked.
This was the very same time
when computers were being invented,
very much based on the idea
of modeling the brain --
of &quot;intelligent machinery,&quot;
as Alan Turing called it,
one of the fathers of computer science.
Warren McCulloch and Walter Pitts
looked at Ramón y Cajal&#39;s drawing
of visual cortex,
which I&#39;m showing here.
This is the cortex that processes
imagery that comes from the eye.
And for them, this looked
like a circuit diagram.
So there are a lot of details
in McCulloch and Pitts&#39;s circuit diagram
that are not quite right.
But this basic idea
that visual cortex works like a series
of computational elements
that pass information
one to the next in a cascade,
is essentially correct.
Let&#39;s talk for a moment
about what a model for processing
visual information would need to do.
The basic task of perception
is to take an image like this one and say,
&quot;That&#39;s a bird,&quot;
which is a very simple thing
for us to do with our brains.
But you should all understand
that for a computer,
this was pretty much impossible
just a few years ago.
The classical computing paradigm
is not one in which
this task is easy to do.
So what&#39;s going on between the pixels,
between the image of the bird
and the word &quot;bird,&quot;
is essentially a set of neurons
connected to each other
in a neural network,
as I&#39;m diagramming here.
This neural network could be biological,
inside our visual cortices,
or, nowadays, we start
to have the capability
to model such neural networks
on the computer.
And I&#39;ll show you what
that actually looks like.
So the pixels you can think
about as a first layer of neurons,
and that&#39;s, in fact,
how it works in the eye --
that&#39;s the neurons in the retina.
And those feed forward
into one layer after another layer,
after another layer of neurons,
all connected by synapses
of different weights.
The behavior of this network
is characterized by the strengths
of all of those synapses.
Those characterize the computational
properties of this network.
And at the end of the day,
you have a neuron
or a small group of neurons
that light up, saying, &quot;bird.&quot;
Now I&#39;m going to represent
those three things --
the input pixels and the synapses
in the neural network,
and bird, the output --

by three variables: x, w and y.
There are maybe a million or so x&#39;s --
a million pixels in that image.
There are billions or trillions of w&#39;s,
which represent the weights of all
these synapses in the neural network.
And there&#39;s a very small number of y&#39;s,
of outputs that that network has.
&quot;Bird&quot; is only four letters, right?
So let&#39;s pretend that this
is just a simple formula,
x &quot;x&quot; w = y.
I&#39;m putting the times in scare quotes
because what&#39;s really
going on there, of course,
is a very complicated series
of mathematical operations.
That&#39;s one equation.
There are three variables.
And we all know
that if you have one equation,
you can solve one variable
by knowing the other two things.
So the problem of inference,
that is, figuring out
that the picture of a bird is a bird,

is this one:
it&#39;s where y is the unknown
and w and x are known.
You know the neural network,
you know the pixels.
As you can see, that&#39;s actually
a relatively straightforward problem.
You multiply two times three
and you&#39;re done.
I&#39;ll show you an artificial neural network
that we&#39;ve built recently,
doing exactly that.
This is running in real time
on a mobile phone,
and that&#39;s, of course,
amazing in its own right,
that mobile phones can do so many
billions and trillions of operations
per second.
What you&#39;re looking at is a phone
looking at one after another
picture of a bird,
and actually not only saying,
&quot;Yes, it&#39;s a bird,&quot;
but identifying the species of bird
with a network of this sort.
So in that picture,
the x and the w are known,
and the y is the unknown.
I&#39;m glossing over the very
difficult part, of course,
which is how on earth
do we figure out the w,
the brain that can do such a thing?
How would we ever learn such a model?
So this process of learning,
of solving for w,
if we were doing this
with the simple equation
in which we think about these as numbers,

we know exactly how to do that: 6 = 2 x w,
well, we divide by two and we&#39;re done.
The problem is with this operator.
So, division --
we&#39;ve used division because
it&#39;s the inverse to multiplication,
but as I&#39;ve just said,
the multiplication is a bit of a lie here.
This is a very, very complicated,
very non-linear operation;
it has no inverse.
So we have to figure out a way
to solve the equation
without a division operator.
And the way to do that
is fairly straightforward.
You just say, let&#39;s play
a little algebra trick,
and move the six over
to the right-hand side of the equation.
Now, we&#39;re still using multiplication.
And that zero -- let&#39;s think
about it as an error.
In other words, if we&#39;ve solved
for w the right way,
then the error will be zero.
And if we haven&#39;t gotten it quite right,
the error will be greater than zero.
So now we can just take guesses
to minimize the error,
and that&#39;s the sort of thing
computers are very good at.

So you&#39;ve taken an initial guess:
what if w = 0?
Well, then the error is 6.
What if w = 1? The error is 4.
And then the computer can
sort of play Marco Polo,
and drive down the error close to zero.
As it does that, it&#39;s getting
successive approximations to w.
Typically, it never quite gets there,
but after about a dozen steps,
we&#39;re up to w = 2.999,
which is close enough.
And this is the learning process.
So remember that what&#39;s been going on here
is that we&#39;ve been taking
a lot of known x&#39;s and known y&#39;s
and solving for the w in the middle
through an iterative process.
It&#39;s exactly the same way
that we do our own learning.
We have many, many images as babies
and we get told, &quot;This is a bird;
this is not a bird.&quot;
And over time, through iteration,
we solve for w, we solve
for those neural connections.
So now, we&#39;ve held
x and w fixed to solve for y;
that&#39;s everyday, fast perception.
We figure out how we can solve for w,
that&#39;s learning, which is a lot harder,
because we need to do error minimization,
using a lot of training examples.
And about a year ago,
Alex Mordvintsev, on our team,
decided to experiment
with what happens if we try solving for x,
given a known w and a known y.
In other words,
you know that it&#39;s a bird,
and you already have your neural network
that you&#39;ve trained on birds,
but what is the picture of a bird?
It turns out that by using exactly
the same error-minimization procedure,
one can do that with the network
trained to recognize birds,
and the result turns out to be ...
a picture of birds.
So this is a picture of birds
generated entirely by a neural network
that was trained to recognize birds,
just by solving for x
rather than solving for y,
and doing that iteratively.
Here&#39;s another fun example.
This was a work made
by Mike Tyka in our group,
which he calls &quot;Animal Parade.&quot;
It reminds me a little bit
of William Kentridge&#39;s artworks,
in which he makes sketches, rubs them out,
makes sketches, rubs them out,
and creates a movie this way.
In this case,
what Mike is doing is varying y
over the space of different animals,
in a network designed
to recognize and distinguish
different animals from each other.
And you get this strange, Escher-like
morph from one animal to another.
Here he and Alex together
have tried reducing
the y&#39;s to a space of only two dimensions,
thereby making a map
out of the space of all things
recognized by this network.
Doing this kind of synthesis
or generation of imagery
over that entire surface,
varying y over the surface,
you make a kind of map --
a visual map of all the things
the network knows how to recognize.
The animals are all here;
&quot;armadillo&quot; is right in that spot.
You can do this with other kinds
of networks as well.
This is a network designed
to recognize faces,
to distinguish one face from another.
And here, we&#39;re putting
in a y that says, &quot;me,&quot;
my own face parameters.
And when this thing solves for x,
it generates this rather crazy,
kind of cubist, surreal,
psychedelic picture of me
from multiple points of view at once.
The reason it looks like
multiple points of view at once
is because that network is designed
to get rid of the ambiguity
of a face being in one pose
or another pose,
being looked at with one kind of lighting,
another kind of lighting.
So when you do
this sort of reconstruction,
if you don&#39;t use some sort of guide image
or guide statistics,
then you&#39;ll get a sort of confusion
of different points of view,
because it&#39;s ambiguous.
This is what happens if Alex uses
his own face as a guide image
during that optimization process
to reconstruct my own face.
So you can see it&#39;s not perfect.
There&#39;s still quite a lot of work to do
on how we optimize
that optimization process.
But you start to get something
more like a coherent face,
rendered using my own face as a guide.
You don&#39;t have to start
with a blank canvas
or with white noise.
When you&#39;re solving for x,
you can begin with an x,
that is itself already some other image.
That&#39;s what this little demonstration is.
This is a network
that is designed to categorize
all sorts of different objects --
man-made structures, animals ...
Here we&#39;re starting
with just a picture of clouds,
and as we optimize,
basically, this network is figuring out
what it sees in the clouds.
And the more time
you spend looking at this,
the more things you also
will see in the clouds.
You could also use the face network
to hallucinate into this,
and you get some pretty crazy stuff.

(Laughter)

Or, Mike has done some other experiments
in which he takes that cloud image,
hallucinates, zooms, hallucinates,
zooms hallucinates, zooms.
And in this way,
you can get a sort of fugue state
of the network, I suppose,
or a sort of free association,
in which the network
is eating its own tail.
So every image is now the basis for,
&quot;What do I think I see next?
What do I think I see next?
What do I think I see next?&quot;
I showed this for the first time in public
to a group at a lecture in Seattle
called &quot;Higher Education&quot; --
this was right after
marijuana was legalized.

(Laughter)

So I&#39;d like to finish up quickly
by just noting that this technology
is not constrained.
I&#39;ve shown you purely visual examples
because they&#39;re really fun to look at.
It&#39;s not a purely visual technology.
Our artist collaborator, Ross Goodwin,
has done experiments involving
a camera that takes a picture,
and then a computer in his backpack
writes a poem using neural networks,
based on the contents of the image.
And that poetry neural network
has been trained
on a large corpus of 20th-century poetry.
And the poetry is, you know,
I think, kind of not bad, actually.

(Laughter)

In closing,
I think that per Michelangelo,
I think he was right;
perception and creativity
are very intimately connected.
What we&#39;ve just seen are neural networks
that are entirely trained to discriminate,
or to recognize different
things in the world,
able to be run in reverse, to generate.
One of the things that suggests to me
is not only that
Michelangelo really did see
the sculpture in the blocks of stone,
but that any creature,
any being, any alien
that is able to do
perceptual acts of that sort
is also able to create
because it&#39;s exactly the same
machinery that&#39;s used in both cases.
Also, I think that perception
and creativity are by no means
uniquely human.
We start to have computer models
that can do exactly these sorts of things.
And that ought to be unsurprising;
the brain is computational.
And finally,
computing began as an exercise
in designing intelligent machinery.
It was very much modeled after the idea
of how could we make machines intelligent.
And we finally are starting to fulfill now
some of the promises
of those early pioneers,
of Turing and von Neumann
and McCulloch and Pitts.
And I think that computing
is not just about accounting
or playing Candy Crush or something.
From the beginning,
we modeled them after our minds.
And they give us both the ability
to understand our own minds better
and to extend them.
Thank you very much.

(Applause)

