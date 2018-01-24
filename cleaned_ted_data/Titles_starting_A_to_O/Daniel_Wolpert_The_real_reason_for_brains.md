
I&#39;m a neuroscientist.
And in neuroscience,
we have to deal with many difficult questions about the brain.
But I want to start with the easiest question
and the question you really should have all asked yourselves at some point in your life,
because it&#39;s a fundamental question
if we want to understand brain function.
And that is, why do we and other animals
have brains?
Not all species on our planet have brains,
so if we want to know what the brain is for,
let&#39;s think about why we evolved one.
Now you may reason that we have one
to perceive the world or to think,
and that&#39;s completely wrong.
If you think about this question for any length of time,
it&#39;s blindingly obvious why we have a brain.
We have a brain for one reason and one reason only,
and that&#39;s to produce adaptable and complex movements.
There is no other reason to have a brain.
Think about it.
Movement is the only way you have
of affecting the world around you.
Now that&#39;s not quite true. There&#39;s one other way, and that&#39;s through sweating.
But apart from that,
everything else goes through contractions of muscles.
So think about communication --
speech, gestures, writing, sign language --
they&#39;re all mediated through contractions of your muscles.
So it&#39;s really important to remember
that sensory, memory and cognitive processes are all important,
but they&#39;re only important
to either drive or suppress future movements.
There can be no evolutionary advantage
to laying down memories of childhood
or perceiving the color of a rose
if it doesn&#39;t affect the way you&#39;re going to move later in life.
Now for those who don&#39;t believe this argument,
we have trees and grass on our planet without the brain,
but the clinching evidence is this animal here --
the humble sea squirt.
Rudimentary animal, has a nervous system,
swims around in the ocean in its juvenile life.
And at some point of its life,
it implants on a rock.
And the first thing it does in implanting on that rock, which it never leaves,
is to digest its own brain and nervous system
for food.
So once you don&#39;t need to move,
you don&#39;t need the luxury of that brain.
And this animal is often taken
as an analogy to what happens at universities
when professors get tenure,
but that&#39;s a different subject.

(Applause)

So I am a movement chauvinist.
I believe movement is the most important function of the brain --
don&#39;t let anyone tell you that it&#39;s not true.
Now if movement is so important,
how well are we doing
understanding how the brain controls movement?
And the answer is we&#39;re doing extremely poorly; it&#39;s a very hard problem.
But we can look at how well we&#39;re doing
by thinking about how well we&#39;re doing building machines
which can do what humans can do.
Think about the game of chess.
How well are we doing determining what piece to move where?
If you pit Garry Kasparov here, when he&#39;s not in jail,
against IBM&#39;s Deep Blue,
well the answer is IBM&#39;s Deep Blue will occasionally win.
And I think if IBM&#39;s Deep Blue played anyone in this room, it would win every time.
That problem is solved.
What about the problem
of picking up a chess piece,
dexterously manipulating it and putting it back down on the board?
If you put a five year-old child&#39;s dexterity against the best robots of today,

the answer is simple:
the child wins easily.
There&#39;s no competition at all.
Now why is that top problem so easy
and the bottom problem so hard?
One reason is a very smart five year-old
could tell you the algorithm for that top problem --
look at all possible moves to the end of the game
and choose the one that makes you win.
So it&#39;s a very simple algorithm.
Now of course there are other moves,
but with vast computers we approximate
and come close to the optimal solution.
When it comes to being dexterous,
it&#39;s not even clear what the algorithm is you have to solve to be dexterous.
And we&#39;ll see you have to both perceive and act on the world,
which has a lot of problems.
But let me show you cutting-edge robotics.
Now a lot of robotics is very impressive,
but manipulation robotics is really just in the dark ages.
So this is the end of a Ph.D. project
from one of the best robotics institutes.
And the student has trained this robot
to pour this water into a glass.
It&#39;s a hard problem because the water sloshes about, but it can do it.
But it doesn&#39;t do it with anything like the agility of a human.
Now if you want this robot to do a different task,
that&#39;s another three-year Ph.D. program.
There is no generalization at all
from one task to another in robotics.
Now we can compare this
to cutting-edge human performance.
So what I&#39;m going to show you is Emily Fox
winning the world record for cup stacking.
Now the Americans in the audience will know all about cup stacking.
It&#39;s a high school sport
where you have 12 cups you have to stack and unstack
against the clock in a prescribed order.
And this is her getting the world record in real time.

(Laughter)


(Applause)

And she&#39;s pretty happy.
We have no idea what is going on inside her brain when she does that,
and that&#39;s what we&#39;d like to know.
So in my group, what we try to do
is reverse engineer how humans control movement.
And it sounds like an easy problem.
You send a command down, it causes muscles to contract.
Your arm or body moves,
and you get sensory feedback from vision, from skin, from muscles and so on.
The trouble is
these signals are not the beautiful signals you want them to be.
So one thing that makes controlling movement difficult
is, for example, sensory feedback is extremely noisy.
Now by noise, I do not mean sound.
We use it in the engineering and neuroscience sense
meaning a random noise corrupting a signal.
So the old days before digital radio when you were tuning in your radio
and you heard &quot;crrcckkk&quot; on the station you wanted to hear,
that was the noise.
But more generally, this noise is something that corrupts the signal.
So for example, if you put your hand under a table
and try to localize it with your other hand,
you can be off by several centimeters
due to the noise in sensory feedback.
Similarly, when you put motor output on movement output,
it&#39;s extremely noisy.
Forget about trying to hit the bull&#39;s eye in darts,
just aim for the same spot over and over again.
You have a huge spread due to movement variability.
And more than that, the outside world, or task,
is both ambiguous and variable.
The teapot could be full, it could be empty.
It changes over time.
So we work in a whole sensory movement task soup of noise.
Now this noise is so great
that society places a huge premium
on those of us who can reduce the consequences of noise.
So if you&#39;re lucky enough to be able to knock a small white ball
into a hole several hundred yards away using a long metal stick,
our society will be willing to reward you
with hundreds of millions of dollars.
Now what I want to convince you of
is the brain also goes through a lot of effort
to reduce the negative consequences
of this sort of noise and variability.
And to do that, I&#39;m going to tell you about a framework
which is very popular in statistics and machine learning of the last 50 years
called Bayesian decision theory.
And it&#39;s more recently a unifying way
to think about how the brain deals with uncertainty.
And the fundamental idea is you want to make inferences and then take actions.
So let&#39;s think about the inference.
You want to generate beliefs about the world.
So what are beliefs?

Beliefs could be: where are my arms in space?
Am I looking at a cat or a fox?
But we&#39;re going to represent beliefs with probabilities.
So we&#39;re going to represent a belief
with a number between zero and one --
zero meaning I don&#39;t believe it at all, one means I&#39;m absolutely certain.
And numbers in between give you the gray levels of uncertainty.
And the key idea to Bayesian inference
is you have two sources of information
from which to make your inference.
You have data,
and data in neuroscience is sensory input.
So I have sensory input, which I can take in to make beliefs.
But there&#39;s another source of information, and that&#39;s effectively prior knowledge.
You accumulate knowledge throughout your life in memories.
And the point about Bayesian decision theory
is it gives you the mathematics
of the optimal way to combine
your prior knowledge with your sensory evidence
to generate new beliefs.
And I&#39;ve put the formula up there.
I&#39;m not going to explain what that formula is, but it&#39;s very beautiful.
And it has real beauty and real explanatory power.
And what it really says, and what you want to estimate,
is the probability of different beliefs
given your sensory input.
So let me give you an intuitive example.
Imagine you&#39;re learning to play tennis
and you want to decide where the ball is going to bounce
as it comes over the net towards you.
There are two sources of information
Bayes&#39; rule tells you.
There&#39;s sensory evidence -- you can use visual information auditory information,
and that might tell you it&#39;s going to land in that red spot.
But you know that your senses are not perfect,
and therefore there&#39;s some variability of where it&#39;s going to land
shown by that cloud of red,
representing numbers between 0.5 and maybe 0.1.
That information is available in the current shot,
but there&#39;s another source of information
not available on the current shot,
but only available by repeated experience in the game of tennis,
and that&#39;s that the ball doesn&#39;t bounce
with equal probability over the court during the match.
If you&#39;re playing against a very good opponent,
they may distribute it in that green area,
which is the prior distribution,
making it hard for you to return.
Now both these sources of information carry important information.
And what Bayes&#39; rule says
is that I should multiply the numbers on the red by the numbers on the green
to get the numbers of the yellow, which have the ellipses,
and that&#39;s my belief.
So it&#39;s the optimal way of combining information.
Now I wouldn&#39;t tell you all this if it wasn&#39;t that a few years ago,
we showed this is exactly what people do
when they learn new movement skills.
And what it means
is we really are Bayesian inference machines.
As we go around, we learn about statistics of the world and lay that down,
but we also learn
about how noisy our own sensory apparatus is,
and then combine those
in a real Bayesian way.
Now a key part to the Bayesian is this part of the formula.
And what this part really says
is I have to predict the probability
of different sensory feedbacks
given my beliefs.
So that really means I have to make predictions of the future.
And I want to convince you the brain does make predictions
of the sensory feedback it&#39;s going to get.
And moreover, it profoundly changes your perceptions
by what you do.
And to do that, I&#39;ll tell you
about how the brain deals with sensory input.
So you send a command out,
you get sensory feedback back,
and that transformation is governed
by the physics of your body and your sensory apparatus.
But you can imagine looking inside the brain.
And here&#39;s inside the brain.
You might have a little predictor, a neural simulator,
of the physics of your body and your senses.
So as you send a movement command down,
you tap a copy of that off
and run it into your neural simulator
to anticipate the sensory consequences of your actions.
So as I shake this ketchup bottle,
I get some true sensory feedback as the function of time in the bottom row.
And if I&#39;ve got a good predictor, it predicts the same thing.
Well why would I bother doing that?
I&#39;m going to get the same feedback anyway.
Well there&#39;s good reasons.
Imagine, as I shake the ketchup bottle,
someone very kindly comes up to me and taps it on the back for me.
Now I get an extra source of sensory information
due to that external act.
So I get two sources.
I get you tapping on it, and I get me shaking it,
but from my senses&#39; point of view,
that is combined together into one source of information.
Now there&#39;s good reason to believe
that you would want to be able to distinguish external events from internal events.
Because external events are actually much more behaviorally relevant
than feeling everything that&#39;s going on inside my body.
So one way to reconstruct that
is to compare the prediction --
which is only based on your movement commands --
with the reality.
Any discrepancy should hopefully be external.
So as I go around the world,
I&#39;m making predictions of what I should get, subtracting them off.
Everything left over is external to me.
What evidence is there for this?
Well there&#39;s one very clear example
where a sensation generated by myself feels very different
then if generated by another person.
And so we decided the most obvious place to start
was with tickling.
It&#39;s been known for a long time, you can&#39;t tickle yourself
as well as other people can.
But it hasn&#39;t really been shown, it&#39;s because you have a neural simulator,
simulating your own body
and subtracting off that sense.
So we can bring the experiments of the 21st century
by applying robotic technologies to this problem.
And in effect, what we have is some sort of stick in one hand attached to a robot,
and they&#39;re going to move that back and forward.
And then we&#39;re going to track that with a computer
and use it to control another robot,
which is going to tickle their palm with another stick.
And then we&#39;re going to ask them to rate a bunch of things
including ticklishness.
I&#39;ll show you just one part of our study.
And here I&#39;ve taken away the robots,
but basically people move with their right arm sinusoidally back and forward.
And we replay that to the other hand with a time delay.
Either no time delay,
in which case light would just tickle your palm,
or with a time delay of two-tenths of three-tenths of a second.
So the important point here
is the right hand always does the same things -- sinusoidal movement.
The left hand always is the same and puts sinusoidal tickle.
All we&#39;re playing with is a tempo causality.
And as we go from naught to 0.1 second,
it becomes more ticklish.
As you go from 0.1 to 0.2,
it becomes more ticklish at the end.
And by 0.2 of a second,
it&#39;s equivalently ticklish
to the robot that just tickled you without you doing anything.
So whatever is responsible for this cancellation
is extremely tightly coupled with tempo causality.
And based on this illustration, we really convinced ourselves in the field
that the brain&#39;s making precise predictions
and subtracting them off from the sensations.
Now I have to admit, these are the worst studies my lab has ever run.
Because the tickle sensation on the palm comes and goes,
you need large numbers of subjects
with these stars making them significant.
So we were looking for a much more objective way
to assess this phenomena.
And in the intervening years I had two daughters.
And one thing you notice about children in backseats of cars on long journeys,
they get into fights --
which started with one of them doing something to the other, the other retaliating.
It quickly escalates.
And children tend to get into fights which escalate in terms of force.
Now when I screamed at my children to stop,
sometimes they would both say to me
the other person hit them harder.
Now I happen to know my children don&#39;t lie,
so I thought, as a neuroscientist,
it was important how I could explain
how they were telling inconsistent truths.
And we hypothesize based on the tickling study
that when one child hits another,
they generate the movement command.
They predict the sensory consequences and subtract it off.
So they actually think they&#39;ve hit the person less hard than they have --
rather like the tickling.
Whereas the passive recipient
doesn&#39;t make the prediction, feels the full blow.
So if they retaliate with the same force,
the first person will think it&#39;s been escalated.
So we decided to test this in the lab.

(Laughter)

Now we don&#39;t work with children, we don&#39;t work with hitting,
but the concept is identical.
We bring in two adults. We tell them they&#39;re going to play a game.
And so here&#39;s player one and player two sitting opposite to each other.
And the game is very simple.
We started with a motor
with a little lever, a little force transfuser.
And we use this motor to apply force down to player one&#39;s fingers
for three seconds and then it stops.
And that player&#39;s been told, remember the experience of that force
and use your other finger
to apply the same force
down to the other subject&#39;s finger through a force transfuser -- and they do that.
And player two&#39;s been told, remember the experience of that force.
Use your other hand to apply the force back down.
And so they take it in turns
to apply the force they&#39;ve just experienced back and forward.
But critically,
they&#39;re briefed about the rules of the game in separate rooms.
So they don&#39;t know the rules the other person&#39;s playing by.
And what we&#39;ve measured
is the force as a function of terms.
And if we look at what we start with,
a quarter of a Newton there, a number of turns,
perfect would be that red line.
And what we see in all pairs of subjects is this --
a 70 percent escalation in force
on each go.
So it really suggests, when you&#39;re doing this --
based on this study and others we&#39;ve done --
that the brain is canceling the sensory consequences
and underestimating the force it&#39;s producing.
So it re-shows the brain makes predictions
and fundamentally changes the precepts.
So we&#39;ve made inferences, we&#39;ve done predictions,
now we have to generate actions.
And what Bayes&#39; rule says is, given my beliefs,
the action should in some sense be optimal.
But we&#39;ve got a problem.
Tasks are symbolic -- I want to drink, I want to dance --
but the movement system has to contract 600 muscles
in a particular sequence.
And there&#39;s a big gap
between the task and the movement system.
So it could be bridged in infinitely many different ways.
So think about just a point to point movement.
I could choose these two paths
out of an infinite number of paths.
Having chosen a particular path,
I can hold my hand on that path
as infinitely many different joint configurations.
And I can hold my arm in a particular joint configuration
either very stiff or very relaxed.
So I have a huge amount of choice to make.
Now it turns out, we are extremely stereotypical.
We all move the same way pretty much.
And so it turns out we&#39;re so stereotypical,
our brains have got dedicated neural circuitry
to decode this stereotyping.
So if I take some dots
and set them in motion with biological motion,
your brain&#39;s circuitry would understand instantly what&#39;s going on.
Now this is a bunch of dots moving.
You will know what this person is doing,
whether happy, sad, old, young -- a huge amount of information.
If these dots were cars going on a racing circuit,
you would have absolutely no idea what&#39;s going on.
So why is it
that we move the particular ways we do?
Well let&#39;s think about what really happens.
Maybe we don&#39;t all quite move the same way.
Maybe there&#39;s variation in the population.
And maybe those who move better than others
have got more chance of getting their children into the next generation.
So in evolutionary scales, movements get better.
And perhaps in life, movements get better through learning.
So what is it about a movement which is good or bad?
Imagine I want to intercept this ball.
Here are two possible paths to that ball.
Well if I choose the left-hand path,
I can work out the forces required
in one of my muscles as a function of time.
But there&#39;s noise added to this.
So what I actually get, based on this lovely, smooth, desired force,
is a very noisy version.
So if I pick the same command through many times,
I will get a different noisy version each time, because noise changes each time.
So what I can show you here
is how the variability of the movement will evolve
if I choose that way.
If I choose a different way of moving -- on the right for example --
then I&#39;ll have a different command, different noise,
playing through a noisy system, very complicated.
All we can be sure of is the variability will be different.
If I move in this particular way,
I end up with a smaller variability across many movements.
So if I have to choose between those two,
I would choose the right one because it&#39;s less variable.
And the fundamental idea
is you want to plan your movements
so as to minimize the negative consequence of the noise.
And one intuition to get
is actually the amount of noise or variability I show here
gets bigger as the force gets bigger.
So you want to avoid big forces as one principle.
So we&#39;ve shown that using this,
we can explain a huge amount of data --
that exactly people are going about their lives planning movements
so as to minimize negative consequences of noise.
So I hope I&#39;ve convinced you the brain is there
and evolved to control movement.
And it&#39;s an intellectual challenge to understand how we do that.
But it&#39;s also relevant
for disease and rehabilitation.
There are many diseases which effect movement.
And hopefully if we understand how we control movement,
we can apply that to robotic technology.
And finally, I want to remind you,
when you see animals do what look like very simple tasks,
the actual complexity of what is going on inside their brain
is really quite dramatic.
Thank you very much.

(Applause)


Chris Anderson: Quick question for you, Dan.

So you&#39;re a movement -- (DW: Chauvinist.) -- chauvinist.
Does that mean that you think that the other things we think our brains are about --
the dreaming, the yearning, the falling in love and all these things --
are a kind of side show, an accident?

DW: No, no, actually I think they&#39;re all important
to drive the right movement behavior to get reproduction in the end.
So I think people who study sensation or memory
without realizing why you&#39;re laying down memories of childhood.
The fact that we forget most of our childhood, for example,
is probably fine, because it doesn&#39;t effect our movements later in life.
You only need to store things which are really going to effect movement.

CA: So you think that people thinking about the brain, and consciousness generally,
could get real insight
by saying, where does movement play in this game?

DW: So people have found out for example
that studying vision in the absence of realizing why you have vision
is a mistake.
You have to study vision with the realization
of how the movement system is going to use vision.
And it uses it very differently once you think about it that way.

CA: Well that was quite fascinating. Thank you very much indeed.

(Applause)

