---
layout: page
title: AEON+
show_sidebar: false
---

<img src="/assets/images/aeonplus_logo_dark_trans.png" width="200pix">

## Motivation
The motivation behind the AEON+ program is that modern astronomical surveys can now deliver tens of 
thousands of new discoveries every night, alerted within minutes.  But discovery is not the same as 
characterization: additional follow-up observations are often essential to understand the physical 
nature and properties of these targets.  These follow-up observations are therefore vital to maximize 
the scientific return from flagship astronomical surveys.  With alerts now being issued from gravitational 
wave and neutrino detectors as well as more traditional optical surveys, follow-up data at different 
wavelengths is often required.  Many of these discoveries are transient in nature, so follow-up programs 
must respond rapidly and with a flexibility governed by the demands of the science.  

Responsive follow-up programs of this kind pose a number of practical challenges to research teams and 
observatory operators.  The targets are often not known in advance, and may only be observable for a limited 
time. Traditional approaches to telescope block scheduling, where specific nights are assigned months in 
advance, is not well suited to this science, nor to ongoing monitoring of evolving phenomena.  
Target-of-Opportunity overrides can provide some responsive 
observations, but are often distruptive to block-scheduled facilities.  A more flexible, dynamic 
queue-scheduled approach better serves the needs of the science and is more efficient overall. 

In addition, observing at most astronomical telescopes traditionally meant physically traveling to the 
telescope, or operating it via a remote interface.  This is extremely disruptive for transient 
research programs, where targets are only identified at short notice.  Long-term monitoring observations 
are also burdensome, requiring teams of observers to be coordinated.  This has led a number of observatories 
to focus on developing software to enable researchers to submit requests for observations, which can 
then be carried out by observatory staff or machines more efficiently.

The AEON+ program aims to address both of these issues by building open-source software tools and observatory 
capabilities to support time domain astrophysics.  Building on the success of the original AEON partnership 
of optical facilities at NOIRLab, LCOGT, SOAR and Gemini, AEON+ will extend the range of time-domain 
follow-up facilities to include radio telescopes as well world-class optical/NIR observatories.  

## Program Elements
Software: Astronomers will be able to request observations from any participating facility using stand-alone 
Python library.  This library is being designed such that it can be applied by any existing platform or 
software in use by the community to manage observing programs.  

Expanding the range of AEON-compatible facilities: Observatories in the AEON network have agreed to some or all of their time being available in  
flexible queue-scheduling mode.  This program supports the observatory-side development of software to 
receive and process observing requests according to each telescopes standard operating practises.   
The combined network will offer access to imaging and spectroscopic instruments on telescopes ranging 
from 0.4m to 10m in aperture, distributed across the world. Each facility retains control over the 
fraction of its time that is executed in AEON mode, and telescope nightly operations need not be fully 
robotic to participate.  

Multi-wavelength facilities: Radio observatories are joining the AEON+ Collaboration for the first time.  We are working to broaden 
the "request language" used to submit observation configurations to incorporate the different 
telescope and instrument parameters necessary.  Once complete, observers will be able to perform multi-wavelength 
follow-up of their targets at the click of a button.

Observatories Forum: We will host annual workshops to bring together observatory operators and their 
development teams to facilitate the sharing of tools and techniques and to enhance collaboration.

Visiting Developers Program: We will enable developers, engineers and scientists from observatories and 
the user community to meet in person for short sprint-style workshops.  This will facilitate the 
development of tools to enable time domain astrophysics for the user community, and necessary functionality 
at the observatories.  

## Documentation
A technical description of AEON has been published in Street et al., 2020, SPIE: Astronomical Telescopes 
and Instrumentation, 1144925.

Video introduction to AEON created by A. Hopkinson and E. Gomez

<iframe width="560" height="315" src="https://www.youtube.com/embed/-BeollWYi98?si=2tlopfMk1OuSuxEY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>