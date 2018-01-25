
[Music]
Oscar sharp I&#39;m Ross Goodwin it starts
quite a while back we haven&#39;t even met
yet and I&#39;m in London and I&#39;m trying to
be a director of films and theater and
I&#39;m trying to understand how you can
make something that is classical and
original and personal how can it be sort
of embodying of the form how can it
innovate on the form and how can it
still say something that&#39;s quite a lot
but a tall order and it&#39;s a it&#39;s the the
classic dilemma for a creative person
I&#39;m sitting for this reason in a room
and watching an actor do this so it&#39;s
quite an odd thing to watch happening
obviously um the reason I&#39;m watching it
is I&#39;m in this workshop and I don&#39;t know
why I&#39;m watching and the person running
the workshop says so what did you just
see happen what was that like oh well
obviously this is a person who&#39;s a bit
worried about the shoe on the floor
maybe a bit disgusted by it maybe they
don&#39;t really like brokes or Oxford&#39;s or
whatever these anyway it turned out that
the things that actor were doing was a
random list of actions they&#39;ve been
assigned those actions randomly and
they&#39;ve been pulled out of I thought god
that&#39;s interesting is a kind of a story
seemed to be there everyone in the room
agreed that they&#39;ve seen some of those
story I&#39;m like did that come from the
actor did that come from me I&#39;m not sure
but how far can we push this can we go
further we can we can we make these
lists of actions longer so I decided to
build a machine that made longer lists
of actions and the machines looked like
this it was a pair of dice because I
actually can&#39;t build machines so I
rolled the dice over and over again made
longer and longer lists and and it still
kind of worked and I studied as they got
longer they can either broke down a bit
so I started applying rules of
story-like
complication resolution and crisis and
conflict in it it still kind of held up
until I tried to apply it to dialogue
here is a piece of dialogue made with
dice
copper explained ill-fated truck neat
unites bronze educated tenuous hum
decisive notice it wasn&#39;t very good I
had a problem I couldn&#39;t make the speech
work I really needed someone who knew
about speech meanwhile I was working as
a political speech writer I worked on
the Obama campaign 2008 then at the
White House for a year then a Treasury
for two years and then I went out on my
own to be a freelance political ghost
you know during that time I was also
learning to code I was teaching myself
and I immediately gravitated toward this
broad and expanding world of natural
language processing and natural language
generation which are they the terms for
those fields that deal with natural
language as opposed to computer language
and I got really obsessed with trying to
find ways to make my writing process
he&#39;s more efficient using computation so
I developed techniques like this where
I&#39;d write in a spreadsheet rather than
in a Word document and if I had to write
a batch of letters let&#39;s say I&#39;d write
all the first paragraphs together down
the first row then all the second
paragraphs together then all the third
paragraphs together with one letter down
each column and a paragraph in each cell
and then every other day I&#39;d randomly
rearrange the paragraphs edit them a
little bit and handed it as a new batch
of letters so doing that I thought I
could take an eight hour a day job and
turn it into a two hour a day job but I
I was still looking for something more I
wanted to explore this type of thing in
a more creative context so I decided to
attend the interactive
telecommunications program at New York
University which is sort of like art
school for engineers or engineering
school for artists and I was seeking a
more creative context for this work and
which floor was it on Ross there&#39;s on
the fourth floor right fourth floor and
meanwhile I was on the tenth floor you
see I in my pursuit of making something
classical and original I&#39;d I tried doing
a story as a short film that was a it
was it used it was about cancer but it
was levitation was levitation and cancer
and it was personal as well because my
mom had cancer so I done something in
this realm but not using automation and
that done well it got nominated for a
BAFTA and it got me a Fulbright
scholarship and brought me to NYU to the
tenth floor but I would sometimes get
off early on the fourth floor into this
Willy Wonka Wonderland of tech geniuses
where you find people like Ross building
well he didn&#39;t do this but robot
jellyfish I remember I remember a wall
of robot dildos that would follow you
around the room I&#39;m not joking that was
real it&#39;s very strange place but very
exciting place and I thought wow maybe I
can find someone in here who can help me
with these dreams that I used to have
and eventually mice to finagle my way
into a class right the class was called
surveillance documentary and we were
learning how to program
pan tilt zoom surveillance cameras for
creative applications so of course they
combined the filmmakers with the
technologies right cameras that makes
sense but as I walk in the thing that&#39;s
exciting to me isn&#39;t the camera it&#39;s
what I can see on Ross&#39;s laptop screen
because it&#39;s a poem that&#39;s writing
itself that&#39;s right it was a Markov
chain poem I&#39;m at the time I&#39;ve been
experimenting with a simple algorithm
called a Markov chain
a very old developed in 1906 it&#39;s
basically it what&#39;s called a state
machine so given the current state it
tries to predict the next state using
only the information contained in the
current state so how that translates to
words is given a sequence of words let&#39;s
say three words it tries to predict
which word would come next given the
occurrence of those three words and all
the words that come after those three
words in a corpus or a body of text so
using that you can predict the next word
over and over again to generate text so
obviously I got kind of excited and he
tried to explain to me and exactly that
way and maybe I kind of lost track about
halfway through but I was shaking him by
the lapels by this point going Ross can
we use this method to write dialogue and
I said yes why not so I tried Markov
chains on some movie dialogue and I got
results that were somewhat like this
cloverleaf will own toontown quite
legally so your cloverleaf no 1
hippopotamus is my favorite genius to
figure out what&#39;s going on here Tina
Tina you motherfucker I&#39;ll kill you like
a moth to a flame so it wasn&#39;t quite
ready for primetime I think you&#39;ll agree
round of applause to Ross though amazing
performance right so we can&#39;t quite make
a movie with that maybe we can go back
to the action stuff and I was talking to
Ross about the rules of screenplay I
said in in action in a screenplay it&#39;s
not like a novel you can&#39;t describe what
people are thinking you can only say
what you see can we use these cameras in
some way with saying what you see right
so I sort of thought about that I
thought about that really long and hard
and I thought you know how to create a
realistically descriptive action
sequence because it&#39;s not trivial with
the computer computer-generated text
especially with Markoff tends to venture
into the realms of the Unreal rather
quickly it doesn&#39;t want to stay grounded
to a realistically descriptive set of
words that might apply to a particular
image or a particular scene so I thought
about that you know and I and I realized
that there are these algorithms that are
coming
to use called convolutional neural
networks that can take an image and
extract a set of words the set of nouns
representing concepts or items found in
that image by the machine so the machine
that can quite literally describe what
it&#39;s seeing and I thought you know maybe
a set of nouns from an image would be a
good place to start and so I built this
camera that wrote poetry from images it
was called word camera and I made it web
app in a series of physical devices like
I just wonder them I can just take
Oscars picture and it&#39;ll it&#39;ll print
something based on what it sees so in
this case similarly the man has a long
hair otherwise it has a Bigfoot than
woman immediately it made journey to
Europe earlier it may fear commitment so
that&#39;s a good one of those so so I had
asked Ross for a camera which I thought
was maybe gonna write scripts based on
what we&#39;d shot and instead he made a
camera that insulted me accurately in
many cases and and and so then we get
four people following along in story
structure land a twist a complication I
got a phone call from this man did you
choose that that&#39;s not okay okay um so I
get phone calls from Tokyo Nagoya the
form of Spider Man he had seen my film
at the levitating woman he really liked
it he&#39;s a producer as well and he said
hey you want to come to Hollywood and
write your first screenplay I said oh
that sounds fun we haven&#39;t got the
Machine working so I might as well do
something so if I go to Hollywood to try
to do that to try to do something
original and and classical and personal
meanwhile I was still playing with my
word camera and I was looking for ways
to improve the output and to have more
control over the output because prior to
this I hadn&#39;t been training my own
neural nets I&#39;d been using those other
people had trained through api&#39;s and web
services and I wanted to start training
my own just to get more of a handle on
the technology and an understanding of
what was really happening as well as
just that level of control over the
output so I discovered some code on
github by a gentleman named Andre
carpathia at Stanford called char RNN
and knurl talked to you respectively
which were a long short term memory
recurrent neural net
which is a neural net that&#39;s a lot like
a Markov chain and that it&#39;s predicting
in this case the next letter over and
over again to generate text and then
neural talk to is an image captioning
system using a convolutional neural net
so I put those two things together to
make a new version of word camera and
the results were really astonishing I
was really amazed with with the tape of
poetry it was producing compared to what
extra grand a moment ago and so I wanted
some voiceover of somebody reading one
of these poems for a documentation video
I was making and Oscar has a great voice
so I sent him this poem generated by the
word camera from a picture of a clock
well yes so by the way it&#39;s Sisson
English accent I&#39;m cheating but he sends
me this thing it&#39;s 2 p.m. I&#39;m lying in
bed in Hollywood and I&#39;m depressed I
have writer&#39;s block I&#39;ve been trying to
write the screenplay that is supposedly
going to be original in classical
impersonal and I am stuck and Toby
occasionally phones me up and goes what
are you doing and I go promise but I get
this email and I open it up and turn on
my microphone because Ross is a friend
and record the following a close-up of a
clock on a wall of four o&#39;clock in the
morning I am NOT so strange and will not
delay the room is blown away from the
door and the stones are beginning to
shine the silence is hardly final
somewhere in the street I can see the
trees begin ladies and gentlemen I
experienced emotions it was a very
strange moment for me the thing is all
of this text that we generated before it
was so weird in a way that when you read
it your main emotion was that&#39;s weird
but the thing about an actor is when you
give them some stuff that just has
enough connection in it that they can
feel something you know that you can
start making drama so I immediately
found out Ross and I go grabbing those
lapels over the airwaves
I don&#39;t know how you did this Ross but
can we use it to make dialogue and I
said yes so I immediately went and
downloaded the Cornell movie scripts
corpus which is a collection of about
5000 screenplays that I ripped out all
the dialogue is at that point he just
asked for dialogue so I wanted to try
dialogue and trained on that and this is
the an example the first thing he sent
me I was so stupid I had to go to the
party I was sorry and I was wondering if
you were gonna make me cry I wondered I
wanted to be a good man I was thinking
of coming back to the
and I was missing something I couldn&#39;t
get the baby so this was better than the
stuff from rolling the dice it&#39;s still
quite weird but it was better and I
thought you know we can do this and at
the same moment I found out we were we
were one month from the sci-fi 48 hour
film challenge run by sci-fi London
which I do every single year is a really
good way of getting back into filmmaking
keeping yourself going and the way it
works is you get 48 hours they give you
a title a proper line of dialogue and 48
hours later you ever written shot cut
and uploaded a movie it&#39;s really fun and
I thought well if we&#39;re gonna use this
dialogue maybe it would be so much
better if it was the whole script but I
remember when we&#39;re doing Markoff you
Markov chains couldn&#39;t deal with
formatting so Ross I guess we can&#39;t we
can&#39;t do the whole script can we well
fortunately time L STM&#39;s can handle
formatting because this one was written
at the character level rather than the
word level and it was able given a
complete screenplay to replicate that
formatting fairly well and differentiate
between action description and dialogue
and it was really fascinating you know I
didn&#39;t say this before watching these
machines training to write letter by
letter at first they&#39;re just spitting
out random gibberish random sequences of
characters and then eventually they
learn what words are and then they learn
how to make sentences out of without of
those words and then paragraphs and it&#39;s
kind of incredible to watch yeah I&#39;ve
taught kids to write screenplays even
medium age kids and honestly our little
screenwriter was doing it better it
learns quite quickly that action is only
what you can see that something it takes
in open-toe me five or six lessons to
get into their heads
it made a dialogue that was sort of the
right length the sentences were right
they were declaratives and accusative
zan an emotional statements and it was
it was kind of learning to write
screenplays as much as they were weird
and there was still one problem which is
we have 48 hours and it had taken three
weeks to train this thing I was like we
can&#39;t we don&#39;t have three weeks to write
the screenplay well I had been training
on graphics processing units or GPUs and
why use high-performance computing
facility and I didn&#39;t have a GPU to
generate text with generating text takes
a lot less time than training but it
still takes quite a while if you&#39;re on a
CPU and you have a big model you know I
was looking for a solution and I
discovered this
Nvidia Jetson system-on-chip which is
sort of like a Raspberry Pi if you know
what that is it&#39;s like a little computer
with the GPU so using that we were able
to generate a screenplay in just a few
seconds so up there is a little
screenwriter Jetson as we called him
because
we just named him after that their thing
so there was a screenwriter in the in
the morning in three seconds flat he
wrote our screenplay we wanted to get a
wonderful team of people on board a
great group of actors including Thomas
Middleditch in Silicon Valley you may
recognize him and we had some producers
Allison Friedman Andrew sweat and you
gave us some money and we went to shoot
the film and that the best part the
whole shit was to read through just
giving these actors this screenplay for
the first time like I said they are
machines for making meaning and you give
them this thing I didn&#39;t tell them what
the story was about and just like the
actor with the shoe as soon as they read
it to each other
they&#39;d not read it and that on their own
this love triangle emerged from nowhere
it just popped into being and and
everyone was laughing it was it was a
beautiful beautiful day we shot the
thing cut it uploaded it and we made the
top ten
one of the jurors said I will give them
top marks if they promise never to do it
again another now that your said the
only thing that would enjoy this is
another computer both of those jurors by
the way were screenwriters which might
tell you something so there was a little
bit of fear involved actually it was a
bit more they didn&#39;t we didn&#39;t win but
they did decide to interview Jetson our
screenwriter at the award show and this
was the last question from that
interview what&#39;s next for you Jetson and
the answer was here we go
the staff is divided by the Train of the
burning machine building with sweat no
one will see your face the children
reach into the furnace but the light is
still slipping to the floor the world is
still embarrassed the party is with your
staff my name is Benjamin
so we got a little frightened some of us
where we start loading it and that was a
lot of the response actually was fear
there were a lot of people who were kind
of afraid they&#39;re going you&#39;re gonna
take creativity away from human beings
you&#39;re gonna ruin the one precious bit
of work that&#39;s left to us you&#39;re taking
it away and then other people just
thought it was stupid and pointless that
we were effectively tearing up a
dictionary and throwing it in the air
and sticking it together getting people
to read it out we disagree with both of
those that&#39;s right personally I don&#39;t
think there&#39;s any reason to be afraid of
this I don&#39;t think there&#39;s any reason to
think it&#39;s stupid and pointless either
enough there&#39;s any reason to be afraid
because the thing that I just got
discovered working with computational
systems and creative writing is that
when we teach machines to write the
machines don&#39;t replace us any more than
a piano replaces a pianist they become
extensions of us they become our pens in
a way and we are able to become more
than writers we can become writers of
writers and additionally there&#39;s not
really much of a reason to think it&#39;s
totally pointless because even text that
is coherent at the sentence level can be
extremely useful in certain cases you
can imagine a lyricist writing a song
and they&#39;re stuck they don&#39;t know what
line should come next well here&#39;s a
machine that given that lyricist
influences and their references can
suggest a thousand possible next lines
in just a few seconds and the lyricist
can browse those maybe find one she
likes edit it a little bit and then move
on there&#39;s known to be blocked up it
introduces new paradigms for writing and
possibly new ways of thinking about
writing any ways of thinking in general
and helping with writer&#39;s block that I
was laboring under in in in LA you
remember that well do you know what I&#39;m
writing something even more difficult at
the moment I&#39;m adapting the work of a
man called Ben Mezrich who I believe is
in the room somewhere his previous book
was adapted by by Aaron Sorkin who won
an Oscar that&#39;s kind of pressure that&#39;s
kind of writer&#39;s book inducing and Ross
trained Benjamin on air all of Aaron
Sorkin&#39;s work and now I can press a
button and get a little Sorkin
suggestion every time I need one helps
break through that barrier it&#39;s useful
for inspiration Benjamin writes
thousands and millions even of titles at
a single move one of my favorites was
the short films of lappa roost are fake
that&#39;s clearly about finding a deserted
planet where there&#39;s a box buried of the
short films about the culture that used
to live that great idea for a movie
right I&#39;d love to make that and we tried
other things we um we trained on all of
the
at the previous work of an actor you may
have heard of called David Hasselhoff
and he performed a character that was
really just a gift out version of all of
his former selves something he&#39;s sort of
been doing for the last 20 years and he
did he did that beautifully honestly I
think it&#39;s one the best performances I
really loved it and so did he I think
and that film is called it&#39;s no game if
you want to look it up there&#39;s still
other things we want to do we want to
build other stuff but for me the main
thing I&#39;ve learned is that remember I
wanted to make something that was
classical and original and personal well
I don&#39;t know these machine systems what
they seem to be good at better than any
human being has before is looking at
what humans have done and finding away
with like a fairground mirror to reflect
how all of our paths work to ourselves
which isn&#39;t that what you do when you&#39;re
trying to learn what filmmaking is or
what theatre is it&#39;s it&#39;s doing that but
it&#39;s doing it in this more sophisticated
way so it shows me what&#39;s happened
before and in a way that helps me to be
original because I can see the cliches
and then break them and as as far as
personal is concerned well every time
you&#39;re inspired by a shoe or a bit of
random something you&#39;ve seen and it
makes you think of something new I think
that&#39;s when the personal comes out so
anything that can inspire you does that
thank you so much for listening I hope
you can thank you
[Applause]
