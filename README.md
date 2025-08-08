# ST 2059-2 - SMPTE Standard - SMPTE Profile for Use of IEEE-1588 Precision Time Protocol in Professional Broadcast Applications

This repository tracks [ST 2059-2 - SMPTE Standard - SMPTE Profile for Use of IEEE-1588 Precision Time Protocol in Professional Broadcast Applications](https://ieeexplore.ieee.org/document/9452731/)

_This repository is *public*._

Please consult [CONTRIBUTING.md](./CONTRIBUTING.md), [CONFIDENTIALITY.md](./CONFIDENTIALITY.md), [LICENSE.md](./LICENSE.md) and
[PATENTS.md](./PATENTS.md) for important notices.

Your feedback is welcome at https://github.com/SMPTE/st2059-2/issues.

#Public Committee Draft (PCD) Notice

The following element is made available for a public review period ending no earlier than October 31, 2025, and no later than August 8, 2026:

[{prose element}]({link to prose element})
#Details

ST 2059-2 is a Precision Time Protocol (PTP) profile for media applications.  The current revision is compatible with PTP specification IEEE-1588:2008 version 2.0. This proposed draft of ST 2059-2 is intended to be compatible with IEEE-1588:2019 version 2.1.

Changes in this revision are:
•	Modify the way in which SMPTE metadata is transported.
•	Update the version advertised in PTP message headers. 
•	Accommodate the new PTP sdoid field.
•	Update which options are permitted.  There are two specific options about which user feedback is requested below.
•	Editorial changes such as removing some residual support for peer-to-peer mode.
 
One challenge in this revision will be accommodating the transition from the current standard.  This draft makes some accommodations to allow what may be a long period where systems are a hybrid of devices from the two revisions.
 
There are two options in IEEE-1588:2019 on which feedback relative to user interest in professional media applications is especially requested in this PCD.  The two options are:
•	Follower event monitoring as described in IEEE-1588:2019 subclause 16.11
•	PTP integrated security mechanism as described in IEEE-1588:2019 subclause 16.14
 
For the Follower event monitoring option, the question is how compelling is this for media applications?   Will it provide significant value?  If there is significant interest, then there will be some follow up discussion on specifics of how it would operate.
 
For the PTP integrated security option, the first question is are users interested?  The second question is which key management process is preferred: the GDOI method in IEEE-1588d-2023 or the NTS4PTP method being proposed by the IETF?

