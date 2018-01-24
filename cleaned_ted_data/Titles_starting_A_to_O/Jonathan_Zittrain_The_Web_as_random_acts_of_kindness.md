
My name is Jonathan Zittrain,
and in my recent work I&#39;ve been a bit of a pessimist.
So I thought this morning I would try to be the optimist,
and give reason to hope
for the future of the Internet
by drawing upon its present.
Now, it may seem like there is less hope today than there was before.
People are less kind. There is less trust around.
I don&#39;t know. As a simple example,
we could run a test here.
How many people have ever hitchhiked?
I know. How many people have hitchhiked
within the past 10 years?
Right. So what has changed?
It&#39;s not better public transportation.
So that&#39;s one reason to think that we might be
declensionists, going in the wrong direction.
But I want to give you three examples
to try to say that the trend line
is in fact in the other direction,
and it&#39;s the Internet helping it along.

So example number one: the Internet itself.
These are three of the founders of the Internet.
They were actually high school classmates together
at the same high school in suburban Los Angles in the 1960s.
You might have had a French club or a Debate club.
They had a &quot;Let&#39;s build a global network&quot; club,
and it worked out very well.
They are pictured here for their 25th anniversary
Newsweek retrospective on the Internet.
And as you can tell,
they are basically goof balls.
They had one great limitation
and one great freedom
as they tried to conceive of a global network.
The limitation was that they didn&#39;t have any money.
No particular amount of capital to invest,
of the sort that for a physical network
you might need for trucks and people
and a hub to move packages around overnight.
They had none of that.
But they had an amazing freedom,
which was they didn&#39;t have to make any money from it.
The Internet has no business plan, never did.
No CEO,
no firm responsible, singly, for building it.
Instead, it&#39;s folks getting together
to do something for fun,
rather than because they were told to,
or because they were expecting to make a mint off of it.
That ethos led to a network architecture,
a structure that was unlike
other digital networks then or since.
So unusual, in fact,
that it was said that it&#39;s not clear the Internet could work.
As late as 1992, IBM was known to say
you couldn&#39;t possibly build a corporate network
using Internet Protocol.
And even some Internet engineers today say
the whole thing is a pilot project and the jury is still out.

(Laughter)

That&#39;s why the mascot of Internet engineering,
if it had one, is said to be the bumblebee.
Because the fur-to-wingspan ratio of the bumblebee
is far too large for it to be able to fly.
And yet, mysteriously, somehow the bee flies.
I&#39;m pleased to say that, thanks to massive government funding,
about three years ago we finally figured out
how bees fly.

(Laughter)

It&#39;s very complicated, but it turns out they
flap their wings very quickly.

(Laughter)

So what is this bizarre architecture configuration
that makes the network sing and be so unusual?
Well, to move data around
from one place to another -- again, it&#39;s not like a package courier.
It&#39;s more like a mosh pit.

(Laughter)

Imagine, you being part of a network
where, you&#39;re maybe at a sporting event,
and you&#39;re sitting in rows like this,
and somebody asks for a beer,
and it gets handed at the aisle.
And your neighborly duty
is to pass the beer along,
at risk to your own trousers,
to get it to the destination.
No one pays you to do this.
It&#39;s just part of your neighborly duty.
And, in a way, that&#39;s exactly how packets move around the Internet,
sometimes in as many as 25 or 30 hops,
with the intervening entities
that are passing the data around
having no particular contractual or legal obligation
to the original sender
or to the receiver.
Now, of course, in a mosh pit it&#39;s hard to specify a destination.
You need a lot of trust,
but it&#39;s not like, &quot;I&#39;m trying to get to Pensacola, please.&quot;
So the Internet needs addressing and directions.
It turns out there is no one overall map of the Internet.
Instead, again, it is as if we are all sitting together in a theater,
but we can only see amidst the fog
the people immediately around us.
So what do we do to figure out who is where?
We turn to the person on the right,
and we tell that person what we see on our left,
and vice versa.
And they can lather, rinse, repeat. And before you know it,
you have a general sense of where everything is.
This is how Internet addressing and routing actually work.
This is a system that relies on kindness and trust,
which also makes it very delicate and vulnerable.
In rare but striking instances,
a single lie told by just one entity
in this honeycomb
can lead to real trouble.
So, for example, last year,
the government of Pakistan
asked its Internet service providers there
to prevent citizens of Pakistan from seeing YouTube.
There was a video there that the government did not like
and they wanted to make sure it was blocked.
This is a common occurrence. Governments everywhere
are often trying to block
and filter and censor content on the Internet.
Well this one ISP in Pakistan
chose to effectuate the block for its subscribers
in a rather unusual way.
It advertised --
the way that you might be asked, if you were part of the Internet,
to declare what you see near you -- it advertised
that near it, in fact, it had suddenly awakened to find
that it was YouTube.
&quot;That&#39;s right,&quot; it said, &quot;I am YouTube.&quot;
Which meant that packets of data
from subscribers going to YouTube
stopped at the ISP, since they thought they were already there,
and the ISP threw them away unopened
because the point was to block it.
But it didn&#39;t stop there.
You see, that announcement
went one click out,
which got reverberated, one click out.
And it turns out that as you look
at the postmortem of this event,
you have at one moment
perfectly working YouTube.
Then, at moment number two,
you have the fake announcement go out.
And within two minutes,
it reverberates around
and YouTube is blocked everywhere in the world.
If you were sitting in Oxford, England, trying to get to YouTube,
your packets were going to Pakistan
and they weren&#39;t coming back.
Now just think about that.
One of the most popular websites in the world,
run by the most powerful company in the world,
and there was nothing that YouTube or Google
were particularly privileged to do about it.
And yet, somehow, within about two hours,
the problem was fixed.
How did this happen?
Well, for a big clue, we turn to NANOG.
The North American Network Operators Group,
a group of people who,
on a beautiful day outside,
enter into a windowless room,
at their terminals
reading email and messages
in fixed proportion font, like this,
and they talk about networks.
And some of them are mid-level employees at Internet service providers
around the world.
And here is the message where one of them says,
&quot;Looks like we&#39;ve got a live one. We have a hijacking of YouTube!
This is not a drill. It&#39;s not just the cluelessness
of YouTube engineers. I promise.
Something is up in Pakistan.&quot;
And they came together to help find the problem and fix it.
So it&#39;s kind of like if your house catches on fire.
The bad news is there is no fire brigade.
The good news is random people apparate from nowhere,
put out the fire and leave without expecting payment or praise.

(Applause)

I was trying to think of the right model to describe
this form of random acts of kindness
by geeky strangers.

(Laughter)

You know, it&#39;s just like the hail goes out
and people are ready to help.
And it turns out this model is everywhere, once you start looking for it.

Example number two: Wikipedia.
If a man named Jimbo came up to you in 2001
and said, &quot;I&#39;ve got a great idea! We start with seven articles
that anybody can edit anything, at any time,
and we&#39;ll get a great encyclopedia! Eh?&quot;
Right. Dumbest idea ever.

(Laughter)

In fact, Wikipedia is an idea so profoundly stupid
that even Jimbo never had it.
Jimbo&#39;s idea was for Nupedia.
It was going to be totally traditional. He would pay people money
because he was feeling like a good guy,
and the money would go to the people
and they would write the articles.
The wiki was introduced
so others could make suggestions on edits --
as almost an afterthought, a back room.
And then it turns out the back room grew
to encompass the entire project.
And today, Wikipedia is so ubiquitous
that you can now find it on Chinese restaurant menus.

(Laughter)

I am not making this up.

(Laughter)

I have a theory I can explain later.
Suffice it to say for now that I prefer my Wikipedia
stir-fried with pimentos.

(Laughter)

But now, Wikipedia doesn&#39;t just spontaneously work.
How does it really work? It turns out
there is a back room that is kind of windowless,
metaphorically speaking.
And there are a bunch of people who, on a sunny day,
would rather be inside
and monitoring this, the administrator&#39;s notice board,
itself a wiki page that anyone can edit.
And you just bring your problems to the page.
It&#39;s reminiscent of the description of history
as &quot;one damn thing after another,&quot; right?

Number one: &quot;Tendentious editing by user Andyvphil.&quot;
Apologies, Andyvphil, if you&#39;re here today.
I&#39;m not taking sides.
&quot;Anon attacking me for reverting.&quot;

Here is my favorite: &quot;A long story.&quot;

(Laughter)

It turns out there are more people checking this page for problems
and wanting to solve them
than there are problems arising on the page.
And that&#39;s what keeps Wikipedia afloat.
At all times, Wikipedia is approximately
45 minutes away from utter destruction. Right?
There are spambots crawling it, trying to turn every article
into an ad for a Rolex watch.

(Laughter)

It&#39;s this thin geeky line
that keeps it going.
Not because it&#39;s a job,
not because it&#39;s a career,
but because it&#39;s a calling.
It&#39;s something they feel impelled to do
because they care about it.
They even gather together in such groups
as the Counter-Vandalism Unit --
&quot;Civility, Maturity, Responsibility&quot; --
to just clean up the pages.
It does make you wonder if there were, for instance,
a massive, extremely popular Star Trek convention one weekend,
who would be minding the store?

(Laughter)

So what we see --

(Laughter)

what we see in this phenomenon
is something that the crazed, late traffic engineer
Hans Monderman discovered in the Netherlands,
and here in South Kensington, that sometimes
if you remove some of the external rules and signs and everything else,
you can actually end up
with a safer environment in which people can function,
and one in which they are more human with each other.
They&#39;re realizing that they
have to take responsibility for what they do.
And Wikipedia has embraced this.
Some of you may remember Star Wars Kid,
the poor teenager who filmed himself with a golf ball retriever,
acting as if it were a light saber.
The film, without his permission or even knowledge at first,
found its way onto the Internet.
Hugely viral video. Extremely popular.
Totally mortifying to him.
Now, it being encyclopedic and all,
Wikipedia had to do an article about Star Wars Kid.
Every article on Wikipedia has a corresponding discussion page,
and on the discussion page
they had extensive argument among the Wikipedians
as to whether to have his real name
featured in the article.
You could see arguments on both sides.
Here is just a snapshot of some of them.
They eventually decided --
not unanimously by any means --
not to include his real name,
despite the fact that nearly all media reports did.
They just didn&#39;t think it was the right thing to do.
It was an act of kindness.
And to this day, the page for Star Wars Kid
has a warning right at the top
that says you are not to put his real name on the page.
If you do, it will be removed immediately,
removed by people who may have disagreed with the original decision,
but respect the outcome
and work to make it stay
because they believe in something bigger than their own opinion.
As a lawyer, I&#39;ve got to say these guys are inventing the law
and stare decisis and stuff like that as they go along.
Now, this isn&#39;t just limited to Wikipedia.
We see it on blogs all over the place.
I mean, this is a 2005 Business Week cover.
Wow. Blogs are going to change your business.
I know they look silly. And sure they look silly.
They start off on all sorts of goofy projects.

This is my favorite goofy blog:
Catsthatlooklikehitler.com.

(Laughter)

You send in a picture of your cat
if it looks like Hitler.

(Laughter)

Yeah, I know. Number four, it&#39;s like, can you imagine
coming home to that cat everyday?

(Laughter)

But then, you can see the same kind of whimsy
applied to people.
So this is a blog devoted to unfortunate portraiture.
This one says, &quot;Bucolic meadow with split-rail fence.
Is that an animal carcass behind her?&quot;

(Laughter)

You&#39;re like, &quot;You know? I think that&#39;s an animal carcass
behind her.&quot;
And it&#39;s one after the other.
But then you hit this one. Image removed at request of owner.
That&#39;s it. Image removed at request of owner.
It turns out that somebody lampooned here
wrote to the snarky guy that does the site,
not with a legal threat, not with an offer of payment,
but just said, &quot;Hey, would you mind?&quot;
The person said, &quot;No, that&#39;s fine.&quot;
I believe we can build architectures online
to make such human requests
that much easier to do,
to make it possible for all of us to see
that the data we encounter online
is just stuff on which to click and paste and copy and forward
that actually represents human emotion
and endeavor and impact,
and to be able to have an ethical moment
where we decide how we want to treat it.
I even think it can go into the real world.
We can end up, as we get in a world with more censors --
everywhere there is something filming you, maybe putting it online --
to be able to have a little clip you could wear
that says, &quot;You know, I&#39;d rather not.&quot;
And then have technology
that the person taking the photo will know later,
this person requested to be contacted
before this goes anywhere big,
if you don&#39;t mind.
And that person taking the photo can make a decision
about how and whether to respect it.
In the real world, we see filtering of this sort
taking place in Pakistan.
And we now have means that we can build, like this system,
so that people can report the filtering as they encounter it.
And it&#39;s no longer just a &quot;I don&#39;t know. I couldn&#39;t get there. I guess I&#39;ll move on,&quot;
but suddenly a collective consciousness
about what is blocked and censored
where online.
In fact, talk about technology imitating life
imitating tech, or maybe it&#39;s the other way around.
An NYU researcher here took little cardboard robots
with smiley faces on them,
and a motor that just drove them forward
and a flag sticking out the back
with a desired destination.
It said, &quot;Can you help me get there?&quot;
Released it on the streets of Manhattan.

(Laughter)

They&#39;ll fund anything these days.
Here is the chart of over 43 people
helping to steer the robot that could not steer
and get it on its way, from one corner
from one corner of Washington Square Park
to another.

That leads to example number three: hitchhiking.
I&#39;m not so sure hitchhiking is dead.
Why? There is the Craigslist rideshare board.
If it were called the Craigslist hitchhiking board,
tumbleweeds would be blowing through it.
But it&#39;s the rideshare board, and it&#39;s basically the same thing.
Now why are people using it?
I don&#39;t know. Maybe they think that, uh, killers don&#39;t plan ahead?

(Laughter)

No. I think the actual answer is
that once you reframe it,
once you get out of one set of stale expectations
from a failed project that had its day,
but now, for whatever reason, is tarnished,
you can actually rekindle the kind of human kindness and sharing
that something like this on Craigslist represents.
And then you can highlight it
into something like,
yes, CouchSurfing.org.

CouchSurfing: one guy&#39;s idea
to, at last, put together people who are going somewhere far away
and would like to sleep on a stranger&#39;s couch for free,
with people who live far away,
and would like someone they don&#39;t know to sleep on their couch for free.
It&#39;s a brilliant idea.
It&#39;s a bee that, yes, flies.
Amazing how many successful couch surfings there have been.
And if you&#39;re wondering, no, there have been no known fatalities
associated with CouchSurfing.
Although, to be sure, the reputation system, at the moment,
works that you leave your report after the couch surfing experience,
so there may be some selection bias there.

(Laughter)

So, my urging, my thought,
is that the Internet isn&#39;t just a pile of information.
It&#39;s not a noun. It&#39;s a verb.
And when you go on it,
if you listen and see carefully and closely enough,
what you will discover
is that that information
is saying something to you.
What it&#39;s saying to you is what we heard yesterday,
Demosthenes was saying to us.
It&#39;s saying, &quot;Let&#39;s march.&quot; Thank you very much.

(Applause)

