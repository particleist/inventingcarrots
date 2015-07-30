# How to reward work on software within the LHCb collaboration.

## Abstract

In the past few decades of high energy physics, computer programming has passed 
from an almost optional activity to a key element, without which acquired data is useless.
Despite the fact that computer programming occupies a large fraction of our working lives, building and maintaining software and its infrastructure is largely disregarded, and is subject to social stigma.
Physicists therefore have little incentive to build sustainable communities around vital software.
This negative attitude towards computing leads to a significant cost in terms of personnel and resources.
This note aims to describe practical proposals to help the LHCb Collaboration
demonstrate that it considers computer programming to be an essential skill.
It also recommends that LHCb members who work on key software tasks are formally recognised, to increase their future employability.

## Introduction

How would your work change if we could dramatically decrease the time between realising a plot needs 
to be made and that plot being available?
How much more efficient and motivated would your students be if working with the software was more about realising physics ideas than solving the tedious, recurring and very technical aspects of data analysis over and over again?

The current generation of experiments require a massive infrastructure to analyse the data taken. 
Without this infrastructure, the data is useless.
With experiment's lifetimes measured in tens of years, this infrastructure needs to be sustainable.
With data volumes soon to increase by an order of magnitude, improving our approach to software 
infrastructure is absolutely necessary to maximize our physics output.

Consider the comparison with communities of highly skilled individuals forming around pieces of detector hardware.
They join forces to design and operate these detectors for long time scales. Knowledge and experience
is passed on to new members who then make significant contributions to the project.
This fosters a community dedicated to their project. In this way, a complex piece of the detector hardware 
can be sustainably maintained over many decades. 

The same does not happen for pieces of software. Most of us write code in the same way that witchdoctors treat
illnesses: curating code fragments acquired over years of doing "whatever works", and assembling them into 
whichever construct is needed to quickly solve today's problem. The approach often is similar to using duct-tape and makeshift contraptions in the lab, which works for the first prototype, but would be inconceivable in the experiment proper.

We are stuck, then, between the contradiction of real world
constraints which make programming well an essential skill, and a
culture which steadfastly refuses to apportion appropriate recognition
to programming well. This leads to suboptimal behaviour. A small core
of "experts" is forever firefighting problems, often improving
existing code in a piecemeal fashion because the resources aren't
available to allow a more holistic approach. In turn these experts
become culturally disconnected from the so-called users, who often
perceive necessary changes brought in by the experts as arbitrary dictates destroying their carefully preserved galleries of useful code fragments. Needless to say, this does not foster learning on the part
of anyone.

In fact, however, most physicists would like to learn how to code
better. Physicists are a naturally curious subset of society, as
demonstrated by the communities from the detector side. When "service"
work exists in a culture which values it, in a culture where the
senior professors are often famous because they built this or that
piece of a detector, and in which said professors are enthusiastic
about passing this knowledge to younger physicists, then said younger
physicists are very enthusiastic to learn.  There is no reason why we
shouldn't be able to create a similar culture around software.

A further relevant implication of a bad programming is a waste of resources.
With these we mean not only the time spent by the enthusiasts, but also directly the
costs in terms of disk space and running time. Gains from optimization and good
programming culture can be quantifiable on the order of one million Euros.
Given the shortage of resources, often referred to by the computing team, 
these practical arguments have a non-negligible impact on the life of our 
Collaboration.


## Courses

One way to create a structure in which physicists can form
communities and learn about software infrastructure in LHCb is to organize software courses.
A recent initiative, launched by a handful of LHCb members, has been 
the [LHCb Starterkit](https://lhcb.github.io/first-analysis-steps).
The course was divided into two parts: the first gave a general introduction to 
the Unix environment and a computer programming, while the second was focused
specifically on LHCb software.
Much attention was paid to the communicative skills of the teachers and on the creation
of a friendly and cooperative atmosphere.
Teachers of the second half were chosen among people directly involved in LHCb
activities on both analysis and computing sides. Many teachers were in fact Master's
or PhD students, "expert enough" in the field to be good teachers for their (often older) colleagues.
In retrospect, this was a key element in encouraging collaborative behaviour
and discouraging the lone genius syndrome. In total, over twelve people contributed to creating
the material. Amazingly, the organisation of the next event has been taken over by new people who
helped last time. This will help ensure the continuity of the event for years to come.


## Prizes

We would like to reward being a programming enthusiast in a direct and tangible way within the LHCb Collaboration.
The list of rewards and incentives we propose is deliberately not simply a list of "prizes" but largely includes
monetary components.
How these would be funded has to be discussed and decided by the Collaboration Board (CB),
however the sums would amount to a few thousand Swiss Francs.
This a small fraction of the hundreds of thousands of Francs that have been already saved in computing power
by improving our software during Long Shutdown 1.

We are aware that all the prizes in the world won't make up
for how software skills get valued by job selection committees.
On the other hand, we note that having prizes of this kind is one of the suggestions made is the recent
"ECFA memorandum on evaluation" to increase the possibility of
external commissions to judge the quality of a candidate applying for job positions outside HEP.

In addition to a monetary prize, we propose funding to attend non-HEP meetings or conferences.
This is also very deliberate, because physicists don't have enough opportunities to
engage with software professionals. It is good both for the
physicist's ability to transfer to industry if they so choose, and
good for bringing advanced programming methods back to our collaboration.

In all cases the nomination process will be open to the whole
collaboration and announced well in advance of any prize being
awarded.

In order to encourage collaborative behaviour and discourage the lone
genius syndrome, the following general rules will apply:

A. Any nominated piece of software will have to include a full test
suite covering all foreseen use cases, and have been reviewed by one
person other than the author. Quality of the test suite should be taken into consideration for the evaluation of the submissions.

B. Any nominated piece of software will have to be fully documented
(whether in a note, TWiki, etc.) including, where appropriate, clear
examples on how the code can be (re)used. In the case of technical
improvements which, for example, speed up existing pieces of code,
the author(s) should provide a clear explanation of why this specific
change made things faster, and at least attempt to give rough examples
of how a similar technique might be applied elsewhere.

The proposed rewards are:

1. An annual thesis prize for "most innovative contribution to LHCb
software by a PhD student", a reward of 500 Swiss Francs plus funding for one
trip to a non-HEP conference, hackathon, or similar of the winner's
choosing. This would be awarded by the computing project management.

2. A prize for any code improvement which speeds up the reconstruction
or trigger by 5% or more, a reward of 1000 Swiss Francs plus
funding for one trip to a non-HEP conference, hackathon, or similar of the
winner's choice. To be jointly awarded by the computing and trigger project
managements.

3. An annual prize for collaborative programming, for initiatives
which make a significant improvement to LHCb software and are seen as
having improved community participation in the software
design. Funding for one trip to a non-HEP
conference, hackathon, or similar (per team member) of the winning team's
choice. To be voted on by collaboration members.

4. A quarterly award for contributions to improving the programming
culture of the collaboration. This is of course somewhat subjective
but example nominations might be: a team which produces a piece of
code or package with particular evidence of a collaborative
test/review/open-issue-discussion based approach; reviewing other
people's code; committing tests for other people's code; giving
helpful comments on other people's code. The winner would be presented
and recognized at a Tuesday meeting and asked to give a short
presentation on their work. To be jointly awarded by the computing and trigger
project managements. Winners would not be eligible for a repeat award
for one year.

All winners are mentioned in public articles on the official LHCb webpage.

## Conclusions

Until we reward being a programming enthusiast in a direct
and tangible way, all the goodwill in the world will not be enough to
overcome the incentive structures which drive people to spend as
little of their time programming well as possible.
This note is a first attempt to formulate a proposal for how to
set up such a reward and incentive structure within the LHCb Collaboration.

Tim Head <thead@cern.ch>

Vava Gligorov <vladimir.gligorov@cern.ch>

Yasmine Amhis <yasmine.amhis@cern.ch>

Barbara Sciascia <barbara.sciascia@cern.ch>

Sebastian Neubert <sebastian.neubert@cern.ch>

Marco Cattaneo <marco.cattaneo@cern.ch>

Conor Fitzpatrick <conor.fitzpatrick@cern.ch>

Silvia Borghi <silvia.borghi@cern.ch>

Barbara Storaci <barbara.storaci@cern.ch>

Chris Jones <jonesc@hep.phy.cam.ac.uk>

Ben Couturier <Ben.Couturier@cern.ch>

Concezio Bozzi <bozzi@fe.infn.it>

Pete Clarke <peter.clarke@ed.ac.uk>

Alex Pearce <alex.pearce@cern.ch>

Stefan Roiser <stefan.roiser@cern.ch>
