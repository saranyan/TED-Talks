
The idea behind the Stuxnet computer worm
is actually quite simple.
We don&#39;t want Iran to get the bomb.
Their major asset for developing nuclear weapons
is the Natanz uranium enrichment facility.
The gray boxes that you see,
these are real-time control systems.
Now if we manage to compromise these systems
that control drive speeds and valves,
we can actually cause a lot of problems
with the centrifuge.
The gray boxes don&#39;t run Windows software;
they are a completely different technology.
But if we manage
to place a good Windows virus
on a notebook
that is used by a maintenance engineer
to configure this gray box,
then we are in business.
And this is the plot behind Stuxnet.
So we start with a Windows dropper.
The payload goes onto the gray box,
damages the centrifuge,
and the Iranian nuclear program is delayed --
mission accomplished.
That&#39;s easy, huh?
I want to tell you how we found that out.
When we started our research on Stuxnet six months ago,
it was completely unknown what the purpose of this thing was.
The only thing that was known
is it&#39;s very, very complex on the Windows part, the dropper part,
used multiple zero-day vulnerabilities.
And it seemed to want to do something
with these gray boxes, these real-time control systems.
So that got our attention,
and we started a lab project
where we infected our environment with Stuxnet
and checked this thing out.
And then some very funny things happened.
Stuxnet behaved like a lab rat
that didn&#39;t like our cheese --
sniffed, but didn&#39;t want to eat.
Didn&#39;t make sense to me.
And after we experimented with different flavors of cheese,
I realized, well, this is a directed attack.
It&#39;s completely directed.
The dropper is prowling actively
on the gray box
if a specific configuration is found,
and even if the actual program code that it&#39;s trying to infect
is actually running on that target.
And if not, Stuxnet does nothing.
So that really got my attention,
and we started to work on this
nearly around the clock,
because I thought, &quot;Well, we don&#39;t know what the target is.
It could be, let&#39;s say for example,
a U.S. power plant,
or a chemical plant in Germany.
So we better find out what the target is soon.&quot;
So we extracted and decompiled
the attack code,
and we discovered that it&#39;s structured in two digital bombs --
a smaller one and a bigger one.
And we also saw that they are very professionally engineered
by people who obviously had all insider information.
They knew all the bits and bites
that they had to attack.
They probably even know the shoe size of the operator.
So they know everything.
And if you have heard that the dropper of Stuxnet
is complex and high-tech,

let me tell you this:
the payload is rocket science.
It&#39;s way above everything
that we have ever seen before.
Here you see a sample of this actual attack code.
We are talking about --
around about 15,000 lines of code.
Looks pretty much like old-style assembly language.
And I want to tell you how we were able
to make sense out of this code.
So what we were looking for is, first of all, system function calls,
because we know what they do.
And then we were looking for timers and data structures
and trying to relate them to the real world --
to potential real world targets.
So we do need target theories
that we can prove or disprove.
In order to get target theories,
we remember
that it&#39;s definitely hardcore sabotage,
it must be a high-value target
and it is most likely located in Iran,
because that&#39;s where most of the infections had been reported.
Now you don&#39;t find several thousand targets in that area.
It basically boils down
to the Bushehr nuclear power plant
and to the Natanz fuel enrichment plant.
So I told my assistant,
&quot;Get me a list of all centrifuge and power plant experts from our client base.&quot;
And I phoned them up and picked their brain
in an effort to match their expertise
with what we found in code and data.
And that worked pretty well.
So we were able to associate
the small digital warhead
with the rotor control.
The rotor is that moving part within the centrifuge,
that black object that you see.
And if you manipulate the speed of this rotor,
you are actually able to crack the rotor
and eventually even have the centrifuge explode.
What we also saw
is that the goal of the attack
was really to do it slowly and creepy --
obviously in an effort
to drive maintenance engineers crazy,
that they would not be able to figure this out quickly.
The big digital warhead -- we had a shot at this
by looking very closely
at data and data structures.
So for example, the number 164
really stands out in that code;
you can&#39;t overlook it.
I started to research scientific literature
on how these centrifuges
are actually built in Natanz
and found they are structured
in what is called a cascade,
and each cascade holds 164 centrifuges.
So that made sense, that was a match.
And it even got better.
These centrifuges in Iran
are subdivided into 15, what is called, stages.
And guess what we found in the attack code?
An almost identical structure.
So again, that was a real good match.
And this gave us very high confidence for what we were looking at.
Now don&#39;t get me wrong here, it didn&#39;t go like this.
These results have been obtained
over several weeks of really hard labor.
And we often went into just a dead end
and had to recover.
Anyway, so we figured out
that both digital warheads
were actually aiming at one and the same target,
but from different angles.
The small warhead is taking one cascade,
and spinning up the rotors and slowing them down,
and the big warhead
is talking to six cascades
and manipulating valves.
So in all, we are very confident
that we have actually determined what the target is.
It is Natanz, and it is only Natanz.
So we don&#39;t have to worry
that other targets
might be hit by Stuxnet.
Here&#39;s some very cool stuff that we saw --
really knocked my socks off.
Down there is the gray box,
and on the top you see the centrifuges.
Now what this thing does
is it intercepts the input values from sensors --
so for example, from pressure sensors
and vibration sensors --
and it provides legitimate program code,
which is still running during the attack,
with fake input data.
And as a matter of fact, this fake input data
is actually prerecorded by Stuxnet.
So it&#39;s just like from the Hollywood movies
where during the heist,
the observation camera is fed with prerecorded video.
That&#39;s cool, huh?
The idea here is obviously
not only to fool the operators in the control room.
It actually is much more dangerous and aggressive.
The idea
is to circumvent a digital safety system.
We need digital safety systems
where a human operator could not act quick enough.
So for example, in a power plant,
when your big steam turbine gets too over speed,
you must open relief valves within a millisecond.
Obviously, this cannot be done by a human operator.
So this is where we need digital safety systems.
And when they are compromised,
then real bad things can happen.
Your plant can blow up.
And neither your operators nor your safety system will notice it.
That&#39;s scary.
But it gets worse.
And this is very important, what I&#39;m going to say.

Think about this:
this attack is generic.
It doesn&#39;t have anything to do, in specifics,
with centrifuges,
with uranium enrichment.
So it would work as well, for example,
in a power plant
or in an automobile factory.
It is generic.
And you don&#39;t have -- as an attacker --
you don&#39;t have to deliver this payload
by a USB stick,
as we saw it in the case of Stuxnet.
You could also use conventional worm technology for spreading.
Just spread it as wide as possible.
And if you do that,
what you end up with
is a cyber weapon of mass destruction.
That&#39;s the consequence
that we have to face.
So unfortunately,
the biggest number of targets for such attacks
are not in the Middle East.
They&#39;re in the United States and Europe and in Japan.
So all of the green areas,
these are your target-rich environments.
We have to face the consequences,
and we better start to prepare right now.
Thanks.

(Applause)


Chris Anderson: I&#39;ve got a question.
Ralph, it&#39;s been quite widely reported
that people assume that Mossad
is the main entity behind this.
Is that your opinion?

Ralph Langner: Okay, you really want to hear that?
Yeah. Okay.
My opinion is that the Mossad is involved,
but that the leading force is not Israel.
So the leading force behind that
is the cyber superpower.
There is only one,
and that&#39;s the United States --
fortunately, fortunately.
Because otherwise,
our problems would even be bigger.

CA: Thank you for scaring the living daylights out of us. Thank you, Ralph.

(Applause)

