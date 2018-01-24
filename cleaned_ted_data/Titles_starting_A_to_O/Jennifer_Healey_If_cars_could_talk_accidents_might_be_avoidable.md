

Translator: Joseph Geni

Reviewer: Morton Bast

Let&#39;s face it:
Driving is dangerous.
It&#39;s one of the things that we don&#39;t like to think about,
but the fact that religious icons and good luck charms
show up on dashboards around the world
betrays the fact that we know this to be true.
Car accidents are the leading cause of death
in people ages 16 to 19 in the United States --
leading cause of death --
and 75 percent of these accidents have nothing to do
with drugs or alcohol.
So what happens?
No one can say for sure, but I remember my first accident.
I was a young driver out on the highway,
and the car in front of me, I saw the brake lights go on.
I&#39;m like, &quot;Okay, all right, this guy is slowing down,
I&#39;ll slow down too.&quot;
I step on the brake.
But no, this guy isn&#39;t slowing down.
This guy is stopping, dead stop, dead stop on the highway.
It was just going 65 -- to zero?
I slammed on the brakes.
I felt the ABS kick in, and the car is still going,
and it&#39;s not going to stop, and I know it&#39;s not going to stop,
and the air bag deploys, the car is totaled,
and fortunately, no one was hurt.
But I had no idea that car was stopping,
and I think we can do a lot better than that.
I think we can transform the driving experience
by letting our cars talk to each other.
I just want you to think a little bit
about what the experience of driving is like now.
Get into your car. Close the door. You&#39;re in a glass bubble.
You can&#39;t really directly sense the world around you.
You&#39;re in this extended body.
You&#39;re tasked with navigating it down
partially-seen roadways,
in and amongst other metal giants, at super-human speeds.
Okay? And all you have to guide you are your two eyes.
Okay, so that&#39;s all you have,
eyes that weren&#39;t really designed for this task,
but then people ask you to do things like,
you want to make a lane change,
what&#39;s the first thing they ask you do?
Take your eyes off the road. That&#39;s right.
Stop looking where you&#39;re going, turn,
check your blind spot,
and drive down the road without looking where you&#39;re going.
You and everyone else. This is the safe way to drive.
Why do we do this? Because we have to,
we have to make a choice, do I look here or do I look here?
What&#39;s more important?
And usually we do a fantastic job
picking and choosing what we attend to on the road.
But occasionally we miss something.
Occasionally we sense something wrong or too late.
In countless accidents, the driver says,
&quot;I didn&#39;t see it coming.&quot;
And I believe that. I believe that.
We can only watch so much.
But the technology exists now that can help us improve that.
In the future, with cars exchanging data with each other,
we will be able to see not just three cars ahead
and three cars behind, to the right and left,
all at the same time, bird&#39;s eye view,
we will actually be able to see into those cars.
We will be able to see the velocity of the car in front of us,
to see how fast that guy&#39;s going or stopping.
If that guy&#39;s going down to zero, I&#39;ll know.
And with computation and algorithms and predictive models,
we will be able to see the future.
You may think that&#39;s impossible.
How can you predict the future? That&#39;s really hard.
Actually, no. With cars, it&#39;s not impossible.
Cars are three-dimensional objects
that have a fixed position and velocity.
They travel down roads.
Often they travel on pre-published routes.
It&#39;s really not that hard to make reasonable predictions
about where a car&#39;s going to be in the near future.
Even if, when you&#39;re in your car
and some motorcyclist comes -- bshoom! --
85 miles an hour down, lane-splitting --
I know you&#39;ve had this experience --
that guy didn&#39;t &quot;just come out of nowhere.&quot;
That guy&#39;s been on the road probably for the last half hour.

(Laughter)

Right? I mean, somebody&#39;s seen him.
Ten, 20, 30 miles back, someone&#39;s seen that guy,
and as soon as one car sees that guy
and puts him on the map, he&#39;s on the map --
position, velocity,
good estimate he&#39;ll continue going 85 miles an hour.
You&#39;ll know, because your car will know, because
that other car will have whispered something in his ear,
like, &quot;By the way, five minutes,
motorcyclist, watch out.&quot;
You can make reasonable predictions about how cars behave.
I mean, they&#39;re Newtonian objects.
That&#39;s very nice about them.
So how do we get there?
We can start with something as simple
as sharing our position data between cars,
just sharing GPS.
If I have a GPS and a camera in my car,
I have a pretty precise idea of where I am
and how fast I&#39;m going.
With computer vision, I can estimate where
the cars around me are, sort of, and where they&#39;re going.
And same with the other cars.
They can have a precise idea of where they are,
and sort of a vague idea of where the other cars are.
What happens if two cars share that data,
if they talk to each other?
I can tell you exactly what happens.
Both models improve.
Everybody wins.
Professor Bob Wang and his team
have done computer simulations of what happens
when fuzzy estimates combine, even in light traffic,
when cars just share GPS data,
and we&#39;ve moved this research out of the computer simulation
and into robot test beds that have the actual sensors

that are in cars now on these robots:
stereo cameras, GPS,
and the two-dimensional laser range finders
that are common in backup systems.
We also attach a discrete short-range communication radio,
and the robots talk to each other.
When these robots come at each other,
they track each other&#39;s position precisely,
and they can avoid each other.
We&#39;re now adding more and more robots into the mix,
and we encountered some problems.
One of the problems, when you get too much chatter,
it&#39;s hard to process all the packets, so you have to prioritize,
and that&#39;s where the predictive model helps you.
If your robot cars are all tracking the predicted trajectories,
you don&#39;t pay as much attention to those packets.
You prioritize the one guy
who seems to be going a little off course.
That guy could be a problem.
And you can predict the new trajectory.
So you don&#39;t only know that he&#39;s going off course, you know how.
And you know which drivers you need to alert to get out of the way.
And we wanted to do -- how can we best alert everyone?
How can these cars whisper, &quot;You need to get out of the way?&quot;

Well, it depends on two things:
one, the ability of the car,
and second the ability of the driver.
If one guy has a really great car,
but they&#39;re on their phone or, you know, doing something,
they&#39;re not probably in the best position
to react in an emergency.
So we started a separate line of research
doing driver state modeling.
And now, using a series of three cameras,
we can detect if a driver is looking forward,
looking away, looking down, on the phone,
or having a cup of coffee.
We can predict the accident
and we can predict who, which cars,
are in the best position to move out of the way
to calculate the safest route for everyone.
Fundamentally, these technologies exist today.
I think the biggest problem that we face
is our own willingness to share our data.
I think it&#39;s a very disconcerting notion,
this idea that our cars will be watching us,
talking about us to other cars,
that we&#39;ll be going down the road in a sea of gossip.
But I believe it can be done in a way that protects our privacy,
just like right now, when I look at your car from the outside,
I don&#39;t really know about you.
If I look at your license plate number,
I don&#39;t really know who you are.
I believe our cars can talk about us behind our backs.

(Laughter)

And I think it&#39;s going to be a great thing.
I want you to consider for a moment
if you really don&#39;t want the distracted teenager behind you
to know that you&#39;re braking,
that you&#39;re coming to a dead stop.
By sharing our data willingly,
we can do what&#39;s best for everyone.
So let your car gossip about you.
It&#39;s going to make the roads a lot safer.
Thank you.

(Applause)

