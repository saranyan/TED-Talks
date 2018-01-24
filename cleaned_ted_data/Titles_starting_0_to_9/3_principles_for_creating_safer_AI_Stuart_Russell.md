
This is Lee Sedol.
Lee Sedol is one of the world&#39;s
greatest Go players,
and he&#39;s having what my friends
in Silicon Valley call
a &quot;Holy Cow&quot; moment --

(Laughter)

a moment where we realize
that AI is actually progressing
a lot faster than we expected.
So humans have lost on the Go board.
What about the real world?
Well, the real world is much bigger,
much more complicated than the Go board.
It&#39;s a lot less visible,
but it&#39;s still a decision problem.
And if we think about some
of the technologies
that are coming down the pike ...
Noriko [Arai] mentioned that reading
is not yet happening in machines,
at least with understanding.
But that will happen,
and when that happens,
very soon afterwards,
machines will have read everything
that the human race has ever written.
And that will enable machines,
along with the ability to look
further ahead than humans can,
as we&#39;ve already seen in Go,
if they also have access
to more information,
they&#39;ll be able to make better decisions
in the real world than we can.
So is that a good thing?
Well, I hope so.
Our entire civilization,
everything that we value,
is based on our intelligence.
And if we had access
to a lot more intelligence,
then there&#39;s really no limit
to what the human race can do.
And I think this could be,
as some people have described it,
the biggest event in human history.
So why are people saying things like this,
that AI might spell the end
of the human race?
Is this a new thing?
Is it just Elon Musk and Bill Gates
and Stephen Hawking?
Actually, no. This idea
has been around for a while.

Here&#39;s a quotation:
&quot;Even if we could keep the machines
in a subservient position,
for instance, by turning off the power
at strategic moments&quot; --
and I&#39;ll come back to that
&quot;turning off the power&quot; idea later on --
&quot;we should, as a species,
feel greatly humbled.&quot;
So who said this?
This is Alan Turing in 1951.
Alan Turing, as you know,
is the father of computer science
and in many ways,
the father of AI as well.
So if we think about this problem,
the problem of creating something
more intelligent than your own species,
we might call this &quot;the gorilla problem,&quot;
because gorillas&#39; ancestors did this
a few million years ago,

and now we can ask the gorillas:
Was this a good idea?
So here they are having a meeting
to discuss whether it was a good idea,
and after a little while,
they conclude, no,
this was a terrible idea.
Our species is in dire straits.
In fact, you can see the existential
sadness in their eyes.

(Laughter)

So this queasy feeling that making
something smarter than your own species
is maybe not a good idea --
what can we do about that?
Well, really nothing,
except stop doing AI,
and because of all
the benefits that I mentioned
and because I&#39;m an AI researcher,
I&#39;m not having that.
I actually want to be able
to keep doing AI.
So we actually need to nail down
the problem a bit more.
What exactly is the problem?
Why is better AI possibly a catastrophe?

So here&#39;s another quotation:
&quot;We had better be quite sure
that the purpose put into the machine
is the purpose which we really desire.&quot;
This was said by Norbert Wiener in 1960,
shortly after he watched
one of the very early learning systems
learn to play checkers
better than its creator.
But this could equally have been said
by King Midas.
King Midas said, &quot;I want everything
I touch to turn to gold,&quot;
and he got exactly what he asked for.
That was the purpose
that he put into the machine,
so to speak,
and then his food and his drink
and his relatives turned to gold
and he died in misery and starvation.
So we&#39;ll call this
&quot;the King Midas problem&quot;
of stating an objective
which is not, in fact,
truly aligned with what we want.
In modern terms, we call this
&quot;the value alignment problem.&quot;
Putting in the wrong objective
is not the only part of the problem.
There&#39;s another part.
If you put an objective into a machine,
even something as simple as,
&quot;Fetch the coffee,&quot;
the machine says to itself,
&quot;Well, how might I fail
to fetch the coffee?
Someone might switch me off.
OK, I have to take steps to prevent that.
I will disable my &#39;off&#39; switch.
I will do anything to defend myself
against interference
with this objective
that I have been given.&quot;
So this single-minded pursuit
in a very defensive mode
of an objective that is, in fact,
not aligned with the true objectives
of the human race --
that&#39;s the problem that we face.
And in fact, that&#39;s the high-value
takeaway from this talk.
If you want to remember one thing,
it&#39;s that you can&#39;t fetch
the coffee if you&#39;re dead.

(Laughter)

It&#39;s very simple. Just remember that.
Repeat it to yourself three times a day.

(Laughter)

And in fact, this is exactly the plot

of &quot;2001: [A Space Odyssey]&quot;
HAL has an objective, a mission,
which is not aligned
with the objectives of the humans,
and that leads to this conflict.
Now fortunately, HAL
is not superintelligent.
He&#39;s pretty smart,
but eventually Dave outwits him
and manages to switch him off.
But we might not be so lucky.
So what are we going to do?
I&#39;m trying to redefine AI
to get away from this classical notion
of machines that intelligently
pursue objectives.
There are three principles involved.
The first one is a principle
of altruism, if you like,
that the robot&#39;s only objective
is to maximize the realization
of human objectives,
of human values.
And by values here I don&#39;t mean
touchy-feely, goody-goody values.
I just mean whatever it is
that the human would prefer
their life to be like.
And so this actually violates Asimov&#39;s law
that the robot has to protect
its own existence.
It has no interest in preserving
its existence whatsoever.
The second law is a law
of humility, if you like.
And this turns out to be really
important to make robots safe.
It says that the robot does not know
what those human values are,
so it has to maximize them,
but it doesn&#39;t know what they are.
And that avoids this problem
of single-minded pursuit
of an objective.
This uncertainty turns out to be crucial.
Now, in order to be useful to us,
it has to have some idea of what we want.
It obtains that information primarily
by observation of human choices,
so our own choices reveal information
about what it is that we prefer
our lives to be like.
So those are the three principles.
Let&#39;s see how that applies

to this question of:
&quot;Can you switch the machine off?&quot;
as Turing suggested.
So here&#39;s a PR2 robot.
This is one that we have in our lab,
and it has a big red &quot;off&quot; switch
right on the back.

The question is: Is it
going to let you switch it off?
If we do it the classical way,
we give it the objective of, &quot;Fetch
the coffee, I must fetch the coffee,
I can&#39;t fetch the coffee if I&#39;m dead,&quot;
so obviously the PR2
has been listening to my talk,
and so it says, therefore,
&quot;I must disable my &#39;off&#39; switch,
and probably taser all the other
people in Starbucks
who might interfere with me.&quot;

(Laughter)

So this seems to be inevitable, right?
This kind of failure mode
seems to be inevitable,
and it follows from having
a concrete, definite objective.
So what happens if the machine
is uncertain about the objective?
Well, it reasons in a different way.
It says, &quot;OK, the human
might switch me off,
but only if I&#39;m doing something wrong.
Well, I don&#39;t really know what wrong is,
but I know that I don&#39;t want to do it.&quot;
So that&#39;s the first and second
principles right there.
&quot;So I should let the human switch me off.&quot;
And in fact you can calculate
the incentive that the robot has
to allow the human to switch it off,
and it&#39;s directly tied to the degree
of uncertainty about
the underlying objective.
And then when the machine is switched off,
that third principle comes into play.
It learns something about the objectives
it should be pursuing,
because it learns that
what it did wasn&#39;t right.
In fact, we can, with suitable use
of Greek symbols,
as mathematicians usually do,
we can actually prove a theorem
that says that such a robot
is provably beneficial to the human.
You are provably better off
with a machine that&#39;s designed in this way
than without it.
So this is a very simple example,
but this is the first step
in what we&#39;re trying to do
with human-compatible AI.
Now, this third principle,
I think is the one that you&#39;re probably
scratching your head over.
You&#39;re probably thinking, &quot;Well,
you know, I behave badly.
I don&#39;t want my robot to behave like me.
I sneak down in the middle of the night
and take stuff from the fridge.
I do this and that.&quot;
There&#39;s all kinds of things
you don&#39;t want the robot doing.
But in fact, it doesn&#39;t
quite work that way.
Just because you behave badly
doesn&#39;t mean the robot
is going to copy your behavior.
It&#39;s going to understand your motivations
and maybe help you resist them,
if appropriate.
But it&#39;s still difficult.
What we&#39;re trying to do, in fact,
is to allow machines to predict
for any person and for any possible life
that they could live,

and the lives of everybody else:
Which would they prefer?
And there are many, many
difficulties involved in doing this;
I don&#39;t expect that this
is going to get solved very quickly.
The real difficulties, in fact, are us.
As I have already mentioned,
we behave badly.
In fact, some of us are downright nasty.
Now the robot, as I said,
doesn&#39;t have to copy the behavior.
The robot does not have
any objective of its own.
It&#39;s purely altruistic.
And it&#39;s not designed just to satisfy
the desires of one person, the user,
but in fact it has to respect
the preferences of everybody.
So it can deal with a certain
amount of nastiness,
and it can even understand
that your nastiness, for example,
you may take bribes as a passport official
because you need to feed your family
and send your kids to school.
It can understand that;
it doesn&#39;t mean it&#39;s going to steal.
In fact, it&#39;ll just help you
send your kids to school.
We are also computationally limited.
Lee Sedol is a brilliant Go player,
but he still lost.
So if we look at his actions,
he took an action that lost the game.
That doesn&#39;t mean he wanted to lose.
So to understand his behavior,
we actually have to invert
through a model of human cognition
that includes our computational
limitations -- a very complicated model.
But it&#39;s still something
that we can work on understanding.
Probably the most difficult part,
from my point of view as an AI researcher,
is the fact that there are lots of us,
and so the machine has to somehow
trade off, weigh up the preferences
of many different people,
and there are different ways to do that.
Economists, sociologists,
moral philosophers have understood that,
and we are actively
looking for collaboration.
Let&#39;s have a look and see what happens
when you get that wrong.
So you can have
a conversation, for example,
with your intelligent personal assistant
that might be available
in a few years&#39; time.
Think of a Siri on steroids.
So Siri says, &quot;Your wife called
to remind you about dinner tonight.&quot;
And of course, you&#39;ve forgotten.
&quot;What? What dinner?
What are you talking about?&quot;
&quot;Uh, your 20th anniversary at 7pm.&quot;
&quot;I can&#39;t do that. I&#39;m meeting

with the secretary-general at 7:30.
How could this have happened?&quot;
&quot;Well, I did warn you, but you overrode
my recommendation.&quot;
&quot;Well, what am I going to do?
I can&#39;t just tell him I&#39;m too busy.&quot;
&quot;Don&#39;t worry. I arranged
for his plane to be delayed.&quot;

(Laughter)

&quot;Some kind of computer malfunction.&quot;

(Laughter)

&quot;Really? You can do that?&quot;
&quot;He sends his profound apologies
and looks forward to meeting you
for lunch tomorrow.&quot;

(Laughter)

So the values here --
there&#39;s a slight mistake going on.
This is clearly following my wife&#39;s values
which is &quot;Happy wife, happy life.&quot;

(Laughter)

It could go the other way.
You could come home
after a hard day&#39;s work,
and the computer says, &quot;Long day?&quot;
&quot;Yes, I didn&#39;t even have time for lunch.&quot;
&quot;You must be very hungry.&quot;
&quot;Starving, yeah.
Could you make some dinner?&quot;
&quot;There&#39;s something I need to tell you.&quot;

(Laughter)

&quot;There are humans in South Sudan
who are in more urgent need than you.&quot;

(Laughter)

&quot;So I&#39;m leaving. Make your own dinner.&quot;

(Laughter)

So we have to solve these problems,
and I&#39;m looking forward
to working on them.
There are reasons for optimism.
One reason is,
there is a massive amount of data.
Because remember -- I said
they&#39;re going to read everything
the human race has ever written.
Most of what we write about
is human beings doing things
and other people getting upset about it.
So there&#39;s a massive amount
of data to learn from.
There&#39;s also a very
strong economic incentive
to get this right.
So imagine your domestic robot&#39;s at home.
You&#39;re late from work again
and the robot has to feed the kids,
and the kids are hungry
and there&#39;s nothing in the fridge.
And the robot sees the cat.

(Laughter)

And the robot hasn&#39;t quite learned
the human value function properly,
so it doesn&#39;t understand
the sentimental value of the cat outweighs
the nutritional value of the cat.

(Laughter)

So then what happens?

Well, it happens like this:
&quot;Deranged robot cooks kitty
for family dinner.&quot;
That one incident would be the end
of the domestic robot industry.
So there&#39;s a huge incentive
to get this right
long before we reach
superintelligent machines.

So to summarize:
I&#39;m actually trying to change
the definition of AI
so that we have provably
beneficial machines.

And the principles are:
machines that are altruistic,
that want to achieve only our objectives,
but that are uncertain
about what those objectives are,
and will watch all of us
to learn more about what it is
that we really want.
And hopefully in the process,
we will learn to be better people.
Thank you very much.

(Applause)


Chris Anderson: So interesting, Stuart.
We&#39;re going to stand here a bit
because I think they&#39;re setting up
for our next speaker.
A couple of questions.
So the idea of programming in ignorance
seems intuitively really powerful.
As you get to superintelligence,
what&#39;s going to stop a robot
reading literature and discovering
this idea that knowledge
is actually better than ignorance
and still just shifting its own goals
and rewriting that programming?

Stuart Russell: Yes, so we want
it to learn more, as I said,
about our objectives.
It&#39;ll only become more certain
as it becomes more correct,
so the evidence is there
and it&#39;s going to be designed
to interpret it correctly.
It will understand, for example,
that books are very biased
in the evidence they contain.
They only talk about kings and princes
and elite white male people doing stuff.
So it&#39;s a complicated problem,
but as it learns more about our objectives
it will become more and more useful to us.

CA: And you couldn&#39;t
just boil it down to one law,

you know, hardwired in:
&quot;if any human ever tries to switch me off,
I comply. I comply.&quot;

SR: Absolutely not.
That would be a terrible idea.
So imagine that you have
a self-driving car
and you want to send your five-year-old
off to preschool.
Do you want your five-year-old
to be able to switch off the car
while it&#39;s driving along?
Probably not.
So it needs to understand how rational
and sensible the person is.
The more rational the person,
the more willing you are
to be switched off.
If the person is completely
random or even malicious,
then you&#39;re less willing
to be switched off.

CA: All right. Stuart, can I just say,
I really, really hope you
figure this out for us.
Thank you so much for that talk.
That was amazing.

SR: Thank you.

(Applause)

