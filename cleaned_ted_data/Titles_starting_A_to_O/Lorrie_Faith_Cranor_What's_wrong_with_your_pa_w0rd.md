
I am a computer science and engineering
professor here at Carnegie Mellon,
and my research focuses on
usable privacy and security,
and so my friends like to give me examples
of their frustrations with computing systems,
especially frustrations related to
unusable privacy and security.
So passwords are something that I hear a lot about.
A lot of people are frustrated with passwords,
and it&#39;s bad enough
when you have to have one really good password
that you can remember
but nobody else is going to be able to guess.
But what do you do when you have accounts
on a hundred different systems
and you&#39;re supposed to have a unique password
for each of these systems?
It&#39;s tough.
At Carnegie Mellon, they used to make it
actually pretty easy for us
to remember our passwords.
The password requirement up through 2009
was just that you had to have a password
with at least one character.
Pretty easy. But then they changed things,
and at the end of 2009, they announced
that we were going to have a new policy,
and this new policy required
passwords that were at least eight characters long,
with an uppercase letter, lowercase letter,
a digit, a symbol,
you couldn&#39;t use the same
character more than three times,
and it wasn&#39;t allowed to be in a dictionary.
Now, when they implemented this new policy,
a lot of people, my colleagues and friends,
came up to me and they said, &quot;Wow,
now that&#39;s really unusable.
Why are they doing this to us,
and why didn&#39;t you stop them?&quot;
And I said, &quot;Well, you know what?
They didn&#39;t ask me.&quot;
But I got curious, and I decided to go talk
to the people in charge of our computer systems
and find out what led them to introduce
this new policy,
and they said that the university
had joined a consortium of universities,
and one of the requirements of membership
was that we had to have stronger passwords
that complied with some new requirements,
and these requirements were that our passwords
had to have a lot of entropy.
Now entropy is a complicated term,
but basically it measures the strength of passwords.
But the thing is, there isn&#39;t actually
a standard measure of entropy.
Now, the National Institute
of Standards and Technology
has a set of guidelines
which have some rules of thumb
for measuring entropy,
but they don&#39;t have anything too specific,
and the reason they only have rules of thumb
is it turns out they don&#39;t actually have any good data
on passwords.
In fact, their report states,
&quot;Unfortunately, we do not have much data
on the passwords users
choose under particular rules.
NIST would like to obtain more data
on the passwords users actually choose,
but system administrators
are understandably reluctant
to reveal password data to others.&quot;
So this is a problem, but our research group
looked at it as an opportunity.
We said, &quot;Well, there&#39;s a need
for good password data.
Maybe we can collect some good password data
and actually advance the state of the art here.
So the first thing we did is,
we got a bag of candy bars
and we walked around campus
and talked to students, faculty and staff,
and asked them for information
about their passwords.
Now we didn&#39;t say, &quot;Give us your password.&quot;
No, we just asked them about their password.
How long is it? Does it have a digit?
Does it have a symbol?
And were you annoyed at having to create
a new one last week?
So we got results from 470 students,
faculty and staff,
and indeed we confirmed that the new policy
was very annoying,
but we also found that people said
they felt more secure with these new passwords.
We found that most people knew
they were not supposed to
write their password down,
and only 13 percent of them did,
but disturbingly, 80 percent of people
said they were reusing their password.
Now, this is actually more dangerous
than writing your password down,
because it makes you much
more susceptible to attackers.
So if you have to, write your passwords down,
but don&#39;t reuse them.
We also found some interesting things
about the symbols people use in passwords.
So CMU allows 32 possible symbols,
but as you can see, there&#39;s only a small number
that most people are using,
so we&#39;re not actually getting very much strength
from the symbols in our passwords.
So this was a really interesting study,
and now we had data from 470 people,
but in the scheme of things,
that&#39;s really not very much password data,
and so we looked around to see
where could we find additional password data?
So it turns out there are a lot of people
going around stealing passwords,
and they often go and post these passwords
on the Internet.
So we were able to get access
to some of these stolen password sets.
This is still not really ideal for research, though,
because it&#39;s not entirely clear
where all of these passwords came from,
or exactly what policies were in effect
when people created these passwords.
So we wanted to find some better source of data.
So we decided that one thing we could do
is we could do a study and have people
actually create passwords for our study.
So we used a service called
Amazon Mechanical Turk,
and this is a service where you can post
a small job online that takes a minute,
a few minutes, an hour,
and pay people, a penny, ten cents, a few dollars,
to do a task for you,
and then you pay them through Amazon.com.
So we paid people about 50 cents
to create a password following our rules
and answering a survey,
and then we paid them again to come back
two days later and log in
using their password and answering another survey.
So we did this, and we collected 5,000 passwords,
and we gave people a bunch of different policies
to create passwords with.
So some people had a pretty easy policy,
we call it Basic8,
and here the only rule was that your password
had to have at least eight characters.
Then some people had a much harder policy,
and this was very similar to the CMU policy,
that it had to have eight characters
including uppercase, lowercase, digit, symbol,
and pass a dictionary check.
And one of the other policies we tried,
and there were a whole bunch more,
but one of the ones we tried was called Basic16,
and the only requirement here
was that your password had
to have at least 16 characters.
All right, so now we had 5,000 passwords,
and so we had much more detailed information.
Again we see that there&#39;s only a small number
of symbols that people are actually using
in their passwords.
We also wanted to get an idea of how strong
the passwords were that people were creating,
but as you may recall, there isn&#39;t a good measure
of password strength.
So what we decided to do was to see
how long it would take to crack these passwords
using the best cracking tools
that the bad guys are using,
or that we could find information about
in the research literature.
So to give you an idea of how bad guys
go about cracking passwords,
they will steal a password file
that will have all of the passwords
in kind of a scrambled form, called a hash,
and so what they&#39;ll do is they&#39;ll make a guess
as to what a password is,
run it through a hashing function,
and see whether it matches
the passwords they have on
their stolen password list.
So a dumb attacker will try every password in order.
They&#39;ll start with AAAAA and move on to AAAAB,
and this is going to take a really long time
before they get any passwords
that people are really likely to actually have.
A smart attacker, on the other hand,
does something much more clever.
They look at the passwords
that are known to be popular
from these stolen password sets,
and they guess those first.
So they&#39;re going to start by guessing &quot;password,&quot;
and then they&#39;ll guess &quot;I love you,&quot; and &quot;monkey,&quot;
and &quot;12345678,&quot;
because these are the passwords
that are most likely for people to have.
In fact, some of you probably have these passwords.
So what we found
by running all of these 5,000 passwords we collected
through these tests to see how strong they were,
we found that the long passwords
were actually pretty strong,
and the complex passwords were pretty strong too.
However, when we looked at the survey data,
we saw that people were really frustrated
by the very complex passwords,
and the long passwords were a lot more usable,
and in some cases, they were actually
even stronger than the complex passwords.
So this suggests that,
instead of telling people that they need
to put all these symbols and numbers
and crazy things into their passwords,
we might be better off just telling people
to have long passwords.

Now here&#39;s the problem, though:
Some people had long passwords
that actually weren&#39;t very strong.
You can make long passwords
that are still the sort of thing
that an attacker could easily guess.
So we need to do more than
just say long passwords.
There has to be some additional requirements,
and some of our ongoing research is looking at
what additional requirements we should add
to make for stronger passwords
that also are going to be easy for people
to remember and type.
Another approach to getting people to have
stronger passwords is to use a password meter.
Here are some examples.
You may have seen these on the Internet
when you were creating passwords.
We decided to do a study to find out
whether these password meters actually work.
Do they actually help people
have stronger passwords,
and if so, which ones are better?
So we tested password meters that were
different sizes, shapes, colors,
different words next to them,
and we even tested one that was a dancing bunny.
As you type a better password,
the bunny dances faster and faster.
So this was pretty fun.
What we found
was that password meters do work.

(Laughter)

Most of the password meters were actually effective,
and the dancing bunny was very effective too,
but the password meters that were the most effective
were the ones that made you work harder
before they gave you that thumbs up and said
you were doing a good job,
and in fact we found that most
of the password meters on the Internet today
are too soft.
They tell you you&#39;re doing a good job too early,
and if they would just wait a little bit
before giving you that positive feedback,
you probably would have better passwords.
Now another approach to better passwords, perhaps,
is to use pass phrases instead of passwords.
So this was an xkcd cartoon 
from a couple of years ago,
and the cartoonist suggests
that we should all use pass phrases,
and if you look at the second row of this cartoon,
you can see the cartoonist is suggesting
that the pass phrase &quot;correct horse battery staple&quot;
would be a very strong pass phrase
and something really easy to remember.
He says, in fact, you&#39;ve already remembered it.
And so we decided to do a research study
to find out whether this was true or not.
In fact, everybody who I talk to,
who I mention I&#39;m doing password research,
they point out this cartoon.
&quot;Oh, have you seen it? That xkcd.
Correct horse battery staple.&quot;
So we did the research study to see
what would actually happen.
So in our study, we used Mechanical Turk again,
and we had the computer pick the random words
in the pass phrase.
Now the reason we did this
is that humans are not very good
at picking random words.
If we asked a human to do it,
they would pick things that were not very random.
So we tried a few different conditions.
In one condition, the computer picked
from a dictionary of the very common words
in the English language,
and so you&#39;d get pass phrases like
&quot;try there three come.&quot;
And we looked at that, and we said,
&quot;Well, that doesn&#39;t really seem very memorable.&quot;
So then we tried picking words
that came from specific parts of speech,
so how about noun-verb-adjective-noun.
That comes up with something
that&#39;s sort of sentence-like.
So you can get a pass phrase like
&quot;plan builds sure power&quot;
or &quot;end determines red drug.&quot;
And these seemed a little bit more memorable,
and maybe people would like those a little bit better.
We wanted to compare them with passwords,
and so we had the computer
pick random passwords,
and these were nice and short, but as you can see,
they don&#39;t really look very memorable.
And then we decided to try something called
a pronounceable password.
So here the computer picks random syllables
and puts them together
so you have something sort of pronounceable,
like &quot;tufritvi&quot; and &quot;vadasabi.&quot;
That one kind of rolls off your tongue.
So these were random passwords that were
generated by our computer.
So what we found in this study was that, surprisingly,
pass phrases were not actually all that good.
People were not really better at remembering
the pass phrases than these random passwords,
and because the pass phrases are longer,
they took longer to type
and people made more errors while typing them in.
So it&#39;s not really a clear win for pass phrases.
Sorry, all of you xkcd fans.
On the other hand, we did find
that pronounceable passwords
worked surprisingly well,
and so we actually are doing some more research
to see if we can make that
approach work even better.
So one of the problems
with some of the studies that we&#39;ve done
is that because they&#39;re all done
using Mechanical Turk,
these are not people&#39;s real passwords.
They&#39;re the passwords that they created
or the computer created for them for our study.
And we wanted to know whether people
would actually behave the same way
with their real passwords.
So we talked to the information
security office at Carnegie Mellon
and asked them if we could
have everybody&#39;s real passwords.
Not surprisingly, they were a little bit reluctant
to share them with us,
but we were actually able to work out
a system with them
where they put all of the real passwords
for 25,000 CMU students, faculty and staff,
into a locked computer in a locked room,
not connected to the Internet,
and they ran code on it that we wrote
to analyze these passwords.
They audited our code.
They ran the code.
And so we never actually saw
anybody&#39;s password.
We got some interesting results,
and those of you Tepper students in the back
will be very interested in this.
So we found that the passwords created
by people affiliated with the
school of computer science
were actually 1.8 times stronger
than those affiliated with the business school.
We have lots of other really interesting
demographic information as well.
The other interesting thing that we found
is that when we compared
the Carnegie Mellon passwords
to the Mechanical Turk-generated passwords,
there was actually a lot of similarities,
and so this helped validate our research method
and show that actually, collecting passwords
using these Mechanical Turk studies
is actually a valid way to study passwords.
So that was good news.
Okay, I want to close by talking about
some insights I gained while on sabbatical
last year in the Carnegie Mellon art school.
One of the things that I did
is I made a number of quilts,
and I made this quilt here.
It&#39;s called &quot;Security Blanket.&quot;

(Laughter)

And this quilt has the 1,000
most frequent passwords stolen
from the RockYou website.
And the size of the passwords is proportional
to how frequently they appeared
in the stolen dataset.
And what I did is I created this word cloud,
and I went through all 1,000 words,
and I categorized them into
loose thematic categories.
And it was, in some cases,
it was kind of difficult to figure out
what category they should be in,
and then I color-coded them.
So here are some examples of the difficulty.
So &quot;justin.&quot;
Is that the name of the user,
their boyfriend, their son?
Maybe they&#39;re a Justin Bieber fan.
Or &quot;princess.&quot;
Is that a nickname?
Are they Disney princess fans?
Or maybe that&#39;s the name of their cat.
&quot;Iloveyou&quot; appears many times
in many different languages.
There&#39;s a lot of love in these passwords.
If you look carefully, you&#39;ll see there&#39;s also
some profanity,
but it was really interesting to me to see
that there&#39;s a lot more love than hate
in these passwords.
And there are animals,
a lot of animals,
and &quot;monkey&quot; is the most common animal
and the 14th most popular password overall.
And this was really curious to me,
and I wondered, &quot;Why are monkeys so popular?&quot;
And so in our last password study,
any time we detected somebody
creating a password with the word &quot;monkey&quot; in it,
we asked them why they had
a monkey in their password.
And what we found out --
we found 17 people so far, I think,
who have the word &quot;monkey&quot; --
We found out about a third of them said
they have a pet named &quot;monkey&quot;
or a friend whose nickname is &quot;monkey,&quot;
and about a third of them said
that they just like monkeys
and monkeys are really cute.
And that guy is really cute.
So it seems that at the end of the day,
when we make passwords,
we either make something that&#39;s really easy
to type, a common pattern,
or things that remind us of the word password
or the account that we&#39;ve created the password for,
or whatever.
Or we think about things that make us happy,
and we create our password
based on things that make us happy.
And while this makes typing
and remembering your password more fun,
it also makes it a lot easier
to guess your password.
So I know a lot of these TED Talks
are inspirational
and they make you think about nice, happy things,
but when you&#39;re creating your password,
try to think about something else.
Thank you.

(Applause)

