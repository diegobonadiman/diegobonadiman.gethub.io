---
layout: post
title: "Plugins for digital fabrication on Rhinoceros and Grasshopper"
date: 2016-06-12
categories:
---
Rhinoceros is a very deep design tool and one of its advantages is the existence of diverse plugins to generate and analyze diverse aspects or architectural design. The most famous is Grasshopper, which is a graphical algorithm editor tightly integrated with Rhino’s 3-D modeling tools. In this text, I will briefly explain some Rhino and Grasshopper plugins.

![1](https://diegobonadiman.github.io/images/Render01Edit.jpg) 

<b>RhinoCAM</b>

In order to translate Rhinoceros models and files to CNC language, one of the most useful tool is a plugin called RhinoCAM, which is is a Computer Aided Machining (CAM) plug-in for CNC that runs completely inside of Rhinoceros 5.0. This plug-in is a general purpose machining program targeted at the general machinist. RhinoCAM marries the power of Rhino’s freeform modeling with the legendary machining capabilities of VisualCAM to bring you a product of unrivaled capability for free form surface machining. With the seamless user interface, selection and display integration RhinoCAM acts and feels like you are working with Rhino when creating your cutter paths. RhinoCAM is fully associative to any geometry changes within Rhino. RhinoCAM includes modules for MILL, TURN, NEST, and ART to address specific needs of various CNC manufacturing processes.

![1](https://diegobonadiman.github.io/images/rhino cam 2.png) 

(Description from [http://mecsoft.com/rhinocam-software/](http://mecsoft.com/rhinocam-software/))

<b>Firefly</b>

Firefly offers a set of software tools dedicated to bridging the gap between Grasshopper (a free plug-in for Rhino) and micro-controllers like the Arduino. It allows near real-time data flow between the digital and physical worlds – enabling the possibility to explore virtual and physical prototypes with unprecedented fluidity.

A notable distinction for Firefly is that it is the first visual microcontroller programming environment designed specifically for a 3-D parametric CAD package (such as Rhino). This feature means that real-world data, acquired from various types of sensors or other input devices (video cameras, internet feeds, or mobile phone devices, etc.) can be used to explicitly define parametric relationships within a Grasshopper model. Firefly completes the communication feedback loop by allowing users the ability to send information from Grasshopper back to the microcontroller in order to incite specific actuations (ie. lights, motors, valves, etc). Ultimately, this workflow creates a new way to create interactive prototypes.

<iframe width="560" height="315" src="https://www.youtube.com/embed/UaX0UIBaD54" frameborder="0" allowfullscreen></iframe>

(Description from [http://www.food4rhino.com/project/firefly?ufh](http://www.food4rhino.com/project/firefly?ufh))

<b>GHowl</b>

GHowl is a set of components which extend Grasshopper's ability to communicate and exchange information with other applications and physical devices.

<iframe width="420" height="315" src="https://www.youtube.com/embed/J70bV0BeW10" frameborder="0" allowfullscreen></iframe>

(Description from [http://www.food4rhino.com/](http://www.food4rhino.com/))
