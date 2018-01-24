
For the last 10 years, I&#39;ve been spending my time trying to figure out
how and why human beings
assemble themselves into social networks.
And the kind of social network I&#39;m talking about
is not the recent online variety,
but rather, the kind of social networks
that human beings have been assembling for hundreds of thousands of years,
ever since we emerged from the African savannah.
So, I form friendships and co-worker
and sibling and relative relationships with other people
who in turn have similar relationships with other people.
And this spreads on out endlessly into a distance.
And you get a network that looks like this.
Every dot is a person.
Every line between them is a relationship between two people --
different kinds of relationships.
And you can get this kind of vast fabric of humanity,
in which we&#39;re all embedded.
And my colleague, James Fowler and I have been studying for quite sometime
what are the mathematical, social,
biological and psychological rules
that govern how these networks are assembled
and what are the similar rules
that govern how they operate, how they affect our lives.
But recently, we&#39;ve been wondering
whether it might be possible to take advantage of this insight,
to actually find ways to improve the world,
to do something better,
to actually fix things, not just understand things.
So one of the first things we thought we would tackle
would be how we go about predicting epidemics.
And the current state of the art in predicting an epidemic --
if you&#39;re the CDC or some other national body --
is to sit in the middle where you are
and collect data
from physicians and laboratories in the field
that report the prevalence or the incidence of certain conditions.
So, so and so patients have been diagnosed with something,
or other patients have been diagnosed,
and all these data are fed into a central repository, with some delay.
And if everything goes smoothly,
one to two weeks from now
you&#39;ll know where the epidemic was today.
And actually, about a year or so ago,
there was this promulgation
of the idea of Google Flu Trends, with respect to the flu,
where by looking at people&#39;s searching behavior today,
we could know where the flu --
what the status of the epidemic was today,
what&#39;s the prevalence of the epidemic today.
But what I&#39;d like to show you today
is a means by which we might get
not just rapid warning about an epidemic,
but also actually
early detection of an epidemic.
And, in fact, this idea can be used
not just to predict epidemics of germs,
but also to predict epidemics of all sorts of kinds.
For example, anything that spreads by a form of social contagion
could be understood in this way,
from abstract ideas on the left
like patriotism, or altruism, or religion
to practices
like dieting behavior, or book purchasing,
or drinking, or bicycle-helmet [and] other safety practices,
or products that people might buy,
purchases of electronic goods,
anything in which there&#39;s kind of an interpersonal spread.
A kind of a diffusion of innovation
could be understood and predicted
by the mechanism I&#39;m going to show you now.
So, as all of you probably know,
the classic way of thinking about this
is the diffusion-of-innovation,
or the adoption curve.
So here on the Y-axis, we have the percent of the people affected,
and on the X-axis, we have time.
And at the very beginning, not too many people are affected,
and you get this classic sigmoidal,
or S-shaped, curve.
And the reason for this shape is that at the very beginning,
let&#39;s say one or two people
are infected, or affected by the thing
and then they affect, or infect, two people,
who in turn affect four, eight, 16 and so forth,
and you get the epidemic growth phase of the curve.
And eventually, you saturate the population.
There are fewer and fewer people
who are still available that you might infect,
and then you get the plateau of the curve,
and you get this classic sigmoidal curve.
And this holds for germs, ideas,
product adoption, behaviors,
and the like.
But things don&#39;t just diffuse in human populations at random.
They actually diffuse through networks.
Because, as I said, we live our lives in networks,
and these networks have a particular kind of a structure.
Now if you look at a network like this --
this is 105 people.
And the lines represent -- the dots are the people,
and the lines represent friendship relationships.
You might see that people occupy
different locations within the network.
And there are different kinds of relationships between the people.
You could have friendship relationships, sibling relationships,
spousal relationships, co-worker relationships,
neighbor relationships and the like.
And different sorts of things
spread across different sorts of ties.
For instance, sexually transmitted diseases
will spread across sexual ties.
Or, for instance, people&#39;s smoking behavior
might be influenced by their friends.
Or their altruistic or their charitable giving behavior
might be influenced by their coworkers,
or by their neighbors.
But not all positions in the network are the same.
So if you look at this, you might immediately grasp
that different people have different numbers of connections.
Some people have one connection, some have two,
some have six, some have 10 connections.
And this is called the &quot;degree&quot; of a node,
or the number of connections that a node has.
But in addition, there&#39;s something else.
So, if you look at nodes A and B,
they both have six connections.
But if you can see this image [of the network] from a bird&#39;s eye view,
you can appreciate that there&#39;s something very different
about nodes A and B.
So, let me ask you this -- I can cultivate this intuition by asking a question --
who would you rather be
if a deadly germ was spreading through the network, A or B?

(Audience: B.) Nicholas Christakis: B, it&#39;s obvious.
B is located on the edge of the network.
Now, who would you rather be
if a juicy piece of gossip were spreading through the network?
A. And you have an immediate appreciation
that A is going to be more likely
to get the thing that&#39;s spreading and to get it sooner
by virtue of their structural location within the network.
A, in fact, is more central,
and this can be formalized mathematically.
So, if we want to track something
that was spreading through a network,
what we ideally would like to do is to set up sensors
on the central individuals within the network,
including node A,
monitor those people that are right there in the middle of the network,
and somehow get an early detection
of whatever it is that is spreading through the network.
So if you saw them contract a germ or a piece of information,
you would know that, soon enough,
everybody was about to contract this germ
or this piece of information.
And this would be much better
than monitoring six randomly chosen people,
without reference to the structure of the population.
And in fact, if you could do that,
what you would see is something like this.
On the left-hand panel, again, we have the S-shaped curve of adoption.
In the dotted red line, we show
what the adoption would be in the random people,
and in the left-hand line, shifted to the left,
we show what the adoption would be
in the central individuals within the network.
On the Y-axis is the cumulative instances of contagion,
and on the X-axis is the time.
And on the right-hand side, we show the same data,
but here with daily incidence.
And what we show here is -- like, here --
very few people are affected, more and more and more and up to here,
and here&#39;s the peak of the epidemic.
But shifted to the left is what&#39;s occurring in the central individuals.
And this difference in time between the two
is the early detection, the early warning we can get,
about an impending epidemic
in the human population.
The problem, however,
is that mapping human social networks
is not always possible.
It can be expensive, not feasible,
unethical,
or, frankly, just not possible to do such a thing.
So, how can we figure out
who the central people are in a network
without actually mapping the network?
What we came up with
was an idea to exploit an old fact,
or a known fact, about social networks,

which goes like this:
Do you know that your friends
have more friends than you do?
Your friends have more friends than you do,
and this is known as the friendship paradox.
Imagine a very popular person in the social network --
like a party host who has hundreds of friends --
and a misanthrope who has just one friend,
and you pick someone at random from the population;
they were much more likely to know the party host.
And if they nominate the party host as their friend,
that party host has a hundred friends,
therefore, has more friends than they do.
And this, in essence, is what&#39;s known as the friendship paradox.
The friends of randomly chosen people
have higher degree, and are more central
than the random people themselves.
And you can get an intuitive appreciation for this
if you imagine just the people at the perimeter of the network.
If you pick this person,
the only friend they have to nominate is this person,
who, by construction, must have at least two
and typically more friends.
And that happens at every peripheral node.
And in fact, it happens throughout the network as you move in,
everyone you pick, when they nominate a random --
when a random person nominates a friend of theirs,
you move closer to the center of the network.
So, we thought we would exploit this idea
in order to study whether we could predict phenomena within networks.
Because now, with this idea
we can take a random sample of people,
have them nominate their friends,
those friends would be more central,
and we could do this without having to map the network.
And we tested this idea with an outbreak of H1N1 flu
at Harvard College
in the fall and winter of 2009, just a few months ago.
We took 1,300 randomly selected undergraduates,
we had them nominate their friends,
and we followed both the random students and their friends
daily in time
to see whether or not they had the flu epidemic.
And we did this passively by looking at whether or not they&#39;d gone to university health services.
And also, we had them [actively] email us a couple of times a week.
Exactly what we predicted happened.
So the random group is in the red line.
The epidemic in the friends group has shifted to the left, over here.
And the difference in the two is 16 days.
By monitoring the friends group,
we could get 16 days advance warning
of an impending epidemic in this human population.
Now, in addition to that,
if you were an analyst who was trying to study an epidemic
or to predict the adoption of a product, for example,
what you could do is you could pick a random sample of the population,
also have them nominate their friends and follow the friends
and follow both the randoms and the friends.
Among the friends, the first evidence you saw of a blip above zero
in adoption of the innovation, for example,
would be evidence of an impending epidemic.
Or you could see the first time the two curves diverged,
as shown on the left.
When did the randoms -- when did the friends take off
and leave the randoms,
and [when did] their curve start shifting?
And that, as indicated by the white line,
occurred 46 days
before the peak of the epidemic.
So this would be a technique
whereby we could get more than a month-and-a-half warning
about a flu epidemic in a particular population.
I should say that
how far advanced a notice one might get about something
depends on a host of factors.
It could depend on the nature of the pathogen --
different pathogens,
using this technique, you&#39;d get different warning --
or other phenomena that are spreading,
or frankly, on the structure of the human network.
Now in our case, although it wasn&#39;t necessary,
we could also actually map the network of the students.
So, this is a map of 714 students
and their friendship ties.
And in a minute now, I&#39;m going to put this map into motion.
We&#39;re going to take daily cuts through the network
for 120 days.
The red dots are going to be cases of the flu,
and the yellow dots are going to be friends of the people with the flu.
And the size of the dots is going to be proportional
to how many of their friends have the flu.
So bigger dots mean more of your friends have the flu.
And if you look at this image -- here we are now in September the 13th --
you&#39;re going to see a few cases light up.
You&#39;re going to see kind of blooming of the flu in the middle.
Here we are on October the 19th.
The slope of the epidemic curve is approaching now, in November.
Bang, bang, bang, bang, bang -- you&#39;re going to see lots of blooming in the middle,
and then you&#39;re going to see a sort of leveling off,
fewer and fewer cases towards the end of December.
And this type of a visualization
can show that epidemics like this take root
and affect central individuals first,
before they affect others.
Now, as I&#39;ve been suggesting,
this method is not restricted to germs,
but actually to anything that spreads in populations.
Information spreads in populations,
norms can spread in populations,
behaviors can spread in populations.
And by behaviors, I can mean things like criminal behavior,
or voting behavior, or health care behavior,
like smoking, or vaccination,
or product adoption, or other kinds of behaviors
that relate to interpersonal influence.
If I&#39;m likely to do something that affects others around me,
this technique can get early warning or early detection
about the adoption within the population.
The key thing is that for it to work,
there has to be interpersonal influence.
It cannot be because of some broadcast mechanism
affecting everyone uniformly.
Now the same insights
can also be exploited -- with respect to networks --
can also be exploited in other ways,
for example, in the use of targeting
specific people for interventions.
So, for example, most of you are probably familiar
with the notion of herd immunity.
So, if we have a population of a thousand people,
and we want to make the population immune to a pathogen,
we don&#39;t have to immunize every single person.
If we immunize 960 of them,
it&#39;s as if we had immunized a hundred [percent] of them.
Because even if one or two of the non-immune people gets infected,
there&#39;s no one for them to infect.
They are surrounded by immunized people.
So 96 percent is as good as 100 percent.
Well, some other scientists have estimated
what would happen if you took a 30 percent random sample
of these 1000 people, 300 people and immunized them.
Would you get any population-level immunity?
And the answer is no.
But if you took this 30 percent, these 300 people
and had them nominate their friends
and took the same number of vaccine doses
and vaccinated the friends of the 300 --
the 300 friends --
you can get the same level of herd immunity
as if you had vaccinated 96 percent of the population
at a much greater efficiency, with a strict budget constraint.
And similar ideas can be used, for instance,
to target distribution of things like bed nets
in the developing world.
If we could understand the structure of networks in villages,
we could target to whom to give the interventions
to foster these kinds of spreads.
Or, frankly, for advertising with all kinds of products.
If we could understand how to target,
it could affect the efficiency
of what we&#39;re trying to achieve.
And in fact, we can use data
from all kinds of sources nowadays [to do this].
This is a map of eight million phone users
in a European country.
Every dot is a person, and every line represents
a volume of calls between the people.
And we can use such data, that&#39;s being passively obtained,
to map these whole countries
and understand who is located where within the network.
Without actually having to query them at all,
we can get this kind of a structural insight.
And other sources of information, as you&#39;re no doubt aware
are available about such features, from email interactions,
online interactions,
online social networks and so forth.
And in fact, we are in the era of what I would call
&quot;massive-passive&quot; data collection efforts.
They&#39;re all kinds of ways we can use massively collected data
to create sensor networks
to follow the population,
understand what&#39;s happening in the population,
and intervene in the population for the better.
Because these new technologies tell us
not just who is talking to whom,
but where everyone is,
and what they&#39;re thinking based on what they&#39;re uploading on the Internet,
and what they&#39;re buying based on their purchases.
And all this administrative data can be pulled together
and processed to understand human behavior
in a way we never could before.
So, for example, we could use truckers&#39; purchases of fuel.
So the truckers are just going about their business,
and they&#39;re buying fuel.
And we see a blip up in the truckers&#39; purchases of fuel,
and we know that a recession is about to end.
Or we can monitor the velocity
with which people are moving with their phones on a highway,
and the phone company can see,
as the velocity is slowing down,
that there&#39;s a traffic jam.
And they can feed that information back to their subscribers,
but only to their subscribers on the same highway
located behind the traffic jam!
Or we can monitor doctors prescribing behaviors, passively,
and see how the diffusion of innovation with pharmaceuticals
occurs within [networks of] doctors.
Or again, we can monitor purchasing behavior in people
and watch how these types of phenomena
can diffuse within human populations.
And there are three ways, I think,
that these massive-passive data can be used.
One is fully passive,
like I just described --
as in, for instance, the trucker example,
where we don&#39;t actually intervene in the population in any way.
One is quasi-active,
like the flu example I gave,
where we get some people to nominate their friends
and then passively monitor their friends --
do they have the flu, or not? -- and then get warning.
Or another example would be,
if you&#39;re a phone company, you figure out who&#39;s central in the network
and you ask those people, &quot;Look, will you just text us your fever every day?
Just text us your temperature.&quot;
And collect vast amounts of information about people&#39;s temperature,
but from centrally located individuals.
And be able, on a large scale,
to monitor an impending epidemic
with very minimal input from people.
Or, finally, it can be more fully active --
as I know subsequent speakers will also talk about today --
where people might globally participate in wikis,
or photographing, or monitoring elections,
and upload information in a way that allows us to pool
information in order to understand social processes
and social phenomena.
In fact, the availability of these data, I think,
heralds a kind of new era
of what I and others would like to call
&quot;computational social science.&quot;
It&#39;s sort of like when Galileo invented -- or, didn&#39;t invent --
came to use a telescope
and could see the heavens in a new way,
or Leeuwenhoek became aware of the microscope --
or actually invented --
and could see biology in a new way.
But now we have access to these kinds of data
that allow us to understand social processes
and social phenomena
in an entirely new way that was never before possible.
And with this science, we can
understand how exactly
the whole comes to be greater
than the sum of its parts.
And actually, we can use these insights
to improve society and improve human well-being.
Thank you.
