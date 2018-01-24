

Translator: Crawford Hunt

Reviewer: Brian Greene
How many of you have used
an electronic spreadsheet,
like Microsoft Excel?
Very good.
Now, how many of you have run a business
with a spreadsheet by hand,
like my dad did for his small
printing business in Philadelphia?
A lot less.
Well, that&#39;s the way it was done
for hundreds of years.
In early 1978,
I started working on an idea
that eventually became VisiCalc.
And the next year it shipped
running on something new
called an Apple II personal computer.
You could tell that things
had really changed when, six years later,
the Wall Street Journal ran an editorial
that assumed you knew what VisiCalc was
and maybe even were using it.
Steve Jobs back in 1990
said that &quot;spreadsheets
propelled the industry forward.&quot;
&quot;VisiCalc propelled the success of Apple
more than any other single event.&quot;
On a more personal note,
Steve said, &quot;If VisiCalc had been written
for some other computer,
you&#39;d be interviewing
somebody else right now.&quot;
So, VisiCalc was instrumental in getting
personal computers on business desks.
How did it come about?
What was it? What did I go through
to make it be what it was?
Well, I first learned to program
back in 1966, when I was 15 --
just a couple months
after this photo was taken.
Few high schoolers had access
to computers in those days.
But through luck
and an awful lot of perseverance,
I was able to get
computer time around the city.
After sleeping in the mud at Woodstock,
I went off to MIT to go to college,
where to make money,
I worked on the Multics Project.
Multics was a trailblazing
interactive time-sharing system.
Have you heard of the Linux
and Unix operating systems?
They came from Multics.
I worked on the Multics versions
of what are known
as interpreted computer languages,
that are used by people
in noncomputer fields
to do their calculations
while seated at a computer terminal.
After I graduated from MIT,
I went to work for
Digital Equipment Corporation.
At DEC, I worked on software
for the new area
of computerized typesetting.
I helped newspapers
replace their reporters&#39; typewriters
with computer terminals.
I&#39;d write software
and then I&#39;d go out in the field
to places like the Kansas City Star,
where I would train users
and get feedback.
This was real-world experience
that is quite different
than what I saw in the lab at MIT.
After that, I was project leader
of the software for DEC&#39;s first
word processor, again a new field.
Like with typesetting, the important thing
was crafting a user interface
that was both natural and efficient
for noncomputer people to use.
After I was at DEC, I went
to work for a small company
that made microprocessor-based electronic
cash registers for the fast-food industry.
But I had always wanted to start
a company with my friend Bob Frankston
that I met on the Multics project at MIT.
So I decided to go back to school to learn
as much as I could about business.
And in the fall of 1977,
I entered the MBA program
at Harvard Business School.
I was one of the few
percentage of students
who had a background
in computer programming.
There&#39;s a picture of me from the yearbook
sitting in the front row.

(Laughter)

Now, at Harvard,
we learned by the case method.
We&#39;d do about three cases a day.
Cases consist of up to a few dozen pages
describing particular business situations.
They often have exhibits,
and exhibits often have words and numbers
laid out in ways that make sense
for the particular situation.
They&#39;re usually all somewhat different.
Here&#39;s my homework.
Again, numbers, words,
laid out in ways that made sense.
Lots of calculations --
we got really close to our calculators.
In fact, here&#39;s my calculator.
For Halloween, I went
dressed up as a calculator.

(Laughter)

At the beginning of each class,
the professor would call on somebody
to present the case.
What they would do is
they would explain what was going on
and then dictate information
that the professor would transcribe
onto the many motorized blackboards
in the front of the class,
and then we&#39;d have a discussion.
One of the really frustrating things
is when you&#39;ve done all your homework,
you come in the next day
only to find out that you made an error
and all of the other numbers
you did were wrong.
And you couldn&#39;t participate as well.
And we were marked by class participation.
So, sitting there with 87 other people
in the class, I got to daydream a lot.
Most programmers in those days
worked on mainframes,
building things like inventory systems,
payroll systems and bill-paying systems.
But I had worked
on interactive word processing
and on-demand personal computation.
Instead of thinking
about paper printouts and punch cards,
I imagined a magic blackboard
that if you erased one number
and wrote a new thing in,
all of the other numbers
would automatically change,
like word processing with numbers.
I imagined that my calculator
had mouse hardware on the bottom of it
and a head-up display,
like in a fighter plane.
And I could type some numbers in,
and circle it, and press the sum button.
And right in the middle of a negotiation
I&#39;d be able to get the answer.
Now I just had to take my fantasy
and turn it into reality.
My father taught me about prototyping.
He showed me mock-ups
that he&#39;d make to figure out
the placement on the page
for the things for brochures
that he was printing.
And he&#39;d use it
to get feedback from customers
and OKs before he sent the job
off to the presses.
The act of making a simple, working
version of what you&#39;re trying to build
forces you to uncover key problems.
And it lets you find solutions
to those problems much less expensively.
So I decided to build a prototype.
I went to a video terminal connected to
Harvard&#39;s time-sharing system
and got to work.
One of the first problems

that I ran into was:
How do you represent values in formulas?
Let me show you what I mean.
I thought that you would point somewhere,
type in some words,
then type in some somewhere else,
put in some numbers and some more numbers,
point where you want the answer.
And then point to the first, press minus,
point to the second,
and get the result.

The problem was:
What should I put in the formula?
It had to be something
the computer knew what to put in.
And if you looked at the formula,
you needed to know
where on the screen it referred to.
The first thing I thought was
the programmer way of doing it.
The first time you pointed to somewhere,
the computer would ask you
to type in a unique name.
It became pretty clear pretty fast that
that was going to be too tedious.
The computer had to automatically
make up the name and put it inside.
So I thought, why not make it be
the order in which you create them?
I tried that. Value 1, value 2.
Pretty quickly I saw
that if you had more than a few values
you&#39;d never remember
on the screen where things were.
Then I said, why not instead of
allowing you to put values anywhere,
I&#39;ll restrict you to a grid?
Then when you pointed to a cell,
the computer could put
the row and column in as a name.
And, if I did it like a map and put ABC
across the top and numbers along the side,
if you saw B7 in a formula,
you&#39;d know exactly
where it was on the screen.
And if you had to type the formula
in yourself, you&#39;d know what to do.
Restricting you to a grid
helped solve my problem.
It also opened up new capabilities,
like the ability to have ranges of cells.
But it wasn&#39;t too restrictive --
you could still put any value,
any formula, in any cell.
And that&#39;s the way we do it to this day,
almost 40 years later.
My friend Bob and I decided that we were
going to build this product together.
I did more work figuring out exactly
how the program was supposed to behave.
I wrote a reference card
to act as documentation.
It also helped me ensure
that the user interface I was defining
could be explained concisely
and clearly to regular people.
Bob worked in the attic of the apartment
he rented in Arlington, Massachusetts.
This is the inside of the attic.
Bob bought time on the MIT Multics System
to write computer code
on a terminal like this.
And then he would download test versions
to a borrowed Apple II
over a phone line
using an acoustic coupler,
and then we would test.
For one of these tests I prepared
for this case about the Pepsi Challenge.
Print wasn&#39;t working yet,
so I had to copy everything down.
Save wasn&#39;t working,
so every time it crashed,
I had to type in all of the formulas
again, over and over again.
The next day in class, I raised my hand;
I got called on, and I presented the case.
I did five-year projections.
I did all sorts of different scenarios.
I aced the case.
VisiCalc was already useful.
The professor said, &quot;How did you do it?&quot;
Well, I didn&#39;t want to tell him
about our secret program.

(Laughter)

So I said, &quot;I took this and added this
and multiplied by this
and subtracted that.&quot;
He said, &quot;Well,
why didn&#39;t you use a ratio?&quot;
I said, &quot;Hah! A ratio --
that wouldn&#39;t have been as exact!&quot;
What I didn&#39;t say was,
&quot;Divide isn&#39;t working yet.&quot;

(Laughter)

Eventually, though,
we did finish enough of VisiCalc
to be able to show it to the public.
My dad printed up a sample reference card
that we could use as marketing material.
In June of 1979, our publisher
announced VisiCalc to the world,
in a small booth at the giant National
Computer Conference in New York City.
The New York Times had
a humorous article about the conference.
&quot;The machines perform
what seem religious rites ...
Even as the believers gather,
the painters in the Coliseum sign room
are adding to the pantheon,
carefully lettering &#39;VISICALC&#39;
in giant black on yellow.
All hail VISICALC!&quot;

(Gasp) New York Times:
&quot;All hail VISICALC.&quot;

(Laughter)

That was the last mention
of the electronic spreadsheet
in the popular business press
for about two years.
Most people didn&#39;t get it yet.
But some did.
In October of 1979, we shipped VisiCalc.
It came in packaging
that looked like this.
And it looked like this
running on the Apple II.
And the rest, as they say, is history.
Now, there&#39;s an awful lot
more to this story,
but that&#39;ll have to wait for another day.
One thing, though, Harvard remembers.
Here&#39;s that classroom.
They put up a plaque
to commemorate what happened there.

(Applause)

But it also serves as a reminder
that you, too, should take
your unique backgrounds, skills and needs
and build prototypes to discover
and work out the key problems,
and through that, change the world.
Thank you.

(Applause)

