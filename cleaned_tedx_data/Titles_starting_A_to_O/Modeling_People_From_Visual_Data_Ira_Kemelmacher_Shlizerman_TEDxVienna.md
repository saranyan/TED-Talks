
[Music]
this is my daughter she was so adorable
when she was born when she was two she
was all about pianos so everywhere we
went she wanted to play one when she saw
one when she got five she forgot about
pianos she was all about makeup and
lipsticks to tell arias then later she
was all about horses and now I have two
daughters and the stories continued and
said this is how I like to think about
my photographs I captured my experiences
my memories my photos tell a story yes
all 35,000 of them except they don&#39;t
really what they actually are 35,000
thumbnails or my harddrive in my camera
roll and you guys probably have the same
story right what we all have it&#39;s just a
digital version of the shoebox our
parents had but in our case it&#39;s a
ginormous box so I&#39;m a computer vision
researcher and I wanted to see if the
technology that I&#39;m developing the model
people from big foreign video
collections can be useful to create
stories from my own photographs and so I
had the following idea I said okay so I
have this huge photo collection I&#39;m
gonna detect the faces and all my photos
now automatically of course I&#39;m gonna
recognize all the faces then I&#39;m gonna
focus on a single person let&#39;s say my
daughter and then what I&#39;ll do I&#39;m gonna
create a huge graph out of all these
photographs where each photo is
represented by a node in this graph and
the edges represent similarities between
each pair of photographs similarities in
terms of the facial expression and if
she smiles or not in terms of the
hairstyle they had posed the time when
the photo was taken and that once I have
this graph is tablished I can teach a
computer
to walk on this graph to create a path
or if you will a story so this was
awesome and I thought okay so I&#39;ve got
the path now I can do it all right
automatically the only thing that is
missing is how to represent this set of
photographs and so I realized that
before the story part that if I&#39;ll just
take the detected faces and I put them
one on top of the other and play them
chronologically it&#39;s it&#39;s kind of
magical so see I can see how she growled
in front of my eyes and what happens now
is that there&#39;s lots of things while
it&#39;s a cool experience there&#39;s lots of
things going on right and so it&#39;s very
long and so the combination of the story
the big graph is a path plus the video
representation creates magic we can even
summarize twenty years of photographs in
30 seconds so let&#39;s watch together the
final result what you will notice is
that the person is in the focus the
transitions between the different
photographs in the final video are
really nice you can see that it&#39;s really
transition smoothly between their facial
expressions and the time and so on and
it tells the story
[Music]
thank you so this is fun I was able to
teach a computer to tell his story from
my existing photographs now the next
question that I asked I thought wow this
is kind of cool so can I actually teach
a computer to simulate what my daughter
will look like she&#39;s now nine what will
she look like when she&#39;s 25 this seems
really hard though how would I how would
I go about it so I thought one idea
right so if I do have a pair of
photographs of the same person these are
two real photos in different ages that
if I have this transition already I can
teach a computer to how to learn these
transitions but I want to do it for any
identity for any person out there in the
world so what I really need is to be
able to somehow estimate the average
transformation across all people in the
world average aging transformation to be
able to simulate later so but to get the
every transformation and it&#39;s and it&#39;s a
representation of all the people in the
world so I had the following idea if I
go to the search engine and just look
for babies I get lots of photos of
babies right here&#39;s an example and then
if I use the same technique as in the
video representation I put all the I
detect all the faces and I put them one
on top of the other but instead of
showing them as a video I will Everage
them per pixel I will get the following
result so I get an average baby and look
this is not a real photo of a baby this
is an average baby from the search
results I can do it for any age so I can
search for 25 year old male and I get a
ton of photos and then average them
again
and I get a 25 year old every male so
far okay cool this is my solution and so
now I have two photographs if you will
not real but you know and I can teach a
computer to estimate the average agent
transformation now the final step is
that we want to apply the
every transformation on any photo out
there even for a three-year-old boy here
and so the another component that we
developed is that we can apply the
average transformation on this photo but
we need to make sure that we keep the
identity of the person and so we did
that and we were able to produce from an
three year old photo of this boy
let&#39;s say 25 year old version of him
we can even produce an eight-year-old
version of him
so you&#39;ll notice that somehow the phase
changes you see the skin changes the
nose shape changed and so on and all
those are real aging changes you will
notice one thing the milk master state
at eight year old this is because the
algorithm thinks that it&#39;s part of his
identity we can do it for any type of
photographs and equality of photographs
here&#39;s one example and he colored
females and males of course and we also
tested it with ground truth is it is it
close to reality or not so we had a
photograph of one person where we had
him at age three and we also had him in
like real photographs in different
different other ages 16 and 16 and then
we applied our algorithm on the
three-year-old for of him just on the
face area so we created his synthesized
face and blended it into the head of the
real for us and we got this we did a
human study and people had a really hard
time to decide which one is real which
one is not so that was promising so I
talked about Xavier look like in the
future but you know some of you may ask
other questions that are related to our
appearance and photographs and how we
look and have you may look so I don&#39;t
know some of you may ask what if I
exercise more will I look differently do
I look good in hats yeah
what if I become vegetarian right no I
look differently maybe not so I wanted
to ask will black hair feed me okay and
so we all know it is well known that
when people change their hairstyles or
the hair color they can even become
unrecognizable it&#39;s pretty dramatic for
our appearance and sometimes research
even showed that sometimes the face is
less important than the hair actually
because we have sometimes unique
hairstyles and this is how people
recognize us and so it&#39;s scary to make a
big change without knowing if it is
gonna look nice or not and
I took a photo of me and I wanted to
answer this question and so of course I
taught a computer to do it and so I
render it myself with black hair started
to write code to create that
automatically and that looked fun so I
said okay so let&#39;s try to render myself
with different hairstyles in black hair
so I got this and that I said and then I
started turning to people and people
were excited like oh yeah that&#39;s so cool
and so I run myself is curly hair and
different colors and in fact I started
to develop it and I built it as a search
engine where I could type there anything
kind of imagine an image search engine
so I could type there India and imagine
myself in India so I could see how I
look like an Indian clothing and hair
and Sun or even go back in time and I
could write 1930 and see how I would
look like in 1930s I tried it on 80
different queries so I could see myself
with dreadlocks and with different hair
colors and styles and with shaved hair
and as a bride and in different
traditional clothing it was a lot of fun
there are many important applications to
the technology that we&#39;re developing in
modeling people from photos and videos I
will talk only about one which is really
close to my heart there are half a
million missing children out there
Justin 2016 Justin you say there are
similar numbers in other countries these
numbers are insane it turns out that a
critical component in the search for
missing children are portraits of how
they may look like in the future
sometimes people go missing for many
many years for example in this example
this woman is missing since 1963 and
what you see on the right is a sketch
that an artist is making a mate to try
to predict how she looks like to be able
to find her or here&#39;s another
sometimes the artists do photoshop&#39;s and
try to predict an age progression how so
for example in this case but who knows
if it is still blonde or if she actually
looks like this this is based on
intuitions of artists it&#39;s also very
hard to do it for half a million for us
because it just manual work in Photoshop
and so we wanted to combine the two
projects one were you imagine how a face
of a person looks like in the future and
the other one is how to imagine it
combined with a like a full portrait of
the person and so here&#39;s an example
where we take a baby photo and in the
search engine we search for a five year
old male and we combine the h progressed
the face and then create also different
hairstyles to try to imagine what if
somebody am changed the color of the
hair of this person or how he will look
like is different clothing we can
imagine how she looks like and as a 20
year old male as a 30 year old male
several examples or even as a 65 year
old male I would like to finish with
saying that computer vision allows us to
see ourselves in new lights there are
many fun and important applications and
I&#39;m so excited about the impact that
it&#39;s having and will have in the future
thank you
you
