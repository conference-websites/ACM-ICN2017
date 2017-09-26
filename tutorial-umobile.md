---
layout: default
title: "Half-Day Tutorial: Grafting opportunistic communications onto ICN: the UMOBILE project"
group: Tutorials

presenters:
- name: Paulo Mendes
  affiliation: COPELABS &amp; University Lusofona
  bio: "<p> Dr. Paulo Mendes is a vice-Director (2014) of COPELABS, the SITI coordinator, and
an Associate Professor of University Lusofona, where he heads the PhD programme
in Informatics, NEMPS. Paulo is also a co-founder of SENCEPTION Lda, a spin-off of
COPELABS. He has a BEng in Informatics Engineering by Univ. Coimbra (93); MSc
in Computers and Electrotecnical Engineering (1998) by IST, UTL, Lisboa, and a PhD
in Informatics Engineering by Univ. Coimbra (2004). He was the Telematics Director
of Fernave, S.A. (1994-1998); Invited Researcher (00-03) at Columbia University, NY,
EUA; researcher at CISUC, Universidade de Coimbra (1996-2002). He was also a
Senior Researcher (2003-2007) at NTT DoCoMo Euro-Labs, Munich, Germany, and
the co-coordinator of the <i>Internet Architectures and Networking</i> area of UTM,
INESC Porto (2007-2010). His research interests relate to cooperative wireless
systems, self-organizing networks, and complex networks. His track-record includes
over 50 scientific peer-reviewed papers. Paulo is also author in 13 international patents. </p>"

- name: Rute Sofia
  affiliation: SENCEPTION, COPELABS, and ULHT
  bio: "<p> Dr. Rute Sofia is a founder and co-Director of SENCEPTION. She is also a Director
(2014) of COPELABS, where she is the Senior Researcher responsible for the
thematic line of Internet Science, and an Associate Professor of ULHT. Rute holds a
BEng in Informatics Engineering by Universidade de Coimbra (95); M.Sc. (99) and
Ph.D. (04) in Informatics by Universidade de Lisboa. Since 1995 she has been
developing research in the industrial context (Grupo Forum, Lisboa, 95-98; SIEMENS
AG, Munich, Germany, 04-07; Nokia-Siemens Networks GmbH & KO, Munich as
Senior Researcher 07) as well as in the academic context (Universidade de Lisboa,
95; FCCN, 98-03; Pennsilvania University, PA, USA as Invited Researcher 00-03;
ICAIR, Evanston, IL, USA, 00; Bundeswehr Universitaet Munich, as Senior
Researcher, 04; INESCTEC, as co- coordinator of the Internet Architectures and
Networking area, UTM, 07-10; SITI, ULHT, 10-13). Her current research interests are:
social Internet design; pervasive sensing; mobility modeling and management. Rute
holds 8 patents and over 40 peer-reviewed publications in her fields of expertise. She
was (2010-2013) the Scientific coordinator of the EU FP7 project ULOOP and has
vast experience in project management worldwide. </p>"

- name: Angela D'Angelo
  affiliation: AFA Systems
  bio: "<p> Angela D'Angelo has a PhD in Information Engineering, graduated at University of
Siena (Italy), where she has been Research Assistant for 5 years. She has been
reviewer for <i>IEEE Transaction in Image Processing</i> and she has published papers
on many scientific journals and conferences, mainly on <i>Digital Image and Video
Processing</i> and <i>Biometrics for Video Surveillance applications</i>. Other specific
research interests include: multimedia security, distributed source coding, video
processing and compression. She was Visiting Researcher at University College of
London (UCL), University of Salzburg, Technical University of Denmark
(Copenhagen). She was Research Engineer for two years at Eurecom (Sophia
Antipolis, France). She has been involved in several EU projects. She currently holds
the position of Multimedia IP Platform Senior Engineer at AFA Systems, in Research
and Development department. She is Project Leader in projects of advanced IP communications. </p>"

- name: Alexandros-Christos Sarros
  affiliation: Athena Research and Innovation Center
  bio: "<p>Christos-Alexandros Sarros obtained his diploma in Electrical and Computer Engineering from the Democritus University of Thrace, in 2016. Currently, he is pursuing a PhD on the same university under the advisory of Prof. Vassilis Tsaoussidis and is working as an associate researcher in Athena Research and Innovation Center in Xanthi. His research interests lie in the area of Delay/Disruption Tolerant Networking and Information-Centric Networking.  He has worked extensively on DTN, studying the use of DTN traffic shaping for energy efficiency, and is a co-author of a conference paper on the topic. Since March 2016, he has been involved in the integration of DTN tunneling into the Named Data Networking architecture in the context of the UMOBILE project.</p>"

---

## {{ page.title }}

### Overview
* TOC
{:toc}

### Trainers

{% include presenters.html presenters=page.presenters %}

### Motivation

Cars, sensors, home appliances, every device in the daily life of citizens is becoming a constituent in Future Internet, adding to the need to reconsider requirements and assumptions in terms of network availability and affordability to support the ever-increasing traffic demand. Still, the current Internet can only evolve adequately, if its infrastructure can be devised to accommodate the emerging services. The increased cost of adding new infrastructure and capacity has a drastic effect on rural and remote communities as well as nomadic users as they become marginalized by not gaining access to crucial Internet services. Our goal is to make the Future Internet universally pervasive supporting a diverse set of services.

To achieve this, we develop a Universal Mobile-centric and Opportunistic communications architecture (UMOBILE), which integrates the principles of Delay Tolerant Networking (DTN) and Information Centric Networking (ICN) in a common framework. By relying on an instance of the UMOBILE architecture, users are able to share information directly with other peers without relying on infrastructure or expensive connectivity services; providers are able to provide services in remote areas as well as in scenarios with intermittent internet access.

This tutorial intends to go over three main innovation aspects concerning ICN: i) NDN operation in opportunistic wireless networks based in contextual awareness; ii) the integration of DTN and NDN to facilitate communications when network is impaired; iii) the UMOBILE Lab: the first NDN/ICN testbed federated in Europe. 


### Tutorial outline (half day schedule)

**i)	UMOBILE in a nutshell (10 min)**
<br/>
Introduction on the UMOBILE architecture, its design and its modules

**ii)	The UMOBILE lab (20 min)**
<br/>
In this section of the tutorial, a detailed description of UMOBILE Lab and its configuration, will be provided. A list of available devices, with their IP addresses and hostname, will be shared with participants. Attendees will learn:
* how to use the lab;
* how to access each device in the lab;
* how to test NDN Network using a Linux device.

**iii)	NDN-DTN integration (20 min)**
<br/>
In this section, attendees will be able to experiment with the DTN interface that has been integrated into the NDN platform. By deliberately inducing network impairments, we will showcase the benefits of the integration.

**iv)	NDN operation in Opportunistic Wireless Networks (40 min)**
<br/>
We'll describe the NDN framework for Opportunistic Networks (NDN-Opp),
which is being developed aiming to support opportunistic forwarding based on users' interests and their dynamic social behavior. NDN-Opp will be demonstrated in a micro-blogging urban scenarios in which a user, makes use of the Now@ application to generate and share expressions of interest in the form of tagged information (e.g., nearby supermarket offers or restaurant review), as well as to generate data related to those interests. This demo aims to show how NDN-Opp allows users to benefit from locally available information.

**v)	Social-aware metrics derived from contextualization (40 min)**
<br/>
UMOBILE integrates in its end-user service application the Contextual Manager (CM), a module that assists in a more efficient data dissemination via capturing and infering network and proximity context. 
In this tutorial we shall go over the UMOBILE contextual manager and explain two main families of routing metrics: i) how the contextual manager can provide metrics derived from encounter duration; ii) how the contextual manager can provide metrics derived from interests and interest matching.

**vi)	Applications (40 min)**
<br/>
Attendees will be able to experiment with Now@ and Oi!, two applications developed to run over the UMOBILE platform.
Now@ is an Android application which enables users to share data based on their interests over an NDN infrastructure. 
Oi! is an application that allows users to send short messages independently of their location and current Internet connectivity. 

### Type of tutorial
* Hands-on

### Requirements for the attendees
* Android smartphone capable of running the most recent version of NDN for Android. Ideally, attendees should also have pre-installed and tested the full Named Data Networking platform. 

* Reasonable conceptual and practical familiarity with the NDN architecture and the fundamentals of Interest/Data exchange. 

* Prior to the tutorial, we will distribute all related UMOBILE software that will be demonstrated during the tutorial.

### Acknowledgements

This project has received funding from the European Union's Horizon 2020 research and innovation programme under grant agreement No 645124.

