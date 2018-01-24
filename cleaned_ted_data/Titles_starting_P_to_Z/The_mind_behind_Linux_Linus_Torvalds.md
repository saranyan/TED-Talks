

Chris Anderson: This is such
a strange thing.
Your software, Linux,
is in millions of computers,
it probably powers much of the Internet.
And I think that there are, like,
a billion and a half active
Android devices out there.
Your software is in every
single one of them.
It&#39;s kind of amazing.
You must have some amazing
software headquarters driving all this.
That&#39;s what I thought -- and I was shocked
when I saw a picture of it.
I mean, this is --
this is the Linux world headquarters.

(Laughter)


(Applause)


Linus Torvalds: It really
doesn&#39;t look like much.
And I have to say,
the most interesting part in this picture,
that people mostly react to,
is the walking desk.
It is the most interesting
part in my office
and I&#39;m not actually using it anymore.
And I think the two things are related.
The way I work is ...
I want to not have external stimulation.
You can kind of see,
on the walls are this light green.
I&#39;m told that at mental institutions
they use that on the walls.

(Laughter)

It&#39;s like a calming color,
it&#39;s not something
that really stimulates you.
What you can&#39;t see is the computer here,
you only see the screen,
but the main thing I worry
about in my computer is --
it doesn&#39;t have to be big
and powerful, although I like that --
it really has to be completely silent.
I know people who work for Google
and they have their own
small data center at home,
and I don&#39;t do that.
My office is the most
boring office you&#39;ll ever see.
And I sit there alone in the quiet.
If the cat comes up,
it sits in my lap.
And I want to hear the cat purring,
not the sound of the fans in the computer.

CA: So this is astonishing,
because working this way,
you&#39;re able to run this vast
technology empire --
it is an empire --
so that&#39;s an amazing testament
to the power of open source.
Tell us how you got
to understand open source
and how it lead
to the development of Linux.

LT: I mean, I still work alone.
Really -- I work alone in my house,
often in my bathrobe.
When a photographer shows up, I dress up,
so I have clothes on.

(Laughter)

And that&#39;s how I&#39;ve always worked.
I mean, this was how I started Linux, too.
I did not start Linux
as a collaborative project.
I started it as one
in a series of many projects
I had done at the time for myself,
partly because I needed the end result,
but even more because I just
enjoyed programming.
So it was about the end of the journey,
which, 25 years later,
we still have not reached.
But it was really about the fact
that I was looking for a project on my own
and there was no open source,
really, on my radar at all.
And what happened is ...
the project grows and becomes something
you want to show off to people.
Really, this is more of a, &quot;Wow,
look at what I did!&quot;
And trust me -- it was not
that great back then.
I made it publicly available,
and it wasn&#39;t even
open source at that point.
At that point it was source that was open,
but there was no intention
behind using the kind of open-source
methodology that we think of today
to improve it.
It was more like,
&quot;Look, I&#39;ve been working
on this for half a year,
I&#39;d love to have comments.&quot;
And other people approached me.
At the University of Helsinki,
I had a friend who was one
of the open source --
it was called mainly
&quot;free software&quot; back then --
and he actually introduced me
to the notion that, hey,
you can use these open-source
licenses that had been around.
And I thought about it for a while.
I was actually worried about the whole
commercial interests coming in.
I mean, that&#39;s one of the worries
I think most people who start out have,
is that they worry about somebody
taking advantage of their work, right?
And I decided, &quot;What the hell?&quot;
And --

CA: And then at some point,
someone contributed
some code that you thought,
&quot;Wow, that really is interesting,
I would not have thought of that.
This could actually improve this.&quot;

LT: It didn&#39;t even start
by people contributing code,
it was more that people
started contributing ideas.
And just the fact that somebody else
takes a look at your project --
and I&#39;m sure it&#39;s true
of other things, too,
but it&#39;s definitely true in code --
is that somebody else
takes an interest in your code,
looks at it enough to actually
give you feedback
and give you ideas.
That was a huge thing for me.
I was 21 at the time, so I was young,
but I had already programmed
for half my life, basically.
And every project before that
had been completely personal
and it was a revelation when people
just started commenting,
started giving feedback on your code.
And even before they started
giving code back,
that was, I think, one of the big
moments where I said,
&quot;I love other people!&quot;
Don&#39;t get me wrong --
I&#39;m actually not a people person.

(Laughter)

I don&#39;t really love other people --

(Laughter)

But I love computers,
I love interacting with other
people on email,
because it kind of gives you that buffer.
But I do love other people who comment
and get involved in my project.
And it made it so much more.

CA: So was there a moment
when you saw what was being built
and it suddenly started taking off,
and you thought, &quot;Wait a sec,
this actually could be something huge,
not just a personal project
that I&#39;m getting nice feedback on,
but a kind of explosive development
in the whole technology world&quot;?

LT: Not really.
I mean, the big point for me, really,
was not when it was becoming huge,
it was when it was becoming little.
The big point for me was not being alone
and having 10, maybe 100
people being involved --
that was a big point.
Then everything else was very gradual.
Going from 100 people to a million people
is not a big deal -- to me.
Well, I mean, maybe it is if you&#39;re --

(Laughter)

If you want to sell your result
then it&#39;s a huge deal --
don&#39;t get me wrong.
But if you&#39;re interested in the technology
and you&#39;re interested in the project,
the big part was getting the community.
Then the community grew gradually.
And there&#39;s actually not
a single point where I went like,
&quot;Wow, that just took off!&quot; because it --
I mean -- it took a long time, relatively.

CA: So all the technologists
that I talk to really credit you
with massively changing their work.
And it&#39;s not just Linux,
it&#39;s this thing called Git,
which is this management system
for software development.
Tell us briefly about that
and your role in that.

LT: So one of the issues we had,
and this took a while to start to appear,
is when you ...
When you grow from having 10 people
or 100 people working on a project
to having 10,000 people, which --
I mean, right now we&#39;re in the situation
where just on the kernel,
we have 1,000 people involved
in every single release
and that&#39;s every two months,
roughly two or three months.
Some of those people don&#39;t do a lot.
There&#39;s a lot of people
who make small, small changes.
But to maintain this,
the scale changes how
you have to maintain it.
And we went through a lot of pain.
And there are whole projects
that do only source-code maintenance.
CVS is the one that used to be
the most commonly used,
and I hated CVS with a passion
and refused to touch it
and tried something else
that was radical and interesting
and everybody else hated.

CA: (Laughs)

LT: And we were in this bad spot,
where we had thousands of people
who wanted to participate,
but in many ways,
I was the kind of break point,
where I could not scale to the point
where I could work
with thousands of people.
So Git is my second big project,
which was only created for me
to maintain my first big project.
And this is literally how I work.
I don&#39;t code for --
well, I do code for fun --
but I want to code
for something meaningful
so every single project I&#39;ve ever done
has been something I needed
and --

CA: So really, both Linux
and Git kind of arose
almost as an unintended consequence
of your desire not to have
to work with too many people.

LT: Absolutely. Yes.

(Laughter)


CA: That&#39;s amazing.

LT: Yeah.

(Applause)

And yet, you&#39;re the man
who&#39;s transformed technology
not just once but twice,
and we have to try
and understand why it is.
You&#39;ve given us some clues, but ...
Here&#39;s a picture of you as a kid,
with a Rubik&#39;s Cube.
You mentioned that you&#39;ve been
programming since you were like 10 or 11,
half your life.
Were you this sort of computer
genius, you know, übernerd,
were you the star at school
who could do everything?
What were you like as a kid?

LT: Yeah, I think I was
the prototypical nerd.
I mean, I was ...
I was not a people person back then.
That&#39;s my younger brother.
I was clearly more interested
in the Rubik&#39;s Cube
than my younger brother.

(Laughter)

My younger sister,
who&#39;s not in the picture,
when we had family meetings --
and it&#39;s not a huge family, but I have,
like, a couple of cousins --
she would prep me beforehand.
Like, before I stepped
into the room she would say,
&quot;OK. That&#39;s so-and-so ...&quot;
Because I was not --
I was a geek.
I was into computers,
I was into math,
I was into physics.
I was good at that.
I don&#39;t think I was
particularly exceptional.
Apparently, my sister said
that my biggest exceptional quality
was that I would not let go.

CA: OK, so let&#39;s go there,
because that&#39;s interesting.
You would not let go.
So that&#39;s not about being
a geek and being smart,
that&#39;s about being ... stubborn?

LT: That&#39;s about being stubborn.
That&#39;s about, like,
just starting something
and not saying, &quot;OK, I&#39;m done,
let&#39;s do something else --

Look: shiny!&quot;
And I notice that in many
other parts in my life, too.
I lived in Silicon Valley for seven years.
And I worked for the same
company, in Silicon Valley,
for the whole time.
That is unheard of.
That&#39;s not how Silicon Valley works.
The whole point of Silicon Valley
is that people jump between jobs
to kind of mix up the pot.
And that&#39;s not the kind of person I am.

CA: But during the actual
development of Linux itself,
that stubbornness sometimes brought
you in conflict with other people.
Talk about that a bit.
Was that essential to sort of maintain
the quality of what was being built?
How would you describe what happened?

LT: I don&#39;t know if it&#39;s essential.
Going back to the &quot;I&#39;m not
a people person,&quot; --
sometimes I&#39;m also ...
shall we say,
&quot;myopic&quot; when it comes
to other people&#39;s feelings,
and that sometimes makes you
say things that hurt other people.
And I&#39;m not proud of that.

(Applause)

But, at the same time, it&#39;s --
I get people who tell me
that I should be nice.
And then when I try to explain to them
that maybe you&#39;re nice,
maybe you should be more aggressive,
they see that as me being not nice.

(Laughter)

What I&#39;m trying to say
is we are different.
I&#39;m not a people person;
it&#39;s not something
I&#39;m particularly proud of,
but it&#39;s part of me.
And one of the things
I really like about open source
is it really allows different
people to work together.
We don&#39;t have to like each other --
and sometimes we really
don&#39;t like each other.
Really -- I mean, there are very,
very heated arguments.
But you can, actually,
you can find things that --
you don&#39;t even agree to disagree,
it&#39;s just that you&#39;re interested
in really different things.
And coming back to the point
where I said earlier
that I was afraid of commercial people
taking advantage of your work,
it turned out, and very
quickly turned out,
that those commercial people
were lovely, lovely people.
And they did all the things that I was not
at all interested in doing,
and they had completely different goals.
And they used open source in ways
that I just did not want to go.
But because it was open
source they could do it,
and it actually works
really beautifully together.
And I actually think
it works the same way.
You need to have the people-people,
the communicators,
the warm and friendly people
who like --

(Laughter)

really want to hug you
and get you into the community.
But that&#39;s not everybody.
And that&#39;s not me.
I care about the technology.
There are people who care about the UI.
I can&#39;t do UI to save my life.
I mean, if I was stranded on an island
and the only way to get off that island
was the make a pretty UI,
I&#39;d die there.

(Laughter)

So there&#39;s different kinds of people,
and I&#39;m not making excuses,
I&#39;m trying to explain.

CA: Now, when we talked last week,
you talked about some
other trait that you have,
which I found really interesting.
It&#39;s this idea called taste.
And I&#39;ve just got a couple of images here.
I think this is an example of not
particularly good taste in code,
and this one is better taste,
which one can immediately see.
What is the difference between these two?

LT: So this is --
How many people here actually have coded?

CA: Oh my goodness.

LT: So I guarantee you,
everybody who raised their hand,
they have done what&#39;s called
a singly-linked list.
And it&#39;s taught --
This, the first not very
good taste approach,
is basically how it&#39;s taught to be done
when you start out coding.
And you don&#39;t have to understand the code.
The most interesting part to me
is the last if statement.
Because what happens
in a singly-linked list --
this is trying to remove
an existing entry from a list --
and there&#39;s a difference
between if it&#39;s the first entry
or whether it&#39;s an entry in the middle.
Because if it&#39;s the first entry,
you have to change
the pointer to the first entry.
If it&#39;s in the middle,
you have to change the pointer
of a previous entry.
So they&#39;re two completely different cases.

CA: And that&#39;s better.

LT: And this is better.
It does not have the if statement.
And it doesn&#39;t really matter --
I don&#39;t want you understand
why it doesn&#39;t have the if statement,
but I want you to understand
that sometimes you can see
a problem in a different way
and rewrite it so that
a special case goes away
and becomes the normal case.
And that&#39;s good code.
But this is simple code.
This is CS 101.
This is not important --
although, details are important.
To me, the sign of people
I really want to work with
is that they have good taste,
which is how ...
I sent you this stupid example
that is not relevant
because it&#39;s too small.
Good taste is much bigger than this.
Good taste is about really
seeing the big patterns
and kind of instinctively knowing
what&#39;s the right way to do things.

CA: OK, so we&#39;re putting
the pieces together here now.
You have taste,
in a way that&#39;s meaningful
to software people.
You&#39;re --

(Laughter)


LT: I think it was meaningful
to some people here.

CA: You&#39;re a very smart computer coder,
and you&#39;re hellish stubborn.
But there must be something else.
I mean, you&#39;ve changed the future.
You must have the ability
of these grand visions of the future.
You&#39;re a visionary, right?

LT: I&#39;ve actually felt slightly
uncomfortable at TED
for the last two days,
because there&#39;s a lot
of vision going on, right?
And I am not a visionary.
I do not have a five-year plan.
I&#39;m an engineer.
And I think it&#39;s really --
I mean -- I&#39;m perfectly
happy with all the people
who are walking around
and just staring at the clouds
and looking at the stars
and saying, &quot;I want to go there.&quot;
But I&#39;m looking at the ground,
and I want to fix the pothole
that&#39;s right in front of me
before I fall in.
This is the kind of person I am.
(Cheers)

(Applause)


CA: So you spoke to me last week
about these two guys.
Who are they and how
do you relate to them?

LT: Well, so this is kind
of cliché in technology,
the whole Tesla versus Edison,
where Tesla is seen as the visionary
scientist and crazy idea man.
And people love Tesla.
I mean, there are people who name
their companies after him.

(Laughter)

The other person there is Edison,
who is actually often vilified
for being kind of pedestrian
and is --
I mean, his most famous quote is,
&quot;Genius is one percent inspiration
and 99 percent perspiration.&quot;
And I&#39;m in the Edison camp,
even if people don&#39;t always like him.
Because if you actually compare the two,
Tesla has kind of this mind
grab these days,
but who actually changed the world?
Edison may not have been a nice person,
he did a lot of things --
he was maybe not so intellectual,
not so visionary.
But I think I&#39;m more
of an Edison than a Tesla.

CA: So our theme at TED
this week is dreams --
big, bold, audacious dreams.
You&#39;re really the antidote to that.

LT: I&#39;m trying to dial it down a bit, yes.

CA: That&#39;s good.

(Laughter)

We embrace you, we embrace you.
Companies like Google and many
others have made, arguably,
like, billions of dollars
out of your software.
Does that piss you off?

LT: No.
No, it doesn&#39;t piss me off
for several reasons.
And one of them is, I&#39;m doing fine.
I&#39;m really doing fine.
But the other reason is --
I mean, without doing the whole
open source and really letting go thing,
Linux would never have been what it is.
And it&#39;s brought experiences
I don&#39;t really enjoy, public talking,
but at the same time,
this is an experience.
Trust me.
So there&#39;s a lot of things going on
that make me a very happy man
and thinking I did the right choices.

CA: Is the open source idea --
this is, I think we&#39;ll end here --
is the open source idea
fully realized now in the world,
or is there more that it could go,
are there more things that it could do?

LT: So, I&#39;m of two minds there.
I think one reason open source
works so well in code
is that at the end of the day,
code tends to be somewhat black and white.
There&#39;s often a fairly good way to decide,
this is done correctly
and this is not done well.
Code either works or it doesn&#39;t,
which means that there&#39;s less
room for arguments.
And we have arguments despite this, right?
In many other areas --
I mean, people have talked about
open politics and things like that --
and it&#39;s really hard sometimes to say
that, yes, you can apply the same
principles in some other areas
just because the black and white
turns into not just gray,
but different colors.
So, obviously open source in science
is making a comeback.
Science was there first.
But then science ended up
being pretty closed,
with very expensive journals
and some of that going on.
And open source is making
a comeback in science,
with things like arXiv and open journals.
Wikipedia changed the world, too.
So there are other examples,
I&#39;m sure there are more to come.

CA: But you&#39;re not a visionary,
and so it&#39;s not up to you to name them.

LT: No.

(Laughter)

It&#39;s up to you guys to make them, right?

CA: Exactly.
Linus Torvalds,
thank you for Linux,
thank you for the Internet,
thank you for all those Android phones.
Thank you for coming here to TED
and revealing so much of yourself.

LT: Thank you.

(Applause)

