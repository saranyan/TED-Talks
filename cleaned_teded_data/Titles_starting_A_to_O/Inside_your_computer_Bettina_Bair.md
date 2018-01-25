
Do you remember when you first realized
that your computer was more
than just a monitor and keyboard?
That between the mouse click
and the video playing,
there was something
that captured your intention,
understood it,
and made it real?
What is that something?
Is it gremlins?
Let&#39;s imagine that we can shrink down
to the size of an electron
and inject ourselves
into a click of a mouse.
If you took your mouse apart,
you&#39;d see that it&#39;s really
a very simple machine.
It has a couple buttons
and a system for detecting
motion and distance.
You might have an optical mouse
that makes these measurements
with lights and sensors,
but older ones did this
with a hard rubber ball
and some plastic wheels.
Same concept.
When you click the button on your mouse,
it sends a message to the computer
with information about its position.
When your mouse click is received,
it&#39;s handled by the basic
input/output subsystem.
This subsystem acts like the eyes and ears
and mouth and hands of the computer.
Basically, it provides
a way for the computer
to interact with its environment.
But it also acts like a buffer
to keep the CPU from being
overwhelmed by distractions.
In this case, the I/O subsystem decides
that your mouse click is pretty important
so it generates an interrupt to the CPU.
&quot;Hey, CPU! Got a click here.&quot;
The CPU, or central processing unit,
is the brains of the whole computer.
Just like your brain doesn&#39;t
take up your whole body,
the CPU doesn&#39;t take
up the whole computer,
but it runs the show all the same.
And the CPU&#39;s job, its whole job,
is fetching instructions from memory
and executing them.
So, while you&#39;re typing, typing, typing,
maybe really fast,
like 60 words a minute,
the CPU is fetching and executing
billions of instructions a second.

Yes, billions every second:
instructions to move your mouse
around on the screen,
to run that clock widget on your desktop,
play your internet radio,
manage the files you&#39;re
editing on the hard drive,
and much, much more.
Your computer&#39;s CPU
is one heck of a multitasker!
&quot;But oh my gosh
there&#39;s a very important mouse click
coming through now!
Let&#39;s drop everything now
and deal with that!&quot;
There are programs for everything
that the CPU does.
A special program for the mouse,
for the clock widget,
for the internet radio,
and for dealing with letters
sent by the keyboard.
Each program was initially
written by a human
in a human-readable programming language,
like Java,
C++,
or Python.
But human programs take up a lot of space
and contain a lot of unnecessary
information to a computer,
so they are compiled and made smaller
and stored in bits of ones
and zeros in memory.
The CPU realizes that it
needs instructions
for how to deal with this mouse click,
so it looks up the address
for the mouse program
and sends a request
to the memory subsystem
for instructions stored there.
Each instruction
in the mouse device driver
is duly fetched and executed.
And that&#39;s not nearly
the end of the story!
Because the CPU learns
that the mouse was clicked
when the cursor was over a picture
of a button on the monitor screen,
and so, the CPU asks memory
for the monitor program
to find out what that button is.
And then the CPU has to ask memory
for the program for the button,
which means that the CPU needs
the monitor program again
to show the video
associated with the button,
and so it goes.
And let&#39;s just say there
are a lot of programs involved
before you even see
the button on the screen
light up when you clicked it.
So, just the simple task
of clicking your mouse
means visiting
all of the critical components

of your computer&#39;s architecture:
peripherals,
the basic input-output system,
the CPU,
programs,
and memory,
and not one gremlin.
