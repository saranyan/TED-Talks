
Ten years ago,
computer vision researchers
thought that getting a computer
to tell the difference
between a cat and a dog
would be almost impossible,
even with the significant advance
in the state of artificial intelligence.
Now we can do it at a level
greater than 99 percent accuracy.
This is called image classification --
give it an image,
put a label to that image --
and computers know
thousands of other categories as well.
I&#39;m a graduate student
at the University of Washington,
and I work on a project called Darknet,
which is a neural network framework
for training and testing
computer vision models.
So let&#39;s just see what Darknet thinks
of this image that we have.
When we run our classifier
on this image,
we see we don&#39;t just get
a prediction of dog or cat,
we actually get
specific breed predictions.
That&#39;s the level
of granularity we have now.
And it&#39;s correct.
My dog is in fact a malamute.
So we&#39;ve made amazing strides
in image classification,
but what happens
when we run our classifier
on an image that looks like this?
Well ...
We see that the classifier comes back
with a pretty similar prediction.
And it&#39;s correct,
there is a malamute in the image,
but just given this label,
we don&#39;t actually know that much
about what&#39;s going on in the image.
We need something more powerful.
I work on a problem
called object detection,
where we look at an image
and try to find all of the objects,
put bounding boxes around them
and say what those objects are.
So here&#39;s what happens
when we run a detector on this image.
Now, with this kind of result,
we can do a lot more
with our computer vision algorithms.
We see that it knows
that there&#39;s a cat and a dog.
It knows their relative locations,
their size.
It may even know some extra information.
There&#39;s a book sitting in the background.
And if you want to build a system
on top of computer vision,
say a self-driving vehicle
or a robotic system,
this is the kind
of information that you want.
You want something so that
you can interact with the physical world.
Now, when I started working
on object detection,
it took 20 seconds
to process a single image.
And to get a feel for why
speed is so important in this domain,
here&#39;s an example of an object detector
that takes two seconds
to process an image.
So this is 10 times faster
than the 20-seconds-per-image detector,
and you can see that by the time
it makes predictions,
the entire state of the world has changed,
and this wouldn&#39;t be very useful
for an application.
If we speed this up
by another factor of 10,
this is a detector running
at five frames per second.
This is a lot better,
but for example,
if there&#39;s any significant movement,
I wouldn&#39;t want a system
like this driving my car.
This is our detection system
running in real time on my laptop.
So it smoothly tracks me
as I move around the frame,
and it&#39;s robust to a wide variety
of changes in size,
pose,
forward, backward.
This is great.
This is what we really need
if we&#39;re going to build systems
on top of computer vision.

(Applause)

So in just a few years,
we&#39;ve gone from 20 seconds per image
to 20 milliseconds per image,
a thousand times faster.
How did we get there?
Well, in the past,
object detection systems
would take an image like this
and split it into a bunch of regions
and then run a classifier
on each of these regions,
and high scores for that classifier
would be considered
detections in the image.
But this involved running a classifier
thousands of times over an image,
thousands of neural network evaluations
to produce detection.
Instead, we trained a single network
to do all of detection for us.
It produces all of the bounding boxes
and class probabilities simultaneously.
With our system, instead of looking
at an image thousands of times
to produce detection,
you only look once,
and that&#39;s why we call it
the YOLO method of object detection.
So with this speed,
we&#39;re not just limited to images;
we can process video in real time.
And now, instead of just seeing
that cat and dog,
we can see them move around
and interact with each other.
This is a detector that we trained
on 80 different classes
in Microsoft&#39;s COCO dataset.
It has all sorts of things
like spoon and fork, bowl,
common objects like that.

It has a variety of more exotic things:
animals, cars, zebras, giraffes.
And now we&#39;re going to do something fun.
We&#39;re just going to go
out into the audience
and see what kind of things we can detect.
Does anyone want a stuffed animal?
There are some teddy bears out there.
And we can turn down
our threshold for detection a little bit,
so we can find more of you guys
out in the audience.
Let&#39;s see if we can get these stop signs.
We find some backpacks.
Let&#39;s just zoom in a little bit.
And this is great.
And all of the processing
is happening in real time
on the laptop.
And it&#39;s important to remember
that this is a general purpose
object detection system,
so we can train this for any image domain.
The same code that we use
to find stop signs or pedestrians,
bicycles in a self-driving vehicle,
can be used to find cancer cells
in a tissue biopsy.
And there are researchers around the globe
already using this technology
for advances in things
like medicine, robotics.
This morning, I read a paper
where they were taking a census
of animals in Nairobi National Park
with YOLO as part
of this detection system.
And that&#39;s because Darknet is open source
and in the public domain,
free for anyone to use.

(Applause)

But we wanted to make detection
even more accessible and usable,
so through a combination
of model optimization,
network binarization and approximation,
we actually have object detection
running on a phone.

(Applause)

And I&#39;m really excited because
now we have a pretty powerful solution
to this low-level computer vision problem,
and anyone can take it
and build something with it.
So now the rest is up to all of you
and people around the world
with access to this software,
and I can&#39;t wait to see what people
will build with this technology.
Thank you.

(Applause)

