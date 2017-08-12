---
layout: default
title: "Half-Day Tutorial: Community Information-Centric Networking (FD.io/cicn)"
group: Tutorials

data:
  - type: day
    time: Friday, August 25, 2017
    room: TBD

  - title: Introduction
    time: 9:00am - 9:15am
    type: tutorial

  - title: The latency budget
    type: tutorial
    time: 9:15am - 9:35am

  - title: Root causes - spending the budget
    type: tutorial
    time: 9:35am - 10:00am

  - title: Mitigations - refunds
    type: tutorial
    time: 10:00am - 10:30am

  - title: Coffee Break
    type: break
    time: 10:30am - 11:00am
    room: Foyer

  - title: Exploring case studies
    time: 11:00am - 11:30am
    type: tutorial

  - title: Some new opportunities
    time: 11:30am - 11:55am
    type: tutorial

  - title: Application in current and emerging networks
    time: 11:55am - 12:20pm
    type: tutorial

  - title: Conclusions and review (with Q&A)
    time: 12:20pm - 12:30pm
    type: tutorial

presenters:
- name: Luca Muscariello
  affiliation: Cisco
  bio: "<p>Luca Muscariello received the MSc and PhD degrees from Politecnico
di Torino in 2002 and 2006 respectively. He works at Cisco Systems as
Principal Engineer and is a research associate at the IRT SystemX. He spent
ten years working at France Telecom R&D and Orange Labs Networks
doing research and innovation in networking. He was program co-chair of
Valuetools 2013, program co-chair of ACM ICN 2014 and general co-chair
of ACM ICN 2014. He is a member of the ACM and a senior member of
the IEEE and SEE.</p>"

- name: Alberto Compagno
  affiliation: Cisco
  bio: "<p>Alberto Compagno is a Software Engineer at Cisco Systems working on
cutting edge secure and privacy preserving mechanism on fixed and mobile
ICN networks. Alberto received the MSc in Computer Science in 2012 from
University of Padua, Italy, and he got his Ph.D. in Computer Science in 2017
from Sapienza, University of Rome, Italy. His work has been published in
high-ranked security conferences and journals. In 2015, He has also been
awarded with the best student paper award at the Applied Cryptography
and Network Security conference. His main research interests are in
network security and user privacy. </p>"

- name: Marcel Enguehard
  affiliation: Cisco &amp; Telecom ParisTech
  bio: "<p>Marcel Enguehard is a PhD student in a joint program between Cisco
and Telecom ParisTech. He works under the supervision of Dr Giovanna
Carofiglio and Prof Dario Rossi. His research focuses on applying
Information-Centric Networking to the Internet of Things. In particular,
he is looking at forwarding strategies in different parts of the IoT vertical.
Previous to his PhD, he completed his MSc in 2016 from E'cole Polytechnique
and KTH - Royal Institute of Technology. He wrote his master thesis
at KTH on optimizing chains of virtualized network functions.
 </p>"

- name: Mauro Sardara
  affiliation: Cisco &amp; Telecom ParisTech
  bio: "<p>Mauro Sardara received the MSc degree from Politecnico di Torino in 2016.
He is currently doing is PhD in conjunction with Telecom ParisTech and
Cisco Systems. The main topic of his PhD is large-scale video delivery over
Information-Centric Networks (ICN). He is working on several research
topics related to ICN, such as architectural design, transport, routing and
forwarding protocols.</p>"

---

## {{ page.title }}

### Overview
* TOC
{:toc}

### Trainers

{% include presenters.html presenters=page.presenters %}

### Motivation

CICN is part of the open source project FD.io in the Linux Foundation. Participation
in FD.io is based on active involvement of individuals to software
development and testing.

The project scope includes CCN network architecture implementation: packet
processing as well as network socket API. Packet processing will be made available
through two main forwarders one based on the Vector Packet Processing
(VPP) framework and one based on sockets to deploy CCN in non VPP environments.
The project will focus on the CCNx 1.0 specification as a reference
implementation, but able to evolve by keeping track of the work done in IRTF
ICN research group. While the main focus is on VPP plugin, the socket based
forwarder will be used to enable end-to-end chains testing, supporting end
devices that do not support VPP. Moreover, for the VPP forwarder, CCNx 1.0
packets will be transported using IPv4, IPv6, Ethernet and WiFi encapsulation.

The objective of the tutorial is to make the audience familiar with the CICN
project and make the ICN community being able to use the available software
for experimental research, demonstrations, proofs of concepts and more.

The tutorial targets both software developers as well as software users. Software
developers will learn the continuous integration facility available in the
Linux foundation as well as the project governance to directly contribute to
the software development and testing.

The CICN project has been launched in March 2017 and the ICN community
attending the ACM ICN conference can take advantage of the tutorial to gain
the basic knowledge to get advantage of the CICN project.

The main objective of this tutorial is to let researchers, students, software
developers, network experimenters to be quickly able to use the software for
their own needs. The attendee at the end of the tutorial should be able to
perform the following tasks with CICN:

* Understand Vector Packet Processing;
* Write applications that make use of the consumer/producer socket API;
* Deploy a network testbed made of several components such as software routers in Linux containers, end-points such as data producers and consumers, collect network analytics;

### Tutorial outline (half day schedule)

The tutorial duration is half-day
and would cover the following
items:

1. CICN project overview (30 min);

2. Vector Packet Processing for ICN (60 min);

3. break (30 min);

4. vICN: configuration, management and control of an virtual ICN network (60min);

5. Applications: Consumer/ Producer Socket API, MPEG-DASH over ICN (30 min).

### Requirements for the attendees

The attendee is familiar with GNU Linux OS, basic knowledge of Information-Centric Networking in particular CCN/NDN. Optionally, the attendee that is familiar with Linux containers, software-defined networking might want to actively reproduce virtual network testbed deployed during the tutorial.
