
My colleagues and I are fascinated
by the science of moving dots.
So what are these dots?
Well, it&#39;s all of us.
And we&#39;re moving in our homes,
in our offices, as we shop and travel
throughout our cities
and around the world.
And wouldn&#39;t it be great
if we could understand all this movement?
If we could find patterns and meaning
and insight in it.
And luckily for us, we live in a time
where we&#39;re incredibly good
at capturing information about ourselves.
So whether it&#39;s through
sensors or videos, or apps,
we can track our movement
with incredibly fine detail.
So it turns out one of the places
where we have the best data about movement
is sports.
So whether it&#39;s basketball or baseball,
or football or the other football,
we&#39;re instrumenting our stadiums
and our players to track their movements
every fraction of a second.
So what we&#39;re doing
is turning our athletes into --
you probably guessed it --
moving dots.
So we&#39;ve got mountains of moving dots
and like most raw data,
it&#39;s hard to deal with
and not that interesting.
But there are things that, for example,
basketball coaches want to know.
And the problem is they can&#39;t know them
because they&#39;d have to watch every second
of every game, remember it and process it.
And a person can&#39;t do that,
but a machine can.
The problem is a machine can&#39;t see
the game with the eye of a coach.
At least they couldn&#39;t until now.
So what have we taught the machine to see?
So, we started simply.
We taught it things like passes,
shots and rebounds.
Things that most casual fans would know.
And then we moved on to things
slightly more complicated.
Events like post-ups,
and pick-and-rolls, and isolations.
And if you don&#39;t know them, that&#39;s okay.
Most casual players probably do.
Now, we&#39;ve gotten to a point where today,
the machine understands complex events
like down screens and wide pins.
Basically things only professionals know.
So we have taught a machine to see
with the eyes of a coach.
So how have we been able to do this?
If I asked a coach to describe
something like a pick-and-roll,
they would give me a description,
and if I encoded that as an algorithm,
it would be terrible.
The pick-and-roll happens to be this dance
in basketball between four players,
two on offense and two on defense.
And here&#39;s kind of how it goes.
So there&#39;s the guy on offense
without the ball
the ball and he goes next to the guy
guarding the guy with the ball,
and he kind of stays there
and they both move and stuff happens,
and ta-da, it&#39;s a pick-and-roll.

(Laughter)

So that is also an example
of a terrible algorithm.
So, if the player who&#39;s the interferer --
he&#39;s called the screener --
goes close by, but he doesn&#39;t stop,
it&#39;s probably not a pick-and-roll.
Or if he does stop,
but he doesn&#39;t stop close enough,
it&#39;s probably not a pick-and-roll.
Or, if he does go close by
and he does stop
but they do it under the basket,
it&#39;s probably not a pick-and-roll.
Or I could be wrong,
they could all be pick-and-rolls.
It really depends on the exact timing,
the distances, the locations,
and that&#39;s what makes it hard.
So, luckily, with machine learning,
we can go beyond our own ability
to describe the things we know.
So how does this work?
Well, it&#39;s by example.
So we go to the machine and say,
&quot;Good morning, machine.
Here are some pick-and-rolls,
and here are some things that are not.
Please find a way to tell the difference.&quot;
And the key to all of this is to find
features that enable it to separate.
So if I was going
to teach it the difference
between an apple and orange,
I might say, &quot;Why don&#39;t you
use color or shape?&quot;
And the problem that we&#39;re solving is,
what are those things?
What are the key features
that let a computer navigate
the world of moving dots?
So figuring out all these relationships
with relative and absolute location,
distance, timing, velocities --
that&#39;s really the key to the science
of moving dots, or as we like to call it,
spatiotemporal pattern recognition,
in academic vernacular.
Because the first thing is,
you have to make it sound hard --
because it is.
The key thing is, for NBA coaches,
it&#39;s not that they want to know
whether a pick-and-roll happened or not.
It&#39;s that they want to know
how it happened.
And why is it so important to them?
So here&#39;s a little insight.
It turns out in modern basketball,
this pick-and-roll is perhaps
the most important play.
And knowing how to run it,
and knowing how to defend it,
is basically a key to winning
and losing most games.
So it turns out that this dance
has a great many variations
and identifying the variations
is really the thing that matters,
and that&#39;s why we need this
to be really, really good.
So, here&#39;s an example.
There are two offensive
and two defensive players,
getting ready to do
the pick-and-roll dance.
So the guy with ball
can either take, or he can reject.
His teammate can either roll or pop.
The guy guarding the ball
can either go over or under.
His teammate can either show
or play up to touch, or play soft
and together they can
either switch or blitz
and I didn&#39;t know
most of these things when I started
and it would be lovely if everybody moved
according to those arrows.
It would make our lives a lot easier,
but it turns out movement is very messy.
People wiggle a lot and getting
these variations identified
with very high accuracy,
both in precision and recall, is tough
because that&#39;s what it takes to get
a professional coach to believe in you.
And despite all the difficulties
with the right spatiotemporal features
we have been able to do that.
Coaches trust our ability of our machine
to identify these variations.
We&#39;re at the point where
almost every single contender
for an NBA championship this year
is using our software, which is built
on a machine that understands
the moving dots of basketball.
So not only that, we have given advice
that has changed strategies
that have helped teams win
very important games,
and it&#39;s very exciting because you have
coaches who&#39;ve been in the league
for 30 years that are willing to take
advice from a machine.
And it&#39;s very exciting,
it&#39;s much more than the pick-and-roll.
Our computer started out
with simple things
and learned more and more complex things
and now it knows so many things.
Frankly, I don&#39;t understand
much of what it does,
and while it&#39;s not that special
to be smarter than me,
we were wondering,
can a machine know more than a coach?
Can it know more than person could know?
And it turns out the answer is yes.
The coaches want players
to take good shots.
So if I&#39;m standing near the basket
and there&#39;s nobody near me,
it&#39;s a good shot.
If I&#39;m standing far away surrounded
by defenders, that&#39;s generally a bad shot.
But we never knew how good &quot;good&quot; was,
or how bad &quot;bad&quot; was quantitatively.
Until now.
So what we can do, again,
using spatiotemporal features,
we looked at every shot.

We can see: Where is the shot?
What&#39;s the angle to the basket?
Where are the defenders standing?
What are their distances?
What are their angles?
For multiple defenders, we can look
at how the player&#39;s moving
and predict the shot type.
We can look at all their velocities
and we can build a model that predicts
what is the likelihood that this shot
would go in under these circumstances?
So why is this important?
We can take something that was shooting,
which was one thing before,

and turn it into two things:
the quality of the shot
and the quality of the shooter.
So here&#39;s a bubble chart,
because what&#39;s TED without a bubble chart?

(Laughter)

Those are NBA players.
The size is the size of the player
and the color is the position.
On the x-axis,
we have the shot probability.
People on the left take difficult shots,
on the right, they take easy shots.
On the [y-axis] is their shooting ability.
People who are good are at the top,
bad at the bottom.
So for example, if there was a player
who generally made
47 percent of their shots,
that&#39;s all you knew before.
But today, I can tell you that player
takes shots that an average NBA player
would make 49 percent of the time,
and they are two percent worse.
And the reason that&#39;s important
is that there are lots of 47s out there.
And so it&#39;s really important to know
if the 47 that you&#39;re considering
giving 100 million dollars to
is a good shooter who takes bad shots
or a bad shooter who takes good shots.
Machine understanding doesn&#39;t just change
how we look at players,
it changes how we look at the game.
So there was this very exciting game
a couple of years ago, in the NBA finals.
Miami was down by three,
there was 20 seconds left.
They were about to lose the championship.
A gentleman named LeBron James
came up and he took a three to tie.
He missed.
His teammate Chris Bosh got a rebound,
passed it to another teammate
named Ray Allen.
He sank a three. It went into overtime.
They won the game.
They won the championship.
It was one of the most exciting
games in basketball.
And our ability to know
the shot probability for every player
at every second,
and the likelihood of them getting
a rebound at every second
can illuminate this moment in a way
that we never could before.
Now unfortunately,
I can&#39;t show you that video.
But for you, we recreated that moment
at our weekly basketball game
about 3 weeks ago.

(Laughter)

And we recreated the tracking
that led to the insights.
So, here is us.
This is Chinatown in Los Angeles,
a park we play at every week,
and that&#39;s us recreating
the Ray Allen moment
and all the tracking
that&#39;s associated with it.
So, here&#39;s the shot.
I&#39;m going to show you that moment
and all the insights of that moment.
The only difference is, instead
of the professional players, it&#39;s us,
and instead of a professional
announcer, it&#39;s me.
So, bear with me.
Miami.
Down three.
Twenty seconds left.
Jeff brings up the ball.
Josh catches, puts up a three!
[Calculating shot probability]
[Shot quality]
[Rebound probability]
Won&#39;t go!
[Rebound probability]
Rebound, Noel.
Back to Daria.
[Shot quality]
Her three-pointer -- bang!
Tie game with five seconds left.
The crowd goes wild.

(Laughter)

That&#39;s roughly how it happened.

(Applause)

Roughly.

(Applause)

That moment had about a nine percent
chance of happening in the NBA
and we know that
and a great many other things.
I&#39;m not going to tell you how many times
it took us to make that happen.

(Laughter)

Okay, I will! It was four.

(Laughter)

Way to go, Daria.
But the important thing about that video
and the insights we have for every second
of every NBA game -- it&#39;s not that.
It&#39;s the fact you don&#39;t have to be
a professional team to track movement.
You do not have to be a professional
player to get insights about movement.
In fact, it doesn&#39;t even have to be about
sports because we&#39;re moving everywhere.
We&#39;re moving in our homes,
in our offices,
as we shop and we travel
throughout our cities
and around our world.
What will we know? What will we learn?
Perhaps, instead of identifying
pick-and-rolls,
a machine can identify
the moment and let me know
when my daughter takes her first steps.
Which could literally be happening
any second now.
Perhaps we can learn to better use
our buildings, better plan our cities.
I believe that with the development
of the science of moving dots,
we will move better, we will move smarter,
we will move forward.
Thank you very much.

(Applause)

