

Translator: Andrea McDonough

Reviewer: Jessica Ruby
What&#39;s an algorithm?
In computer science,
an algorithm is a set of instructions
for solving some problem, step-by-step.
Typically, algorithms are executed by computers,
but we humans have algorithms as well.
For instance, how would you go about counting
the number of people in a room?
Well, if you&#39;re like me,
you probably point at each person,
one at a time,

and count up from 0:
1, 2, 3, 4 and so forth.
Well, that&#39;s an algorithm.
In fact, let&#39;s try to express it
a bit more formally in pseudocode,
English-like syntax
that resembles a programming language.
Let n equal 0.
For each person in room, set n = n + 1.
How to interpret this pseudocode?
Well, line 1 declares, so to speak,
a variable called n
and initializes its value to zero.
This just means that at the beginning of our algorithm,
the thing with which we&#39;re counting
has a value of zero.
After all, before we start counting,
we haven&#39;t counted anything yet.
Calling this variable n is just a convention.
I could have called it almost anything.
Now, line 2 demarks the start of loop,
a sequence of steps that will repeat some number of times.
So, in our example, the step we&#39;re taking
is counting people in the room.
Beneath line 2 is line 3,
which describes exactly how we&#39;ll go about counting.
The indentation implies that it&#39;s line 3
that will repeat.
So, what the pseudocode is saying
is that after starting at zero,
for each person in the room,
we&#39;ll increase n by 1.
Now, is this algorithm correct?
Well, let&#39;s bang on it a bit.
Does it work if there are 2 people in the room?
Let&#39;s see.
In line 1, we initialize n to zero.
For each of these two people,
we then increment n by 1.
So, in the first trip through the loop,
we update n from zero to 1,
on the second trip through that same loop,
we update n from 1 to 2.
And so, by this algorithm&#39;s end, n is 2,
which indeed matches the number of people in the room.
So far, so good.
How about a corner case, though?
Suppose that there are zero people in the room,
besides me, who&#39;s doing the counting.
In line 1, we again initialize n to zero.
This time, though, line 3 doesn&#39;t execute at all
since there isn&#39;t a person in the room,
and so, n remains zero,
which indeed matches the number of people in the room.
Pretty simple, right?
But counting people one a time is pretty inefficient, too, no?
Surely, we can do better!
Why not count two people at a time?
Instead of counting 1, 2, 3, 4, 5, 6, 7, 8, and so forth,
why not count
2, 4, 6, 8, and so on?
It even sounds faster, and it surely is.
Let&#39;s express this optimization in pseudocode.
Let n equal zero.
For each pair of people in room,
set n = n + 2.
Pretty simple change, right?
Rather than count people one at a time,
we instead count them two at a time.
This algorithm&#39;s thus twice as fast as the last.
But is it correct?
Let&#39;s see.
Does it work if there are 2 people in the room?
In line 1, we initialize n to zero.
For that one pair of people, we then increment n by 2.
And so, by this algorithm&#39;s end, n is 2,
which indeed matches the number of people in the room.
Suppose next that there are zero people in the room.
In line 1, we initialize n to zero.
As before, line 3 doesn&#39;t execute at all
since there aren&#39;t any pairs of people in the room,
and so, n remains zero,
which indeed matches the number of people in the room.
But what if there are 3 people in the room?
How does this algorithm fair?
Let&#39;s see.
In line 1, we initialize n to zero.
For a pair of those people,
we then increment n by 2,
but then what?
There isn&#39;t another full pair of people in the room,
so line 2 no longer applies.
And so, by this algorithm&#39;s end,
n is still 2, which isn&#39;t correct.
Indeed this algorithm is said to be buggy
because it has a mistake.
Let&#39;s redress with some new pseudocode.
Let n equal zero.
For each pair of people in room,
set n = n + 2.
If 1 person remains unpaired,
set n = n + 1.
To solve this particular problem,
we&#39;ve introduced in line 4 a condition,
otherwise known as a branch,
that only executes if there is one person
we could not pair with another.
So now, whether there&#39;s 1 or 3
or any odd number of people in the room,
this algorithm will now count them.
Can we do even better?
Well, we could count in 3&#39;s or 4&#39;s or even 5&#39;s and 10&#39;s,
but beyond that it&#39;s going to get
a little bit difficult to point.
At the end of the day,
whether executed by computers or humans,
algorithms are just a set of instructions
with which to solve problems.
These were just three.
What problem would you solve with an algorithm?
