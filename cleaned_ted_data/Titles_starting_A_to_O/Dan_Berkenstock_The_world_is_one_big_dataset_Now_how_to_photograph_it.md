
Five years ago, I was a Ph.D. student
living two lives.
In one, I used NASA supercomputers
to design next-generation spacecraft,
and in the other I was a data scientist
looking for potential smugglers
of sensitive nuclear technologies.
As a data scientist, I did a lot of analyses,
mostly of facilities,
industrial facilities around the world.
And I was always looking for a better canvas
to tie these all together.
And one day, I was thinking about how
all data has a location,
and I realized that the answer
had been staring me in the face.
Although I was a satellite engineer,
I hadn&#39;t thought about using satellite imagery
in my work.
Now, like most of us, I&#39;d been online,
I&#39;d see my house, so I thought,
I&#39;ll hop in there and I&#39;ll start looking up
some of these facilities.
And what I found really surprised me.
The pictures that I was finding
were years out of date,
and because of that,
it had relatively little relevance
to the work that I was doing today.
But I was intrigued.
I mean, satellite imagery is pretty amazing stuff.
There are millions and millions of sensors
surrounding us today,
but there&#39;s still so much we
don&#39;t know on a daily basis.
How much oil is stored in all of China?
How much corn is being produced?
How many ships are in all of our world&#39;s ports?
Now, in theory, all of these questions
could be answered by imagery,
but not if it&#39;s old.
And if this data was so valuable,
then how come I couldn&#39;t get my hands
on more recent pictures?
So the story begins over 50 years ago
with the launch of the first generation
of U.S. government photo reconnaissance satellites.
And today, there&#39;s a handful
of the great, great grandchildren
of these early Cold War machines
which are now operated by private companies
and from which the vast majority of satellite imagery
that you and I see on a daily basis comes.
During this period, launching things into space,
just the rocket to get the satellite up there,
has cost hundreds of millions of dollars each,
and that&#39;s created tremendous pressure
to launch things infrequently
and to make sure that when you do,
you cram as much functionality in there as possible.
All of this has only made satellites
bigger and bigger and bigger
and more expensive,
now nearly a billion, with a b, dollars per copy.
Because they are so expensive,
there aren&#39;t very many of them.
Because there aren&#39;t very many of them,
the pictures that we see on a daily basis
tend to be old.
I think a lot of people actually
understand this anecdotally,
but in order to visualize just how sparsely
our planet is collected,
some friends and I put together a dataset
of the 30 million pictures that have been gathered
by these satellites between 2000 and 2010.
As you can see in blue, huge areas of our world
are barely seen, less than once a year,
and even the areas that are seen most frequently,
those in red, are seen at best once a quarter.
Now as aerospace engineering grad students,
this chart cried out to us as a challenge.
Why do these things have to be so expensive?
Does a single satellite really have to cost
the equivalent of three 747 jumbo jets?
Wasn&#39;t there a way to build a smaller,
simpler, new satellite design that could enable
more timely imaging?
I realize that it does sound a little bit crazy
that we were going to go out and just
begin designing satellites,
but fortunately we had help.
In the late 1990s, a couple of professors
proposed a concept for radically reducing the price
of putting things in space.
This was hitchhiking small satellites
alongside much larger satellites.
This dropped the cost of putting objects up there
by over a factor of 100,
and suddenly we could afford to experiment,
to take a little bit of risk,
and to realize a lot of innovation.
And a new generation of engineers and scientists,
mostly out of universities,
began launching these very small,
breadbox-sized satellites called CubeSats.
And these were built with electronics obtained
from RadioShack instead of Lockheed Martin.
Now it was using the lessons
learned from these early missions
that my friends and I began a series of sketches
of our own satellite design.
And I can&#39;t remember a specific day
where we made a conscious decision
that we were actually going to
go out and build these things,
but once we got that idea in our minds
of the world as a dataset,
of being able to capture millions of data points
on a daily basis describing the global economy,
of being able to unearth billions of connections
between them that had never before been found,
it just seemed boring
to go work on anything else.
And so we moved into a cramped,
windowless office in Palo Alto,
and began working to take our design
from the drawing board into the lab.
The first major question we had to tackle
was just how big to build this thing.
In space, size drives cost,
and we had worked with these very small,
breadbox-sized satellites in school,
but as we began to better
understand the laws of physics,
we found that the quality of pictures
those satellites could take was very limited,
because the laws of physics dictate
that the best picture you
can take through a telescope
is a function of the diameter of that telescope,
and these satellites had a very small,
very constrained volume.
And we found that the best picture we would
have been able to get looked something like this.
Although this was the low-cost option,
quite frankly it was just too blurry
to see the things that make
satellite imagery valuable.
So about three or four weeks later,
we met a group of engineers randomly
who had worked on the first
private imaging satellite ever developed,
and they told us that back in the 1970s,
the U.S. government had found a powerful
optimal tradeoff --
that in taking pictures at right
about one meter resolution,
being able to see objects one meter in size,
they had found that they could not
just get very high-quality images,
but get a lot of them at an affordable price.
From our own computer simulations,
we quickly found that one meter really was
the minimum viable product
to be able to see the drivers of our global economy,
for the first time, being able to count
the ships and cars and shipping
containers and trucks
that move around our world on a daily basis,
while conveniently still not
being able to see individuals.
We had found our compromise.
We would have to build something larger
than the original breadbox,
now more like a mini-fridge,
but we still wouldn&#39;t have to build a pickup truck.
So now we had our constraint.
The laws of physics dictated
the absolute minimum-sized
telescope that we could build.
What came next was making the rest of the satellite
as small and as simple as possible,
basically a flying telescope with four walls
and a set of electronics smaller than a phone book
that used less power than a 100 watt lightbulb.
The big challenge became actually taking
the pictures through that telescope.
Traditional imaging satellites use a line scanner,
similar to a Xerox machine,
and as they traverse the Earth, they take pictures,
scanning row by row by row
to build the complete image.
Now people use these because they get a lot of light,
which means less of the noise you see
in a low-cost cell phone image.
The problem with them is they require
very sophisticated pointing.
You have to stay focused on a 50-centimeter target
from over 600 miles away
while moving at more than
seven kilometers a second,
which requires an awesome degree of complexity.
So instead, we turned to a new
generation of video sensors,
originally created for use in night vision goggles.
Instead of taking a single, high quality image,
we could take a videostream
of individually noisier frames,
but then we could recombine
all of those frames together
into very high-quality images
using sophisticated pixel processing techniques
here on the ground,
at a cost of one one hundredth a traditional system.
And we applied this technique
to many of the other systems on the satellite as well,
and day by day, our design evolved
from CAD to prototypes
to production units.
A few short weeks ago,
we packed up SkySat 1,
put our signatures on it,
and waved goodbye for the last time on Earth.
Today, it&#39;s sitting in its final launch configuration
ready to blast off in a few short weeks.
And soon, we&#39;ll turn our attention to launching
a constellation of 24 or more of these satellites
and beginning to build the scalable analytics
that will allow us to unearth the insights
in the petabytes of data we will collect.
So why do all of this? Why build these satellites?
Well, it turns out imaging satellites
have a unique ability to provide global transparency,
and providing that transparency on a timely basis
is simply an idea whose time has come.
We see ourselves as pioneers of a new frontier,
and beyond economic data,
unlocking the human story, moment by moment.
For a data scientist
that just happened to go to space camp as a kid,
it just doesn&#39;t get much better than that.
Thank you.

(Applause)

