

Chris Anderson: Help us understand
what machine learning is,
because that seems to be the key driver
of so much of the excitement
and also of the concern
around artificial intelligence.
How does machine learning work?

Sebastian Thrun: So, artificial
intelligence and machine learning
is about 60 years old
and has not had a great day
in its past until recently.
And the reason is that today,
we have reached a scale
of computing and datasets
that was necessary to make machines smart.
So here&#39;s how it works.
If you program a computer today,
say, your phone,
then you hire software engineers
that write a very,
very long kitchen recipe,
like, &quot;If the water is too hot,
turn down the temperature.
If it&#39;s too cold, turn up
the temperature.&quot;
The recipes are not just 10 lines long.
They are millions of lines long.
A modern cell phone
has 12 million lines of code.
A browser has five million lines of code.
And each bug in this recipe
can cause your computer to crash.
That&#39;s why a software engineer
makes so much money.
The new thing now is that computers
can find their own rules.
So instead of an expert
deciphering, step by step,
a rule for every contingency,
what you do now is you give
the computer examples
and have it infer its own rules.
A really good example is AlphaGo,
which recently was won by Google.
Normally, in game playing,
you would really write down all the rules,
but in AlphaGo&#39;s case,
the system looked over a million games
and was able to infer its own rules
and then beat the world&#39;s
residing Go champion.
That is exciting, because it relieves
the software engineer
of the need of being super smart,
and pushes the burden towards the data.
As I said, the inflection point
where this has become really possible --
very embarrassing, my thesis
was about machine learning.
It was completely
insignificant, don&#39;t read it,
because it was 20 years ago
and back then, the computers
were as big as a cockroach brain.
Now they are powerful enough
to really emulate
kind of specialized human thinking.
And then the computers
take advantage of the fact
that they can look at
much more data than people can.
So I&#39;d say AlphaGo looked at
more than a million games.
No human expert can ever
study a million games.
Google has looked at over
a hundred billion web pages.
No person can ever study
a hundred billion web pages.
So as a result,
the computer can find rules
that even people can&#39;t find.

CA: So instead of looking ahead
to, &quot;If he does that, I will do that,&quot;
it&#39;s more saying, &quot;Here is what
looks like a winning pattern,
here is what looks like
a winning pattern.&quot;

ST: Yeah. I mean, think about
how you raise children.
You don&#39;t spend the first 18 years
giving kids a rule for every contingency
and set them free
and they have this big program.
They stumble, fall, get up,
they get slapped or spanked,
and they have a positive experience,
a good grade in school,
and they figure it out on their own.
That&#39;s happening with computers now,
which makes computer programming
so much easier all of a sudden.
Now we don&#39;t have to think anymore.
We just give them lots of data.

CA: And so, this has been key
to the spectacular improvement
in power of self-driving cars.
I think you gave me an example.
Can you explain what&#39;s happening here?

ST: This is a drive of a self-driving car
that we happened to have at Udacity
and recently made
into a spin-off called Voyage.
We have used this thing
called deep learning
to train a car to drive itself,
and this is driving
from Mountain View, California,
to San Francisco
on El Camino Real on a rainy day,
with bicyclists and pedestrians
and 133 traffic lights.
And the novel thing here is,
many, many moons ago, I started
the Google self-driving car team.
And back in the day, I hired
the world&#39;s best software engineers
to find the world&#39;s best rules.
This is just trained.
We drive this road 20 times,
we put all this data
into the computer brain,
and after a few hours of processing,
it comes up with behavior
that often surpasses human agility.
So it&#39;s become really easy to program it.
This is 100 percent autonomous,
about 33 miles, an hour and a half.

CA: So, explain it -- on the big part
of this program on the left,
you&#39;re seeing basically what
the computer sees as trucks and cars
and those dots overtaking it and so forth.

ST: On the right side, you see the camera
image, which is the main input here,
and it&#39;s used to find lanes,
other cars, traffic lights.
The vehicle has a radar
to do distance estimation.
This is very commonly used
in these kind of systems.
On the left side you see a laser diagram,
where you see obstacles like trees
and so on depicted by the laser.
But almost all the interesting work
is centering on the camera image now.
We&#39;re really shifting over from precision
sensors like radars and lasers
into very cheap, commoditized sensors.
A camera costs less than eight dollars.

CA: And that green dot
on the left thing, what is that?
Is that anything meaningful?

ST: This is a look-ahead point
for your adaptive cruise control,
so it helps us understand
how to regulate velocity
based on how far
the cars in front of you are.

CA: And so, you&#39;ve also
got an example, I think,
of how the actual
learning part takes place.
Maybe we can see that. Talk about this.

ST: This is an example where we posed
a challenge to Udacity students
to take what we call
a self-driving car Nanodegree.
We gave them this dataset
and said &quot;Hey, can you guys figure out
how to steer this car?&quot;
And if you look at the images,
it&#39;s, even for humans, quite impossible
to get the steering right.
And we ran a competition and said,
&quot;It&#39;s a deep learning competition,
AI competition,&quot;
and we gave the students 48 hours.
So if you are a software house
like Google or Facebook,
something like this costs you
at least six months of work.
So we figured 48 hours is great.
And within 48 hours, we got about
100 submissions from students,
and the top four got it perfectly right.
It drives better than I could
drive on this imagery,
using deep learning.
And again, it&#39;s the same methodology.
It&#39;s this magical thing.
When you give enough data
to a computer now,
and give enough time
to comprehend the data,
it finds its own rules.

CA: And so that has led to the development
of powerful applications
in all sorts of areas.
You were talking to me
the other day about cancer.
Can I show this video?

ST: Yeah, absolutely, please.

CA: This is cool.

ST: This is kind of an insight
into what&#39;s happening
in a completely different domain.
This is augmenting, or competing --
it&#39;s in the eye of the beholder --
with people who are being paid
400,000 dollars a year,
dermatologists,
highly trained specialists.
It takes more than a decade of training
to be a good dermatologist.
What you see here is
the machine learning version of it.
It&#39;s called a neural network.
&quot;Neural networks&quot; is the technical term
for these machine learning algorithms.
They&#39;ve been around since the 1980s.
This one was invented in 1988
by a Facebook Fellow called Yann LeCun,
and it propagates data stages
through what you could think of
as the human brain.
It&#39;s not quite the same thing,
but it emulates the same thing.
It goes stage after stage.
In the very first stage, it takes
the visual input and extracts edges
and rods and dots.
And the next one becomes
more complicated edges
and shapes like little half-moons.
And eventually, it&#39;s able to build
really complicated concepts.
Andrew Ng has been able to show
that it&#39;s able to find
cat faces and dog faces
in vast amounts of images.
What my student team
at Stanford has shown is that
if you train it on 129,000 images
of skin conditions,
including melanoma and carcinomas,
you can do as good a job
as the best human dermatologists.
And to convince ourselves
that this is the case,
we captured an independent dataset
that we presented to our network
and to 25 board-certified
Stanford-level dermatologists,
and compared those.
And in most cases,
they were either on par or above
the performance classification accuracy
of human dermatologists.

CA: You were telling me an anecdote.
I think about this image right here.
What happened here?

ST: This was last Thursday.
That&#39;s a moving piece.
What we&#39;ve shown before and we published
in &quot;Nature&quot; earlier this year
was this idea that we show
dermatologists images
and our computer program images,
and count how often they&#39;re right.
But all these images are past images.
They&#39;ve all been biopsied to make sure
we had the correct classification.
This one wasn&#39;t.
This one was actually done at Stanford
by one of our collaborators.
The story goes that our collaborator,
who is a world-famous dermatologist,
one of the three best, apparently,
looked at this mole and said,
&quot;This is not skin cancer.&quot;
And then he had
a second moment, where he said,
&quot;Well, let me just check with the app.&quot;
So he took out his iPhone
and ran our piece of software,
our &quot;pocket dermatologist,&quot; so to speak,

and the iPhone said: cancer.
It said melanoma.
And then he was confused.
And he decided, &quot;OK, maybe I trust
the iPhone a little bit more than myself,&quot;
and he sent it out to the lab
to get it biopsied.
And it came up as an aggressive melanoma.
So I think this might be the first time
that we actually found,
in the practice of using deep learning,
an actual person whose melanoma
would have gone unclassified,
had it not been for deep learning.

CA: I mean, that&#39;s incredible.

(Applause)

It feels like there&#39;d be an instant demand
for an app like this right now,
that you might freak out a lot of people.
Are you thinking of doing this,
making an app that allows self-checking?

ST: So my in-box is flooded
about cancer apps,
with heartbreaking stories of people.
I mean, some people have had
10, 15, 20 melanomas removed,
and are scared that one
might be overlooked, like this one,
and also, about, I don&#39;t know,
flying cars and speaker inquiries 
these days, I guess.
My take is, we need more testing.
I want to be very careful.
It&#39;s very easy to give a flashy result
and impress a TED audience.
It&#39;s much harder to put
something out that&#39;s ethical.
And if people were to use the app
and choose not to consult
the assistance of a doctor
because we get it wrong,
I would feel really bad about it.
So we&#39;re currently doing clinical tests,
and if these clinical tests commence
and our data holds up,
we might be able at some point
to take this kind of technology
and take it out of the Stanford clinic
and bring it to the entire world,
places where Stanford
doctors never, ever set foot.

CA: And do I hear this right,
that it seemed like what you were saying,
because you are working
with this army of Udacity students,
that in a way, you&#39;re applying
a different form of machine learning
than might take place in a company,
which is you&#39;re combining machine learning
with a form of crowd wisdom.
Are you saying that sometimes you think
that could actually outperform
what a company can do,
even a vast company?

ST: I believe there&#39;s now
instances that blow my mind,
and I&#39;m still trying to understand.
What Chris is referring to
is these competitions that we run.
We turn them around in 48 hours,
and we&#39;ve been able to build
a self-driving car
that can drive from Mountain View
to San Francisco on surface streets.
It&#39;s not quite on par with Google
after seven years of Google work,
but it&#39;s getting there.
And it took us only two engineers
and three months to do this.
And the reason is, we have
an army of students
who participate in competitions.
We&#39;re not the only ones
who use crowdsourcing.
Uber and Didi use crowdsource for driving.
Airbnb uses crowdsourcing for hotels.
There&#39;s now many examples
where people do bug-finding crowdsourcing
or protein folding, of all things,
in crowdsourcing.
But we&#39;ve been able to build
this car in three months,
so I am actually rethinking
how we organize corporations.
We have a staff of 9,000 people
who are never hired,
that I never fire.
They show up to work
and I don&#39;t even know.
Then they submit to me
maybe 9,000 answers.
I&#39;m not obliged to use any of those.
I end up -- I pay only the winners,
so I&#39;m actually very cheapskate here,
which is maybe not the best thing to do.
But they consider it part
of their education, too, which is nice.
But these students have been able
to produce amazing deep learning results.
So yeah, the synthesis of great people
and great machine learning is amazing.

CA: I mean, Gary Kasparov said on
the first day [of TED2017]
that the winners of chess, surprisingly,
turned out to be two amateur chess players
with three mediocre-ish,
mediocre-to-good, computer programs,
that could outperform one grand master
with one great chess player,
like it was all part of the process.
And it almost seems like
you&#39;re talking about a much richer version
of that same idea.

ST: Yeah, I mean, as you followed
the fantastic panels yesterday morning,
two sessions about AI,
robotic overlords and the human response,
many, many great things were said.
But one of the concerns is
that we sometimes confuse
what&#39;s actually been done with AI
with this kind of overlord threat,
where your AI develops
consciousness, right?
The last thing I want
is for my AI to have consciousness.
I don&#39;t want to come into my kitchen
and have the refrigerator fall in love
with the dishwasher
and tell me, because I wasn&#39;t nice enough,
my food is now warm.
I wouldn&#39;t buy these products,
and I don&#39;t want them.
But the truth is, for me,
AI has always been
an augmentation of people.
It&#39;s been an augmentation of us,
to make us stronger.
And I think Kasparov was exactly correct.
It&#39;s been the combination
of human smarts and machine smarts
that make us stronger.
The theme of machines making us stronger
is as old as machines are.
The agricultural revolution took
place because it made steam engines
and farming equipment
that couldn&#39;t farm by itself,
that never replaced us;
it made us stronger.
And I believe this new wave of AI
will make us much, much stronger
as a human race.

CA: We&#39;ll come on to that a bit more,
but just to continue with the scary part
of this for some people,
like, what feels like it gets
scary for people is when you have
a computer that can, one,
rewrite its own code,
so, it can create
multiple copies of itself,
try a bunch of different code versions,
possibly even at random,
and then check them out and see
if a goal is achieved and improved.
So, say the goal is to do better
on an intelligence test.
You know, a computer
that&#39;s moderately good at that,
you could try a million versions of that.
You might find one that was better,
and then, you know, repeat.
And so the concern is that you get
some sort of runaway effect
where everything is fine
on Thursday evening,
and you come back into the lab
on Friday morning,
and because of the speed
of computers and so forth,
things have gone crazy, and suddenly --

ST: I would say this is a possibility,
but it&#39;s a very remote possibility.
So let me just translate
what I heard you say.
In the AlphaGo case,

we had exactly this thing:
the computer would play
the game against itself
and then learn new rules.
And what machine learning is
is a rewriting of the rules.
It&#39;s the rewriting of code.
But I think there was
absolutely no concern
that AlphaGo would take over the world.
It can&#39;t even play chess.

CA: No, no, no, but now,
these are all very single-domain things.
But it&#39;s possible to imagine.
I mean, we just saw a computer
that seemed nearly capable
of passing a university entrance test,
that can kind of -- it can&#39;t read
and understand in the sense that we can,
but it can certainly absorb all the text
and maybe see increased
patterns of meaning.
Isn&#39;t there a chance that,
as this broadens out,
there could be a different
kind of runaway effect?

ST: That&#39;s where
I draw the line, honestly.
And the chance exists --
I don&#39;t want to downplay it --
but I think it&#39;s remote, and it&#39;s not
the thing that&#39;s on my mind these days,
because I think the big revolution
is something else.
Everything successful in AI
to the present date
has been extremely specialized,
and it&#39;s been thriving on a single idea,
which is massive amounts of data.
The reason AlphaGo works so well
is because of massive numbers of Go plays,
and AlphaGo can&#39;t drive a car
or fly a plane.
The Google self-driving car
or the Udacity self-driving car
thrives on massive amounts of data,
and it can&#39;t do anything else.
It can&#39;t even control a motorcycle.
It&#39;s a very specific,
domain-specific function,
and the same is true for our cancer app.
There has been almost no progress
on this thing called &quot;general AI,&quot;
where you go to an AI and say,
&quot;Hey, invent for me special relativity
or string theory.&quot;
It&#39;s totally in the infancy.
The reason I want to emphasize this,
I see the concerns,
and I want to acknowledge them.
But if I were to think about one thing,
I would ask myself the question,
&quot;What if we can take anything repetitive
and make ourselves
100 times as efficient?&quot;
It so turns out, 300 years ago,
we all worked in agriculture
and did farming and did repetitive things.
Today, 75 percent of us work in offices
and do repetitive things.
We&#39;ve become spreadsheet monkeys.
And not just low-end labor.
We&#39;ve become dermatologists
doing repetitive things,
lawyers doing repetitive things.
I think we are at the brink
of being able to take an AI,
look over our shoulders,
and they make us maybe 10 or 50 times
as effective in these repetitive things.
That&#39;s what is on my mind.

CA: That sounds super exciting.
The process of getting there seems
a little terrifying to some people,
because once a computer
can do this repetitive thing
much better than the dermatologist
or than the driver, especially,
is the thing that&#39;s talked about
so much now,
suddenly millions of jobs go,
and, you know, the country&#39;s in revolution
before we ever get to the more
glorious aspects of what&#39;s possible.

ST: Yeah, and that&#39;s an issue,
and it&#39;s a big issue,
and it was pointed out yesterday morning
by several guest speakers.
Now, prior to me showing up onstage,
I confessed I&#39;m a positive,
optimistic person,
so let me give you an optimistic pitch,
which is, think of yourself
back 300 years ago.
Europe just survived 140 years
of continuous war,
none of you could read or write,
there were no jobs that you hold today,
like investment banker
or software engineer or TV anchor.
We would all be in the fields and farming.
Now here comes little Sebastian
with a little steam engine in his pocket,
saying, &quot;Hey guys, look at this.
It&#39;s going to make you 100 times
as strong, so you can do something else.&quot;
And then back in the day,
there was no real stage,
but Chris and I hang out
with the cows in the stable,
and he says, &quot;I&#39;m really
concerned about it,
because I milk my cow every day,
and what if the machine does this for me?&quot;
The reason why I mention this is,
we&#39;re always good in acknowledging
past progress and the benefit of it,
like our iPhones or our planes
or electricity or medical supply.
We all love to live to 80,
which was impossible 300 years ago.
But we kind of don&#39;t apply
the same rules to the future.
So if I look at my own job as a CEO,
I would say 90 percent
of my work is repetitive,
I don&#39;t enjoy it,
I spend about four hours per day
on stupid, repetitive email.
And I&#39;m burning to have something
that helps me get rid of this.
Why?
Because I believe all of us
are insanely creative;
I think the TED community
more than anybody else.
But even blue-collar workers;
I think you can go to your hotel maid
and have a drink with him or her,
and an hour later,
you find a creative idea.
What this will empower
is to turn this creativity into action.
Like, what if you could
build Google in a day?
What if you could sit over beer
and invent the next Snapchat,
whatever it is,
and tomorrow morning it&#39;s up and running?
And that is not science fiction.
What&#39;s going to happen is,
we are already in history.
We&#39;ve unleashed this amazing creativity
by de-slaving us from farming
and later, of course, from factory work
and have invented so many things.
It&#39;s going to be even better,
in my opinion.
And there&#39;s going to be
great side effects.
One of the side effects will be
that things like food and medical supply
and education and shelter
and transportation
will all become much more
affordable to all of us,
not just the rich people.

CA: Hmm.
So when Martin Ford argued, you know,
that this time it&#39;s different
because the intelligence
that we&#39;ve used in the past
to find new ways to be
will be matched at the same pace
by computers taking over those things,
what I hear you saying
is that, not completely,
because of human creativity.
Do you think that that&#39;s fundamentally
different from the kind of creativity
that computers can do?

ST: So, that&#39;s my firm
belief as an AI person --
that I haven&#39;t seen
any real progress on creativity
and out-of-the-box thinking.
What I see right now -- and this is
really important for people to realize,
because the word &quot;artificial
intelligence&quot; is so threatening,
and then we have Steve Spielberg
tossing a movie in,
where all of a sudden
the computer is our overlord,
but it&#39;s really a technology.
It&#39;s a technology that helps us
do repetitive things.
And the progress has been
entirely on the repetitive end.
It&#39;s been in legal document discovery.
It&#39;s been contract drafting.
It&#39;s been screening X-rays of your chest.
And these things are so specialized,
I don&#39;t see the big threat of humanity.
In fact, we as people --

I mean, let&#39;s face it:
we&#39;ve become superhuman.
We&#39;ve made us superhuman.
We can swim across
the Atlantic in 11 hours.
We can take a device out of our pocket
and shout all the way to Australia,
and in real time, have that person
shouting back to us.
That&#39;s physically not possible.
We&#39;re breaking the rules of physics.
When this is said and done,
we&#39;re going to remember everything
we&#39;ve ever said and seen,
you&#39;ll remember every person,
which is good for me
in my early stages of Alzheimer&#39;s.
Sorry, what was I saying? I forgot.

CA: (Laughs)

ST: We will probably have
an IQ of 1,000 or more.
There will be no more
spelling classes for our kids,
because there&#39;s no spelling issue anymore.
There&#39;s no math issue anymore.
And I think what really will happen
is that we can be super creative.
And we are. We are creative.
That&#39;s our secret weapon.

CA: So the jobs that are getting lost,
in a way, even though
it&#39;s going to be painful,
humans are capable
of more than those jobs.
This is the dream.
The dream is that humans can rise
to just a new level of empowerment
and discovery.
That&#39;s the dream.

ST: And think about this:
if you look at the history of humanity,
that might be whatever --
60-100,000 years old, give or take --
almost everything that you cherish
in terms of invention,
of technology, of things we&#39;ve built,
has been invented in the last 150 years.
If you toss in the book and the wheel,
it&#39;s a little bit older.
Or the axe.
But your phone, your sneakers,
these chairs, modern
manufacturing, penicillin --
the things we cherish.
Now, that to me means
the next 150 years will find more things.
In fact, the pace of invention
has gone up, not gone down, in my opinion.
I believe only one percent of interesting
things have been invented yet. Right?
We haven&#39;t cured cancer.
We don&#39;t have flying cars -- yet.
Hopefully, I&#39;ll change this.
That used to be an example
people laughed about. (Laughs)
It&#39;s funny, isn&#39;t it?
Working secretly on flying cars.
We don&#39;t live twice as long yet. OK?
We don&#39;t have this magic
implant in our brain
that gives us the information we want.
And you might be appalled by it,
but I promise you,
once you have it, you&#39;ll love it.
I hope you will.
It&#39;s a bit scary, I know.
There are so many things
we haven&#39;t invented yet
that I think we&#39;ll invent.
We have no gravity shields.
We can&#39;t beam ourselves
from one location to another.
That sounds ridiculous,
but about 200 years ago,
experts were of the opinion
that flight wouldn&#39;t exist,
even 120 years ago,
and if you moved faster
than you could run,
you would instantly die.
So who says we are correct today
that you can&#39;t beam a person
from here to Mars?

CA: Sebastian, thank you so much
for your incredibly inspiring vision
and your brilliance.
Thank you, Sebastian Thrun.
That was fantastic. 
(Applause)

