
I spend most of my day in front of
computers so I tend to take shotgun
whenever I take a shared ride this one
time I happen to mention that I&#39;m on my
way to give a talk about artificial
intelligence the driver&#39;s eyebrows go up
y&#39;all make robots we got enough trouble
without robots of course I don&#39;t know
the exact pattern of electromagnetic
signals going through his brain at that
moment but I can guess Skynet Terminator
healthcare I say I work in healthcare we
match patients to treatments ah you
decide who gets what and all of a sudden
despite being a generally small
unassuming female I have become the man
what can we do the thing is though thing
is he does underscore a very legitimate
concern a eyes while extremely powerful
are also extremely literal an extremely
literal problem-solving combined with an
inaccurate problem definition that was a
reason behind our most recent mortgage
crisis truth be told
an AI task to find the most cost
effective treatments to cancer would
probably choose to end lives rather than
save them that said I see great
potential for a is to improve our lives
in healthcare we have too much data
electronic health records social media
all of the published literature it&#39;s far
too much for us humans to be able to
consume in my lab we leverage these
massive data so on
Stan how we can personalize treatment
for HIV and depression to understand the
trajectories of children with autism all
of this would be impossible without AI
but if we&#39;re going to reap the benefits
of what a eyes have to offer we must
find ways to hold ai&#39;s accountable today
I&#39;ll tell you one way through
explanation but first let me make the
challenges a little more clear where I
work most of my data comes from
electronic health records these records
only contain views of the patient when
they&#39;re very sick they are entered by
overburdened conditions who see no
benefit for their labor and as a result
values often go missing or even worse
are it left at incorrect defaults and
that&#39;s just the start couple years ago
my colleagues and I designed a system to
identify who was at high risk of dying
in the ICU and we fed it all the volumes
of data that we had available from the
physiological monitors to all of the
clinicians notes everything and we got
some Rock awesome au C&#39;s we were doing
great at predicting when patients were
likely to die our clinicians were like
how this is amazing so we started
digging and what we discovered is that
oftentimes our AI is we&#39;re not actually
using the volumes of data that we were
making available to them instead our
super fancy AI had discovered that when
the clinician writes down the word
chaplain in the clinic note it&#39;s often a
bad sign yeah so you know our patients
were suffering from sepsis and our AI
had a really bad case of causality
leakage you see what had happened is
that the clinician realized that the
situation looked grim asked for the
chaplain
and then an unfortunate event occurred
meanwhile our a I notice the action that
the clinician had taken on us using that
action to make excellent predictions
about what the clinician already knew it
was situations such as these that
brought me to realize the value of AI
systems that can provide explanation for
their decisions because while
explanation alone cannot guarantee
causality or fairness or safety or any
other hard to explain to a literal
computer objective having some insights
into an AIS logic can help us identify
when its recommendations are sensible
and when they are not
unfortunately a eyes are astoundingly
complex modern a eyes have millions upon
millions of parameters operating on tens
of thousands of compute nodes terabytes
of memory petabytes of data and us
humans seven plus or minus two seven
discrete ideas or thoughts that&#39;s about
all that our memories can hold at one
time so well I guess there goes the
explain ability plan if we wanted a eyes
that were explainable we&#39;d have to make
them so simple that it would defeat the
purpose of a tool that we could give
large amounts of data in the first place
and even if we could magically
understand all those bits and all those
registers forcing companies to reveal
such detailed information would destroy
trade secrets and hamper innovation so
faced with these realities must we
choose between accountability and
progress well no I&#39;ve been working with
bean Kim Sam Gershman and colleagues of
the Berkman Kline Center to understand
how we can have both and the key point
is that explanation is distinct from
transparency when I ask another human
for explanation I am NOT looking for the
flow of electricity through their
neurons and similarly when I ask an AI
for explanation I am NOT looking for the
flow of bits through its registers I&#39;m
looking for something that I can
understand and utilize let&#39;s talk a bit
about what that looks like so for now
I&#39;m going to focus on the case called
local explanation
so that&#39;s explanation for a specific
decision in my world in healthcare this
corresponds to why this patient got this
drug rather than trying to explain all
the hairy process of how drugs are being
recommended overall this notion of
context is extremely important cognitive
science research shows that humans
naturally give explanations tailored to
the context at hand a clinician might
give one reason why an elderly patient
was given a drug and that explanation
might be completely different for why a
different drug was given to a younger
patient with maybe some unlucky genetics
as humans we don&#39;t expect these
explanations to be the same or even
consistent what we do expect is that the
explanation hold for similar
circumstances something that I&#39;m going
to call local counterfactual
faithfulness for example suppose that
you were denied alone and you were told
it was because you hadn&#39;t paid your last
3 but then it turns out there&#39;s a
bookkeeping error right it&#39;s all good
you actually did pay your last three
loans well you would expect to get the
loan but then suppose that you had been
denied your loan because of insufficient
income then you wouldn&#39;t expect no one
in this room would expect
that if your prior payment history
changed the decision the loan decision
would change right so here&#39;s how we have
expectations where we only expect to
produce outcomes for similar related
circumstances these notions these human
notions of what we want from systems are
good for designers of explainable a is
in particular ideas such as local
explanation and local counterfactual
faithfulness just mean that we have to
explain a small part of an a i&#39;s
decision-making logic the part that&#39;s
relevant for the context at hand even
better simple local boundaries the kinds
that are easiest to explain are often
also the best predictors knowing what we
want from explanation though also
highlights what&#39;s going to be hard as
humans we have ways to convert all the
firings of our neurons into warts but a
eyes don&#39;t currently speak our language
they deal in pixels and power spectra
and the patterns of characters across a
page explanation in terms of those
inputs would be incomprehensible to
humans but these pixels often do
correspond to things that humans do have
names for higher-level concepts for
example a collection of pixels might
correspond to hippopotamus or a cat a
collection of lidar measurements might
correspond to a tree the fact that a
patient is taking lithium and has had
anesthesia for electroconvulsive therapy
might suggest that the patient has
bipolar disorder what&#39;s missing is a
common vocabulary for these higher-level
concepts creating this higher-level
vocabulary though is going to require a
joint effort
on the computational side there&#39;s
ongoing research to create ia eyes that
share a language with humans and in my
lab we&#39;ve used ontology zuv how diseases
are related to each other in order to
provide succinct summaries of disease
and progression the harder question in
this case is how to makes us systems
faithful under counterfactual reasoning
for example if I want to know if my
system would have recommended the same
drug had the patient not been obese it
would be nonsensical for me to change
the weight input without also changing
the BMI on the policy side creating a
common language is going to require
labels and examples even when those
labels are sensitive our current notion
is that justice is blind if there&#39;s
information that shouldn&#39;t be used in a
decision we should just never collect it
the trouble with this notion is that AIS
are very good at reconstructing things
that they&#39;ve never seen before for
example given your location your
browsing history your purchasing history
all things that companies can very
easily buy an a I could probably
reconstruct your gender and race very
accurately and if we&#39;d never collected
that information about race or gender
we&#39;d never know that our system was
inadvertently discriminating that&#39;s why
now we have to think about AI with our
eyes open in we must give a eyes the the
sense of potentially sensitive
information so that it does not
inadvertently reconstruct information
that it shouldn&#39;t be of course this
creates a host of nuanced questions like
how do we keep the humans who are
programming the AIS with a sensitive
information from misusing it even while
our AIS are not and finally creating a
joint language is going to require all
of us being ready to learn new concepts
presented to us by our a eyes
concepts that are end up being highly
predictive or useful for tasks but we
don&#39;t have names for it right now
before I finish I started out with the
question of how we can hold the eyes
accountable and I just want to make
clear that explanation is just one tool
it&#39;s best for situations when the
problem is incomplete and we need to
check the system&#39;s logic in other
situations we can rely on proofs or
guarantees our encryption systems are
provably secure and there&#39;s no further
explanation required or we can rely on
statistical evidence if a new product
recommendation system increases sales
maybe we&#39;re happy that with that and no
further explanation is needed either the
point is we have the tools to create
beneficial AIS and we must a short while
ago I visited my uncle in the hospital
he just suffered a dangerous drop in
blood pressure not due to the heart
condition that brought him in but
because someone had missed some data and
prescribed him too much diuretic maybe
humans can only deal in seven slots but
such errors are unconscionable when we
have machines that can manage at all to
not use our tools to synthesize and
manage all of our health care
information is to accept all our current
harms due to our current human inability
inaction is a choice and it is a choice
with consequences that said a eyes are
extremely literal and they may act and
incorrect in unexpected ways and thus we
have the moral imperative
to use these systems wisely I&#39;m
convinced we can I&#39;m convinced that we
can take advantage of all the potential
for good that a eyes have to offer while
also holding them accountable a eyes are
not so impossible to understand and we
can and sometimes should demand
explanation from them and if you
continue to doubt take a look at the
beautiful computing system seated to
your right and here left with billions
of neurons firing away and patterns that
are far too complex for you to follow
and yet you understand them it sometimes
takes attention and work but it is
possible and so too it is with our
machines thank you
[Applause]
