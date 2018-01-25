
[Music]
I have four kids and they all love math
and logic puzzles the beginning of the
school year I asked him why they love
math and logic puzzles so much and my 11
year old answered it&#39;s because I&#39;m a
detective it&#39;s because I&#39;m a problem
solver and I love to solve problems
about the world and so succinctly my
eleven-year-old summed up what I&#39;ve been
feeling my entire career that I have
mysteries and problems that I want to
solve and the way I&#39;m gonna do it is by
learning as much about machine learning
as I possibly can so why is machine
learning the right tool to solve these
mysteries in genomics and biology and
medicine well I think in order to think
about this we need to first discuss the
two cultures in machine learning right
now so leo breiman was a professor at UC
Berkeley where I did my PhD in
statistics and he&#39;s well known for
building methods and models like a
random forests that solve real-world
problems in an elegant way he passed
away in 2005 and in his obituary he&#39;s
quoted as saying to students remember
that the great adventure of statistics
is in gathering and using data to solve
interesting and important real-world
problems so he was clearly a detective
too in 2001 leo breiman wrote a paper
called statistical modeling the two
cultures and in this paper he describes
the two cultures in machine learning one
of which I&#39;m going to refer to as the
black box which leo breiman was
advocating and the other one i&#39;m going
to call the open box so when we think
about analyzing data in the real world
let&#39;s say we have an observation X this
observation could be a picture on the
Internet it could be the fMRI scan from
a patient and then we have some Y which
could be the label for that observation
so the image on the internet might be
labeled as cat or the fMRI scan might be
labeled as bipolar disorder or healthy
so in the black box approach to modeling
these data we&#39;re going to use something
like a decision tree or neural networks
to in a brute force way model the
relationship between x and y ok because
it&#39;s brute force because we don&#39;t even
attempt to model nature it&#39;s a black box
we can&#39;t open it up and we also need a
lot of data to be able to model this
relationship without
surely pretending to model nature the
open box approach is quite different so
we use very simplified models like
factor analysis linear and logistic
regression and canonical correlation
analysis to try an approximate nature we
essentially build a scaffold based on
what we think is the relationship
between x and y and then fill that
scaffold in using data the good news is
that it takes a lot less data but the
bad news is that we really need to know
something about our domain that we&#39;re
working in to be able to build this
scaffold appropriately so if we&#39;re using
a black box method to try and label
pictures on the Internet let&#39;s say we
start out with a hundred thousand
labeled images some of which have cat
and some of which don&#39;t then when we see
a new picture on the internet with high
accuracy we can label this image cat so
Brad Efron who is a very distinguished
statistician wrote a response to the two
cultures paper advocating the open box
approach and in his response he says the
whole point of science is to open up
black boxes understand their insides and
build better poxes for the purposes of
mankind
and I think this succinctly encapsulate
exactly what I think about this open box
approach where we need to open the box
model nature and see what&#39;s going on
inside see what we&#39;ve learned from the
data
so now if I apply the open box approach
to trying to label images on the
internet I might see this image of a cat
again and I might say it&#39;s a cat and not
a hippopotamus because it has a
beautiful structure that looks like a
cat the nose is exactly a cat&#39;s nose the
fur is a repeated pattern that is in the
shape of a cat it has fuzzy ears it has
a tail it looks like a cat
so I&#39;m explaining why I&#39;m giving it this
label of cat but for this particular
problem we don&#39;t care why the label is
the most important thing the same is not
true if you have an fMRI scan of a
patient we can&#39;t just say this patient
has bipolar disorder or not we need to
know why we need to know what it is
about that fMRI scan that allows us to
give this patient a diagnosis so how do
we actually open the box then in these
biomedical problems well let&#39;s say we&#39;re
studying a rare brain disease and we
have maybe 10,000 patients in the world
at all with this brain disease that&#39;s
not enough patients even if we can see
them all to be able to use blackbox
methods to diagnose these patients just
because the signals that differentiate
this brain disease from every other
brain disease are going to be very very
difficult to find so the the open box
method instead bills is scaffold of all
the possible ways that small numbers of
genes and biomarkers and fMRI scan
images can maybe be responsible for this
label of this disease and by using just
a small amount of data and this
representative scaffold we can narrow
down the causes for this disease very
effectively using a few samples a small
number of data points so these open box
methods allow us to search for causes
and mechanisms and patterns in the data
and then as detectives we have to look
at those patterns open the box and
figure out what those patterns represent
in terms of biology so how do we do this
detective work given that we have
patterns that we find patterns in these
complex datasets we can now attach each
of those patterns to specific processes
in the cell that lead to disease and the
effects of those diseases back on the
cell and once we know these we can start
thinking about labeling causes
how to draw diagnoses out of early stage
patients with a particular disease and
then treatments that treat the disease
and not necessarily the symptoms so
let&#39;s go in a little bit deeper to this
open box approach for the problem of
thinking about gene expression levels so
let&#39;s say I have 500 patients and gene
expression levels for those patients in
the 20,000 genes that may be expressed
in whole blood so this will be a whole
blood sample but instead of gene
expression levels I should say we can be
talking about genotypes from people
across the world or lab and vital signs
from patients in a hospital so let&#39;s say
then that we can also separate our group
of patients into those with heart
disease and those without to heart
disease so the first thing we might do
with an open box method is compute the
average gene expression levels for those
20,000 genes for the patients with heart
disease and the average gene expression
levels for those without heart disease
and then we can compare those averages
very naively to see which genes
expressed differently and the heart
disease versus the not heart disease
patients but in my work we go a step
further and if you think about each of
these patients none of their gene
expression levels will be exactly like
the mean the average but those patterns
hidden in how the genes vary from the
average so in particular now I can think
about pairs and groups of genes that
differ from the average gene expression
levels in a coordinated way and this
coordination gives us clues about what&#39;s
going on in the data so what could these
coordinated patterns represent well
sometimes it&#39;s is biological information
that we can use so for example it&#39;s
possible that some genes vary from the
average because there&#39;s different
proportions of immune cells in those
patients which may mean they&#39;ve started
to fight an infection it could be
because there&#39;s rare genetic mutation in
some of these patients that actually
upregulate two or three genes in just
those patients it could be because
there&#39;s some cells that have already
started a precancerous program and you
can already see the evidence of this in
the changes in a handful of cells away
from the mean differences from the mean
could also come about because two
samples were run on different machines
or actually a different technician in
the lab prepared the sample slightly
differently
these could be representative of
biological factors about the patient&#39;s
like their age their sex or their
ethnicity they could even be lifestyle
choices so we found genes that vary from
the average according to whether the
patient was a tobacco smoker or not so
this really encapsulates why this open
box approach is so powerful in medicine
to me because a limited number of
samples can find these hidden patterns
of variation and then with detective
work we can actually put labels name
each of those patterns of variation
according to their causes and their
biological sources so I want to tell you
quickly about three success stories
about open box science that came out of
my group recently so the first one
involves a paper that was published last
week and the goal of the paper was to
describe how mutations in a genome
impact expression levels differently
across healthy human tissues 44 healthy
human tissues and my role in this
project was to consider mutations
identify mutations in the genome that
affected gene expression levels for
genes that were not located on the same
chromosome as that mutation so we have
23 chromosomes in humans and let&#39;s think
about what this actually involved so
there&#39;s four million measurements of
mutations in a genome we were thinking
across 44 different human tissue types
there are 20,000 expressed genes in each
of these tissue types so we melted our
core by running three point five
trillion statistical tests to identify
what ended up being only about 500
associations okay
so let&#39;s actually look at one of those
associations and talk about what we did
to follow up on this
so in thyroid cells we found that
there&#39;s a mutation that affects the gene
expression levels of two genes off of
the chromosome and only in thyroid sorry
this is a scatterplot of the 44
different tissues and that top one the
green one is thyroid this is actually a
sample a tissue sample from one of our
donors in this projects of their thyroid
and we found this association it was
very exciting because it turns out that
this mutation in previous study has been
associated with a higher risk of thyroid
cancer so it feels like Rhonda
thing here so being a detective we
looked around the region of this
mutation on the genome and we found that
there is a gene really close to this
mutation called foxy one so foxy one is
special because it&#39;s a thyroid specific
transcription factor which means it&#39;s
only expressed in thyroid tissues and
that when it&#39;s up regulated in thyroid
tissues that there&#39;s a cascading effect
and many other genes in thyroid are also
up regulated so this was really exciting
again we feel like we&#39;re onto something
but when we looked at our blackbox
statistical methods that throw away all
of the variation that can&#39;t be explained
we couldn&#39;t find any association between
the mutation and foxy one and all of
these genes that it&#39;s supposed to affect
that&#39;s when we open the box we applied
these statistical methods that allow us
to go in and inquiry what&#39;s going on
here and not only did we find an
association between the mutation and
foxy one and many genes downstream but
we were able to replicate the signal in
a sample of 500 cancer tumor cancer
patients with with thyroid cancer which
is quite astounding for signals this
this small so the second story I wanted
to tell you about has to do with the
genomics of tissues so for the exact
same study that I&#39;m talking about we
actually had slides of tissue samples
pathology images from about 2,000 of the
samples that were matched with gene
expression levels so these samples
represents tissue samples from a from a
donor where they stain them and put them
under a microscope and take a photograph
of them and that&#39;s what you&#39;re seeing
here these are cerebellum and cerebral
cortex samples so what we did by opening
the box this time was actually find not
just coordinated patterns of variation
in gene expression but small sets of
genes that were coordinated with image
features so in other words when these
genes were differential so were these
sets of image features and again opening
the box we were able to as far as I know
for the first time identify a mutation
that in individuals with two copies of
that mutation have brain tissue that
looks one way and zero copies of that
mutation have brain tissues that look
another way and we were able to do the
exact same thing with a muscle mutation
for muscle tissue where in
with two copies of that mutation had
muscle tissue that looked quite
different from individuals with zero
copies of that mutation so the third
story is about open box machine learning
to assist doctors so here we&#39;re
collaborating with doctors at the
University of Pennsylvania Hospital and
they gave us access to 270,000 patients
in their inpatient setting in the
hospital setting and our goal in this
study was to learn how to recommend to a
doctor when to remove a patient from a
ventilator from a mechanical ventilator
so doctors are conservative when they
remove a patient from a ventilator
because they they don&#39;t want to have to
re ventilate that patient understandably
but there&#39;s actually negative impact to
keeping a patient on a ventilator too
long they may develop infection or
dependency and so of course our machine
learning method which was able to look
across these 270,000 patients can start
giving doctors recommendations but if
you&#39;re a doctor there&#39;s no reason you&#39;d
accept a machine telling you what to do
because the Machine hasn&#39;t been to med
school like you have you need some
evidence that it&#39;s the right thing to do
at that time so along with this
recommendation our system tells the
doctors what signs what vital signs and
what lab results what about the
patient&#39;s take it gives it a reason to
recommend that it&#39;s time to remove a
patient from a ventilator in other words
in all the patients that this machine
has seen so far how do the signs and
symptoms suggest that this patient is
going to do well off of a ventilator and
then how can I communicate that to a
doctor so that they will follow this
recommendation and this is a particular
example where 40 hours before the doctor
removed this patient from a ventilator
our recommendation system said it was
probably safe to do so so I&#39;m gonna very
briefly tell you about two of the
methods that I use in open box machine
learning one is called sparse factor
analysis so this Y matrix is exactly the
matrix that I&#39;ve been talking about
where we have samples or patients or
donors and 20,000 gene expression levels
everything after the equal sign is what
we have to learn in this scaffolded
model of nature okay and in particular
when you think about these the columns
of my lambda matrix the K columns each
of those are going to be a component
the variation in other words they&#39;re
gonna be a subset of coordinated genes
that differ together and the key about
that is that there&#39;s only gonna be a
small number of genes so once I fit this
model I can go back and look at each of
those K components find those small sets
of genes that have coordinated variation
and dig into it using my detective work
and my understanding of biology to
understand what is going wrong with
those particular sets of genes so sparse
canonical correlation analysis takes us
one step further and not only find small
sets of genes but also coordinates that
with another type of observation in this
case we looked at image features and now
it&#39;s not only finding sets of genes that
differ coordinated way but sets of image
features that are also coordinated and
this allows us to actually pair multiple
data types and multiple data sources so
that&#39;s very exciting so there&#39;s two real
difficulties in applying these methods
to real data problems and the first one
is you need to actually know a lot about
the domain you&#39;re working on or else you
can&#39;t build this scaffold in the
appropriate way and you can&#39;t do the
detective work in a precise way that I
can&#39;t solve for you but the other one is
that the availability of these methods
is not as ubiquitous as for example deep
learning is right now so there&#39;s a lot
of software tools that allow you to do
this but not a lot that allow you to do
sparse canonical correlation analysis so
I&#39;m working with software engineers
right now to try and get these methods
develop free for use for everyone and I
hope that people in science will take me
up on it so now I want to tell you about
the next question I want to answer the
next why I want to find out
so last March my mother passed away from
complications due to Lewy body dementia
LBD is a neurodegenerative disease where
you have symptoms that include memory
and behavioral problems and parkinsonian
like stiffness in your muscles you
shuffle Lewy body dementia is impossible
to diagnose before death so you have to
die and have an autopsy to definitively
find this diagnosis and how you find it
is that you have a brain tissue like the
one you see above with a Lois body in it
which is that brown blob the problem is
that even if you give drugs to treat
Lewy body dementia none of them actually
treat the causes because we don&#39;t really
know the causes of Lewy body dementia
and in fact if we treat the symptoms
often these drugs are counterindicated
so you try and treat the parkinsonian
like symptoms the memory and behavioral
symptoms get worse and vice-versa so I
think we have a lot of the data that we
actually need to start putting the
pieces together and solving this problem
in an open box way so in other words we
have mutations that are related to
dementia broadly defined not necessarily
Lewy body from genome-wide Association
studies we understand how mutations
affect brain cells and tissues from this
work that I told you about earlier and
we have a lot of images of post-mortem
individuals from autopsies of people
with Lewy body dementia so I feel like
we just need to build these open box
models to be able to put the pieces
together and then in an iterative way
start building new models new scaffolds
of how we might generate new hypotheses
from the signals the patterns that we&#39;re
finding in these data and maybe even go
out and produce some enabling data to
answer the questions more directly but
the implications of doing this of
putting these pieces together are
gigantic if we can figure out the causes
whether they&#39;re genetic or environmental
of Lewy body dementia if we can diagnose
these patients not after death but
twelve years before they actually end up
dying from Lewy body and if we can treat
not just the symptoms but the causes of
Lewy body dementia we&#39;re talking about
solving diseases here which is something
I think really important everyone every
one of us just by nature of being human
is curious and there are specific
questions we have about the world and
about nature and I hope that you will
think next time you have a question that
you&#39;d like to solve and a mystery you&#39;d
like to address so you think about using
the tools in open box science to be able
to build boxes for the betterment of
mankind thank you
[Applause]
