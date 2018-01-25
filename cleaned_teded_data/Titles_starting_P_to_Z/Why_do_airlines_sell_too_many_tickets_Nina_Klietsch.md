
Have you ever sat in a doctor&#39;s
office for hours
despite having an appointment
at a specific time?
Has a hotel turned down
your reservation because it&#39;s full?
Or have you been bumped off a flight
that you paid for?
These are all symptoms of overbooking,
a practice where businesses
and institutions
sell or book more 
than their full capacity.
While often infuriating for the customer,
overbooking happens because
it increases profits
while also letting businesses
optimize their resources.
They know that not everyone
will show up to their appointments,
reservations,
and flights,
so they make more available
than they actually have to offer.
Airlines are the classical example,
partially because it happens so often.
About 50,000 people get bumped
off their flights each year.
That figure comes at little surprise
to the airlines themselves,
which use statistics to determine
exactly how many tickets to sell.
It&#39;s a delicate operation.
Sell too few, and they&#39;re wasting seats.
Sell too many, and they pay penalties -
money, free flights, hotel stays,
and annoyed customers.
So here&#39;s a simplified version
of how their calculations work.
Airlines have collected years worth
of information
about who does and doesn&#39;t show up
for certain flights.
They know, for example,
that on a particular route,
the probability that each individual
customer will show up on time is 90%.
For the sake of simplicity,
we&#39;ll assume that every customer
is traveling individually
rather than as families or groups.
Then, if there are 180 seats on the plane
and they sell 180 tickets,
the most likely result is that 162
passengers will board.
But, of course, you could also
end up with more passengers,
or fewer.
The probability for each value
is given by what&#39;s called
a binomial distribution,
which peaks at the most likely outcome.
Now let&#39;s look at the revenue.
The airline makes money from each
ticket buyer
and loses money for each person
who gets bumped.
Let&#39;s say a ticket costs $250
and isn&#39;t exchangeable for a later flight.
And the cost of bumping 
a passenger is $800.
These numbers are just for the sake
of example.
Actual amounts vary considerably.
So here, if you don&#39;t sell
any extra tickets, you make $45,000.
If you sell 15 extras
and at least 15 people are no shows,
you make $48,750.
That&#39;s the best case.
In the worst case, everyone shows up.
15 unlucky passengers get bumped,
and the revenue will only be $36,750,
even less than if you only sold 180
tickets in the first place.
But what matters isn&#39;t just how
good or bad a scenario is financially,
but how likely it is to happen.
So how likely is each scenario?
We can find out by using
the binomial distribution.
In this example, the probability
of exactly 195 passengers boarding
is almost 0%.
The probability of exactly 184 passengers
boarding is 1.11%, and so on.
Multiply these probabilities
by the revenue for each case,
add them all up,
and subtract the sum from the earnings
by 195 sold tickets,
and you get the expected revenue
for selling 195 tickets.
By repeating this calculation
for various numbers of extra tickets,
the airline can find the one likely
to yield the highest revenue.
In this example, that&#39;s 198 tickets,
from which the airline will probably
make $48,774,
almost 4,000 more than without
overbooking.
And that&#39;s just for one flight.
Multiply that by a million flights
per airline per year,
and overbooking adds up fast.
Of course, the actual calculation
is much more complicated.
Airlines apply many factors
to create even more accurate models.
But should they?
Some argue that overbooking is unethical.
You&#39;re charging two people 
for the same resource.
Of course, if you&#39;re 100% sure 
someone won&#39;t show up,
it&#39;s fine to sell their seat.
But what if you&#39;re only 95% sure?
75%?
Is there a number that separates being
unethical from being practical?
