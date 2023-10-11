# Things that are not on my resume

## Experience

### Microsoft Research
- Worked on an implementation of the "BaRK" protocol by [Kolesnikov, et al](https://www.microsoft.com/en-us/research/publication/efficient-batched-oblivious-prf-applications-private-set-intersection/). BaRK was implemented in the Cocoon framework (general purpose 2-party protocol runner).
Tasks include:
    - Familiarize with the public API by writing some demos + examples that work with the library
    - Refactor implementation: it's a PSI protocol that is built on top of an OPRF protocol, which has a dependency on oblivious transfer (random OT -> OT extension). The pieces weren't clearly separated from each other. I have a lot of notes about Cuckoo tables.
    - I have some notes about consolidating randomness; consolidate all randomness-generating methods into a single class, looking through different libraries to find better APIs, looking for secure defaults + whether seeding was secure.
    - Wrote out general-purpose PSI tests
- Added automated deployment of any Cocoon protocol in Seclud developer platform.
    - Set up Kubernetes and nodes and stuff to actually run the computation
    - Tried to define secure default values + settings
    - Made a demo that runs PSI on data stored in Azure

Other things I learned about
- logging vs saving in memory
- appropriate-level message abstractions
- first time working with QAT + professional software dev.

### MIT Lincoln Laboratory
Lexington, MA USA. Research Intern. May - August 2014.
- Developed an end-to-end prototype for a cryptographically secure mechanism for authentication from a single fortified device.

### Tufts University
Medford, MA. Teaching Fellow. September 2012 - May 2015.
- Taught hands-on programming labs to introductory CS students and held regular office hours for one-on-one assistance
- Lead TA training sessions and small-group meetings throughout the semester to promote motivation and consistency in the TA community

### Google
New York City, NY. Engineering Practicum Intern. June 2013 - August 2013.
- Worked with a partner and two mentors to develop a saving filters feature for the DoubleClick for Publishers team
- Created the client-facing interface for the feature and implemented saving functionality in Java
- OR: Designed and implemented a client-facing interface and implementation for a saving filters feature with the DoubleClick for Publishers team.

### Brain State Technologies 
Bloomington, MN. Software Development Intern. August 2012.
- Worked with a mentor to develop applications to assist in the retrieval, inspection, and update of XML based signal processing flow designs
- Defined XML schema to bind application configuration parameters to Java objects (using Apache XMLBeans)

## Publications
- Measuring Small Subgroup Attacks on Diffie-Hellman. 
Luke Valenta, David Adrian, Antonio Sanso, Shaanan Cohney, Joshua Fried, Marcella Hastings, J. Alex Halderman, Nadia Heninger. 
In _Network and Distributed System Security Symposium_ (NDSS `17). February 2017.
- Weak Keys Remain Widespread in Network Devices.  Marcella Hastings, Joshua Fried, and Nadia Heninger. In _Proceedings of the 2016 ACM on Internet Measurement Conference_ (IMC `16). November 2016.

## Invited Talks
- General purpose compilers for secure multi-party computation
  - DC Area Crypto Day, December 2018
  - Theory and Practice of Multi-Party Computation Workshops, June 2019
  - Real World Cryptography, January 2020

## Education
UPenn GPA: 3.90.

## Teaching
Designed course materials, taught hands-on programming labs, developed grading software, managed teaching assistants, and held regular office hours for undergraduate and graduate-level courses.

### University of Pennsylvania
- CIS 331: Introduction to Networks and System Security, Spring 2017.
- CIS 556: Cryptography, Fall 2016.
- GEMS Computer Science Workshop, Summer 2017.
### Tufts University
- COMP 170: Theory of Computation, Spring 2015.
- COMP 50: Problem-Solving by Computer, Fall 2013.
- COMP 11: Introduction to Computer Science, Fall 2012 - Spring 2015.

## Leadership + Marketing

### Computer Science Exchange
September 2012 - May 2014
- As president for two years, led a small executive board in organizing 10-12 events per semester
- Coordinated with students and visiting professional speakers to arrange technical workshops, lectures, career preparatory nights, and other relevant events
- Led marketing campaigns, including visiting classrooms, distributing posters, and producing a weekly email digest

### TuftsHack
September 2013 - February 2014.
  - Organized a 24-hour hackathon for 130 Tufts students
  - Coordinated over \$1500 in corporate and academic sponsorships 
  - Arranged for industry mentors and workshops leading up to and throughout the event

### Technovation
January 2014 - May 2014
- Served as a university mentor to a team of high school girls building an Android app and associated business plan.

### Orthodox Christian Fellowship
September 2011 - May 2015
- Organized weekly discussion meetings and coordinated with the greater OCF organization 

### JumboTalk
September 2012 - May 2015
- Wrote regular blogs for the Tufts admissions website to give prospective students an honest look at daily life at Tufts 