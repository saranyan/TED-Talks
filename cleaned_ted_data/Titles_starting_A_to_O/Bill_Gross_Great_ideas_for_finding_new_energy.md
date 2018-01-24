
Right when I was 15 was when
I first got interested in solar energy.
My family had moved from Fort Lee,
New Jersey to California,
from the snow to lots of heat,
and gas lines.
There was gas rationing in 1973.
The energy crisis was in full bore.
I started reading
&quot;Popular Science&quot; magazine,
and I got really excited
about the potential of solar energy
to try and solve that crisis.
I had just taken
trigonometry in high school,
I learned about the parabola
and how it could concentrate
rays of light to a single focus.
That got me very excited.
And I really felt
that there would be potential
to build some kind of thing
that could concentrate light.
So, I started this company
called Solar Devices.
And this was a company
where I built parabolas,
I took metal shop,
and I remember walking into metal shop
building parabolas and Stirling engines.
And I was building a Stirling engine
over on the lathe,
and all the motorcycle guys said,
&quot;You&#39;re building a bong, aren&#39;t you?&quot;
And I said, &quot;No, it&#39;s a Stirling engine.&quot;
But they didn&#39;t believe me.
I sold the plans for this engine
and for this dish in the back
of &quot;Popular Science&quot; magazine,
for four dollars each.
And I earned enough money
to pay for my first year of Caltech.
It was a really big excitement for me
to get into Caltech.
And at my first year at Caltech,
I continued the business.
But then, in the second year of Caltech,
they started grading.
The whole first year was pass/fail,
but the second year was graded.
I wasn&#39;t able to keep up
with the business,
and I ended up with a 25-year detour.
My dream had been to convert solar energy
at a very practical cost,
but then I had this big detour.
First, the coursework at Caltech.
Then, when I graduated from Caltech,
the IBM PC came out,
and I got addicted to the IBM PC in 1981.
And then in 1983, Lotus 1-2-3 came out,
and I was completely blown away
by Lotus 1-2-3.
I began operating my business with 1-2-3,
began writing add-ins for 1-2-3,
wrote a natural language
interface to 1-2-3.
I started an educational software company
after I joined Lotus,
and then I started Idealab
so I could have a roof
under which I could build
multiple companies in succession.
Much later -- in 2000, very recently --
the new California energy crisis --
what was purported to be
a big energy crisis -- was coming.
And I was trying to figure out
if we could build something
that would capitalize on that
and get people backup energy,
in case the crisis really came.
And I started looking at how
we could build battery backup systems
that could give people five hours,
10 hours, maybe even a full day,
or three days&#39; worth of backup power.
I&#39;m glad you heard earlier today,
batteries are unbelievably --
lack density compared to fuel.
So much more energy can be stored
with fuel than with batteries.
You&#39;d have to fill your entire
parking space of one garage space
just to give yourself
four hours of battery backup.
And I concluded, after researching
every other technology
that we could deploy for storing energy --
flywheels, different
formulations of batteries --
it just wasn&#39;t practical to store energy.
So what about making energy?
Maybe we could make energy.
I tried to figure out --
maybe solar&#39;s become attractive.
It&#39;s been 25 years since I was doing this,
let me go back and look
at what&#39;s been happening with solar cells.
And the price had gone down
from 10 dollars a watt
to about four or five dollars a watt,
but it stabilized.
And it needed to get much lower
to be cost-effective.
I studied all the new things
that had happened in solar cells,
and was looking for ways we could
make solar cells more inexpensively.
A lot of new things
are happening to do that,
but fundamentally, the process
requires a tremendous amount of energy.
Some people say it takes
more energy to make a solar cell
than it will give out in its entire life.
If we reduce the amount of energy
it takes to make the cells,
that will become more practical.
But right now, you pretty much
have to take silicon,
put it in an oven at 1600 F
for 17 hours, to make the cells.
A lot of people are working
to try and reduce that,
but I didn&#39;t have anything to contribute.
So I tried to figure out
what other way could we try
to make cost-effective solar electricity.
What if we collect the sun
with a large reflector --
like I had been thinking about
in high school,
but maybe with modern technology
we could make it cheaper --
concentrate it to a small converter,
and then the conversion device
wouldn&#39;t have to be as expensive,
because it&#39;s much smaller,
rather than solar cells,
which have to cover the entire surface
that you want to gather sun from.
This seemed practical now,
because a lot of new technologies
had come in the 25 years
since I had last looked at it.
There was a lot
of new manufacturing techniques,
not to mention really cheap
miniature motors --
brushless motors,
servomotors, stepper motors,
that are used in printers and scanners.
So, that&#39;s a breakthrough.
Of course, inexpensive microprocessors
and a very important breakthrough --
genetic algorithms.
I&#39;ll be very short on genetic algorithms.
It&#39;s a powerful way of solving intractable
problems using natural selection.
You take a problem that you can&#39;t solve
with a pure mathematical answer,
you build an evolutionary system
to try multiple tries at guessing,
you add sex --
where you take half of one solution
and half of another
and then make new mutations --
and you use natural selection
to kill off not-as-good solutions.
Usually, with a genetic algorithm
on a computer today,
with a three gigahertz processor,
you can solve many
formerly intractable problems
in just a matter of minutes.
So we tried to come up with a way
to use genetic algorithms
to create a new type of concentrator.
And I&#39;ll show you what we came up with.
Traditionally,
concentrators look like this.
Those shapes are parabolas.
They take all the parallel incoming rays
and focus it to a single spot.
They have to track the sun,
because they have to point
directly at the sun.
They usually have
a one degree acceptance angle --
once they&#39;re more than a degree off,
none of the sunlight rays
will hit the focus.
So we tried to come up
with a non-tracking collector
that would gather much more than
one degree of light, with no moving parts.
So we created a genetic algorithm
to try this out,
we made a model in Excel
of a multisurface reflector,
and an amazing thing evolved, literally,
from trying a billion cycles,
a billion different attempts,
with a fitness function that defined
how can you collect the most light,
from the most angles,
over a day, from the sun.
And this is the shape that evolved.
It&#39;s this non-tracking collector
with these six tuba-like horns,
and each of them collect light
in the following way --
if the sunlight strikes right here,
it might bounce right to the center,
the hot spot, directly,
but if the sun is off axis
and comes from the side,
it might hit two places
and take two bounces.
So for direct light,
it takes only one bounce,
for off-axis light it might take two,
and for extreme off-axis,
it might take three.
Your efficiency goes down
with more bounces,
because you lose about 10 percent
with each bounce,
but this allowed us to collect light
from a plus or minus 25-degree angle.
So, about two and a half hours of the day
we could collect
with a stationary component.
Solar cells collect light
for four and a half hours though.
On an average adjusted day,
a solar cell --
because the sun&#39;s moving across the sky,
the solar cell is going down
with a sine wave function of performance
at the off-axis angles.
It collects about four and a half
average hours of sunlight a day.
So even this, although it was great
with no moving parts --
we could achieve high
temperatures -- wasn&#39;t enough.
We needed to beat solar cells.
So we took a look at another idea.
We looked at a way to break up a parabola
into individual petals that would track.
So what you see here is 12 separate petals
that each could be controlled
with individual microprocessors
that would only cost a dollar.
You can buy a two-megahertz
microprocessor for a dollar now.
And you can buy stepper motors
that pretty much never wear out
because they have no brushes,
for a dollar.
So we can control all 12 of these petals
for under 50 dollars
and what this would allow us to do
is not have to move the focus any more,
but only move the petals.
The whole system would have
a much lower profile,
but also we could gather sunlight
for six and a half to seven hours a day.
Now that we have concentrated sunlight,
what are we going to put at the center
to convert sunlight to electricity?
So we tried to look
at all the different heat engines
that have been used in history to convert
sunlight or heat to electricity,
And one of the great ones of all time,
James Watt&#39;s steam engine of 1788
was a major breakthrough.
James Watt didn&#39;t actually invent
the steam engine, he just refined it.
But his refinements were incredible.
He added new linear
motion guides to the pistons,
he added a condenser
to cool the steam outside the cylinder,
he made the engine double-acting,
so it had double the power.
Those were major breakthroughs.
All of the improvements he made --
and it&#39;s justifiable
that our measure of energy, the watt,
today is named after him.
So we looked at this engine,
and this had some potential.
Steam engines are dangerous,
and they had tremendous impact
on the world --
industrial revolution
and ships and locomotives.
But they&#39;re usually good to be large,
so they&#39;re not good
for distributed power generation.
They&#39;re also very high-pressure,
so they&#39;re dangerous.
Another type of engine
is the hot air engine.
And the hot air engine
also was not invented by Robert Stirling,
but Robert Stirling came along in 1816
and radically improved it.
This engine, because it was
so interesting --
it only worked on air, no steam --
has led to hundreds
of creative designs over the years
that use the Stirling engine principle.
But after the Stirling engine,
Otto came along,
and also, he didn&#39;t invent
the internal combustion engine,
he just refined it.
He showed it in Paris in 1867,
and it was a major achievement
because it brought the power density
of the engine way up.
You could now get a lot more power
in a lot smaller space,
and that allowed the engine
to be used for mobile applications.
So, once you have mobility,
you&#39;re making a lot of engines
because you&#39;ve got lots of units,
as opposed to steam ships
or big factories,
so this was the engine that ended up
benefiting from mass production
where all the other engines didn&#39;t.
So, because it went into mass production,
costs were reduced,
100 years of refinement,
emissions were reduced,
tremendous production value.
There have been hundreds of millions
of internal combustion engines built,
compared to thousands
of Stirling engines built.
And not nearly as many
small steam engines being built anymore,
only large ones for big operations.
So after looking
at these three, and 47 others,
we concluded that the Stirling engine
would be the best one to use.
I want to give you a brief explanation
of how we looked at it and how it works.
So we tried to look
at the Stirling engine in a new way,
because it was practical --
weight no longer mattered
for our application.
The internal combustion engine
took off because weight mattered,
because you were moving around.
But if you&#39;re trying to generate
solar energy in a static place
the weight doesn&#39;t matter so much.
We also discovered that efficiency
doesn&#39;t matter so much
if your energy source is free.
Normally, efficiency is crucial
because the fuel cost
of your engine over its life
dwarfs the cost of the engine.
But if your fuel source is free,
then the only thing that matters
is the up-front
capital cost of the engine.
So you don&#39;t want
to optimize for efficiency,
you want to optimize for power per dollar.
So using that new twist,
with the new criteria,
we thought we could
relook at the Stirling engine,
and also bring genetic algorithms in.
Basically, Robert Stirling
didn&#39;t have Gordon Moore before him
to get us three gigahertz
of processor power.
So we took the same genetic algorithm
that we used earlier
to make that concentrator,
which didn&#39;t work out for us,
to optimize the Stirling engine,
and make its design sizes
and all of its dimensions
the exact optimum
to get the most power per dollar,
irrespective of weight,
irrespective of size,
just to get the most conversion
of solar energy,
because the sun is free.
And that&#39;s the process we took --
let me show you how the engine works.
The simplest heat engine,
or hot air engine, of all time
would be this -- take a box,
a steel canister, with a piston.
Put a flame under it, the piston moves up.
Take it off the flame
and pour water on it, or let it cool down,
the piston moves down.
That&#39;s a heat engine.
That&#39;s the most fundamental
heat engine you could have.
The problem is the efficiency
is one hundredth of one percent,
because you&#39;re heating
all the metal of the chamber
and then cooling all the metal
of the chamber each time.
And you&#39;re only getting power from the air
that&#39;s heating at the same time,
but you&#39;re wasting energy
heating and cooling the metal.
So someone came up
with a very clever idea.
Instead of heating and cooling
the whole cylinder,
what about if you put
a displacer inside --
a little thing that shuttles
the air back and forth.
You move that up and down
with a little bit of energy
but now you&#39;re only shifting the air down
to the hot end and up to the cold end.
So, now you&#39;re not alternately heating
and cooling the metal, just the air.
That allows you to get the efficiency up
from a hundredth of a percent
to about two percent.
And then Robert Stirling
came along with this genius idea,
which was, well, I&#39;m still
not heating the metal now,
with this kind of engine,
but I&#39;m still reheating all the air.
I&#39;m still heating the air every time
and cooling the air every time.
What about if I put
a thermal sponge in the middle,
in the passageway between where the air
has to move between hot and cold?
So he made fine wires, and cracked glass,
and all different kinds of materials
to be a heat sponge.
So when the air pushes up
to go from the hot end to the cold end,
it puts some heat into the sponge.
And then when the air comes back
after it&#39;s been cooled,
it picks up that heat again.
So you&#39;re reusing your energy
five or six times,
and that brings the efficiency
up to between 30 and 40 percent.
It&#39;s a little known, but brilliant,
genius invention of Robert Stirling
that takes the hot air engine
from being somewhat impractical --
like I found out when I made
the real simple version in high school --
to very potentially possible,
once you get the efficiency up,
if you can design this
to be low enough cost.
So we really set out on a path
to try and make the lowest cost possible.
We built a huge mathematical model
of how a Stirling engine works.
We applied the genetic algorithm.
We got the results from that
for the optimal engine.
We built engines --
so we built 100 different engines
over the last two years.
We measured each one, we readjusted
the model to what we measured,
and then we led that
to the current prototype.
It led to a very compact,
inexpensive engine,
and this is what the engine looks like.
Let me show you
what it looks like in real life.
So this is the engine.
It&#39;s just a small cylinder down here,
which holds the generator
inside and all the linkage,
and it&#39;s the hot cap --
the hot cylinder on the top --
this part gets hot, this part is cool,
and electricity comes out.
The exact converse is also true.
If you put electricity in,
this will get hot and this will get cold,
you get refrigeration.
So it&#39;s a complete reversible cycle,
a very efficient cycle,
and quite a simple thing to make.
So now you put the two things together.
So you have the engine.
What if you combine
the petals and the engine in the center?
The petals track and the engine
gets the concentrated sunlight,
takes that heat
and turns it into electricity.
This is what the first prototype
of our system looked like
with the petals
and the engine in the center.
This is being run out in the sun,
and now I want to show you
what the actual thing looks like.

(Applause)

Thank you.
So this is a unit with the 12 petals.
These petals cost about a dollar each --
they&#39;re lightweight,
injection-molded plastic, aluminized.
The mechanism to control
each petal is below there,
with a microprocessor on each one.
There are thermocouples on the engine --
little sensors that detect the heat
when the sunlight strikes them.
Each petal adjusts itself separately
to keep the highest temperature on it.
When the sun comes out in the morning,
the petals will seek the sun,
find it by searching
for the highest temperature.
About a minute and a half or two minutes
after the rays are striking the hot cap
the engine will be warm enough to start
and then the engine
will generate electricity
for about six and a half hours a day --
six and a half to seven hours
as the sun moves across the sky.
A critical part
that we can take advantage of
is that we have these
inexpensive microprocessors
and each of these petals is autonomous,
and each of these petals figures out
where the sun is with no user setup.
So you don&#39;t have to tell
what latitude, longitude you&#39;re at,
what your roof slope angle is,
or what orientation.
It doesn&#39;t really care.
What it does is it searches
to find the hottest spot,
it searches again a half an hour later,
a day later, a month later.
It basically figures out
where on Earth you are
by watching the direction the sun moves,
so you don&#39;t have to
actually enter anything about that.
The way the unit works is,
when the sun comes out,
the engine will start
and you get power out here.
We have AC and DC, get 12 volts DC,
so that could be used
for certain applications.
We have an inverter in there,
so you get 117 volts AC.
And you also get hot water.
The hot water&#39;s optional.
You don&#39;t have to use it,
it will cool itself.
But you can use it
to optionally heat hot water
and that brings
the efficiency up even higher
because some of the heat
that you&#39;d normally be rejecting,
you can now use as useful energy,
whether it&#39;s for a pool or hot water.
Let me show you a quick movie
of what this looks like running.
This is the first test
where we took it outside
and each of the petals
were individually seeking.
And what they do is step,
very coarsely at first,
and very finely afterward.
Once they get a temperature reading
on the thermocouple
indicating they found the sun,
they slow down and do a fine search.
Then the petals will move into position,
and the engine will start.
We&#39;ve been working on this
for the last two years.
We&#39;re very excited about the progress,
we have a long way to go though.
This is how we envision

it would be in a residential installation:
you&#39;d probably have
more than one unit on your roof.
It could be on your roof,
your backyard, or somewhere else.
You don&#39;t have to have enough units
to power your entire house,
you just save money
with each incremental one you add.
So you&#39;re still using
the grid potentially,
in this type of application,
to be your backup supply --
of course, you can&#39;t use these at night,
and you can&#39;t use these on cloudy days.
But by reducing your energy use,
pretty much at the peak times --
usually when you have
your air conditioning on,
or other times like that --
this generates the peak power
at the peak usage time,
so it&#39;s very complementary in that sense.
This is how we would envision
a residential application.
We also think there&#39;s
very big potential for energy farms,
especially in remote land
where there happens to be a lot of sun.
It&#39;s a really good combination
of those two factors.
It turns out there&#39;s a lot of powerful sun
all around the world, obviously,
but in special places
where it happens to be
relatively inexpensive to place these
and also in many more places
where there is high wind power.
So an example of that is,
here&#39;s the map of the United States.
Pretty much everywhere that&#39;s
not green or blue is a really ideal place,
but even the green or blue areas are good,
just not as good as the places
that are red, orange and yellow.
But the hot spot right around Las Vegas
and Death Valley is very good.
And is only affects the payback period,
it doesn&#39;t mean that you
couldn&#39;t use solar energy;
you could use it anywhere on Earth.
It just affects the payback period
if you&#39;re comparing
to grid-supplied electricity.
But if you don&#39;t have
grid-supplied electricity,
then the question of payback
is a different one entirely.
It&#39;s just how many watts
do you get per dollar,
and how could you benefit from that
to change your life in some way.
This is the map of the whole Earth,
and you can see
a huge swathe in the middle
where a large part of the population is,
there&#39;s tremendous chances
for solar energy.
And of course, look at Africa.
The potential to take advantage
of solar energy there is unbelievable,
and I&#39;m really excited to talk more
about finding ways we can help with that.
So, in conclusion, I would say
my journey has shown me
that you can revisit
old ideas in a new light,
and sometimes ideas
that have been discarded in the past
can be practical now if you apply
some new technology or new twists.
We believe we&#39;re getting very close
to something practical and affordable.
Our short-term goal for this
is to be half the price of solar cells
and our longer-term goal
is to be less than a five-year payback.
And at less than a five-year payback,
this becomes very economic.
So you don&#39;t have to just have
a feel-good attitude about energy
to want to have one of these.
It just makes economic sense.
Right now, solar paybacks
are between 30 and 50 years.
If you get it down below five years,
then it&#39;s almost a no-brainer
because the interest to own it --
someone else will finance it for you
and you can just make money from day one.
So that&#39;s our real powerful goal
that we&#39;re really
shooting for in the company.
Two other things that I learned
that were very surprising to me --
one was how casual we are about energy.
I was walking from the elevator over here,
and even just looking
at the stage right now --
so there&#39;s probably
20,500-watt lights right now.
There&#39;s 10,000 watts of light
pouring on the stage,
one horsepower
is 746 watts, at full power.
So there&#39;s basically 15 horses running
at full speed just to keep the stage lit.
Not to mention the 200 horses
that are probably running right now
to keep the air-conditioning going.
And it&#39;s just amazing,
walk in the elevator,
and there&#39;s lights on in the elevator.
Of course, now I&#39;m very sensitive at home
when we leave the lights on by mistake.
But, everywhere around us
we have insatiable use for energy
because it&#39;s so cheap.
And it&#39;s cheap because
we&#39;ve been subsidized by energy
that&#39;s been concentrated by the sun.
Basically, oil is
solar-energy concentrate.
It&#39;s been pounded for a billion years
with a lot of energy
to make it have all that energy
contained in it.
And we don&#39;t have a birthright
to just use that up
as fast as we are, I think.
And it would be great if we could
make our energy usage renewable,
where as we&#39;re using the energy,
we&#39;re creating it at the same pace,
and I really hope we can get there.
Thank you very much,
you&#39;ve been a great audience.
