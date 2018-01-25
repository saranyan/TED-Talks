
I&#39;m a computer science professor and my
area of expertise is computer and
information security when I was in
graduate school I had the opportunity to
overhear my grandmother describing to
one of her fellow senior citizens what I
did for a living
apparently I was in charge of making
sure that no one stole the computers
from the university and you know that&#39;s
a perfectly reasonable thing for her to
think because I told her I was working
in computer security and it was
interesting to get her perspective but
that&#39;s not the most ridiculous thing
I&#39;ve ever heard anyone say about my work
the most ridiculous thing I ever heard
is I was at a dinner party and a woman
heard that I work in computer security
and she asked me if she said her
computer had been infected by a virus
and she was very concerned that she
might get sick from it that she could
get this virus and I&#39;m not a doctor but
I reassured her that it was very very
unlikely that this would happen but if
she felt more comfortable she could be
free to use latex gloves when she was on
the computer and it&#39;d be no harm
whatsoever than that I&#39;m going to get
back to this notion of being able to get
a virus from your computer in a serious
way what I&#39;m going to talk to you about
today are some hacks some real-world
cyberattacks that people in my community
the academic research community have
performed which I don&#39;t think most
people know about and I think they&#39;re
very interesting and scary and this talk
is kind of a greatest hits of the
academic security community&#39;s hacks none
of the work is my work it&#39;s all work
that my colleagues have done and
actually ask them for their slides and
incorporated them into this talk so the
first one I&#39;m going to talk about are
implanted medical devices now medical
devices have come a long way
technologically you can see in 1926 the
first pacemaker was invented in 1960 the
first internal pacemaker was implanted
hopefully a little smaller than that one
that you see there and technology has
continued to move forward
in 2006 we hit an important milestone
from the perspective of of computer
security and why do I say that because
that&#39;s when implanted devices inside of
people started to have networking
capabilities one thing that brings us
close to home as we look at Dick
Cheney&#39;s device he had a device that
pumped blood from an aorta to another
part of the heart and as you could see
at the bottom there it was controlled by
a computer controller and if you ever
thought that software reliability was
very important get one of these inside
of you now what a research team did was
they got their hands on what&#39;s called an
ICD this is a defibrillator and this is
a device that goes into a person to
control their heart rhythm and these
have saved many lives well in order to
not have to open up the person every
time you want to reprogram their device
or do some Diagnostics on it they made
the thing be able to communicate
wirelessly and what this research team
did is they reverse engineered the
wireless protocol and they built the
device you see pictured here with a
little antenna that could talk the
protocol to the device and and thus
control it in order to make their
experience real they were unable to find
any volunteers and so they went and they
got some ground beef and some bacon and
they wrapped it all up to about the size
of a human beings area where the device
would go when they stuck the device
inside it to perform their experiments
somewhat realistically they launched
many many successful attacks one that
I&#39;ll highlight here is changing the
patient&#39;s name I don&#39;t know why you
would want to do that but I sure
wouldn&#39;t want that done to me and they
were able to change therapies including
disabling the device and this is with a
real commercial off-the-shelf device
simply by performing reverse engineering
and sending wireless signals to it there
was a piece on NPR that some of these AI
CDs could actually have their
performance disrupted simply by holding
a pair of headphones on to them now
Wireless and the Internet can improve
healthcare greatly there are several
examples up on the screen of situations
where doctors are looking to implant
devices inside of people and all of
these devices now it&#39;s standard that
they communicate wirelessly and I think
this is great but without a full
understanding of trust
the computing and without understanding
what attackers can do and the security
risks from the beginning there&#39;s a lot
of danger in this ok let me shift gears
and show you another target I&#39;m going to
show you a few different targets like
this and that&#39;s my talk so we&#39;ll look at
automobiles this is a car and it has a
lot of components a lot of electronics
in it today
in fact it&#39;s got many many different
computers inside of it
more Pentiums than my lab did when i was
in college and they&#39;re connected by a
wired network there&#39;s also a wireless
network in the car which can be reached
from many different ways so there&#39;s
Bluetooth there&#39;s the FM and XM radio
there&#39;s actually Wi-Fi there are sensors
in the wheels that wirelessly
communicate the tire pressure to a
controller onboard the modern car is a
sophisticated multi computer device and
what happens if somebody wanted to
attack this well that&#39;s what the
researchers that I&#39;m going to talk about
today did they basically stuck an
attacker on the wired network and on the
wireless network now they have two areas
they can attack one is short-range
wireless where you can actually
communicate with device from nearby
either through Bluetooth or Wi-Fi and
the other it&#39;s long range where you can
communicate with the car through the
cellular network or through one of the
radio stations think about it when a car
receives a radio signal it&#39;s processed
by software that software has to receive
and decode the radio signal and then
figure out what to do with it even if
it&#39;s just music that it needs to play on
the radio and that software that does
that decoding if it has any bugs in it
could create a vulnerability for
somebody to hack the car the way that
the researchers did this work is they
read the software in in the computer
chips that were in the car and then they
use sophisticated reverse engineering
tools to figure out what that software
did and then they found vulnerabilities
in that software and then they built
exploits to exploit those they actually
carried out their attack in real life
they bought two cars and I guess they
have better budgets than I do
the first threat model was to see what
someone could do if an attacker actually
got access to the internal network on
the car ok so think of
if someone gets to go to your car they
get to mess around with it and then they
leave and now what kind of trouble are
you in the other threat model is that
they contact you in real-time over one
of the wireless networks like the
cellular or something like that never
having actually gotten physical access
to your car this is what their setup
looks like for the first model where you
get to have access to the car they put a
laptop and they connected to the
diagnostic unit on the in-car network
and they did all kinds of silly things
like here&#39;s a picture of the speedometer
showing 140 miles an hour when the cars
in park once you have control of the
cars computers you can do anything now
you might say okay that&#39;s silly well
what if you make the car always say it&#39;s
going 20 miles an hour slower than it&#39;s
actually going you might produce a lot
of speeding tickets then they went out
to an abandoned airstrip with two cars
the target victim car in the chase car
and they launched a bunch of other
attacks one of the things they were able
to do from the chase cars apply the
brakes on the other car simply by
hacking the computer they were able to
disable the brakes they also were able
to install malware that wouldn&#39;t kick in
and wouldn&#39;t trigger until the car was
doing something like going over 20 miles
an hour or something like that the
results are astonishing and when they
gave this talk even though they gave
this talk at a conference to a bunch of
computer security researchers everybody
was gasping they were able to take over
a bunch of critical computers inside the
car the brakes computer the lighting
computer the engine the dash the radio
etc and they were able to perform these
on real commercial cars that they
purchased using the Radio Network they
were able to compromise every single one
of the pieces of software that
controlled every single one of the
wireless capabilities of the car all of
these are implemented successfully how
would you steal a car in this model well
you compromised the car by a buffer
overflow vulnerability in the software
or something like that you use the GPS
in the car to locate it you remotely
unlock the doors through the computer
that controls that start the engine
bypass anti-theft and you&#39;ve got
yourself a car surveillance was really
interesting the authors of the study
have a video where they show themselves
taking over a car
and then turning on the microphone in
the car and listening in on the car
while tracking it via GPS on a map and
so that&#39;s something that the drivers of
the car would never know was happening
scaring you yet got a few more of these
interesting ones these are ones where I
went to a conference and my mind was
just blown and I said I have to share
this with other people
this was Fabien Monroe says lab at the
University of North Carolina and what
they did was something intuitive once
you see it but kind of surprising they
videotape people on a bus and then they
post processes the video what you see
here in number one is a reflection in
somebody&#39;s glasses of the smartphone
that they&#39;re typing in they wrote
software to stabilize even though they
were on a bus and maybe someone&#39;s
holding their phone at an angle to
stabilize the phone process it and you
may know on your smartphone when you
type a password the keys pop out a
little bit and they were able to use
that to reconstruct what the person was
typing and had a language model for
detecting typing with what was
interesting is by videotaping on a bus
they were able to produce exactly what
people on their smartphones were typing
and then they had a surprising result
which is that their software had not
only done it for their target but other
people who accidentally happen to be in
the picture they were able to produce
what those people had been typing and
that was kind of an accidental artifact
of what their software was doing I&#39;ll
show you two more one is p25 radios p25
radios are used by law enforcement and
all kinds of government agencies and
people in combat to communicate and
there&#39;s an encryption option on these
phones this is what the phone looks like
it&#39;s not really a phone it&#39;s more of a
two-way radio motorola makes the most
widely used one and you can see that
they&#39;re used by Secret Service they&#39;re
used in combat it&#39;s a very very common
standard in the US and elsewhere so one
question the researchers asked
themselves is could you block this thing
right could you run a denial of service
because these are first responders so
what a terrorist organization want to
black out the ability of police and fire
to communicate at an emergency they
found that there&#39;s this girl tech device
used for texting that happens to operate
at the same exact frequency
is the p25 and they built what they
called my first jammer if you look
closely at this device it&#39;s got a switch
for encryption or clear text let me
advance the slide and now I&#39;ll go back
you see the difference this is plain
text this is encrypted there&#39;s one
little dot that shows up on the screen
and one little tiny turn of the switch
and so the researchers asked themselves
I wonder how many times very secure
important sensitive conversations are
happening on these 2-way radios where
they forget to encrypt and they don&#39;t
notice that they didn&#39;t encrypt so they
bought a scanner these are perfectly
legal and they run at the frequency of
the p25 and what they did is they hopped
around frequencies and they wrote
software to listen in if they found
encrypted communication they stayed on
that channel and they wrote down that&#39;s
a channel that these people communicate
in these law enforcement agencies and
they went to 20 metropolitan areas and
listened in on conversations that were
happening at those frequencies they
found that in every metropolitan area
they would capture over 20 minutes a day
of clear text communication and what
kind of things were people talking about
well they found the names and
information about confidential
informants they found information that
was being recorded in wiretaps a bunch
of crimes that were being discussed
sensitive information
it was mostly law enforcement and
criminal they went and reported this to
the law enforcement agencies after
anonymizing it and the vulnerability
here is simply the user interface wasn&#39;t
good enough if you&#39;re talking about
something really secure and sensitive it
should be really clear to you that this
conversation is encrypted that one&#39;s
pretty easy to fix the last one I
thought was really really cool I just
had to show it to you it&#39;s probably not
something that you&#39;re going to lose
sleep over like the cars or the
defibrillators but it&#39;s stealing
keystrokes now we&#39;ve all looked at smart
phones upside down every security expert
wants to hack a smart phone and we tend
to look at the USB port to GPS for
tracking the camera the microphone but
no one up till this point had looked at
the accelerometer the accelerometer is
the thing that determines the vertical
orientation of the smartphone and so
they had a simple setup they put a smart
phone next to a keyboard and they had
people type and then their goal was to
use the vibrations that were created by
typing to measure the change in the
accelerometer reading to determine what
the person had been typing now when they
tried this on an iPhone 3GS this is a
graph of the perturbations that were
created by the typing and you can see
that it&#39;s very difficult to tell when
somebody was typing or what they were
typing but iPhone 4 greatly improved the
accelerometer and so the same
measurement produced this graph now that
gave you a lot of information while
someone was typing and what they did
then is used advanced artificial
intelligence techniques called machine
learning to have a training phase and so
they got most likely grad students to
type in a whole lot of things and to
learn to have the system use the machine
learning tools that were available to
learn what it is that the people were
typing and to match that up with the
measurements in the accelerometer and
then there&#39;s the attack phase where you
get somebody to type something in you
don&#39;t know what it was but you use your
model that you created in the training
phase to figure out what they were
typing they had pretty good success this
is an article from the USA Today they
typed in the Illinois Supreme Court has
ruled that Ram Immanuel is eligible to
run for mayor of Chicago see I tied into
the last talk and ordered him to stay on
the ballot now the system is interesting
because it produced Illinois Supreme and
then it wasn&#39;t sure the model produced a
bunch of options and this is the beauty
of of some of the AI techniques is that
computers are good at some things humans
are good at other things take the best
of both let the human solve this one
don&#39;t waste computer cycles a human&#39;s
not going to think it&#39;s the supreme
might it&#39;s the Supreme Court right and
so together we&#39;re able to reproduce
typing simply by measuring the
accelerometer why is this matter well in
in the Android platform for example the
developers have a manifest where every
device on their the microphone etc has
to register if you&#39;re going to use it so
that hackers can&#39;t take over it but
nobody controls the accelerometer so
what&#39;s the point you can leave your
iPhone next to someone&#39;s keyboard and
just leave the room and then later
recover
they did even without using the
microphone if someone is able to put
malware on your iPhone they could then
maybe get the typing that you do
whenever you put your iPhone next to
your keyboard there&#39;s several other
notable attacks that unfortunately I
don&#39;t have time to go into but the one
that I wanted to point out was a group
from the University of Michigan which
was able to take voting machines the
Sequoia AVC edged er ease that we&#39;re
going to be used in New Jersey in the
election that we&#39;re left in a hallway
and put pac-man on it so they ran the
pac-man game what does this all mean
well I think that society tends to adopt
technology really quickly I love the
next coolest gadget but it&#39;s very
important and these researchers are
showing that the developers of these
things need to take security into
account from the very beginning and need
to realize that they may have a threat
model but the attackers may not be nice
enough to limit themselves to that
threat model and so you need to think
outside of the box what we can do is be
aware that devices can be compromised
and anything that has software in it is
going to be vulnerable it&#39;s going to
have bugs thank you very much
you
