
[Music]
I&#39;m super excited to talk to you today
about the present and future of
artificial intelligence whenever there&#39;s
a buzzword and a complex subject matter
it&#39;s usually good to start with a
definition but it&#39;s actually a little
tricky because the definition of
artificial intelligence seems to be
constantly moving whenever we solve a
problem we don&#39;t quite call it
artificial intelligence anymore
it started with chess a lot of smart
researchers looked at other smart people
and thought well we&#39;re really good at
math and logic and playing complex games
like chess and so they started working
on those kinds of problems thinking that
once they solve them a lot of other
things will just fall into place but it
didn&#39;t quite because those were
simulated environments that didn&#39;t have
the right to the same kind of noise that
we have in the real world
so now research has actually shifted
largely from playing games which is
still an important area and can feature
some things - things that we didn&#39;t used
to consider as that much of high
intelligence just understanding spoken
words seems relatively simple we can all
do it but that was actually a really
hard problem up until 2010 when deep
learning changed it and is able to make
much more progress on this and now we
don&#39;t call it AI anymore it&#39;s just Siri
it&#39;s just a speech recognition software
but that was a really hard problem that
we weren&#39;t able to solve and there&#39;s
still some tricky issues in research in
it another area that deep learning has
made a huge amount of progress in in
recent years is computer vision namely
image classification and this is the one
time I&#39;ll try to explain a little bit to
you what these kinds of models do and
how they work one of the most important
ideas of recent years in the AI is to
have so-called end-to-end trainable
models where we take in raw input for
instance the pixels of an image and want
to predict a final output for instance
is there a cat or a dog or house or
clock in that image and so as we put
that raw input the pixels into these
models they keep trying to learn more
and more complex representations so as
they
start looking at the pixels the first
layer might only identify simple edges
and blobs which actually turns out to
also have good correlation to the early
visual cortex in the human brain but
then as they go to the next layer they
combine these blobs and colors and edges
to more complex textures and then as
they go further and deeper into these
different layers they&#39;ll identify object
parts and eventually combine those
object parts to identify full objects
and that was really really hard and
initially people tried to manually
identify oh if there&#39;s a cat then maybe
their whiskers here then this might
improve to increase the probability of a
cat and things like that and now this
entire process all these visualizations
that you see here on this slide they&#39;re
all learned automatically just by giving
it a lot of supervised data here&#39;s an
image and it&#39;s pixels here&#39;s the output
that we care about
now we&#39;ve actually been able to combine
in computer vision even with some
language processing and we can do quite
amazing things in the last couple of
years here you see a visualization of a
recent paper of collaborators of mine
where we color code where the algorithm
is paying attention to as it&#39;s trying to
generate a description of an image so
you have a little girl sitting on a
bench holding an umbrella and you see
that indeed when it&#39;s generating the
word girl it is looking at the girl when
it&#39;s generating the bench it is focusing
its attention on bench or a zebra
standing next to a zebra in a dirt field
these are very factual descriptions
we&#39;re not gonna get very interesting
ones from them but indeed the first
zebra it&#39;s focusing its attention on is
the one in the foreground and then to
the next zebra it&#39;s actually the one in
the background and you see that color
coded too so computer vision algorithms
have gotten a lot more sophisticated and
actually also telling us a little bit
where they&#39;re paying attention to as
they&#39;re trying to translate from visual
data into text it gets even further we
can also do so-called visual question
answering this is an interesting task
where you basically as training data
give it an image a question and an
answer and now you want to probe the
algorithm you can ask it lots of the
some kinds of questions about an image
and you see if it still gets dried or
not so the example here at the top what
color are the bananas is a good one
because if you didn&#39;t know the image in
90% of the cases you&#39;d probably be
correct just saying yellow without the
image but we have here the visualization
also of where the algorithm is paying
attention to as it&#39;s trying to answer
this particular question and it&#39;s
actually focusing its attention on the
brighter areas in that image and
realizes those bananas are actually
green and gives the correct answer
another fun one what is the pattern on
the cat&#39;s fur on its tail it actually
focuses most of its attention again in
that bright area on the cat&#39;s tail and
correctly identifies this as striped and
another fun example what is the boy
holding it&#39;s actually figuring out based
on the question that you now need to
focus your attention on the arm and the
object below the arm and correctly
classifies this as surfboard so those
are some of the great applications that
we&#39;re now able to do as long as we have
enough training data about a certain
domain if you never show at a baseball
image and it&#39;s training time it won&#39;t be
able to answer any questions about
baseball they actually even more
powerful applications that we can now do
with computer vision one of the ones
that I&#39;m very excited about as in the
medical field particular oncology this
is a small start-up a felis that
actually is automating blood cell
counting so you can make it very small
pricking your finger and you can count
blood cells with the same kind of
architecture as the one I showed you
before it&#39;s a convolutional neural
network and now that you make this so
cheap this used to cost a couple hundred
dollars to have people actually sit
there and for each blood sample count
how many red or white blood cells they
are now that you can make this much
cheaper you can prove oncology care you
can identify infections and help
patients with leukemia and so on in
general I think radiology will also have
a huge impact with AI the problem with
radiology is that we need a lot of
trained data because unlike in a blood
scan or pathology scan you&#39;re looking
for a thousand different things that
could be wrong in a head CT
a scan and it will take us a while
before we could automate that entire
process so for a very long time
AI will work together with radiologists
to improve that process and in fact we
already know that we can identify
certain things that can very quickly
kill you so for instance a stroke or a
so called intracranial hemorrhage brain
bleeds those we can identify very
quickly and then without knowing all the
other things that might be wrong in a
head CT scan we can put those to the top
of the queue in an emergency room
setting and that can already save lives
now we talked about computer vision and
speech recognition as two successes of
AI there&#39;s actually still some areas
that we&#39;re struggling with and that is
motor control this is a DARPA Grand
Challenge and a bunch of examples of
some very expensive robots that are
trying to walk around open doors turn
levers and things like that and as you
can see we&#39;re still quite far away as a
community in fact you could say that
we&#39;re not even at the level of Abby yet
when it comes to motor control abby is
actually quite complex has a million
neurons it needs to identify a lot of
different paths and so on and we&#39;re not
there yet so that is a very active area
of research one of the most interesting
manifestations of human intelligence I
think is language and in language making
a huge amount of progress right now but
there&#39;s still a lot of ways to go so
here&#39;s an example I think we could bed
do better now but this is from 2011 when
folks realized that whenever Anne
Hathaway famous actress won a couple of
Oscars starred in a movie the reviews
came out all the sudden the stocks for
the company Berkshire Hathaway go up a
significant amount so it was already
clear in 2011 people were trying to use
natural language processing for
algorithmic trading and in this case
made the mistake of so-called entity
disambiguation they disambiguated a
Hathaway to the company instead of the
actress and then made pretty substantial
monetary decisions
where we have gotten better an NLP is
actually on just text classification in
fact here are a couple of examples of
sentences that up until two years ago
pretty much every algorithm out there
would have incorrectly classified the
first sentence is in its ragged cheap
and unassuming way the movie works so
traditional algorithms would have said
well it&#39;s ragged and cheap so it&#39;s
probably negative sentence because they
haven&#39;t had the ability to capture the
whole context but now and what you see
here is we actually have two passes over
that sentence and in the second pass the
algorithm focuses much more on works the
movie actually working despite its flaws
so it correctly classified this as
positive and the second one is the
opposite kind of example the best way to
hope for any chance of enjoying this
film is by lowering your expectations
again a kind of example that is quite
tricky because algorithms in the past
would just look at single words and has
best and hope and chance and enjoying
such a positive sentence yet you can
only get there if you already think the
movie is pretty crappy so those are
examples that we can now do largely
because of advances also again in deep
learning there&#39;s some active areas of
research that we still work on and one
of them is text summarization it&#39;s
actually a really tricky problem pretty
much every natural language processing
in a model that you&#39;ve seen in the past
only can generate at most a sentence
coherently once tried when we tried as a
community to generate longer sequences
fully automatically in this end-to-end
deep learning models which usually
didn&#39;t do very well so this is a result
from just a couple of months ago where
our group worked on summarization and
you see here at the bottom a longer
document and at the top you see the
summary and what&#39;s fascinating here is
that it actually the summarization
algorithm learned to some cases copy and
paste particular words sometimes entire
phrases but sometimes it also picks and
chooses which words to pick from which
area of the longer document in order to
generate the summary in many cases
actually generates coherent longer
document summarize summaries and as the
summary correctly says to do this really
well still remains an open research
problem one of the areas of NLP that I&#39;m
personally most excited about is
question answering because you can
actually think of question answering as
a task that encompasses pretty much
every other NLP task you can ask what is
the translation of the sentence into
French you can ask what is the sentiment
you can ask what is the summary right in
some ways everything becomes a question
answering problem if you have a really
powerful question answering model and so
here we worked on this regrade data set
that stanford collected called squad
with stanford question answering data
set that takes lots of wikipedia
articles and then asks crowd workers to
collect questions and then also
different guard workers to collect the
answers and the models that you now see
that dwell on this task are much more
complex than a model I showed you in the
beginning that had the same kind of
layer just learning more abstract
representations language by itself also
seems to require a lot of distributed
computing in our brain that takes a lot
of different parts and elements now what
makes me really excited and looking
forward to this to the next couple of
years is the number of people that are
now entering the field it&#39;s there&#39;s a
lot of excitement in AI and just in a
class I echo talked with Chris Manning
earlier this year we had over 660
students at Stanford attending that
class even though it&#39;s a graduate level
class and there are hundreds of
thousands of views on YouTube of pretty
technical material and that is very
exciting but as we see AI actually
working we have to acknowledge also that
it&#39;s just a tool and it will stay a tool
for the foreseeable future we don&#39;t
really have to worry about Skynet or
terminator kinds of scenarios but what
is important is to understand that tools
can be used in good ways and in bad ways
in some ways AI is just like the
internet or hammer or cars and you can
use them as weapons or you can use them
to transport sick people and it&#39;s
important for us to acknowledge that
the tools are only as good as the people
and the political systems that end up
using them in fact if we use them well I
think AI and especially AI power
language capabilities will allow us to
improve our communication pretty sure we
can eventually have the Babel Fish in
the next couple of years where we talk
in one language and we listen in another
one coming live at the other end we can
improve access to information question
answering is a great example for that
and in general make work much more
efficient in fact I think we&#39;ll be able
to automate most of the basic human
needs like food we can automate farming
with computer vision and some simpler
robotic control we can build houses
automatically and so on I think in the
end as human intelligence and
productivity gets enhanced I hope that
that will lead us to a future where we
can focus on unique and creative tasks
and those kinds of tasks that require
empathy and where we care for each other
and we can basically automate a lot of
the boring treachery that is out there
what&#39;s important to acknowledge is that
AI is only as good as a training data
that we give it if your training data is
sexist or racist then the I will pick
those patterns up and in some cases
repeat them or even amplify them so as
we&#39;re applying AI to more and more
different areas in simple things like
loan applications but also more complex
things like the financial system or the
judicial system and medical applications
and political advertisement and so on
they I will eventually be in all of
these areas I think it&#39;s important that
we think about regulations or at least
guidelines to prevent the negative
effects that could happen and that may
have already been in our training data
and lastly it&#39;s not just the data that
might have biases is also the communion
itself and the IEEE community right now
it&#39;s actually quite aware that we have a
diversity issue and that is some
that we continue to work on all right
thank you
[Applause]
