
If you remember that first decade of the web,
it was really a static place.
You could go online, you could look at pages,
and they were put up either by organizations
who had teams to do it
or by individuals who were really tech-savvy
for the time.
And with the rise of social media
and social networks in the early 2000s,
the web was completely changed
to a place where now the vast majority of content
we interact with is put up by average users,
either in YouTube videos or blog posts
or product reviews or social media postings.
And it&#39;s also become a much more interactive place,
where people are interacting with others,
they&#39;re commenting, they&#39;re sharing,
they&#39;re not just reading.
So Facebook is not the only place you can do this,
but it&#39;s the biggest,
and it serves to illustrate the numbers.
Facebook has 1.2 billion users per month.
So half the Earth&#39;s Internet population
is using Facebook.
They are a site, along with others,
that has allowed people to create an online persona
with very little technical skill,
and people responded by putting huge amounts
of personal data online.
So the result is that we have behavioral,
preference, demographic data
for hundreds of millions of people,
which is unprecedented in history.
And as a computer scientist, 
what this means is that
I&#39;ve been able to build models
that can predict all sorts of hidden attributes
for all of you that you don&#39;t even know
you&#39;re sharing information about.
As scientists, we use that to help
the way people interact online,
but there&#39;s less altruistic applications,
and there&#39;s a problem in that users don&#39;t really
understand these techniques and how they work,
and even if they did, they don&#39;t
have a lot of control over it.
So what I want to talk to you about today
is some of these things that we&#39;re able to do,
and then give us some ideas
of how we might go forward
to move some control back into the hands of users.
So this is Target, the company.
I didn&#39;t just put that logo
on this poor, pregnant woman&#39;s belly.
You may have seen this anecdote that was printed
in Forbes magazine where Target
sent a flyer to this 15-year-old girl
with advertisements and coupons
for baby bottles and diapers and cribs
two weeks before she told her parents
that she was pregnant.
Yeah, the dad was really upset.
He said, &quot;How did Target figure out
that this high school girl was pregnant
before she told her parents?&quot;
It turns out that they have the purchase history
for hundreds of thousands of customers
and they compute what they 
call a pregnancy score,
which is not just whether or 
not a woman&#39;s pregnant,
but what her due date is.
And they compute that
not by looking at the obvious things,
like, she&#39;s buying a crib or baby clothes,
but things like, she bought more vitamins
than she normally had,
or she bought a handbag
that&#39;s big enough to hold diapers.
And by themselves, those purchases don&#39;t seem
like they might reveal a lot,
but it&#39;s a pattern of behavior that,
when you take it in the context 
of thousands of other people,
starts to actually reveal some insights.
So that&#39;s the kind of thing that we do
when we&#39;re predicting stuff
about you on social media.
We&#39;re looking for little
patterns of behavior that,
when you detect them among millions of people,
lets us find out all kinds of things.
So in my lab and with colleagues,
we&#39;ve developed mechanisms where we can
quite accurately predict things
like your political preference,
your personality score, gender, sexual orientation,
religion, age, intelligence,
along with things like
how much you trust the people you know
and how strong those relationships are.
We can do all of this really well.
And again, it doesn&#39;t come from what you might
think of as obvious information.
So my favorite example is from this study
that was published this year
in the Proceedings of the National Academies.
If you Google this, you&#39;ll find it.
It&#39;s four pages, easy to read.
And they looked at just people&#39;s Facebook likes,
so just the things you like on Facebook,
and used that to predict all these attributes,
along with some other ones.
And in their paper they listed the five likes
that were most indicative of high intelligence.
And among those was liking a page
for curly fries. 
(Laughter)

Curly fries are delicious,
but liking them does not necessarily mean
that you&#39;re smarter than the average person.
So how is it that one of the strongest indicators
of your intelligence
is liking this page
when the content is totally irrelevant
to the attribute that&#39;s being predicted?
And it turns out that we have to look at
a whole bunch of underlying theories
to see why we&#39;re able to do this.
One of them is a sociological
theory called homophily,
which basically says people are
friends with people like them.
So if you&#39;re smart, you tend to
be friends with smart people,
and if you&#39;re young, you tend
to be friends with young people,
and this is well established
for hundreds of years.
We also know a lot
about how information spreads through networks.
It turns out things like viral videos
or Facebook likes or other information
spreads in exactly the same way
that diseases spread through social networks.
So this is something we&#39;ve studied for a long time.
We have good models of it.
And so you can put those things together
and start seeing why things like this happen.
So if I were to give you a hypothesis,
it would be that a smart guy started this page,
or maybe one of the first people who liked it
would have scored high on that test.
And they liked it, and their friends saw it,
and by homophily, we know that
he probably had smart friends,
and so it spread to them, 
and some of them liked it,
and they had smart friends,
and so it spread to them,
and so it propagated through the network
to a host of smart people,
so that by the end, the action
of liking the curly fries page
is indicative of high intelligence,
not because of the content,
but because the actual action of liking
reflects back the common attributes
of other people who have done it.
So this is pretty complicated stuff, right?
It&#39;s a hard thing to sit down and explain
to an average user, and even if you do,
what can the average user do about it?
How do you know that 
you&#39;ve liked something
that indicates a trait for you
that&#39;s totally irrelevant to the
content of what you&#39;ve liked?
There&#39;s a lot of power that users don&#39;t have
to control how this data is used.
And I see that as a real 
problem going forward.
So I think there&#39;s a couple paths
that we want to look at
if we want to give users some control
over how this data is used,
because it&#39;s not always going to be used
for their benefit.
An example I often give is that,
if I ever get bored being a professor,
I&#39;m going to go start a company
that predicts all of these attributes
and things like how well you work in teams
and if you&#39;re a drug user, if you&#39;re an alcoholic.
We know how to predict all that.
And I&#39;m going to sell reports
to H.R. companies and big businesses
that want to hire you.
We totally can do that now.
I could start that business tomorrow,
and you would have
absolutely no control
over me using your data like that.
That seems to me to be a problem.
So one of the paths we can go down
is the policy and law path.
And in some respects, I think
that that would be most effective,
but the problem is we&#39;d
actually have to do it.
Observing our political process in action
makes me think it&#39;s highly unlikely
that we&#39;re going to get a bunch of representatives
to sit down, learn about this,
and then enact sweeping changes
to intellectual property law in the U.S.
so users control their data.
We could go the policy route,
where social media companies say,
you know what? You own your data.
You have total control over how it&#39;s used.
The problem is that the revenue models
for most social media companies
rely on sharing or exploiting 
users&#39; data in some way.
It&#39;s sometimes said of Facebook that the users
aren&#39;t the customer, they&#39;re the product.
And so how do you get a company
to cede control of their main asset
back to the users?
It&#39;s possible, but I don&#39;t think it&#39;s something
that we&#39;re going to see change quickly.
So I think the other path
that we can go down that&#39;s
going to be more effective
is one of more science.
It&#39;s doing science that allowed us to develop
all these mechanisms for computing
this personal data in the first place.
And it&#39;s actually very similar research
that we&#39;d have to do
if we want to develop mechanisms
that can say to a user,
&quot;Here&#39;s the risk of that action you just took.&quot;
By liking that Facebook page,
or by sharing this piece of personal information,
you&#39;ve now improved my ability
to predict whether or not you&#39;re using drugs
or whether or not you get
along well in the workplace.
And that, I think, can affect whether or not
people want to share something,
keep it private, or just keep it offline altogether.
We can also look at things like
allowing people to encrypt data that they upload,
so it&#39;s kind of invisible and worthless
to sites like Facebook
or third party services that access it,
but that select users who the person who posted it
want to see it have access to see it.
This is all super exciting research
from an intellectual perspective,
and so scientists are going to be willing to do it.
So that gives us an advantage over the law side.
One of the problems that people bring up
when I talk about this is, they say,
you know, if people start
keeping all this data private,
all those methods that you&#39;ve been developing
to predict their traits are going to fail.
And I say, absolutely, and for me, that&#39;s success,
because as a scientist,
my goal is not to infer information about users,
it&#39;s to improve the way people interact online.
And sometimes that involves
inferring things about them,
but if users don&#39;t want me to use that data,
I think they should have the right to do that.
I want users to be informed and consenting
users of the tools that we develop.
And so I think encouraging this kind of science
and supporting researchers
who want to cede some of that control back to users
and away from the social media companies
means that going forward, as these tools evolve
and advance,
means that we&#39;re going to have an educated
and empowered user base,
and I think all of us can agree
that that&#39;s a pretty ideal way to go forward.
Thank you.

(Applause)

