
thank you
I&#39;m Paul Cantrell I teach computer
science here at McAllister which raises
an interesting question why why do I
teach computer science at a liberal arts
college well the short answer to that
question is that computer science is or
at least can be more than just job
training and so should education to help
illustrate what I mean by that I want to
talk about a project that I wrote with
my excellent colleagues at bust out
solutions for the Como Zoo and
conservatory they wanted an interactive
iPad exhibit to go with their bonsai
tree exhibit that would let kids make
their own virtual bonsai tree on an iPad
keep him busy for five minutes while
their parents look at the trees and
hopefully maybe even educate and engage
and inspire them which gave us an
interesting problem to solve we had to
create a tree in software and I don&#39;t
just mean a picture of a tree we want
you to be able to trim your own tree
your choice is your tree that means we
need an algorithm that makes things that
look and feel like trees the way we do
that is using something called an L
system and the way it works is we start
with just one segment we&#39;re gonna build
tree out of these segments we start with
a segment and we apply a rule to it
that&#39;s the rule at the lower left there
take that segment and replace it with
several segments and then we take each
of these several segments and apply the
same rule to them and apply the rule to
each of these segments and we get a
structure a plant like structure that we
can work with here&#39;s what that looks
like on an iPad this doesn&#39;t look like a
tree yet but we&#39;ll get there the first
thing we need to do to make it look like
a bonsai is that on one side trees start
out dents and shrubby so that you have
material to trim away we need to make
our tree look shrubby the way I do that
is at each step of the substitution I
remove a few segments so instead of
substitute substitute substitute it&#39;s
now
that you remove a few substitute remove
a few that kind of keeps it dense as it
grows here&#39;s what it looks like and it
looks shrubby for sure but it&#39;s like
some kind of grassy tumbleweed maybe we
want something that looks like a woody
tree so how do we do that how do we make
it look like wood well perhaps we might
want to get an image of some bark right
something better than this generic Brown
some maybe even the texture of the bark
but no it turns out there&#39;s a much
simpler and more effective way to make
it look like a woody tree which is that
we take each of these segments that the
tree is built out of and we make them
thicker depending on how many
descendants they have up the tree and we
make them just slightly taller if
they&#39;re closer to the root of the tree
and there we have something that
actually I think looks like it&#39;s made
out of wood doesn&#39;t it it&#39;s still just a
bunch of cylinders stuck together
there&#39;s not a lot going on here but what
turned out to be a problem of shape and
proportion might have seemed at first
like a problem of color and texture um
something that happens when we write
software it asks us to look at things
very closely software involves close
seeing and therefore software becomes a
way of seeing like any creative endeavor
software is a way of seeing the work
we&#39;re doing right here this is this is
not scientific seeing we&#39;re not forming
a hypothesis about a tree we&#39;re trying
to do something artistic the goal is not
accuracy it&#39;s to it&#39;s to make something
convincing now there&#39;s a problem with
this it&#39;s a pretty serious one you&#39;ll
see it when i zoom in the cylinders
don&#39;t quite join up in some places there
are these visible seams between them
because when you take a bunch of
cylinders with their hard edges and you
stick them together sometimes there are
little gaps well one way to solve that
might be to round off the ends right so
let&#39;s see what that looks like
oh that&#39;s arguably even worse
to understand why this is so bad we need
to know a little bit about how computers
do shading in 3d graphics when you have
a 3d model you compute what&#39;s called the
normals these are just lines that stick
straight out from the surface then you
imagine light falling on the surface and
you say well if one of these normals is
placing is is pointing straight at the
light then we should give it a little
high light and if it&#39;s pointing more
away from the light than not then we
should put it in shadow that&#39;s how we do
shading the reason it looks so bad when
we put two of these rounded ends next to
each other is that when we do that we
end up with normals pointing very
different directions right next to each
other which means that the light and the
shadow make an abrupt transition now we
might fix this by saying trying to fill
in those little gaps but it turns out
mathematically and programmatically
that&#39;s very difficult to do and there&#39;s
an easier faster better way which is
that we just take these normals and he
lie we straight up lie we say actually
it&#39;s always pointing straight off to the
side even when it isn&#39;t that makes it so
that when there&#39;s a joined point between
two of these rounded edges there&#39;s not
such an abrupt transition and in fact
that fixes the problem we&#39;ve only
changed the shading and not the shape it
seemed like it was a problem of shape
it&#39;s really a problem of light and dark
and shading on which is the beautiful
thing about software we come up with
ideas notions assumptions hopes wishes
and dreams we encode them we literally
encode them and then the computer throws
them back at us with mindless literalism
and we see our own ideas and our ideas
talk back to us software makes our ideas
talk back to us if we let it right now
we need people desperately need people
who will listen to that because software
is doing a lot of things in our world
it&#39;s talking back to us in surprising
ways and we need to listen to that now
we throw a few leaves on that thing and
you got something that looks like it
looks like a tree right it&#39;s pretty cool
and the beautiful thing about having an
algorithm for this is that if we just
change the art for the leaves and tweak
a few parameters in the algorithm we get
not only an endless variety of maples
but also junipers ficuses the only
difference between these three species
of trees is a few numbers in an
algorithm and different art for the
leaves what we&#39;re doing here this is
this is essentially art we&#39;re making a
tree drawing a tree but we&#39;re making it
with algorithms it&#39;s art and the medium
is algorithms you can see why software
companies put a huge premium on people
who can cross boundaries and synthesize
ideas from different fields if we take a
look at the finished app here&#39;s somebody
working on their tree after a few
minutes perfecting their masterpiece
here&#39;s math software art and graphic
design a smidge of botany also
psychology if the user putting ourselves
in the user&#39;s shoes which is something
that we get actually from reading
literature and there&#39;s also the many
factors that went into this nonprofit
their mission what do they want all
these different disciplines are coming
together just like we do in a liberal
arts education like this one liberal
arts is fantastic background for writing
software but that&#39;s not the question
that I asked we get confused about this
so easily we see that education is
useful for jobs and we say well it must
be worthwhile but that&#39;s not enough
that&#39;s not enough I didn&#39;t ask why is
liberal arts education good for software
I asked why does software belong in a
liberal arts education there was a
moment in this project when somebody
asked how do we stop kids using this
from taking their tree and just trimming
it down to a stump I said what you don&#39;t
stop them
you never a child yourself you walk up
to this thing you can trim the tree
what&#39;s the first thing you&#39;re gonna do
and it&#39;s true kid after kid you watch
them using this thing at the Como Zoo
they walk up to it and they trim it down
to a stump and they say good I did yeah
and then you can see it hit him they
said wait
nobody&#39;s policing me I can trim my tree
down to a stump if I want this is my
tree and then it comes over them they
become absorbed and they just lose
themselves in that tree as they work on
their personal masterpiece time after
time you can watch this happen I walked
in once and her two kids ain&#39;t mommy
mommy my tree is in the virtual
collection it happens to adults too
don&#39;t tell and that moment that moment
of realizing that this is my tree and
I&#39;m free to make it what I want that is
what liberal arts education is about do
any of you know what liberal arts
actually means
I confess I didn&#39;t when I was a student
I knew that it didn&#39;t just mean
politically liberal something bigger
than that I thought it meant like
liberal maybe all inclusive something
something along those lines in fact know
the Latin phrase that liberal arts comes
from artist liberalist the Liebherr
Alice here means of free people this was
the education centuries ago that free
people received as opposed to slaves
this was the education that gave people
the power to determine their own lives
meaning and the ability to take
responsibility for that power this was
the education that people deserved and
needed who weren&#39;t completely defined as
people by their economic value think
about what it means that we think that
liberal arts education is something
narrow and specialized that only a few
people need to bother with think about
what that means this is something that
every human being should have I don&#39;t
mean that everyone should go to a
four-year private liberal arts
I don&#39;t mean that this needs to happen
in school at all education is much
bigger than school but this is something
that every human being deserves and I
don&#39;t mean to shortchange job training
it&#39;s important it&#39;s necessary but it is
not sufficient we need education to be
more than that yes we should help
students answer the question how will I
make money but we should also help them
answer the question what should I do
with that money when I have it what do I
value what change do I want to create in
the world I can trim my life to a stump
so who do I want to be and software
software can help answer these questions
it asks us to see closely
it makes our ideas talk back to us it
shows us that everything is connected to
everything software is kind of an ideal
liberal art probably any discipline can
be liberal arts is not about what we
teach but about how we teach that we
teach with the belief that every human
being deserves to be the author of their
own life&#39;s meaning and needs to be able
to take responsibility for that power
that&#39;s what liberal arts education is
now I don&#39;t know what software will look
like in 20 or 40 years job training has
kind of a short shelf life but I do know
that the things that my students learn
from writing software will serve their
unforce evil lives in unforeseen ways
and that is why I choose to spend my
life teaching computer science at a
liberal arts college
you
