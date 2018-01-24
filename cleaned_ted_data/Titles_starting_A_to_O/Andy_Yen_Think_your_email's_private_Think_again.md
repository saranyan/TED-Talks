
Twenty-five years ago, scientists at CERN
created the World Wide Web.
Since then, the Internet has transformed 
the way we communicate,
the way we do business,
and even the way we live.
In many ways,
the ideas that gave birth to Google,
Facebook, Twitter, and so many others,
have now really transformed our lives,
and this has brought us many real benefits
such as a more connected society.
However, there are also
some downsides to this.
Today, the average person
has an astounding amount
of personal information online,
and we add to this online information
every single time we post on Facebook,
each time we search on Google,
and each time we send an email.
Now, many of us probably think,
well, one email,
there&#39;s nothing in there, right?
But if you consider
a year&#39;s worth of emails,
or maybe even a lifetime of email,
collectively, this tells a lot.
It tells where we have been,
who we have met,
and in many ways,
even what we&#39;re thinking about.
And the more scary part about this is
our data now lasts forever,
so your data can and will outlive you.
What has happened is that we&#39;ve largely
lost control over our data
and also our privacy.
So this year, as the web turns 25,
it&#39;s very important for us
to take a moment
and think about the implications of this.
We have to really think.
We&#39;ve lost privacy, yes,
but actually what we&#39;ve also lost
is the idea of privacy itself.
If you think about it,
most of us here today probably remember 
what life was like before the Internet,
but today, there&#39;s a new generation
that is being taught from a very young age
to share everything online,
and this is a generation that is not 
going to remember when data was private.
So we keep going down this road,
20 years from now,
the word &#39;privacy&#39; is going to have
a completely different meaning
from what it means to you and I.
So, it&#39;s time for us 
to take a moment and think,
is there anything we can do about this?
And I believe there is.
Let&#39;s take a look at one of the most
widely used forms of communication

in the world today: email.
Before the invention of email,
we largely communicated using letters,
and the process was quite simple.
You would first start by writing
your message on a piece of paper,
then you would place it
into a sealed envelope,
and from there,
you would go ahead and send it
after you put a stamp and address on it.
Unfortunately, today,
when we actually send an email,
we&#39;re not sending a letter.
What you are sending, in many ways,
is actually a postcard,
and it&#39;s a postcard in the sense
that everybody that sees it
from the time it leaves your computer
to when it gets to the recipient
can actually read the entire contents.
So, the solution to this
has been known for some time,
and there&#39;s many attempts to do it.
The most basic solution
is to use encryption,
and the idea is quite simple.
First, you encrypt the connection
between your computer
and the email server.
Then, you also encrypt the data
as it sits on the server itself.
But there&#39;s a problem with this,
and that is, the email servers
also hold the encryption keys,
so now you have a really big lock
with a key placed right next to it.
But not only that, any government
could lawfully ask for
and get the key to your data,
and this is all without you
being aware of it.
So the way we fix this problem

is actually relatively easy, in principle:
You give everybody their own keys,
and then you make sure the server
doesn&#39;t actually have the keys.
This seems like common sense, right?
So the question that comes up is,
why hasn&#39;t this been done yet?
Well, if we really think about it,
we see that the business model
of the Internet today
really isn&#39;t compatible with privacy.
Just take a look at some
of the biggest names on the web,
and you see that advertising
plays a huge role.
In fact, this year alone,
advertising is 137 billion dollars,
and to optimize the ads
that are shown to us,
companies have to know
everything about us.
They need to know where we live,
how old we are, what we like,
what we don&#39;t like,
and anything else
they can get their hands on.
And if you think about it,
the best way to get this information
is really just to invade our privacy.
So these companies
aren&#39;t going to give us our privacy.
If we want to have privacy online,
what we have to do is
we&#39;ve got to go out and get it ourselves.
For many years, when it came to email,
the only solution
was something known as PGP,
which was quite complicated
and only accessible to the tech-savvy.
Here&#39;s a diagram that basically shows
the process for encrypting
and decrypting messages.
So needless to say,
this is not a solution for everybody,
and this actually is part of the problem,
because if you think about communication,
by definition, it involves
having someone to communicate with.
So while PGP does a great job
of what it&#39;s designed to do,
for the people out there
who can&#39;t understand how to use it,
the option to communicate privately
simply does not exist.
And this is a problem
that we need to solve.
So if we want to have privacy online,
the only way we can succeed
is if we get the whole world on board,
and this is only possible
if we bring down the barrier to entry.
I think this is actually the key challenge
that lies in the tech community.
What we really have to do
is work and make privacy more accessible.
So last summer, when
the Edward Snowden story came out,
several colleagues and I decided to see
if we could make this happen.
At that time, we were working at the
European Organization for Nuclear Research
at the world&#39;s largest particle collider,
which collides protons, by the way.
We were all scientists,
so we used our scientific creativity
and came up with a very

creative name for our project:
ProtonMail.

(Laughter)

Many startups these days
actually begin in people&#39;s garages
or people&#39;s basements.
We were a bit different.
We started out at the CERN cafeteria,
which actually is great, because look,
you have all the food
and water you could ever want.
But even better than this
is that every day
between 12 p.m. and 2 p.m.,
free of charge,
the CERN cafeteria comes with
several thousand scientists and engineers,
and these guys basically know
the answers to everything.
So it was in this environment
that we began working.
What we actually want to do
is we want to take your email
and turn it into something
that looks more like this,
but more importantly,
we want to do it in a way
that you can&#39;t even tell
that it&#39;s happened.
So to do this, we actually need
a combination of technology
and also design.
So how do we go about
doing something like this?
Well, it&#39;s probably a good idea
not to put the keys on the server.
So what we do is we generate
encryption keys on your computer,
and we don&#39;t generate a single key,
but actually a pair of keys,
so there&#39;s an RSA private key
and an RSA public key,
and these keys
are mathematically connected.
So let&#39;s have a look
and see how this works
when multiple people communicate.
So here we have Bob and Alice,
who want to communicate privately.
So the key challenge
is to take Bob&#39;s message
and to get it to Alice in such a way
that the server cannot read that message.
So what we have to do
is we have to encrypt it
before it even leaves Bob&#39;s computer,
and one of the tricks is, we encrypt it
using the public key from Alice.
Now this encrypted data is sent
through the server to Alice,
and because the message was encrypted
using Alice&#39;s public key,
the only key that can now decrypt it
is a private key that belongs to Alice,
and it turns out Alice is the only person
that actually has this key.
So we&#39;ve now accomplished the objective,
which is to get the message
from Bob to Alice
without the server being able
to read what&#39;s going on.
Actually, what I&#39;ve shown here
is a highly simplified picture.
The reality is much more complex
and it requires a lot of software
that looks a bit like this.
And that&#39;s actually

the key design challenge:
How do we take all this complexity,
all this software,
and implement it in a way
that the user cannot see it.
I think with ProtonMail,
we have gotten pretty close to doing this.
So let&#39;s see how it works in practice.
Here, we&#39;ve got Bob and Alice again,
who also want to communicate securely.
They simply create accounts on ProtonMail,
which is quite simple
and takes a few moments,
and all the key encryption and generation
is happening automatically
in the background
as Bob is creating his account.
Once his account is created,
he just clicks &quot;compose,&quot;
and now he can write his email
like he does today.
So he fills in his information,
and then after that, 
all he has to do is click &quot;send,&quot;
and just like that,
without understanding cryptography,
and without doing anything different
from how he writes email today,
Bob has just sent an encrypted message.
What we have here
is really just the first step,
but it shows that
with improving technology,
privacy doesn&#39;t have to be difficult,
it doesn&#39;t have to be disruptive.
If we change the goal from maximizing 
ad revenue to protecting data,
we can actually make it accessible.
Now, I know a question
on everybody&#39;s minds is,
okay, protecting privacy,
this is a great goal,
but can you actually do this
without the tons of money
that advertisements give you?
And I think the answer is actually yes,
because today, we&#39;ve reached a point
where people around the world really
understand how important privacy is,
and when you have that,
anything is possible.
Earlier this year,
ProtonMail actually had so many users 
that we ran out of resources,
and when this happened,
our community of users got together
and donated half a million dollars.
So this is just an example
of what can happen
when you bring the community together
towards a common goal.
We can also leverage the world.
Right now,
we have a quarter of a million people
that have signed up for ProtonMail,
and these people come from everywhere,
and this really shows that privacy
is not just an American
or a European issue,
it&#39;s a global issue
that impacts all of us.
It&#39;s something that we really
have to pay attention to going forward.
So what do we have to do
to solve this problem?
Well, first of all,
we need to support a different
business model for the Internet,
one that does not rely
entirely on advertisements
for revenue and for growth.
We actually need to build a new Internet
where our privacy and our ability 
to control our data is first and foremost.
But even more importantly,
we have to build an Internet 
where privacy is no longer just an option
but is also the default.
We have done the first step
with ProtonMail,
but this is really just the first step
in a very, very long journey.
The good news I can share
with you guys today,
the exciting news,
is that we&#39;re not traveling alone.
The movement to protect people&#39;s privacy
and freedom online
is really gaining momentum,
and today, there are dozens of projects
from all around the world
who are working together
to improve our privacy.
These projects protect things
from our chat to voice communications,
also our file storage, our online search,
our online browsing,
and many other things.
And these projects are not backed
by billions of dollars in advertising,
but they&#39;ve found support
really from the people,
from private individuals like you and I
from all over the world.
This really matters, because ultimately,
privacy depends on each
and every one of us,
and we have to protect it now
because our online data
is more than just a collection
of ones and zeros.
It&#39;s actually a lot more than that.
It&#39;s our lives, our personal stories,
our friends, our families,
and in many ways,
also our hopes and our aspirations.
We need to spend time now
to really protect our right
to share this only with people
that we want to share this with,
because without this,
we simply can&#39;t have a free society.
So now&#39;s the time for us
to collectively stand up and say,
yes, we do want to live
in a world with online privacy,
and yes, we can work together
to turn this vision into a reality.
Thank you.

(Applause)

