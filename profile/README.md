## Hi there 👋

IN PROGRESS README

This organization is a community of scientists from the University of North Carolina at Wilmington, University of North Carolina at Greensboro, and North Carolina State University. The purpose of this organization is describe how to build an openMV and Boron sensor that is capable of transmitting real time data through cellular transmission. 

The [Boron respository](https://github.com/TinyCamML/Boron/commit/057b4ee289c73935bf9799aa4b66d42032f21d21) describes firmware necessary to communicate with the openMV, which has firmware details in the [OpenMV respository](https://github.com/TinyCamML/OMVmodel). This firmware applied to both devices will have the Boron wake up, use digitalwrite() to wake up the OpenMV that will then determine if what it is looking at is Flood or No Flood, return this back to the Boron, then both return to sleep for 60 seconds. 

The [Boron and OpenMV basics repository](https://github.com/TinyCamML/Boron-and-OpenMV-Basics) provides the same firmware from the previous repositories named but also includes a circuit diagram. 

The [UART Connections Repository](https://github.com/TinyCamML/UART-Communications) provides firmware for each device. Universal Asynchronous Reciever-Transmitter (UART) is the communciation protocol we use for exchanging data. 

The [Boron and OpenMV Respository](https://github.com/TinyCamML/Boron-and-OpenMV) contains firmware for the openMV and firmware for the Boron that allows the Boron to undergo cellular transmission. The goal of this repository is to allow the user to copy the firmware and circuit diagram to create a functioning sensor. 


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
