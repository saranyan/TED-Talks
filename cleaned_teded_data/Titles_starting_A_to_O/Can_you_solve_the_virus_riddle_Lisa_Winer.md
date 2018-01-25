
Your research team has found
a prehistoric virus
preserved in the permafrost
and isolated it for study.
After a late night working,
you&#39;re just closing up the lab
when a sudden earthquake hits
and knocks out the power.
As the emergency generators kick in,

an alarm confirms your worst fears:
all the sample vials have broken.
The virus is contained for now,
but unless you can destroy it,
the vents will soon open
and unleash a deadly airborne plague.
Without hesitation, you grab
your HazMat suit
and get ready to save the world.
The lab is a four by four compound
of 16 rooms
with an entrance on the northwest corner
and an exit at the southeast.
Each room is connected to the adjacent
ones by an airlock,
and the virus has been released
in every room except the entrance.
To destroy it, you must enter each
contaminated room
and pull its emergency 
self-destruct switch.
But there&#39;s a catch.
Because the security system 
is on lockdown,
once you enter the contaminated room,
you can&#39;t exit without 
activating the switch,
and once you&#39;ve done so,
you won&#39;t be able to go 
back in to that room.
You start to draw out possible
routes on a pad of paper,
but nothing seems to get you
to the exit
without missing at least one room.
So how can you destroy the virus
in every contaminated room
and survive to tell the story?
Pause here if you want 
to figure it out for yourself.

Answer in: 3

Answer in: 2

Answer in: 1
If your first instinct is to try to graph
your possible moves on a grid,
you&#39;ve got the right idea.
This puzzle is related to 
the Hamiltonian path problem
named after the 19th century Irish 
mathematician William Rowan Hamilton.
The challenge 
of the path problem
is to find whether a given graph
has a Hamiltonian path.
That&#39;s a route that visits 
every point within it exactly once.
This type of problem, classified 
as NP-complete,
is notoriously difficult when the graph
is sufficiently large.
Although any proposed solution
can be easily verified,
we have no reliable formula or shortcut
for finding one,
or determining that one exists.
And we&#39;re not even sure
if it&#39;s possible for computers
to reliably find 
such solutions, either.
This puzzle adds a twist
to the Hamiltonian path problem
in that you have to start 
and end at specific points.
But before you waste a ton of graph paper,
you should know that a true
Hamiltonian path
isn&#39;t possible with these end points.
That&#39;s because the rooms form a grid
with an even number of rooms on each side.
In any grid with that configuration,
a Hamiltonian path that starts and 
ends in opposite corners is impossible.
Here&#39;s one way of understanding why.
Consider a checkerboard grid with
an even number of squares on each side.
Every path through it will alternate
black and white.
These grids will all also have an even
total number of squares
because an even number times
and even number is even.
So a Hamiltonian path on an
even-sided grid that starts on black
will have to end on white.
And one that starts on white
will have to end on black.
However, in any grid with even
numbered sides,
opposite corners are the same color,
so it&#39;s impossible to start and end
a Hamiltonian path on opposite corners.
It seems like you&#39;re out of luck,
unless you look at the rules carefully
and notice an important exception.
It&#39;s true that once you activate
the switch in a contaminated room,
it&#39;s destroyed and you can never go back.
But there&#39;s one room 
that wasn&#39;t contaminated - the entrance.
This means that you can leave it once
without pulling the switch
and return there when you&#39;ve
destroyed either of these two rooms.
The corner room may have
been contaminated
from the airlock opening,
but that&#39;s okay
because you can destroy the entrance
after your second visit.
That return trip gives you four options
for a successful route,
and a similar set of options if you
destroyed this room first.
Congratulations. You&#39;ve prevented
an epidemic of apocalyptic proportions,
but after such a stressful episode,
you need a break.
Maybe you should take up that recent
job offer to become a traveling salesman.
