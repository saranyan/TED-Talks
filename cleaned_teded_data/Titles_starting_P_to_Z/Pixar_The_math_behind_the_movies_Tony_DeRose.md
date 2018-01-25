
At Pixar, we&#39;re all about telling stories,
but one story that hasn&#39;t been told very much
is the huge degree to which math is used
in the production of our films.
The math that you&#39;re learning in
middle school and high school
is used all the time at Pixar.
So, let&#39;s start with a very simple example.
Anybody recognize this guy? (Cheers)
Yeah, so this is Woody from Toy Story,
and let&#39;s ask Woody to, say, walk across the stage
from, say, left to right, just like that.
So, believe it or not, you just saw a ton of mathematics.
Where is it?
Well, to explain that,
it&#39;s important to understand
that artists and designers think in terms of
shape and images
but computers think in terms of numbers and equations.
So, to bridge those two worlds
we use a mathematical concept called
coordinate geometry, right?
That is, we lay down a coordinate system
with x describing how far something is to the right
and y describing how high something is.
So, with these coordinates we can describe
where Woody is at any instant in time.
For instance, if we know the coordinates of
the lower left corner of that image,
then we know where the rest of the image is.
And in that little sliding animation we saw a second ago,
that motion we call translation,
the x coordinate started with a value of one,
and it ended with a value of about five.
So, if we want to write that in mathematics,
we see that the x at the end is four bigger
than x at the start.
So, in other words, the mathematics of translation
is addition.
Alright?
How about scaling?
That is making something bigger or smaller.
Any guesses as to what the mathematics of scaling might be?
Dilation, multiplication, exactly.
If you&#39;re going to make something twice as big,
you need to mulitply the x and the y coordinates
all by two.
So, this shows us that the mathematics of scaling
is mulitiplication.
Okay?
How about this one?
How about rotation? Alright, spinning around.
The mathematics of rotation is trigonometry.
So, here&#39;s an equation that expresses that.
It looks a little scary at first.
You&#39;ll probably get this in eighth or ninth grade.
If you find yourselves sitting in trigonometry class
wondering when you&#39;re ever going to need this stuff,
just remember that any time you see anything rotate
in one of our films,
there&#39;s trigonometry at work underneath.
I first fell in love with mathematics in seventh grade.
Any seventh graders? A few of you? Yeah.
My seventh grade science teacher showed me
how to use trigonometry to compute
how high the rockets that I was building was going.
I just thought that was amazing,
and I&#39;ve been enamored with math ever since.
So, this is kind of old mathematics.
Mathematics that&#39;s been known and, you know,
developed by the old dead Greek guys.
And there&#39;s a myth out there that all the interesting
mathematics has already been figured out,
in fact all of mathematics has been figured out.
But the real story is that new mathematics
is being created all the time.
And some of it is being created at Pixar.
So, I&#39;d like to give you an example of that.
So, here are some characters

from some of our early films:
Finding Nemo, Monsters Inc. and Toy Story 2.
Anybody know who the blue character in the upper left is?
It&#39;s Dory. Okay, that was easy.
Here&#39;s a little harder one.
Anybody know who&#39;s the character in the lower right?
Al McWhiggin from Al&#39;s Toy Barn, exactly.
The thing to notice about these characters
is they&#39;re really complicated.
Those shapes are really complicated.
In fact, the toy cleaner, I have an example,
the toy cleaner there in the middle,
here&#39;s his hand.
You can imagine how fun it was to bring this
through airport security.
His hand is a really complicated shape.
It&#39;s not just a bunch of spheres and cylinders stuck together, right?
And not only is it complicated,
but it has to move in complicated ways.
So, I&#39;d like to tell you how we do that,
and to do that I need to tell you about midpoints.
So, here&#39;s a couple of points, A and B,
and the line segment between them.
We&#39;re going to start out first in two dimensions.
The midpoint, M, is the point
that splits that line segment in the middle, right?
So, that&#39;s the geometry.
To make equations and numbers,
we again introduce a coordinate system,
and if we know the coordinates of A and B,
we can easily compute the coordinates of M
just by averaging.
You now know enough to work at Pixar.
Let me show you.
So, I&#39;m going to do something slightly terrifying
and move to a live demo here.
So, what I have is a four-point polygon here,
and it&#39;s going to be my job
to make a smooth curve out of this thing.
And I&#39;m going to do it just using the idea of midpoints.
So, the first thing I&#39;m going to do
is an operation I&#39;ll call split,
which adds midpoints to all those edges.
So, I went from four points to eight points,
but it&#39;s no smoother.
I&#39;m going to make it a little bit smoother
by moving all of these points from where they are now
to the midpoint of their clockwise neighbor.
So, let me animate that for you.
I&#39;m going to call that the averaging step.
So, now I&#39;ve got eight points,
they&#39;re a little bit smoother,
my job is to make a smooth curve,
so what do I do?
Do it again. Split and average.
So, now I&#39;ve got sixteen points.
I&#39;m going to put those two steps,
split and average, together into something
I&#39;ll call subdivide,
which just means split and then average.
So, now I&#39;ve got 32 points.
If that&#39;s not smooth enough, I&#39;ll do more.
I&#39;ll get 64 points.
Do you see a smooth curve appearing here from
those original points?
And that&#39;s how we create the shapes
of our charcters.
But remember, I said a moment ago
it&#39;s not enough just to know the static shape,
the fixed shape.
We need to animate it.
And to animate these curves,
the cool thing about subdivision.
Did you see the aliens in Toy Story?
You know that sound they make,
&quot;Ooh&quot;? Ready?
So, the way we animate these curves
is simply by animating the original four points.
&quot;Ooh.&quot;
Alright, I think that&#39;s pretty cool,
and if you don&#39;t, the door is there,
it doesn&#39;t get any better than that, so.
This idea of splitting and averaging
also holds for surfaces.
So, I&#39;ll split, and I&#39;ll average.
I&#39;ll split, and I&#39;ll average.
Put those together into subdivide,
and this how we actually create the shapes
of all of our surface characters in three dimensions.
So, this idea of subdivision
was first used in a short film in 1997
called Geri&#39;s Game.
And Geri actually made a cameo apperance
in Toy Story 2 as the toy cleaner.
Each of his hands
was the first time we ever used subdivision.
So, each hand was a subdivision surface,
his face was a subdivision surface,
so was his jacket.
Here&#39;s Geri&#39;s hand before subdivision,
and here&#39;s Geri&#39;s hand after subdivision,
so subdivision just goes in and smooths out
all those facets,
and creates the beautiful surfaces
that you see on the screen and in the theaters.
Since that time, we&#39;ve built all of our characters this way.
So, here&#39;s Merida, the lead character from Brave.
Her dress was a subdivision surface,
her hands, her face.
The faces and hands of all the clansman
were subdivision surfaces.
Today we&#39;ve seen how addition, multiplication,
trigonometry and geometry play a roll in our films.
Given a little more time,
I could show you how linear algebra,
differential calculus, integral calculus
also play a roll.
The main thing I want you to go away with today is
to just remember that all the math that you&#39;re learning
in high school and actually up through sophomore college
we use all the time, everyday, at Pixar. Thanks.
