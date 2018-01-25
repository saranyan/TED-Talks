

Translator: Andrea McDonough

Reviewer: Bedirhan Cinar
Hello, my name is Christian Rudder,
and I was one of the founders of OkCupid.
It&#39;s now one of the biggest
dating sites in the United States.
Like most everyone at the site,
I was a math major,
As you may expect, we&#39;re known
for the analytic approach we take to love.
We call it our matching algorithm.
Basically, OkCupid&#39;s matching
algorithm helps us decide
whether two people should go on a date.
We built our entire business around it.
Now, algorithm is a fancy word,
and people like to drop it
like it&#39;s this big thing.
But really, an algorithm
is just a systematic,
step-by-step way to solve a problem.
It doesn&#39;t have to be fancy at all.
Here in this lesson,
I&#39;m going to explain how we arrived
at our particular algorithm,
so you can see how it&#39;s done.
Now, why are algorithms even important?
Why does this lesson even exist?
Well, notice one very significant

phrase I used above:
they are a step-by-step
way to solve a problem,
and as you probably know, computers
excel at step-by-step processes.
A computer without an algorithm
is basically an expensive paperweight.
And since computers are such
a pervasive part of everyday life,
algorithms are everywhere.
The math behind OkCupid&#39;s matching
algorithm is surprisingly simple.
It&#39;s just some addition, multiplication,
a little bit of square roots.
The tricky part in designing it
was figuring out how to take
something mysterious,
human attraction,
and break it into components
that a computer can work with.
The first thing we needed
to match people up was data,
something for the algorithm to work with.
The best way to get data quickly
from people is to just ask for it.
So we decided that OkCupid
should ask users questions,
stuff like, &quot;Do you want
to have kids one day?&quot;
&quot;How often do you brush your teeth?&quot;
&quot;Do you like scary movies?&quot;
And big stuff like,
&quot;Do you believe in God?&quot;
Now, a lot of the questions
are good for matching like with like,
that is, when both people
answer the same way.
For example, two people
who are both into scary movies
are probably a better match
than one person who is and one who isn&#39;t.
But what about a question like,
&quot;Do you like to be
the center of attention?&quot;
If both people in a relationship
are saying yes to this,
they&#39;re going to have massive problems.
We realized this early on,
and so we decided we needed
a bit more data from each question.
We had to ask people to specify
not only their own answer,
but the answer they wanted
from someone else.
That worked really well.
But we needed one more dimension.
Some questions tell you more
about a person than others.
For example, a question
about politics, something like,

&quot;Which is worse:
book burning or flag burning?&quot;
might reveal more about someone
than their taste in movies.
And it doesn&#39;t make sense
to weigh all things equally,
so we added one final data point.
For everything that OkCupid asks you,
you have a chance to tell us
the role it plays in your life.
And this ranges
from irrelevant to mandatory.
So now, for every question,

we have three things for our algorithm:
first, your answer;
second, how you want someone else --
your potential match -- to answer;
and third, how important
the question is to you at all.
With all this information,
OkCupid can figure out
how well two people will get along.
The algorithm crunches the numbers
and gives us a result.
As a practical example,
let&#39;s look at how we&#39;d match you
with another person.
Let&#39;s call him &quot;B.&quot;
Your match percentage with B is based
on questions you&#39;ve both answered.
Let&#39;s call that set
of common questions &quot;s.&quot;
As a very simple example,
we use a small set &quot;s&quot;
with just two questions in common,
and compute a match from that.
Here are our two example questions.
The first one, let&#39;s say, is,
&quot;How messy are you?&quot;

And the answer possibilities are:
very messy, average and very organized.
And let&#39;s say you answered
&quot;very organized,&quot;
and you&#39;d like someone else
to answer &quot;very organized,&quot;
and the question is very important to you.
Basically, you&#39;re a neat freak.
You&#39;re neat, you want someone else
to be neat, and that&#39;s it.
And let&#39;s say B is a little bit different.
He answered &quot;very organized&quot; for himself,
but &quot;average&quot; is OK with him
as an answer from someone else,
and the question is only
a little important to him.
Let&#39;s look at the second question,

from our previous example:
&quot;Do you like to be
the center of attention?&quot;
The answers are &quot;yes&quot; and &quot;no.&quot;
You&#39;ve answered &quot;no,&quot; you want
someone else to answer &quot;no,&quot;
and the question is only
a little important to you.
Now B, he&#39;s answered &quot;yes.&quot;
He wants someone else to answer &quot;no,&quot;
because he wants the spotlight on him,
and the question is somewhat
important to him.
So, let&#39;s try to compute all of this.
Our first step is, since we use
computers to do this,
we need to assign numerical values
to ideas like &quot;somewhat
important&quot; and &quot;very important,&quot;
because computers need
everything in numbers.
We at OkCupid decided

on the following scale:
&quot;Irrelevant&quot; is worth 0.
&quot;A little important&quot; is worth 1.
&quot;Somewhat important&quot; is worth 10.
&quot;Very important&quot; is 50.
And &quot;absolutely mandatory&quot; is 250.
Next, the algorithm makes
two simple calculations.

The first is: How much did
B&#39;s answers satisfy you?
That is, how many possible points
did B score on your scale?
Well, you indicated that B&#39;s answer
to the first question,
about messiness,
was very important to you.
It&#39;s worth 50 points and B got that right.
The second question is worth only 1,
because you said
it was only a little important.
B got that wrong,
so B&#39;s answers were 50
out of 51 possible points.
That&#39;s 98% satisfactory. Pretty good.
The second question the algorithm

looks at is: How much did you satisfy B?
Well, B placed 1 point on your answer
to the messiness question
and 10 on your answer to the second.
Of those 11, that&#39;s 1 plus 10,
you earned 10 --
you guys satisfied each other
on the second question.
So your answers were 10 out of 11
equals 91 percent satisfactory to B.
That&#39;s not bad.
The final step is to take
these two match percentages
and get one number for the both of you.
To do this, the algorithm
multiplies your scores,
then takes the nth root,
where &quot;n&quot; is the number of questions.
Because s, which is the number
of questions in this sample,
is only 2,

we have: match percentage
equals the square root
of 98 percent times 91 percent.
That equals 94 percent.
That 94 percent is your match
percentage with B.
It&#39;s a mathematical expression
of how happy you&#39;d be with each other,
based on what we know.
Now, why does the algorithm multiply,
as opposed to, say, average
the two match scores together,
and do the square-root business?
In general, this formula
is called the geometric mean.
It&#39;s a great way to combine
values that have wide ranges
and represent very different properties.
In other words, it&#39;s perfect
for romantic matching.
You&#39;ve got wide ranges and you&#39;ve got
tons of different data points,
like I said, about movies, politics,
religion -- everything.
Intuitively, too, this makes sense.
Two people satisfying
each other 50 percent
should be a better match
than two others who satisfy 0 and 100,
because affection needs to be mutual.
After adding a little correction
for margin of error,
in the case where we have
a small number of questions,
like we do in this example,
we&#39;re good to go.
Any time OkCupid matches two people,
it goes through the steps
we just outlined.
First it collects data about your answers,
then it compares your choices
and preferences to other people&#39;s
in simple, mathematical ways.
This, the ability to take
real-world phenomena
and make them something
a microchip can understand,
is, I think, the most important skill
anyone can have these days.
Like you use sentences
to tell a story to a person,
you use algorithms
to tell a story to a computer.
If you learn the language,
you can go out and tell your stories.
I hope this will help you do that.
