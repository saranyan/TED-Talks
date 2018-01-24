
So you go to the doctor
and get some tests.
The doctor determines
that you have high cholesterol
and you would benefit
from medication to treat it.
So you get a pillbox.
You have some confidence,
your physician has some confidence
that this is going to work.
The company that invented it did
a lot of studies, submitted it to the FDA.
They studied it very carefully,
skeptically, they approved it.
They have a rough idea of how it works,
they have a rough idea
of what the side effects are.
It should be OK.
You have a little more
of a conversation with your physician
and the physician is a little worried
because you&#39;ve been blue,
haven&#39;t felt like yourself,
you haven&#39;t been able to enjoy things
in life quite as much as you usually do.
Your physician says, &quot;You know,
I think you have some depression.
I&#39;m going to have to give
you another pill.&quot;
So now we&#39;re talking
about two medications.
This pill also -- millions
of people have taken it,
the company did studies,
the FDA looked at it -- all good.
Think things should go OK.
Think things should go OK.
Well, wait a minute.
How much have we studied
these two together?
Well, it&#39;s very hard to do that.
In fact, it&#39;s not traditionally done.
We totally depend on what we call
&quot;post-marketing surveillance,&quot;
after the drugs hit the market.
How can we figure out
if bad things are happening
between two medications?
Three? Five? Seven?
Ask your favorite person
who has several diagnoses
how many medications they&#39;re on.
Why do I care about this problem?
I care about it deeply.
I&#39;m an informatics and data science guy
and really, in my opinion,
the only hope -- only hope --
to understand these interactions
is to leverage lots
of different sources of data
in order to figure out
when drugs can be used together safely
and when it&#39;s not so safe.
So let me tell you a data science story.
And it begins with my student Nick.
Let&#39;s call him &quot;Nick,&quot;
because that&#39;s his name.

(Laughter)

Nick was a young student.
I said, &quot;You know, Nick, we have
to understand how drugs work
and how they work together
and how they work separately,
and we don&#39;t have a great understanding.
But the FDA has made available
an amazing database.
It&#39;s a database of adverse events.
They literally put on the web --
publicly available, you could all
download it right now --
hundreds of thousands
of adverse event reports
from patients, doctors,
companies, pharmacists.

And these reports are pretty simple:
it has all the diseases
that the patient has,
all the drugs that they&#39;re on,
and all the adverse events,
or side effects, that they experience.
It is not all of the adverse events
that are occurring in America today,
but it&#39;s hundreds and hundreds
of thousands of drugs.
So I said to Nick,
&quot;Let&#39;s think about glucose.
Glucose is very important,
and we know it&#39;s involved with diabetes.
Let&#39;s see if we can understand
glucose response.
I sent Nick off. Nick came back.
&quot;Russ,&quot; he said,
&quot;I&#39;ve created a classifier that can
look at the side effects of a drug
based on looking at this database,
and can tell you whether that drug
is likely to change glucose or not.&quot;
He did it. It was very simple, in a way.
He took all the drugs
that were known to change glucose
and a bunch of drugs
that don&#39;t change glucose,
and said, &quot;What&#39;s the difference
in their side effects?
Differences in fatigue? In appetite?
In urination habits?&quot;
All those things conspired
to give him a really good predictor.
He said, &quot;Russ, I can predict
with 93 percent accuracy
when a drug will change glucose.&quot;
I said, &quot;Nick, that&#39;s great.&quot;
He&#39;s a young student,
you have to build his confidence.
&quot;But Nick, there&#39;s a problem.
It&#39;s that every physician in the world
knows all the drugs that change glucose,
because it&#39;s core to our practice.
So it&#39;s great, good job,
but not really that interesting,
definitely not publishable.&quot;

(Laughter)

He said, &quot;I know, Russ.
I thought you might say that.&quot;
Nick is smart.
&quot;I thought you might say that,
so I did one other experiment.
I looked at people in this database
who were on two drugs,
and I looked for signals similar,
glucose-changing signals,
for people taking two drugs,
where each drug alone
did not change glucose,
but together I saw a strong signal.&quot;
And I said, &quot;Oh! You&#39;re clever.
Good idea. Show me the list.&quot;
And there&#39;s a bunch of drugs,
not very exciting.
But what caught my eye

was, on the list there were two drugs:
paroxetine, or Paxil, an antidepressant;
and pravastatin, or Pravachol,
a cholesterol medication.
And I said, &quot;Huh. There are millions
of Americans on those two drugs.&quot;
In fact, we learned later,
15 million Americans on paroxetine
at the time, 15 million on pravastatin,
and a million, we estimated, on both.
So that&#39;s a million people
who might be having some problems
with their glucose
if this machine-learning mumbo jumbo
that he did in the FDA database
actually holds up.
But I said, &quot;It&#39;s still not publishable,
because I love what you did
with the mumbo jumbo,
with the machine learning,
but it&#39;s not really standard-of-proof
evidence that we have.&quot;
So we have to do something else.
Let&#39;s go into the Stanford
electronic medical record.
We have a copy of it
that&#39;s OK for research,
we removed identifying information.
And I said, &quot;Let&#39;s see if people
on these two drugs
have problems with their glucose.&quot;
Now there are thousands
and thousands of people
in the Stanford medical records
that take paroxetine and pravastatin.
But we needed special patients.
We needed patients who were on one of them
and had a glucose measurement,
then got the second one and had
another glucose measurement,
all within a reasonable period of time --
something like two months.
And when we did that,
we found 10 patients.
However, eight out of the 10
had a bump in their glucose
when they got the second P --
we call this P and P --
when they got the second P.
Either one could be first,
the second one comes up,
glucose went up
20 milligrams per deciliter.
Just as a reminder,
you walk around normally,
if you&#39;re not diabetic,
with a glucose of around 90.
And if it gets up to 120, 125,
your doctor begins to think
about a potential diagnosis of diabetes.
So a 20 bump -- pretty significant.
I said, &quot;Nick, this is very cool.
But, I&#39;m sorry, we still
don&#39;t have a paper,
because this is 10 patients
and -- give me a break --
it&#39;s not enough patients.&quot;
So we said, what can we do?
And we said, let&#39;s call our friends
at Harvard and Vanderbilt,
who also -- Harvard in Boston,
Vanderbilt in Nashville,
who also have electronic
medical records similar to ours.
Let&#39;s see if they can find
similar patients
with the one P, the other P,
the glucose measurements
in that range that we need.
God bless them, Vanderbilt
in one week found 40 such patients,
same trend.
Harvard found 100 patients, same trend.
So at the end, we had 150 patients
from three diverse medical centers
that were telling us that patients
getting these two drugs
were having their glucose bump
somewhat significantly.
More interestingly,
we had left out diabetics,
because diabetics already
have messed up glucose.
When we looked
at the glucose of diabetics,
it was going up 60 milligrams
per deciliter, not just 20.
This was a big deal, and we said,
&quot;We&#39;ve got to publish this.&quot;
We submitted the paper.
It was all data evidence,
data from the FDA, data from Stanford,
data from Vanderbilt, data from Harvard.
We had not done a single real experiment.
But we were nervous.
So Nick, while the paper
was in review, went to the lab.
We found somebody
who knew about lab stuff.
I don&#39;t do that.
I take care of patients,
but I don&#39;t do pipettes.
They taught us how to feed mice drugs.
We took mice and we gave them
one P, paroxetine.
We gave some other mice pravastatin.
And we gave a third group
of mice both of them.
And lo and behold, glucose went up
20 to 60 milligrams per deciliter
in the mice.
So the paper was accepted
based on the informatics evidence alone,
but we added a little note at the end,
saying, oh by the way,
if you give these to mice, it goes up.
That was great, and the story
could have ended there.
But I still have six and a half minutes.

(Laughter)

So we were sitting around
thinking about all of this,
and I don&#39;t remember who thought
of it, but somebody said,
&quot;I wonder if patients
who are taking these two drugs
are noticing side effects
of hyperglycemia.
They could and they should.
How would we ever determine that?&quot;
We said, well, what do you do?
You&#39;re taking a medication,
one new medication or two,
and you get a funny feeling.
What do you do?
You go to Google
and type in the two drugs you&#39;re taking
or the one drug you&#39;re taking,
and you type in &quot;side effects.&quot;
What are you experiencing?
So we said OK,
let&#39;s ask Google if they will share
their search logs with us,
so that we can look at the search logs
and see if patients are doing
these kinds of searches.
Google, I am sorry to say,
denied our request.
So I was bummed.
I was at a dinner with a colleague
who works at Microsoft Research
and I said, &quot;We wanted to do this study,
Google said no, it&#39;s kind of a bummer.&quot;
He said, &quot;Well, we have
the Bing searches.&quot;

(Laughter)

Yeah.
That&#39;s great.
Now I felt like I was --

(Laughter)

I felt like I was talking to Nick again.
He works for one of the largest
companies in the world,
and I&#39;m already trying
to make him feel better.
But he said, &quot;No, Russ --
you might not understand.
We not only have Bing searches,
but if you use Internet Explorer
to do searches at Google,
Yahoo, Bing, any ...
Then, for 18 months, we keep that data
for research purposes only.&quot;
I said, &quot;Now you&#39;re talking!&quot;
This was Eric Horvitz,
my friend at Microsoft.
So we did a study
where we defined 50 words
that a regular person might type in
if they&#39;re having hyperglycemia,
like &quot;fatigue,&quot; &quot;loss of appetite,&quot;
&quot;urinating a lot,&quot; &quot;peeing a lot&quot; --
forgive me, but that&#39;s one
of the things you might type in.
So we had 50 phrases
that we called the &quot;diabetes words.&quot;
And we did first a baseline.
And it turns out
that about .5 to one percent
of all searches on the Internet
involve one of those words.
So that&#39;s our baseline rate.
If people type in &quot;paroxetine&quot;
or &quot;Paxil&quot; -- those are synonyms --
and one of those words,
the rate goes up to about two percent
of diabetes-type words,
if you already know
that there&#39;s that &quot;paroxetine&quot; word.
If it&#39;s &quot;pravastatin,&quot; the rate goes up
to about three percent from the baseline.
If both &quot;paroxetine&quot; and &quot;pravastatin&quot;
are present in the query,
it goes up to 10 percent,
a huge three- to four-fold increase
in those searches with the two drugs
that we were interested in,
and diabetes-type words
or hyperglycemia-type words.
We published this,
and it got some attention.
The reason it deserves attention
is that patients are telling us
their side effects indirectly
through their searches.
We brought this
to the attention of the FDA.
They were interested.
They have set up social media
surveillance programs
to collaborate with Microsoft,
which had a nice infrastructure
for doing this, and others,
to look at Twitter feeds,
to look at Facebook feeds,
to look at search logs,
to try to see early signs that drugs,
either individually or together,
are causing problems.
What do I take from this?
Why tell this story?
Well, first of all,
we have now the promise
of big data and medium-sized data
to help us understand drug interactions
and really, fundamentally, drug actions.
How do drugs work?
This will create and has created
a new ecosystem
for understanding how drugs work
and to optimize their use.
Nick went on; he&#39;s a professor
at Columbia now.
He did this in his PhD
for hundreds of pairs of drugs.
He found several
very important interactions,
and so we replicated this
and we showed that this
is a way that really works
for finding drug-drug interactions.
However, there&#39;s a couple of things.
We don&#39;t just use pairs
of drugs at a time.
As I said before, there are patients
on three, five, seven, nine drugs.
Have they been studied with respect
to their nine-way interaction?
Yes, we can do pair-wise,
A and B, A and C, A and D,
but what about A, B, C,
D, E, F, G all together,
being taken by the same patient,
perhaps interacting with each other
in ways that either makes them
more effective or less effective
or causes side effects
that are unexpected?
We really have no idea.
It&#39;s a blue sky, open field
for us to use data
to try to understand
the interaction of drugs.

Two more lessons:
I want you to think about the power
that we were able to generate
with the data from people who had
volunteered their adverse reactions
through their pharmacists,
through themselves, through their doctors,
the people who allowed the databases
at Stanford, Harvard, Vanderbilt,
to be used for research.
People are worried about data.
They&#39;re worried about their privacy
and security -- they should be.
We need secure systems.
But we can&#39;t have a system
that closes that data off,
because it is too rich of a source
of inspiration, innovation and discovery
for new things in medicine.
And the final thing I want to say is,
in this case we found two drugs
and it was a little bit of a sad story.
The two drugs actually caused problems.
They increased glucose.
They could throw somebody into diabetes
who would otherwise not be in diabetes,
and so you would want to use
the two drugs very carefully together,
perhaps not together,
make different choices
when you&#39;re prescribing.
But there was another possibility.
We could have found
two drugs or three drugs
that were interacting in a beneficial way.
We could have found new effects of drugs
that neither of them has alone,
but together, instead
of causing a side effect,
they could be a new and novel treatment
for diseases that don&#39;t have treatments
or where the treatments are not effective.
If we think about drug treatment today,
all the major breakthroughs --
for HIV, for tuberculosis,
for depression, for diabetes --
it&#39;s always a cocktail of drugs.
And so the upside here,
and the subject for a different
TED Talk on a different day,
is how can we use the same data sources
to find good effects
of drugs in combination
that will provide us new treatments,
new insights into how drugs work
and enable us to take care
of our patients even better?
Thank you very much.

(Applause)

