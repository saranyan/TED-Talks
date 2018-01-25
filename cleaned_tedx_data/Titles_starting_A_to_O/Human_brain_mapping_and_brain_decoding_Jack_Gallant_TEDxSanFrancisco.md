
[Music]
brains a computer I know it seems
strange to think of the human brain as a
computer but you know it&#39;s not a
computer like your desktop or like your
cell phone which are architected systems
it&#39;s an evolved system that has
developed over millions of years
continuously building on what was there
before but it processes information you
sit here you have sensory experiences
you combine those sensory experiences
with prior information prior knowledge
you make decisions and you act in the
world and an information processing
system like that is a computer so in
principle we should be able to
understand the human brain as a computer
by reverse engineering it and
discovering the underlying computation
algorithms that govern its function and
if we do that we can invert those
algorithms and create very powerful
brain decoding devices that can probably
in the future replace all other kinds of
grain machine interfaces and brain
computer interfaces now the brain looks
like a pretty homogeneous organ there&#39;s
a cerebral cortex this big folded part
on the top and there&#39;s a cerebellum on
the bottom underneath the cerebral
cortex this mantle of tissue there are
many many subcortical nuclei all
together though the brain has about some
13 we think on the order of say 500
different parts about a third of those
are gonna be subcortical nuclei and
two-thirds of them are going to be
cortical areas that are functionally and
anatomically distinct and these areas
are hooked together in very dense
networks we don&#39;t really know the area&#39;s
yet for humans or exactly how they&#39;re
hooked together but animal studies
suggest that the brain is 50% connected
that is for any given location on the
cerebral cortex it is connected to 50%
of all of the other locations and all of
these connections are feed-forward and
feedback so the brain is a giant
interconnected recurrent Network and
systems like this in science are known
as nonlinear dynamical systems and they
have interesting properties the property
of the system as a whole its function
cannot necessarily be predicted by
looking at the individual parts because
nonlinear dynamical systems have
emergent properties and in humans of
course one of the most import
emergent properties is probably
consciousness to get a handle on what
the human brain is as a computer to
understand its structure we can first of
all try to map it we can separate the
cerebral cortex into its distinct
anatomical and functional parts and try
to get a handle on them and then look at
how they interact now people have known
for hundreds of years that the human
brain was divided into different
functional parts and they&#39;ve tried
mostly unsuccessfully until recently to
really parse laid out - the cerebral
cortex the main part of the human brain
that you see on the in a slide that
distinguishes us mostly from lower
animals they&#39;ve tried to parse late to
the brain using a variety of methods
that were mostly unsuccessful the most
notorious of these is phrenology a
nineteenth-century discredited science
in which people tried to look at the
bumps on the surface of the skull and
infer from the pattern of bumps what the
underlying function was of the tissue
underneath the bumps today we all laugh
at this it seems completely silly but
the phrenologist weren&#39;t completely
crazy they were we had very poor methods
they were 40 poor scientists but they
did have one good idea which is that the
brain is functionally localized and
today we can map the functional
localization of the brain using powerful
methods such as functional magnetic
resonance imaging so I&#39;m going to show
you an example of an fMRI experiment
that kind of gives you a flavor of the
kind of data we can recover from this
method the brain is inconveniently
folded up inside the skull so we
computationally inflate it we put some
slices in it and we flatten it out so
now we&#39;re looking at the surface of the
cerebral cortex if we did this to your
brain we would have something about the
size of a large pizza there arose a left
and a right hemisphere the middle of the
screen is showing the visual system at
the far left and the far right as the
prefrontal cortex
now we can paint brain activity on the
surface of the cerebral cortex while
someone watches a movie and they&#39;re
simply passively watching this movie and
interpreting what&#39;s going on of course
think about what happens to your brain
when you watch a movie anything that you
can conceive of in this movie must be
reflected somewhere in the brain in
terms of patterns of brain activity
obviously you can see the structure of
the movie you can see the wall you can
see water you can see the edges of the
screen you can see textures you can see
oriented lines those are represented in
one part of the brain other parts of the
brain represent information that is
reflects the objects and actions in the
movie that there&#39;s a car or a smokestack
that there&#39;s smoke that there&#39;s airflow
other parts of the brain reflect
information that isn&#39;t directly in the
movie but is associated with it for
example you might be hungry right now so
you might be thinking about food or you
might be annoyed at the price of gas or
you might want coffee all of these
things would be also represented in the
brain these desires needs wants and
associations all of this stuff must be
represented somewhere that really so you
can think of the problem of brain
mapping as finding systemic
relationships between the stuff in the
world in this case the things in the
movie and the patterns of brain activity
those are going to be fairly
straightforward relationships to map
there&#39;s also of course going to be a lot
of information in the brain that isn&#39;t
directly in the movie your implicit
associations your biases your private ik
prior experiences and those are going to
be a bit more difficult to map but in
principle we should be able to slowly
over time aggregate a huge amount of
information about the relationships
between brain activity and the world in
order to create functional maps of the
brain so here are the results of a few
mapping experiments that have been
aggregated together in these experiments
we had people watch movies or we had
them listen to stories in the MRI
machine these experiments probably took
eight or ten hours in total for one
individual but we didn&#39;t do this all at
once these were experiments that were
done across weeks of time and now we can
take this information I essentially this
is a regression problem where the X
variables are the world the stories are
the movies and the Y variables are our
brain activity
and we can use machine learning and data
analysis tools to recover functional
maps of brain activity and those are
shown here as colored maps and the
different colors here reflects different
kinds of meaning that are represented in
the patterns of brain activity about the
information in the stories and movies
now these patterns are fairly
complicated and rich and this conceptual
knowledge that we&#39;re mapping this
particular experiment is distributed
broadly across the brain this is a lot
of information to take in we&#39;re making a
hundred thousand spatial measurements
across these cortical maps and it&#39;s too
much to think about
so we&#39;ve created an online brain viewer
that you can actually play with on my
website and this online brain viewer
allows you to interact with these maps
to determine what kind of conceptual
information is represented across the
brain so this particular dataset comes
from a story listening experiment where
people listened to The Moth Radio Hour
from Public Radio International and now
we can create maps that reveal what kind
of information is represented at
different locations in the brain and
here I&#39;m clicking on an individual voxel
down in the temporal lobe on the side of
the head that represents social
information families mothers fathers
daughters things that happen to families
weddings births deaths and so on there
are many locations to represent social
information here&#39;s one in the lateral
prefrontal cortex that also represents
social information in fact all of the
red spots on this map represents social
information there are other networks
that represent other kinds of
information for example here&#39;s a spot in
the posterior parietal cortex that
represents a numerical information
numbers time money mathematical
equations you might be processing in
your brain anything related to numbers
is represented this network of green
areas in fact there are networks for
hundreds of different kinds of
conceptual information every piece of
conceptual information truth dreaming
sculptures anything you can think of
these concept concepts are represented
in multiple locations across the surface
of cortex and each potential each
location on the cortex represents
multiple kinds of information now of
course brains aren&#39;t all the same I you
know everyone has the same ears everyone
hears the same
your bits but everybody&#39;s ears look
slightly different and it&#39;s the same for
brains
everyone&#39;s brain is essentially the same
in its general form but all individual
brains are different and we can
aggregate data across different brains
like we see here we can see that about
1/3 of the functional activity and
brains is shared across individuals and
about 2/3 reflects individual
differences which are both developmental
and experiential differences that are
reflected in function now even though
there are individual differences in the
brain because the brain is essentially a
collection of wires which are the nerves
that connect different areas together
there&#39;s a very strong relationship
between the structure of the brain and
the function of the brain and by
aggregating data across many subjects
and using computational modeling methods
we can create a mathematical model that
links an individual brain anatomy to the
distribution of function across that
brain here we show one particular
functional map for one individual who&#39;s
listening to stories and this is a
conceptual map this is mapping to
thousand different kinds of objects and
actions that can occur in stories across
one individual brain they&#39;re about a
hundred and sixty different brain areas
that represent conceptual knowledge in
these stories and we can do this for any
individual now up to now I&#39;ve suggested
to you that the brain is static that
different places in the brain represent
a certain small constellation of
quantities and that those
representations are static in fact
they&#39;re not the way the brain is
designed it there are emergent
properties that arise as a consequence
of the task that you are trying to
perform that actually change the way
that information is represented in the
brain so this is data from a simple
experiment where we have people
passively watching movies versus
attending to humans in the movies versus
attending to vehicles in the movies and
you can see that the conceptual maps in
these three different cases are
different and actually the maps vary
this least in the visual system these
functional maps very enormous lis in
prefrontal cortex because prefrontal
cortex represents abstract thought plans
goals console things like that and as
you change your task the activity in
cortex actually represents different
kinds of quantities so for example if
you lose your cat your prefrontal cortex
becomes a giant cat detector and all
other functions are suppressed and you
everything is trying to represent cats
as much as it can and that is true for
pretty much any tasks you perform now
that one of the interesting things about
these encoding models if you are just a
civilian or not a neuroscientist is that
once you have a computational model of
the brain that relates the world to
brain activity you can invert that model
and you can convert your encoding model
into a decoding model and can use it to
decode brain activity and in fact
there&#39;s an inevitable symmetry between
brain and coding and brain decoding such
that whenever we can create a better
computational model of the brain we can
always by definition build a better
brain decoder and oftentimes it&#39;s a
little easier to understand what kind of
information we can recover from current
brain measurements by looking at decoder
so I&#39;d like to show you a few of these
as examples here&#39;s one brain decoder
that&#39;s only recovering information from
primary visual cortex a very early
visual area that represents very simple
aspects of the scene like edges and
textures and colors
on the upper left is the movie we showed
two subjects on the upper right is
information we&#39;re decoding from primary
visual cortex and the bottom two photos
show you the edge maps these should
correspond well because we know that
this part of the brain represents edges
here&#39;s a decoder that is recovering
information and decoding it from
high-level visual areas these visual
areas they don&#39;t really carry a lot of
information about this specific
structure of a scene the distribution of
surfaces and colors and textures they
carry information about the content of
the scene what people were present were
their objects present the the semantic
information the scene and you can see
that this decoder also works fairly well
it doesn&#39;t do well when the scene
changes very rapidly like right now
because these MRI changes that we are
measuring our metabolic not neural and
they are fairly slow but when the scene
changes slowly the decoder does quite a
good job of recovering information about
the semantic content of the scene so
where is this technology going
well the analogy I like to make is with
early photography this is the very first
photograph that was taken by Joseph
Nietzsche in the South of France in the
early 19th century and this is a bad
photograph right no one would pay for
this photograph but you can see that it
is a photo there are walls there&#39;s a
horizon there&#39;s a roof you can tell it&#39;s
maybe some sort of farm scene or a
village scene it is a photograph and
this photograph launched an entire
industry that sought to develop
photography into what we have today
where photography is so ubiquitous and
of such high quality that no one even
wants to pay for it they expect to just
get it for free on their cell phones and
brain decoding we&#39;ll pursue this same
trajectory as long as the government is
investing in neuroscience and
neuroscientists are working to
understand the brain they&#39;ll be
developing new methods of measurement
those new brain measurement methods will
allow us to create more sophisticated
computational models of the brain and
those computational models will allow us
to decode brain activity with much
higher fidelity so at some point in the
future we&#39;re going to have very cheap
very powerful portable brain decoding
devices that we&#39;re not there yet as I
mentioned at the beginning of this talk
the brain is a nonlinear dynamical
system and one of the important
properties of these systems is that in
order to understand the entire dynamical
surface the sort of dynamical landscape
you need to record in both space and
time at very high resolution
simultaneously but right now we don&#39;t
have any methods that allow us to record
in both space and time all the methods
we have either sacrificed time or they
sacrifice space so for example
functional MRI the method that I showed
you earlier in the talk it has fantastic
spatial resolution but very poor
temporal resolution because it measures
metabolic signals changes in blood flow
that are consequent to neural activity
it doesn&#39;t measure changes in neural
activity itself so when we&#39;re I cannot
really recover any dynamic information a
very common consumer method that is used
to measure and decode brain activity oh
today is electroencephalography EEG and
the EEG has fantastic temporal
resolution but it has horrible spatial
resolution so although it can measure
happening in time it does not know where
those events came from in the brain so
all the different maps that occur in the
brain get all essentially mixed together
and this is reduces the amount of
information we can decode from EEG to
just a few bits but we do know that
brain measurement improves all the time
because neuroscience community is very
focused on improving measurement since
measurement limitations are the main
factor we have limiting our progress in
neuroscience today so in the future we
are going to end up with better brain
measurement methods that will recover
information in both space and time and
at high resolution we don&#39;t know when
this is going to happen it could be a
decade it could be 20 years it could be
50 years down the road but at some point
probably in the lifetimes of young
people here there will be a brain
decoding method that is cheap portable
very powerful and that will become
ubiquitous people will you know be able
to just wear a brain hat around and have
their internal thoughts decoded all the
time
and this would have a very profound
effect on society after all how do I
interact with my computer today I used
these meaty thumbs that were evolved
billions of years ago millions of years
ago and it&#39;s kind of insane for me to
interact with my cellphone with my
thumbs when I have a very good internal
speech a little man in my head that&#39;s
talking to me continuously and it could
just interact with my cellphone directly
in fact anything that is going on in
your head is potentially decodable all
of your inner thoughts your intentions
desires your attitudes in fact things
you haven&#39;t even that haven&#39;t even
reached conscious awareness yet are
potentially decodable and all that
information will be decoded using future
brain decoding technology now that&#39;s
both exciting and frankly quite scary
because you can imagine all the ethical
issues that this will open up after all
Americans in particular but humans in
general are pretty bad about guarding
their privacy and there are real
interesting privacy and ethical issues
are going to be opened up when Google
and Facebook have access to all of your
innermost thoughts with no filter from
your thumbs right that&#39;s going to be a
very strange world but it is the world
we&#39;re going to live in very soon thank
you for your time
