# The Night the Network Stopped

On the evening of November 2, 1988, administrators at American universities and research institutions began encountering computers that were unexpectedly busy. Work slowed, processes accumulated, and systems that normally served many users became difficult or impossible to use. At first, each administrator had an apparently local problem: a machine under load, a malfunction, perhaps an intrusion.

Reports from other institutions changed the scale of the question. Similar failures were appearing across the network. Berkeley, MIT, and other major research centers were not merely sharing an unfortunate evening. Something was travelling between their computers. The machines that connected scientists were providing a route for a problem none of those scientists had requested.

## Before the web

This was the Internet before the World Wide Web. Its users were concentrated in universities, laboratories, government, and related institutions. Computers exchanged mail, allowed remote access, and supplied services that assumed a relatively cooperative community. That did not mean no one understood security. It meant many everyday arrangements still reflected a network whose participants expected substantially more trust than the modern public Internet can sustain.

The immediate challenge was diagnosis. A busy machine can be overloaded for many reasons. Administrators had to identify unfamiliar processes, understand how they had arrived, and find out whether removing one would actually clear the system. Then they had to determine which route would let it return.

Disconnecting offered protection at a cost. It could prevent additional traffic from reaching a host, but it also prevented that institution from receiving the advice other investigators were exchanging. The network carried both the incident and the attempted response. Pulling a cable could help a computer while making the people responsible for it less informed.

This complication became especially serious as affected computers struggled to deliver ordinary communications. The channels through which a warning should travel were among the systems whose capacity was disappearing.

## The copies that kept arriving

Technical investigation established that the program was a worm: software capable of spreading from system to system without relying on a user deliberately sending each copy onward. It targeted particular Unix environments, including widely used systems at the institutions experiencing trouble.

It did not depend on a single entry route. Weaknesses in mail-handling and user-information services supplied openings. It also exploited weak passwords and relationships of trust between machines. A computer admitting commands from a familiar partner might become vulnerable once that partner was compromised. The attacker did not need every system to contain the same mistake if several different mistakes could accomplish the same purpose.

The distinction between a worm and a destructive file-erasing program was important. Administrators did not find that the incident's principal mechanism was deleting their research. Their systems were losing the ability to function because unwanted copies occupied resources. A machine can retain every file and still be unavailable for the work those files exist to support.

This made the event harder to describe as a conventional act of vandalism. It also made it easier for its author to say that catastrophic damage had not been the purpose. But the absence of a deletion routine did not make the unauthorized activity benign. Availability is part of a computer's value, and the network was losing it.

## Why one infection did not stay one infection

The program included a mechanism intended to check whether a machine was already infected. Such a check could, in principle, prevent needless duplication. But its author had anticipated a countermeasure: a defender might falsely report that the worm was present in order to keep it away.

To avoid being defeated by that response, the worm sometimes continued despite receiving an indication of prior infection. The result was repeated occupation of the same hosts. Copies did not merely spread outward into untouched territory. They accumulated where copies already existed, increasing the load and degrading the machines that were meant to carry the next stage of propagation.

That explains why a seemingly modest safeguard could become a central cause of the emergency. The author had designed the program to distrust a response from its prospective victim. Under real network conditions, the decision defeated a limit on the program's own growth.

The technical findings also narrowed the mystery of responsibility. The worm was written by someone who understood Unix services and network behavior. It did not appear spontaneously from several universities at once. Investigators had an artifact whose choices reflected a particular programmer's assumptions, and those assumptions had consequences the programmer had failed to contain.

## A warning that could not outrun the problem

According to the FBI's account, the person who released the worm became alarmed and contacted friends. He wanted an anonymous warning distributed, including guidance on dealing with the program. Much of that warning did not arrive in time because the attack had already interfered with network communication.

That is one of the incident's most revealing reversals. A network designed to spread useful information could also spread software that impaired the network's ability to deliver useful information. The corrective message and the program competed for a medium the program was degrading.

A friend contacted *The New York Times*. While discussing the author, the friend inadvertently supplied the initials RTM. Reporting then identified Robert Tappan Morris, a twenty-three-year-old graduate student at Cornell. The trail toward a person developed quickly alongside the technical response. The name did not come from a triumphant tracing of every network hop; human disclosure helped expose the origin.

Morris had released the program through a computer at MIT, distancing the launch point from Cornell. He had the technical background investigators would expect. His father was a prominent computer expert, and Morris himself had recently graduated from Harvard. None of that made the disruption an authorized research project. It helped explain how he had acquired the knowledge to create it.

## An experiment meets a statute

Morris's stated lack of destructive intent became an important part of the public discussion. It did not resolve the legal issue. The Computer Fraud and Abuse Act prohibited unauthorized access to protected computers. The case turned on conduct as well as on what outcome he claimed to have wanted.

The FBI investigated, and Morris was prosecuted. A jury convicted him in 1990. He received probation, community service, and a fine rather than imprisonment. The conviction survived appeal. This was the first conviction under the 1986 act, making the case a landmark in the application of federal law to computer misuse.

The outcome should not be distorted into the proposition that every programming error is a crime. The relevant distinction was that the program entered and used other people's computers without authorization. An unintended degree of damage does not retroactively supply permission for the underlying intrusion.

The size of the incident also needs careful treatment. The familiar figure is roughly 6,000 affected computers, often described as about a tenth of the Internet at the time. That is an estimate, not a complete census. Later accounts question how precisely it was derived. The uncertainty changes how confidently a statistic should be repeated; it does not make the widespread disruption doubtful.

## The institution created by the emergency

Administrators and researchers collaborated to understand and remove the worm. The work revealed a need for something more durable than improvised calls and scattered messages during the next crisis. Soon afterward, the Computer Emergency Response Team Coordination Center was established at Carnegie Mellon with Defense Department support.

Its purpose addressed the organizational problem the worm had exposed: a network incident could cross many institutions while no one institution possessed all the relevant observations. Shared technical information and a recognizable coordination point could reduce the delay between someone finding a useful answer and others receiving it.

The worm was therefore a technical failure and an institutional test. Shared software helped it spread; shared knowledge helped stop it. Trust between machines provided an opportunity for unauthorized propagation, while trust among researchers supported recovery. The lesson was not to abolish connection. It was to recognize that connection required deliberate boundaries and a plan for failures that would not remain local.

The most durable image is the warning that arrived too late. The author could realize the scale of the damage, ask for help, and supply information, yet still be unable to recall what he had released. A program that travelled independently had turned a private decision into a collective emergency. By the time its creator wanted the network to carry an apology, he had already made the network less capable of doing so.

## Sources and evidence

- [FBI, “Morris Worm”](https://www.fbi.gov/history/cases-and-criminals/morris-worm), consulted directly for the chronology, institutions affected, disclosure of the author, investigation, conviction, and creation of an emergency response team.
- [Wikipedia, “Morris worm”](https://en.wikipedia.org/wiki/Morris_worm), consulted for the multiple entry routes, repeated-infection mechanism, appeal, and uncertainty around the commonly quoted host count.
- The narrative distinguishes Morris's claimed intent from the demonstrated behavior of the software and from the legal finding of unauthorized access.
