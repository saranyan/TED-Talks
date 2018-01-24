

I will start by posing a little bit of a challenge:
the challenge of dealing with data,
data that we have to deal with
in medical situations.
It&#39;s really a huge challenge for us.
And this is our beast of burden --
this is a Computer Tomography machine,
a CT machine.
It&#39;s a fantastic device.
It uses X-rays, X-ray beams,
that are rotating very fast around the human body.
It takes about 30 seconds to go through the whole machine
and is generating enormous amounts of information
that comes out of the machine.
So this is a fantastic machine
that we can use
for improving health care,
but as I said, it&#39;s also a challenge for us.
And the challenge is really found in this picture here.
It&#39;s the medical data explosion
that we&#39;re having right now.
We&#39;re facing this problem.
And let me step back in time.
Let&#39;s go back a few years in time and see what happened back then.
These machines that came out --
they started coming in the 1970s --
they would scan human bodies,
and they would generate about 100 images
of the human body.
And I&#39;ve taken the liberty, just for clarity,
to translate that to data slices.
That would correspond to about 50 megabytes of data,
which is small
when you think about the data we can handle today
just on normal mobile devices.
If you translate that to phone books,
it&#39;s about one meter of phone books in the pile.
Looking at what we&#39;re doing today
with these machines that we have,
we can, just in a few seconds,
get 24,000 images out of a body,
and that would correspond to about 20 gigabytes of data,
or 800 phone books,
and the pile would then be 200 meters of phone books.
What&#39;s about to happen --
and we&#39;re seeing this; it&#39;s beginning --
a technology trend that&#39;s happening right now
is that we&#39;re starting to look at time-resolved situations as well.
So we&#39;re getting the dynamics out of the body as well.
And just assume
that we will be collecting data during five seconds,
and that would correspond to one terabyte of data --
that&#39;s 800,000 books
and 16 kilometers of phone books.
That&#39;s one patient, one data set.
And this is what we have to deal with.
So this is really the enormous challenge that we have.
And already today -- this is 25,000 images.
Imagine the days
when we had radiologists doing this.
They would put up 25,000 images,
they would go like this, &quot;25,0000, okay, okay.
There is the problem.&quot;
They can&#39;t do that anymore. That&#39;s impossible.
So we have to do something that&#39;s a little bit more intelligent than doing this.
So what we do is that we put all these slices together.
Imagine that you slice your body in all these directions,
and then you try to put the slices back together again
into a pile of data, into a block of data.
So this is really what we&#39;re doing.
So this gigabyte or terabyte of data, we&#39;re putting it into this block.
But of course, the block of data
just contains the amount of X-ray
that&#39;s been absorbed in each point in the human body.
So what we need to do is to figure out a way
of looking at the things we do want to look at
and make things transparent that we don&#39;t want to look at.
So transforming the data set
into something that looks like this.
And this is a challenge.
This is a huge challenge for us to do that.
Using computers, even though they&#39;re getting faster and better all the time,
it&#39;s a challenge to deal with gigabytes of data,
terabytes of data
and extracting the relevant information.
I want to look at the heart.
I want to look at the blood vessels. I want to look at the liver.
Maybe even find a tumor,
in some cases.
So this is where this little dear comes into play.
This is my daughter.
This is as of 9 a.m. this morning.
She&#39;s playing a computer game.
She&#39;s only two years old,
and she&#39;s having a blast.
So she&#39;s really the driving force
behind the development of graphics-processing units.
As long as kids are playing computer games,
graphics is getting better and better and better.
So please go back home, tell your kids to play more games,
because that&#39;s what I need.
So what&#39;s inside of this machine
is what enables me to do the things that I&#39;m doing
with the medical data.
So really what I&#39;m doing is using these fantastic little devices.
And you know, going back
maybe 10 years in time
when I got the funding
to buy my first graphics computer --
it was a huge machine.
It was cabinets of processors and storage and everything.
I paid about one million dollars for that machine.
That machine is, today, about as fast as my iPhone.
So every month there are new graphics cards coming out,
and here is a few of the latest ones from the vendors --
NVIDIA, ATI, Intel is out there as well.
And you know, for a few hundred bucks
you can get these things and put them into your computer,
and you can do fantastic things with these graphics cards.
So this is really what&#39;s enabling us
to deal with the explosion of data in medicine,
together with some really nifty work
in terms of algorithms --
compressing data,
extracting the relevant information that people are doing research on.
So I&#39;m going to show you a few examples of what we can do.
This is a data set that was captured using a CT scanner.
You can see that this is a full data [set].
It&#39;s a woman. You can see the hair.
You can see the individual structures of the woman.
You can see that there is [a] scattering of X-rays
on the teeth, the metal in the teeth.
That&#39;s where those artifacts are coming from.
But fully interactively
on standard graphics cards on a normal computer,
I can just put in a clip plane.
And of course all the data is inside,
so I can start rotating, I can look at it from different angles,
and I can see that this woman had a problem.
She had a bleeding up in the brain,
and that&#39;s been fixed with a little stent,
a metal clamp that&#39;s tightening up the vessel.
And just by changing the functions,
then I can decide what&#39;s going to be transparent
and what&#39;s going to be visible.
I can look at the skull structure,
and I can see that, okay, this is where they opened up the skull on this woman,
and that&#39;s where they went in.
So these are fantastic images.
They&#39;re really high resolution,
and they&#39;re really showing us what we can do
with standard graphics cards today.
Now we have really made use of this,
and we have tried to squeeze a lot of data
into the system.
And one of the applications that we&#39;ve been working on --
and this has gotten a little bit of traction worldwide --
is the application of virtual autopsies.
So again, looking at very, very large data sets,
and you saw those full-body scans that we can do.
We&#39;re just pushing the body through the whole CT scanner,
and just in a few seconds we can get a full-body data set.
So this is from a virtual autopsy.
And you can see how I&#39;m gradually peeling off.
First you saw the body bag that the body came in,
then I&#39;m peeling off the skin -- you can see the muscles --
and eventually you can see the bone structure of this woman.
Now at this point, I would also like to emphasize
that, with the greatest respect
for the people that I&#39;m now going to show --
I&#39;m going to show you a few cases of virtual autopsies --
so it&#39;s with great respect for the people
that have died under violent circumstances
that I&#39;m showing these pictures to you.
In the forensic case --
and this is something
that ... there&#39;s been approximately 400 cases so far
just in the part of Sweden that I come from
that has been undergoing virtual autopsies
in the past four years.
So this will be the typical workflow situation.
The police will decide --
in the evening, when there&#39;s a case coming in --
they will decide, okay, is this a case where we need to do an autopsy?
So in the morning, in between six and seven in the morning,
the body is then transported inside of the body bag
to our center
and is being scanned through one of the CT scanners.
And then the radiologist, together with the pathologist
and sometimes the forensic scientist,
looks at the data that&#39;s coming out,
and they have a joint session.
And then they decide what to do in the real physical autopsy after that.
Now looking at a few cases,
here&#39;s one of the first cases that we had.
You can really see the details of the data set.
It&#39;s very high-resolution,
and it&#39;s our algorithms that allow us
to zoom in on all the details.
And again, it&#39;s fully interactive,
so you can rotate and you can look at things in real time
on these systems here.
Without saying too much about this case,
this is a traffic accident,
a drunk driver hit a woman.
And it&#39;s very, very easy to see the damages on the bone structure.
And the cause of death is the broken neck.
And this women also ended up under the car,
so she&#39;s quite badly beaten up
by this injury.
Here&#39;s another case, a knifing.
And this is also again showing us what we can do.
It&#39;s very easy to look at metal artifacts
that we can show inside of the body.
You can also see some of the artifacts from the teeth --
that&#39;s actually the filling of the teeth --
but because I&#39;ve set the functions to show me metal
and make everything else transparent.
Here&#39;s another violent case. This really didn&#39;t kill the person.
The person was killed by stabs in the heart,
but they just deposited the knife
by putting it through one of the eyeballs.
Here&#39;s another case.
It&#39;s very interesting for us
to be able to look at things like knife stabbings.
Here you can see that knife went through the heart.
It&#39;s very easy to see how air has been leaking
from one part to another part,
which is difficult to do in a normal, standard, physical autopsy.
So it really, really helps
the criminal investigation
to establish the cause of death,
and in some cases also directing the investigation in the right direction
to find out who the killer really was.
Here&#39;s another case that I think is interesting.
Here you can see a bullet
that has lodged just next to the spine on this person.
And what we&#39;ve done is that we&#39;ve turned the bullet into a light source,
so that bullet is actually shining,
and it makes it really easy to find these fragments.
During a physical autopsy,
if you actually have to dig through the body to find these fragments,
that&#39;s actually quite hard to do.
One of the things that I&#39;m really, really happy
to be able to show you here today
is our virtual autopsy table.
It&#39;s a touch device that we have developed
based on these algorithms, using standard graphics GPUs.
It actually looks like this,
just to give you a feeling for what it looks like.
It really just works like a huge iPhone.
So we&#39;ve implemented
all the gestures you can do on the table,
and you can think of it as an enormous touch interface.
So if you were thinking of buying an iPad,
forget about it. This is what you want instead.
Steve, I hope you&#39;re listening to this, all right.
So it&#39;s a very nice little device.
So if you have the opportunity, please try it out.
It&#39;s really a hands-on experience.
So it gained some traction, and we&#39;re trying to roll this out
and trying to use it for educational purposes,
but also, perhaps in the future,
in a more clinical situation.
There&#39;s a YouTube video that you can download and look at this,
if you want to convey the information to other people
about virtual autopsies.
Okay, now that we&#39;re talking about touch,
let me move on to really &quot;touching&quot; data.
And this is a bit of science fiction now,
so we&#39;re moving into really the future.
This is not really what the medical doctors are using right now,
but I hope they will in the future.
So what you&#39;re seeing on the left is a touch device.
It&#39;s a little mechanical pen
that has very, very fast step motors inside of the pen.
And so I can generate a force feedback.
So when I virtually touch data,
it will generate forces in the pen, so I get a feedback.
So in this particular situation,
it&#39;s a scan of a living person.
I have this pen, and I look at the data,
and I move the pen towards the head,
and all of a sudden I feel resistance.
So I can feel the skin.
If I push a little bit harder, I&#39;ll go through the skin,
and I can feel the bone structure inside.
If I push even harder, I&#39;ll go through the bone structure,
especially close to the ear where the bone is very soft.
And then I can feel the brain inside, and this will be the slushy like this.
So this is really nice.
And to take that even further, this is a heart.
And this is also due to these fantastic new scanners,
that just in 0.3 seconds,
I can scan the whole heart,
and I can do that with time resolution.
So just looking at this heart,
I can play back a video here.
And this is Karljohan, one of my graduate students
who&#39;s been working on this project.
And he&#39;s sitting there in front of the Haptic device, the force feedback system,
and he&#39;s moving his pen towards the heart,
and the heart is now beating in front of him,
so he can see how the heart is beating.
He&#39;s taken the pen, and he&#39;s moving it towards the heart,
and he&#39;s putting it on the heart,
and then he feels the heartbeats from the real living patient.
Then he can examine how the heart is moving.
He can go inside, push inside of the heart,
and really feel how the valves are moving.
And this, I think, is really the future for heart surgeons.
I mean it&#39;s probably the wet dream for a heart surgeon
to be able to go inside of the patient&#39;s heart
before you actually do surgery,
and do that with high-quality resolution data.
So this is really neat.
Now we&#39;re going even further into science fiction.
And we heard a little bit about functional MRI.
Now this is really an interesting project.
MRI is using magnetic fields
and radio frequencies
to scan the brain, or any part of the body.
So what we&#39;re really getting out of this
is information of the structure of the brain,
but we can also measure the difference
in magnetic properties of blood that&#39;s oxygenated
and blood that&#39;s depleted of oxygen.
That means that it&#39;s possible
to map out the activity of the brain.
So this is something that we&#39;ve been working on.
And you just saw Motts the research engineer, there,
going into the MRI system,
and he was wearing goggles.
So he could actually see things in the goggles.
So I could present things to him while he&#39;s in the scanner.
And this is a little bit freaky,
because what Motts is seeing is actually this.
He&#39;s seeing his own brain.
So Motts is doing something here,
and probably he is going like this with his right hand,
because the left side is activated
on the motor cortex.
And then he can see that at the same time.
These visualizations are brand new.
And this is something that we&#39;ve been researching for a little while.
This is another sequence of Motts&#39; brain.
And here we asked Motts to calculate backwards from 100.
So he&#39;s going &quot;100, 97, 94.&quot;
And then he&#39;s going backwards.
And you can see how the little math processor is working up here in his brain
and is lighting up the whole brain.
Well this is fantastic. We can do this in real time.
We can investigate things. We can tell him to do things.
You can also see that his visual cortex
is activated in the back of the head,
because that&#39;s where he&#39;s seeing, he&#39;s seeing his own brain.
And he&#39;s also hearing our instructions
when we tell him to do things.
The signal is really deep inside of the brain as well,
and it&#39;s shining through,
because all of the data is inside this volume.
And in just a second here you will see --
okay, here. Motts, now move your left foot.
So he&#39;s going like this.
For 20 seconds he&#39;s going like that,
and all of a sudden it lights up up here.
So we&#39;ve got motor cortex activation up there.
So this is really, really nice,
and I think this is a great tool.
And connecting also with the previous talk here,
this is something that we could use as a tool
to really understand
how the neurons are working, how the brain is working,
and we can do this with very, very high visual quality
and very fast resolution.
Now we&#39;re also having a bit of fun at the center.
So this is a CAT scan -- Computer Aided Tomography.
So this is a lion from the local zoo
outside of Norrkoping in Kolmarden, Elsa.
So she came to the center,
and they sedated her
and then put her straight into the scanner.
And then, of course, I get the whole data set from the lion.
And I can do very nice images like this.
I can peel off the layer of the lion.
I can look inside of it.
And we&#39;ve been experimenting with this.
And I think this is a great application
for the future of this technology,
because there&#39;s very little known about the animal anatomy.
What&#39;s known out there for veterinarians is kind of basic information.
We can scan all sorts of things,
all sorts of animals.
The only problem is to fit it into the machine.
So here&#39;s a bear.
It was kind of hard to get it in.
And the bear is a cuddly, friendly animal.
And here it is. Here is the nose of the bear.
And you might want to cuddle this one,
until you change the functions and look at this.
So be aware of the bear.
So with that,
I&#39;d like to thank all the people
who have helped me to generate these images.
It&#39;s a huge effort that goes into doing this,
gathering the data and developing the algorithms,
writing all the software.
So, some very talented people.
My motto is always, I only hire people that are smarter than I am
and most of these are smarter than I am.
So thank you very much.

(Applause)

