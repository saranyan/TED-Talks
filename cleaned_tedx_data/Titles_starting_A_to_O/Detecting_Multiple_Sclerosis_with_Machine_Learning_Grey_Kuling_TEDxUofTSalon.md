
it wasn&#39;t until a conversation with the
childhood friend
that I realized the truth
of my research and here&#39;s what she said
I&#39;ve been very fortunate but it&#39;s
definitely because I tried to exercise
and eat well but it hasn&#39;t always been
this good I&#39;ve lost my vision in the
past and my ability to walk but
obviously I&#39;ve got it back
I have relapse remitting multiple
sclerosis so I&#39;m fine
90% of the time but yeah that other 10%
multiple sclerosis is an autoimmune
disease for the immune system attacks
the healthy neurons of the patient&#39;s
central nervous system this renders the
neuron incapable of communicating
signals to the rest of the body
the damaged in scarred tissue of the
neuron is called an MS lesion and we can
visualize these using magnetic resonance
imaging or MRI in analyzing different
scans we see a very distinct pattern
between the lesions and the healthy
tissue and currently radiologists use
this pattern to outline the lesions
manually calling it a segmentation now
this is important in all stages of an MS
such as initial diagnosis evaluation of
disease progression and determining
treatment efficacy
however manual segmentation is difficult
and often variable to physicians may not
agree on the same segmentation as well a
physician may not segment the lesion the
same way twice and this results in human
error therefore it has been proposed to
segment lesions automatically using
machine learning now
machine learning has become a hot topic
in recent years it&#39;s literally
everywhere recognizing and learning
patterns and information around us
Google Facebook and now Apple&#39;s own
iPhone uses machine
learning for facial recognition as well
our email inboxes use machine learning
to filter out spam we could use a
machine learning algorithm to learn the
pattern of lesions in these four scans
but first what information are we
looking at in these images
what is this data exactly well a picture
is a matrix of pixel intensities at a
given x and y coordinate we then can
stack the images on top of each other
making a third dimension so we can
visualize the data and tissue in 3d this
then turns the pixel intensity into a
volumetric intensity or a voxel in a
given X Y and Zed coordinate so if we
were looking at these voxels ourselves
and we wanted to try and identify what
tissue were looking at how would we
figure that it well let&#39;s make it a
little bit simpler if we were looking at
any kind of object how would we
recognize what we&#39;re looking at say for
example animals we could build a
dictionary of examples in our memory
that we could reference and it turns out
that a computer can do the same so that
it could identify a gorilla from a lion
in dictionary learning we take a
collection of image examples and we take
the pixel intensities and we rearrange
them into a vector we then place those
vector examples side-by-side into a new
matrix that we call a dictionary then we
can identify a test subject by using
regression analysis now this just means
that we try to recreate the test subject
by using a select amount of dictionary
examples so if a dictionary of lions
tried to identify a gorilla it wouldn&#39;t
do a very good job
and the error would be large but if it
tried to identify a lion the error would
be small declaring that it is indeed
perceiving a lion in the case of MS we
want to look at the individual voxels
and determine what kind of tissue were
looking at specifically gray matter
white matter cerebral spinal fluid and
ms lesions so we could build the
dictionary for all four the question now
is how will we characterize each
individual voxel to build examples in
our dictionary we&#39;re not looking at a
whole picture anymore we&#39;re just looking
at a small portion of it well
classically researchers have taken a
large spatial patch of the voxel
intensities that surround the voxel of
interest so the voxel of interest is in
the center and then we take all the
information around them we would
rearrange that information into a vector
and then build our dictionaries so let&#39;s
see how well this turns out this is a
picture of the ground truth this is the
correct answer this is what we want to
see the algorithm recreate and these are
the results we get it turns out it
doesn&#39;t do a very good job there&#39;s a lot
of over segmentation and a lot of false
positives my supervisor dr. hamaji and I
looked at this critically and thought it
must be looking at too much information
at once resulting in too many confusing
factors so we thought why not just keep
it simple let&#39;s just use the voxel in
question and not a spatial patch so we
tried this out and it&#39;s segmented the
lesions perfectly now we were a little
skeptical about these results because we
actually had pre-processed our data to
be ideal we took out any noise or
distortions in the images that may make
the information confusing to the
computer so we thought why not
bit up without their level make it
harder and try and segment images with
three percent noise added and it
couldn&#39;t handle the noise and our false
positives returned to solve this problem
we asked ourselves what is the noise
changing in these photos if we take a
look at them side by side we can see
that the lines are a little bit blurry
but the biggest difference is between
the lines we can see that the white
matter and cerebral spinal fluid have
gone from one solid color to a fuzzy
pattern so if you were looking at this
fuzzy pattern how would you describe it
I&#39;ll make it a little bit simpler how
would you describe the difference
between these images each panel has a
very distinct texture the texture of
ashphalt is contrasting ly different
than the texture of a brick wall
therefore our brains understand what
we&#39;re looking at we subconsciously
analyze the texture and it turns out
again a computer can do the same by
looking at the pixel intensities we can
count how often a certain intensity
level shows up in the picture by
Counting the frequency of each intensity
level we get a probability distribution
then we can calculate the mean the
standard deviation the entropy and all
sorts of information we wanted to build
a dictionary for all the tissues that
uses the voxel intensity in question and
a texture quantification calculated
statistically from the adjacent voxels
to the voxel of interest now as it turns
out as you increase the noise the
standard deviation will increase but the
mean will stay relatively the same since
the standard deviation is so sensitive
to the noise we coupled it we
the voxel intensity and rebuilt our
dictionaries and it solved the problem
it could even segment small lesions that
are hard to find now these are very
exciting results but unfortunately it
might be a while before this becomes
clinical use the results that I&#39;ve shown
you today were calculated on a simulated
brain scan from McGill University called
brain web and papers that have made the
jump from simulated data to real patient
data have dropped in accuracy by almost
50% I currently at this moment do not
have a database of real patient data to
test on and the approval of a clinical
trial to acquire such data set depends
on one imminent issue accountability
when a scan is segmented manually for
lesions a physician is diagnosing the
lesions if the segmentation was done
automatically who is doing the
diagnosing now this is the big issue
with introducing machine learning to
medicine now in the case of dictionary
learning the machine makes a decision
based off of the dictionary it was
provided with therefore it&#39;s like I&#39;ve
trained assistant but it&#39;s the doctor
who needs to make the final decision
it&#39;s not a question of will the machine
make the wrong choice but will the
doctor allow the machine to make the
wrong choice thank you
you
you
