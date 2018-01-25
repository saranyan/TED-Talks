
You work at the college library.
You&#39;re in the middle of a quiet afternoon
when suddenly a shipment of 1,280
different books arrives.
The books have been dropped of
in one long straight line,
but they&#39;re all out of order,
and the automatic sorting 
system is broken.
To make matters worse,
classes start tomorrow,
which means that 
first thing in the morning,
students will show up in droves
looking for these books.
How can you get them all sorted in time?
One way would be to start at one end
of the line with the first pair of books.
If the first two books are in order,
then leave them as they are.
Otherwise, swap them.
Then, look at the second and third books,
repeat the process,
and continue until you reach 
the end of the line.
At some point, you&#39;ll come across
the book that should be last,
and keep swapping it with every
subsequent book,
moving it down the line until it
reaches the end where it belongs.
Then, start from the beginning
and repeat the process
to get the second to last book
in its proper place,
and keep going until all books are sorted.
This approach is called Bubble Sort.
It&#39;s simple but slow.
You&#39;d make 1,279 comparisons
in the first round,
then 1,278, and so on,
adding up to 818,560 comparisons.
If each took just one second,
the process would take over nine days.
A second strategy would be to start
by sorting just the first two books.
Then, take the third book and compare it
with the book in the second spot.
If it belongs before the second book,
swap them,
then compare it 
with the book in the first spot,
and swap again if needed.
Now you&#39;ve sorted the first three books.
Keep adding one book at a time
to the sorted sub-line,
comparing and swapping the new book
with the one before it
until it&#39;s correctly placed
among the books sorted so far.
This is called Insertion Sort.
Unlike Bubble Sort, it usually doesn&#39;t
require comparing every pair of books.
On average, we&#39;d expect to only need
to compare each book
to half of the books that came before it.
In that case, the total 
number of comparisons
would be 409,280,
taking almost five days.
You&#39;re still doing 
way too many comparisons.
Here&#39;s a better idea.
First, pick a random book.
Call it the partition and compare it
to every other book.
Then, divide the line
by placing all the books 
that come before the partition on its left
and all the ones that come after it
on its right.
You&#39;ve just saved loads of time
by not having to compare 
any of the books on the left
to any of the ones 
on the right ever again.
Now, looking only 
at the books on the left,
you can again pick a random partition book
and separate those books that come
before it from those that come after it.
You can keep creating 
sub-partitions like this
until you have a bunch of small sub-lines,
each of which you&#39;d sort quickly using
another strategy, like Insertion Sort.
Each round of partitioning requires
about 1,280 comparisons.
If your partitions are pretty balanced,
dividing the books into 128 sub-lines of ten
would take about seven rounds,
or 8,960 seconds.
Sorting these sub-lines would add
about 22 seconds each.
All in all, this method 
known as QuickSort
could sort the books 
in under three and a half hours.
But there&#39;s a catch.
Your partitions could end up lopsided,
saving no time at all.
Luckily, this rarely happens.
That&#39;s why QuickSort is one of the most
efficient strategies
used by programmers today.
They use it for things like sorting items
in an online store by price,
or creating a list of all the gas stations
close to a given location
sorted by distance.
In your case, you&#39;re done quick sorting
with time to spare.
Just another high-stakes day 
in the library.
