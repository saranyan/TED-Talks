
The city has just opened its
one-of-a-kind Fabergé Egg Museum
with a single egg displayed on each floor
of a 100-story building.
And the world&#39;s most notorious jewel thief
already has her eyes on the prize.
Because security is tight
and the eggs are so large,
she&#39;ll only get the chance to steal one
by dropping it out the window
into her waiting truck
and repelling down 
before the police can arrive.
All eggs are identical in weight
and construction,
but each floor&#39;s egg is more rare 
and valuable than the one below it.
While the thief would naturally like
to take the priceless egg at the top,
she suspects it won&#39;t survive
a 100-story drop.
Being pragmatic, she decides to settle
for the most expensive egg she can get.
In the museum&#39;s gift shop, 
she finds two souvenir eggs,
perfect replicas 
that are perfectly worthless.
The plan is to test drop them
to find the highest floor 
at which an egg will survive the fall
without breaking.
Of course, the experiment 
can only be repeated
until both replica eggs are smashed.
And throwing souvenirs out the window
too many times
is probably going to draw 
the guards&#39; attention.
What&#39;s the least number of tries
it would take
to guarantee that 
she find the right floor?
Pause here if you want 
to figure it out for yourself!

Answer in: 3

Answer in: 2

Answer in: 1
If you&#39;re having trouble getting started
on the solution,
it might help to start 
with a simpler scenario.
Imagine our thief only 
had one replica egg.

She&#39;d have a single option:
To start by dropping it 
from the first floor
and go up one by one until it breaks.
Then she&#39;d know that the floor below that
is the one she needs 
to target for the real heist.
But this could require 
as many as 100 tries.
Having an additional replica egg
gives the thief a better option.
She can drop the first egg from different
floors at larger intervals
in order to narrow down the range
where the critical floor can be found.
And once the first breaks,
she can use the second egg to explore
that interval floor by floor.
Large floor intervals don&#39;t work great.
In the worst case scenario, they require
many tests with the second egg.
Smaller intervals work much better.
For example, if she starts by dropping
the first egg from every 10th floor,
once it breaks, she&#39;ll only have to test
the nine floors below.
That means it&#39;ll take at most
19 tries to find the right floor.
But can she do even better?
After all, there&#39;s no reason 
every interval has to be the same size.
Let&#39;s say there were only ten floors.
The thief could test this whole building
with just four total throws
by dropping the first egg
at floors four,
seven,
and nine.
If it broke at floor four, it would take
up to three throws of the second egg
to find the exact floor.
If it broke at seven,
it would take up to two throws
with the second egg.
And if it broke at floor nine,
it would take just one more
throw of the second egg.
Intuitively, what we&#39;re trying to do here
is divide the building into sections
where no matter which floor is correct,
it takes up to the same number
of throws to find it.
We want each interval to be one floor
smaller than the last.
This equation can help us solve
for the first floor we need to start with
in the 100 floor building.
There are several ways 
to solve this equation,
including trial and error.
If we plug in two for n,
that equation would look like this.
If we plug in three, we get this.
So we can find the first n to pass 100
by adding more terms 
until we get to our answer,
which is 14.
And so our thief starts on the 14th floor,
moving up to the 27th,
the 39th,
and so on,
for a maximum of 14 drops.
Like the old saying goes, you can&#39;t 
pull a heist without breaking a few eggs.
