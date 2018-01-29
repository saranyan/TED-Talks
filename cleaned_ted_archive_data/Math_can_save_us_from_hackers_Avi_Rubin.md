
I&#39;m going to talk to you about how math
can save the day and you might ask
yourself why does the day need saving
well the day needs saving because
hackers today are exploiting systems and
they&#39;re very successful at this if you
think about target home depot anthem
insurance all these sites have been
hacked and the hackers are stealing
personal information from these servers
and from the databases I want to focus
in on one in particular the Office of
Personnel and management known as OPM
you may not be familiar with OPM but if
you apply for security clearance with
the US government you&#39;ll know about OPM
because that&#39;s the part of the
government that collects the information
when they&#39;re trying to decide if
somebody should be given a security
clearance like top secret so they
collect all kinds of really important
valuable information about people and
they got hacked millions of records
about people&#39;s personal information were
stolen and so the day needs to be saved
and math is going to do it and the
question is how do we protect this
information and the answer is that we&#39;re
going to encrypt it and buy encrypted I
mean that we&#39;re going to perform a
transformation on the data in the
databases using a secret key that will
result in something unreadable to an
attacker and then we decrypt it with the
same secret key and that way if a
database gets hacked and the information
is encrypted in the database then the
attackers don&#39;t get that private
information however there&#39;s a challenge
because I said we&#39;re going to use a
secret key and where are we going to get
that key from let&#39;s imagine a scenario
where you want to buy a song on iTunes
okay so you&#39;re at your computer and you
want to send your credit card over to
iTunes over the Internet we all know
that the internet is full of attackers
eavesdroppers hackers and so I&#39;m posing
a problem to you you&#39;re over here you
have your credit card number itunes
servers over here and the eavesdropper
is going to hear every communication
between you how do you an iTunes server
establish a secret key to commune
k with an eavesdropper seeing everything
it seems impossible but math will save
the day so let me start off simply and
say I&#39;m going to use some colors to
illustrate the concept and then I&#39;ll
plug in some formulas and some math so
we start out with some public
information a generator and a prime
these are going to go into blue dots and
we say that the eavesdropper knows this
information as well and then you and the
iTunes server are each going to generate
a secret so you know the yellow key and
the iTunes server knows the red key you
generate the secret you keep it to
yourself so the eaves droppers on the
internet don&#39;t know it and now what
we&#39;re going to do is each side is going
to combine their secret information with
the public information and in the case
of colors the blue and yellow results in
green and the red and blue results in
purple and they&#39;re going to exchange
that information and what happens is the
eavesdropper also gets to see those
combinations but the eavesdropper does
not have its own secret and it doesn&#39;t
know the two secrets that you and the
iTunes server have and so it can&#39;t
combine a secret with the part that was
made public and you and the iTunes
server can do that so you take your
yellow secret and you combine it with
the purple you received from the iTunes
server and you get brown and the iTunes
server takes the green part that it got
from you and combines it with its red
secret and also gets brown and lo and
behold both of you now know brown but
the eavesdropper can&#39;t produce brown ok
well in practice we&#39;re going to use math
and we&#39;re going to use numbers and so
the way it works is that the public
information is a number G which is a
generator in a particular number field
and a P which is a prime we all know
Prime&#39;s these are numbers that you can&#39;t
divide by anything except themselves in
one and they have certain mathematical
properties that make this work and so
what you do is you take your secret
let&#39;s call it X and you you perform the
computation G to the X mod p what does
that mean it means you multiply G by
itself x times and you take the
remainder when you divide by P and then
on the other side the
server takes y multiplies it by itself
multiplies G by itself y times and takes
the remainder / p so these are pretty
simple calculations they exchange that
information and then when you receive G
to the y mod p from the iTunes server
you raise that to the X meaning you
multiply that result by itself x x
divided by p and take the remainder and
so if you plug numbers into this really
really simple numbers you can see like
if we&#39;re using three and seven as the
generator and the Prime and if we&#39;re
using three as your secret and we&#39;re
using for as the secret of the iTunes
server we can plug and chug we call it
we plug it into these formulas and in
the end we see that we get the number
one and so amazingly you and the iTunes
server can both calculate a number the
number one without an eavesdropper who
saw every single message passing between
you and has unlimited computational
power being able to know this secret so
in practice we&#39;re not going to use three
and seven we&#39;re going to use digits that
are hundreds of digits long right we&#39;re
going to take huge numbers and these
calculations can take a little bit of
time on a computer maybe ten years ago
it would take a few seconds but today
it&#39;s almost instantaneous and so I find
it fascinating hopefully you do too that
you can use math to exchange secrets
that you can use to encrypt information
and databases to protect you if you get
hacked now why is this important because
this can lead to money and jobs and you
can do this kind of math you&#39;re going to
be in very very high demand in the
future and you&#39;re never going to be
bored because this stuff is fascinating
trust me thank
thank you so much I&#39;ll be that was
amazing I have one question for you sure
what do you think will be the biggest
security threat of the future the
biggest security threat of the future
right now I think we have a big problem
with software I have a SmartWatch at the
Apple watch there is more software in my
Apple watch than there was computational
power when I was in graduate school in
the world and so the more software that
you have the more bugs they&#39;re going to
be in the software the more malware
malicious software will be able to take
advantage of it and allow hackers to
break into systems which is why we&#39;re
seeing all of these hacks in the news
all the time Wow well it&#39;s pretty scary
but thank you thank you thank you
everyone
