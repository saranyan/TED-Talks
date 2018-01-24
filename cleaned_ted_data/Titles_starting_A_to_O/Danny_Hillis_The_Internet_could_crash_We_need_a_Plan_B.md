

Translator: Joseph Geni

Reviewer: Morton Bast
So, this book that I have in my hand
is a directory of everybody who had an email address
in 1982. 
(Laughter)

Actually, it&#39;s deceptively large.
There&#39;s actually only about 20 people on each page,
because we have the name, address
and telephone number of every single person.
And, in fact, everybody&#39;s listed twice,
because it&#39;s sorted once by name and once by email address.
Obviously a very small community.
There were only two other Dannys on the Internet then.
I knew them both.
We didn&#39;t all know each other,
but we all kind of trusted each other,
and that basic feeling of trust
permeated the whole network,
and there was a real sense that
we could depend on each other to do things.
So just to give you an idea of the level of trust in this community,
let me tell you what it was like
to register a domain name in the early days.
Now, it just so happened that I got to register
the third domain name on the Internet.
So I could have anything I wanted
other than bbn.com and symbolics.com.
So I picked think.com, but then I thought,
you know, there&#39;s a lot of really interesting names out there.
Maybe I should register a few extras just in case.
And then I thought, &quot;Nah, that wouldn&#39;t be very nice.&quot;

(Laughter)

That attitude of only taking what you need
was really what everybody had on the network in those days,
and in fact, it wasn&#39;t just the people on the network,
but it was actually kind of built into the protocols
of the Internet itself.
So the basic idea of I.P., or Internet protocol,
and the way that the -- the routing algorithm that used it,
were fundamentally &quot;from each according to their ability,
to each according to their need.&quot;
And so, if you had some extra bandwidth,
you&#39;d deliver a message for someone.
If they had some extra bandwidth, they would deliver a message for you.
You&#39;d kind of depend on people to do that,
and that was the building block.
It was actually interesting that such a communist principle
was the basis of a system developed during the Cold War
by the Defense Department,
but it obviously worked really well,
and we all saw what happened with the Internet.
It was incredibly successful.
In fact, it was so successful that there&#39;s no way
that these days you could make a book like this.
My rough calculation is it would be about 25 miles thick.
But, of course, you couldn&#39;t do it,
because we don&#39;t know the names of all the people
with Internet or email addresses,
and even if we did know their names,
I&#39;m pretty sure that they would not want their name,
address and telephone number published to everyone.
So the fact is that there&#39;s a lot of bad guys on the Internet these days,
and so we dealt with that by making
walled communities,
secure subnetworks, VPNs,
little things that aren&#39;t really the Internet
but are made out of the same building blocks,
but we&#39;re still basically building it out of those
same building blocks with those same assumptions of trust.
And that means that it&#39;s vulnerable
to certain kinds of mistakes that can happen,
or certain kinds of deliberate attacks,
but even the mistakes can be bad.
So, for instance,
in all of Asia recently,
it was impossible to get YouTube for a little while
because Pakistan made some mistakes
in how it was censoring YouTube in its internal network.
They didn&#39;t intend to screw up Asia, but they did
because of the way that the protocols work.
Another example that may have affected many of you in this audience is,
you may remember a couple of years ago,
all the planes west of the Mississippi were grounded
because a single routing card in Salt Lake City
had a bug in it.
Now, you don&#39;t really think
that our airplane system depends on the Internet,
and in some sense it doesn&#39;t.
I&#39;ll come back to that later.
But the fact is that people couldn&#39;t take off
because something was going wrong on the Internet,
and the router card was down.
And so, there are many of those things that start to happen.
Now, there was an interesting thing that happened last April.
All of a sudden,
a very large percentage of the traffic on the whole Internet,
including a lot of the traffic between U.S. military installations,
started getting re-routed through China.
So for a few hours, it all passed through China.
Now, China Telecom says it was just an honest mistake,
and it is actually possible that it was, the way things work,
but certainly somebody could make
a dishonest mistake of that sort if they wanted to,
and it shows you how vulnerable the system is even to mistakes.
Imagine how vulnerable the system is to deliberate attacks.
So if somebody really wanted to attack the United States
or Western civilization these days,
they&#39;re not going to do it with tanks.
That will not succeed.
What they&#39;ll probably do is something
very much like the attack that happened
on the Iranian nuclear facility.
Nobody has claimed credit for that.
There was basically a factory of industrial machines.
It didn&#39;t think of itself as being on the Internet.
It thought of itself as being disconnected from the Internet,
but it was possible for somebody to smuggle
a USB drive in there, or something like that,
and software got in there that causes the centrifuges,
in that case, to actually destroy themselves.
Now that same kind of software could destroy an oil refinery
or a pharmaceutical factory or a semiconductor plant.
And so there&#39;s a lot of -- I&#39;m sure you&#39;ve read a lot in papers,
about worries about cyberattacks
and defenses against those.
But the fact is, people are mostly focused on
defending the computers on the Internet,
and there&#39;s been surprisingly little attention
to defending the Internet itself as a communications medium.
And I think we probably do need to pay
some more attention to that, because it&#39;s actually kind of fragile.
So actually, in the early days,
back when it was the ARPANET,
there were actually times -- there was a particular time it failed completely
because one single message processor
actually got a bug in it.
And the way the Internet works is
the routers are basically exchanging information
about how they can get messages to places,
and this one processor, because of a broken card,
decided it could actually get a message
to some place in negative time.
So, in other words, it claimed it could deliver a message before you sent it.
So of course, the fastest way to get a message anywhere
was to send it to this guy,
who would send it back in time and get it there super early,
so every message in the Internet
started getting switched through this one node,
and of course that clogged everything up.
Everything started breaking.
The interesting thing was, though,
that the sysadmins were able to fix it,
but they had to basically turn every single thing on the Internet off.
Now, of course you couldn&#39;t do that today.
I mean, everything off, it&#39;s like
the service call you get from the cable company,
except for the whole world.
Now, in fact, they couldn&#39;t do it for a lot of reasons today.
One of the reasons is a lot of their telephones
use IP protocol and use things like Skype and so on
that go through the Internet right now,
and so in fact we&#39;re becoming dependent on it
for more and more different things,
like when you take off from LAX,
you&#39;re really not thinking you&#39;re using the Internet.
When you pump gas, you really don&#39;t think you&#39;re using the Internet.
What&#39;s happening increasingly, though, is these systems
are beginning to use the Internet.
Most of them aren&#39;t based on the Internet yet,
but they&#39;re starting to use the Internet for service functions,
for administrative functions,
and so if you take something like the cell phone system,
which is still relatively independent of the Internet for the most part,
Internet pieces are beginning to sneak into it
in terms of some of the control and administrative functions,
and it&#39;s so tempting to use these same building blocks
because they work so well, they&#39;re cheap,
they&#39;re repeated, and so on.
So all of our systems, more and more,
are starting to use the same technology
and starting to depend on this technology.
And so even a modern rocket ship these days
actually uses Internet protocol to talk
from one end of the rocket ship to the other.
That&#39;s crazy. It was never designed to do things like that.
So we&#39;ve built this system
where we understand all the parts of it,
but we&#39;re using it in a very, very different way than we expected to use it,
and it&#39;s gotten a very, very different scale
than it was designed for.
And in fact, nobody really exactly understands
all the things it&#39;s being used for right now.
It&#39;s turning into one of these big emergent systems
like the financial system, where we&#39;ve designed all the parts
but nobody really exactly understands
how it operates and all the little details of it
and what kinds of emergent behaviors it can have.
And so if you hear an expert talking about the Internet
and saying it can do this, or it does do this, or it will do that,
you should treat it with the same skepticism
that you might treat the comments of an economist about the economy
or a weatherman about the weather, or something like that.
They have an informed opinion,
but it&#39;s changing so quickly that even the experts
don&#39;t know exactly what&#39;s going on.
So if you see one of these maps of the Internet,
it&#39;s just somebody&#39;s guess.
Nobody really knows what the Internet is right now
because it&#39;s different than it was an hour ago.
It&#39;s constantly changing. It&#39;s constantly reconfiguring.
And the problem with it is,
I think we are setting ourselves up for a kind of disaster
like the disaster we had in the financial system,
where we take a system that&#39;s basically built on trust,
was basically built for a smaller-scale system,
and we&#39;ve kind of expanded it way beyond the limits
of how it was meant to operate.
And so right now, I think it&#39;s literally true
that we don&#39;t know what the consequences
of an effective denial-of-service attack
on the Internet would be,
and whatever it would be is going to be worse next year,
and worse next year, and so on.
But so what we need is a plan B.
There is no plan B right now.
There&#39;s no clear backup system that we&#39;ve very carefully kept
to be independent of the Internet,
made out of completely different sets of building blocks.
So what we need is something that doesn&#39;t necessarily
have to have the performance of the Internet,
but the police department has to be able
to call up the fire department even without the Internet,
or the hospitals have to order fuel oil.
This doesn&#39;t need to be a multi-billion-dollar government project.
It&#39;s actually relatively simple to do, technically,
because it can use existing fibers that are in the ground,
existing wireless infrastructure.
It&#39;s basically a matter of deciding to do it.
But people won&#39;t decide to do it
until they recognize the need for it,
and that&#39;s the problem that we have right now.
So there&#39;s been plenty of people,
plenty of us have been quietly arguing
that we should have this independent system for years,
but it&#39;s very hard to get people focused on plan B
when plan A seems to be working so well.
So I think that, if people understand
how much we&#39;re starting to depend on the Internet,
and how vulnerable it is,
we could get focused on
just wanting this other system to exist,
and I think if enough people say, &quot;Yeah, I would like to use it,
I&#39;d like to have such a system,&quot; then it will get built.
It&#39;s not that hard a problem.
It could definitely be done by people in this room.
And so I think that this is actually,
of all the problems you&#39;re going to hear about at the conference,
this is probably one of the very easiest to fix.
So I&#39;m happy to get a chance to tell you about it.
Thank you very much.

(Applause)

