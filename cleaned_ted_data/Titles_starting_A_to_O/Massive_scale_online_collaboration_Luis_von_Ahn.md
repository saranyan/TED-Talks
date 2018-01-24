
How many of you had to fill out a web form
where you&#39;ve been asked to read
a distorted sequence
of characters like this?
How many of you found it really annoying?

(Laughter)

OK, outstanding. So I invented that.

(Laughter)

Or I was one of the people who did it.
That thing is called a CAPTCHA.
And it is there to make sure
you, the entity filling out the form,
are a human and not a computer program
that was written to submit
the form millions of times.
The reason it works is because humans,
at least non-visually-impaired humans,
have no trouble reading
these distorted characters,
whereas programs can&#39;t do it as well yet.
In the case of Ticketmaster,
the reason you have
to type these characters
is to prevent scalpers
from writing a program
that can buy millions
of tickets, two at a time.
CAPTCHAs are used all over the Internet.
And since they&#39;re used so often,
a lot of times the sequence
of random characters shown to the user
is not so fortunate.
So this is an example
from the Yahoo registration page.
The random characters
that happened to be shown to the user
were W, A, I, T,
which, of course, spell a word.
But the best part is the message
that the Yahoo help desk
got about 20 minutes later.
[Help! I&#39;ve been waiting
for over 20 minutes and nothing happens.]

(Laughter)

This person thought they needed to wait.
This, of course,
is not as bad as this poor person.

(Laughter)

CAPTCHA Project is something that we did
at Carnegie Melllon over 10 years ago,
and it&#39;s been used everywhere.
Let me now tell you about a project
that we did a few years later,
which is sort of
the next evolution of CAPTCHA.
This is a project that we call reCAPTCHA,
which is something that we started
here at Carnegie Mellon,
then we turned it into a start-up company.
And then about a year and a half ago,
Google actually acquired this company.
Let me tell you what this project started.
This project started

from the following realization:
It turns out that approximately
200 million CAPTCHAs
are typed everyday
by people around the world.
When I first heard this,
I was quite proud of myself.
I thought, look at the impact
my research has had.
But then I started feeling bad.

Here&#39;s the thing:
each time you type a CAPTCHA,
essentially, you waste
10 seconds of your time.
And if you multiply that by 200 million,
you get that humanity is wasting
about 500,000 hours every day
typing these annoying CAPTCHAs.

(Laughter)

So then I started feeling bad.

(Laughter)

And then I started thinking, of course,
we can&#39;t just get rid of CAPTCHAs,
because the security of the web
depends on them.
But then I started thinking,
can we use this effort
for something that is good for humanity?
So see, here&#39;s the thing.
While you&#39;re typing a CAPTCHA,
during those 10 seconds,
your brain is doing something amazing.
Your brain is doing something
that computers cannot yet do.
So can we get you to do useful work
for those 10 seconds?
Is there some humongous problem
that we cannot yet get computers to solve,
yet we can split
into tiny 10-second chunks
such that each time
somebody solves a CAPTCHA,
they solve a little bit of this problem?
And the answer to that is &quot;yes,&quot;
and this is what we&#39;re doing now.
Nowadays, while you&#39;re typing a CAPTCHA,
not only are you authenticating
yourself as a human,
but in addition you&#39;re helping us
to digitize books.
Let me explain how this works.
There&#39;s a lot of projects
trying to digitize books.
Google has one.
The Internet Archive has one.
Amazon, with the Kindle,
is trying to digitize books.
Basically, the way this works
is you start with an old book.
You&#39;ve seen those things, right?
Like a book?

(Laughter)

So you start with a book
and then you scan it.
Now, scanning a book
is like taking a digital
photograph of every page.
It gives you an image for every page.
This is an image with text
for every page of the book.
The next step in the process
is that the computer needs to be able
to decipher the words in this image.
That&#39;s using a technology called OCR,
for optical character recognition,
which takes a picture of text
and tries to figure out
what text is in there.
Now, the problem
is that OCR is not perfect.
Especially for older books
where the ink has faded
and the pages have turned yellow,
OCR cannot recognize a lot of the words.
For things that were written
more than 50 years ago,
the computer cannot recognize
about 30 percent of the words.
So now we&#39;re taking all of the words
that the computer cannot recognize
and we&#39;re getting people
to read them for us
while they&#39;re typing
a CAPTCHA on the Internet.
So the next time you type a CAPTCHA,
these words that you&#39;re typing
are actually words from books
that are being digitized
that the computer could not recognize.
The reason we have
two words nowadays instead of one
is because one of the words
is a word that the system
just got out of a book,
it didn&#39;t know what it was
and it&#39;s going to present it to you.
But since it doesn&#39;t know the answer,
it cannot grade it.
So we give you another word,
for which the system does know the answer.
We don&#39;t tell you which one&#39;s which
and we say, please type both.
And if you type the correct word
for the one for which
the system knows the answer,
it assumes you are human
and it also gets some confidence
that you typed the other word correctly.
And if we repeat this process
to 10 different people
and they agree on what the new word is,
then we get one more word
digitized accurately.
So this is how the system works.
And since we released it
about three or four years ago,
a lot of websites have started
switching from the old CAPTCHA,
where people wasted their time,
to the new CAPTCHA where people
are helping to digitize books.
So every time you buy
tickets on Ticketmaster,
you help to digitize a book.

Facebook: Every time
you add a friend or poke somebody,
you help to digitize a book.
Twitter and about 350,000 other sites
are all using reCAPTCHA.
And the number of sites
that are using reCAPTCHA is so high
that the number of words
we&#39;re digitizing per day is really large.
It&#39;s about 100 million a day,
which is the equivalent of about
two and a half million books a year.
And this is all being done
one word at a time
by just people typing
CAPTCHAs on the Internet.

(Applause)

Now, of course,
since we&#39;re doing so many words per day,
funny things can happen.
This is especially true
because now we&#39;re giving people
two randomly chosen English words
next to each other.
So funny things can happen.
For example, we presented this word.
It&#39;s the word &quot;Christians&quot;;
there&#39;s nothing wrong with it.
But if you present it along
with another randomly chosen word,
bad things can happen.
So we get this.
[bad Christians]
But it&#39;s even worse, because
the website where we showed this
actually happened to be called
The Embassy of the Kingdom of God.

(Laughter)

Oops.

(Laughter)

Here&#39;s another really bad one.
JohnEdwards.com
[Damn liberal]

(Laughter)

So we keep on insulting people
left and right everyday.
Of course, we&#39;re not
just insulting people.
Here&#39;s the thing. Since we&#39;re presenting
two randomly chosen words,
interesting things can happen.
So this actually has given rise
to a really big Internet meme
that tens of thousands of people
have participated in,
which is called CAPTCHA art.
I&#39;m sure some of you have heard about it.
Here&#39;s how it works.
Imagine you&#39;re using the Internet
and you see a CAPTCHA
that you think is somewhat peculiar,
like this CAPTCHA.
[invisible toaster]
What you&#39;re supposed to do
is you take a screenshot of it.
Then of course, you fill out the CAPTCHA
because you help us digitize a book.
But first you take a screenshot
and then you draw something
that is related to it.

(Laughter)

That&#39;s how it works.

(Laughter)

There are tens of thousands of these.
Some of them are very cute.
[clenched it]

(Laughter)

Some of them are funnier.
[stoned Founders]

(Laughter)

And some of them,
like paleontological shvisle ...

(Laughter)

they contain Snoop Dogg.

(Laughter)

OK, so this is my favorite
number of reCAPTCHA.
So this is the favorite thing
that I like about this whole project.
This is the number of distinct people
that have helped us digitize at least

one word out of a book through reCAPTCHA:
750 million, a little over 10 percent
of the world&#39;s population,
has helped us digitize human knowledge.
And it is numbers like these
that motivate my research agenda.
So the question that motivates

my research is the following:
If you look at humanity&#39;s
large-scale achievements,
these really big things
that humanity has gotten together
and done historically --
like, for example,
building the pyramids of Egypt
or the Panama Canal
or putting a man on the Moon --
there is a curious fact about them,
and it is that they were all done
with about the same number of people.
It&#39;s weird; they were all done
with about 100,000 people.
And the reason for that is because,
before the Internet,
coordinating more than 100,000 people,
let alone paying them,
was essentially impossible.
But now with the Internet,
I&#39;ve just shown you a project
where we&#39;ve gotten 750 million people
to help us digitize human knowledge.
So the question
that motivates my research is,
if we can put a man
on the Moon with 100,000,
what can we do with 100 million?
So based on this question,
we&#39;ve had a lot of different projects
that we&#39;ve been working on.
Let me tell you about one
that I&#39;m most excited about.
This is something that we&#39;ve been
semiquietly working on
for the last year and a half or so.
It hasn&#39;t yet been launched.
It&#39;s called Duolingo.
Since it hasn&#39;t been launched, shhh!

(Laughter)

Yeah, I can trust you&#39;ll do that.
So this is the project.
Here&#39;s how it started.
It started with me posing a question
to my graduate student, Severin Hacker.
OK, that&#39;s Severin Hacker.
So I posed the question
to my graduate student.
By the way, you did hear me correctly;
his last name is Hacker.

(Laughter)


So I posed this question to him:
How can we get 100 million people
translating the web
into every major language for free?
There&#39;s a lot of things
to say about this question.
First of all, translating the web.
Right now, the web
is partitioned into multiple languages.
A large fraction of it is in English.
If you don&#39;t know English,
you can&#39;t access it.
But there&#39;s large fractions
in other different languages,
and if you don&#39;t know them,
you can&#39;t access it.
So I would like to translate
all of the web,
or at least most of it,
into every major language.
That&#39;s what I would like to do.
Now, some of you may say,
why can&#39;t we use computers to translate?
Machine translation
is starting to translate
some sentences here and there.
Why can&#39;t we use it to translate the web?
The problem with that
is it&#39;s not yet good enough
and it probably won&#39;t be
for the next 15 to 20 years.
It makes a lot of mistakes.
Even when it doesn&#39;t,
since it makes so many mistakes,
you don&#39;t know whether to trust it or not.
So let me show you an example
of something that was
translated with a machine.
Actually, it was a forum post.
It was somebody who was trying
to ask a question about JavaScript.
It was translated
from Japanese into English.
So I&#39;ll just let you read.
This person starts apologizing
for the fact that
it&#39;s translated with a computer.
So the next sentence is going to be
the preamble to the question.
So he&#39;s just explaining something.
Remember, it&#39;s a question
about JavaScript.
[At often, the goat-time
install a error is vomit.]

(Laughter)

Then comes the first part of the question.
[How many times like the wind,
a pole, and the dragon?]

(Laughter)

Then comes my favorite part
of the question.
[This insult to father&#39;s stones?]

(Laughter)

And then comes the ending,
which is my favorite part
of the whole thing.
[Please apologize for your stupidity.
There are a many thank you.]

(Laughter)

OK, so computer translation,
not yet good enough.
So back to the question.
So we need people
to translate the whole web.
So now the next question you may have is,
well, why can&#39;t we just
pay people to do this?
We could pay professional translators
to translate the whole web.
We could do that.
Unfortunately, it would be
extremely expensive.
For example, translating a tiny fraction
of the whole web, Wikipedia,
into one other language, Spanish.
OK? Wikipedia exists in Spanish,
but it&#39;s very small
compared to the size of English.
It&#39;s about 20 percent
of the size of English.
If we wanted to translate
the other 80 percent into Spanish,
it would cost at least
50 million dollars --
and this is even at the most exploited,
outsourcing country out there.
So it would be very expensive.
So what we want to do is,
we want to get 100 million people
translating the web
into every major language for free.
If this is what you want to do,
you quickly realize
you&#39;re going to run
into two big hurdles, two big obstacles.
The first one is a lack of bilinguals.
So I don&#39;t even know
if there exists 100 million people
out there using the web
who are bilingual enough
to help us translate.
That&#39;s a big problem.
The other problem you&#39;re going to run into
is a lack of motivation.
How are we going to motivate people
to actually translate the web for free?
Normally, you have to pay
people to do this.
So how are we going to motivate them
to do it for free?
When we were starting to think about this,
we were blocked by these two things.
But then we realized, there&#39;s a way
to solve both these problems
with the same solution.
To kill two birds with one stone.
And that is to transform
language translation
into something that millions
of people want to do
and that also helps
with the problem of lack of bilinguals,
and that is language education.
So it turns out that today,
there are over 1.2 billion people
learning a foreign language.
People really want
to learn a foreign language.
And it&#39;s not just because
they&#39;re being forced to do so in school.
In the US alone,
there are over five million people
who have paid over $500
for software to learn a new language.
So people really want
to learn a new language.
So what we&#39;ve been working on
for the last year and a half
is a new website --
it&#39;s called Duolingo --
where the basic idea is
people learn a new language for free
while simultaneously translating the web.
And so basically,
they&#39;re learning by doing.
So the way this works
is whenever you&#39;re a just a beginner,
we give you very simple sentences.
There&#39;s a lot of very simple
sentences on the web.
We give you very simple sentences
along with what each word means.
And as you translate them
and as you see how other people
translate them,
you start learning the language.
And as you get more advanced,
we give you more complex
sentences to translate.
But at all times,
you&#39;re learning by doing.
Now, the crazy thing about this method
is that it actually really works.
People are really learning a language.
We&#39;re mostly done building it
and now we&#39;re testing it.
People really can
learn a language with it.
And they learn it about as well
as the leading language learning software.
So people really do learn a language.
And not only do they learn it as well,
but actually it&#39;s more interesting.
Because with Duolingo,
people are learning with real content.
As opposed to learning
with made-up sentences,
people are learning with real content,
which is inherently interesting.
So people really do learn a language.
But perhaps more surprisingly,
the translations that we get
from people using the site,
even though they&#39;re just beginners,
the translations that we get
are as accurate as those
of professional language translators,
which is very surprising.
So let me show you one example.
This is a sentence that was translated
from German into English.
The top is the German.
The middle is an English translation
that was done by a professional translator
who we paid 20 cents a word
for this translation.
And the bottom is a translation
by users of Duolingo,
none of whom knew any German
before they started using the site.
If you can see, it&#39;s pretty much perfect.
Of course, we play a trick here
to make the translations as good
as professional language translators.
We combine the translations
of multiple beginners
to get the quality
of a single professional translator.
Now, even though
we&#39;re combining the translations,
the site actually
can translate pretty fast.
So let me show you,
this is our estimates
of how fast we could translate Wikipedia
from English into Spanish.
Remember, this is
50 million dollars&#39; worth of value.
So if we wanted to translate
Wikipedia into Spanish,
we could do it in five weeks
with 100,000 active users.
And we could do it in about 80 hours
with a million active users.
Since all the projects
my group has worked on so far
have gotten millions of users,
we&#39;re hopeful that we&#39;ll be able
to translate extremely fast.
Now, the thing that
I&#39;m most excited about with Duolingo
is I think this provides a fair
business model for language education.

So here&#39;s the thing:
The current business model
for language education
is the student pays,
and in particular, the student
pays Rosetta Stone 500 dollars.

(Laughter)

That&#39;s the current business model.
The problem with this business model
is that 95 percent of the world&#39;s
population doesn&#39;t have 500 dollars.
So it&#39;s extremely unfair towards the poor.
This is totally biased towards the rich.
Now, see, in Duolingo,
because while you learn,
you&#39;re actually creating value,
you&#39;re translating stuff --
which, for example, we could
charge somebody for translations,
so this is how we could monetize this.
Since people are creating value
while they&#39;re learning,
they don&#39;t have to pay with their money,
they pay with their time.
But the magical thing here
is that is time that would have had
to have been spent anyways
learning the language.
So the nice thing about Duolingo
is, I think, it provides
a fair business model --
one that doesn&#39;t discriminate
against poor people.
So here&#39;s the site. Thank you.

(Applause)

We haven&#39;t yet launched,
but if you go there, you can sign up
to be part of our private beta,
which is probably going to start
in three or four weeks.
We haven&#39;t yet launched it.
By the way, I&#39;m the one talking here,
but Duolingo is the work
of a really awesome team,
some of whom are here. So thank you.

(Applause)

