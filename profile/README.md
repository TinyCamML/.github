## Hi there 👋

IN PROGRESS README

The purpose of this organization is to describe how to build an sensor with on-device machine learning and cellular transmission to identify spatial extent of coastal flooding. The two main devices are the OpenMV and Particle Boron. Below are a list of the repositories within this organization that help understand the individual devices (including firmware and circuit diagrams) and how they can be combined to create a functioning long-term, low cost, high efficiency sensor. 

This organization is a community of scientists from the University of North Carolina at Wilmington, University of North Carolina at Greensboro, and North Carolina State University.

There is one active repository, and several archived repositories.

The Active repository is [Boron and OpenMV Respository](https://github.com/TinyCamML/Boron-and-OpenMV), which contains firmware for the openMV and the Boron, a circuit diagram, and more images of what you should be looking at. The Boron's firmware in this repository is unique from the other repositories because it includes added cellular transmission and long-term sleeping capabilities. With this updated firmware and correct power supplies you should be able to create a device independent of the computer that has cellular transmission and publishing abilities. This repo is in progress. 

Archived repositories include:

The [Boron respository](https://github.com/TinyCamML/Boron/commit/057b4ee289c73935bf9799aa4b66d42032f21d21) describes firmware necessary to communicate with the openMV.
[OpenMV respository](https://github.com/TinyCamML/OMVmodel) describes firmware necessary to communicate with the Boron. This repository also contains a tf.lite file that is necessary to upload onto the camera in order to successfully run the firmware. 

The [Boron and OpenMV basics repository](https://github.com/TinyCamML/Boron-and-OpenMV-Basics) provides the same firmware from the previous repositories named but also includes the circuit diagram. tf.lite file, and images for what you should be looking at. This repository contains a "How-To" guide for creating a device that is dependent on the computer USB power and does no have cellular transmission. This repo will allow you to test the firmware and wiring connections. This repository would be very helpful if you have an understanding of both devices and are ready to start running code. 


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
