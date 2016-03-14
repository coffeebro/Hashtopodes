# Hashtopodes
An evolution of Hashtopus for deployment in the cloud.

# Inspiration: Hashtopus
<a href="https://github.com/curlyboi/hashtopus">Hashtopus</a> is a wrapper for oclHashcat that allows for distributed hash cracking.  After testing oclHashcat on AWS' GPU-equipped EC2 instances, as well as the VR Lab here on the University of Missouri campus (sporting a Quadro K6000), I found myself addicted to getting the highest rate of hashes calculated per second; it's like a security high score!  In order to boost my "score" any further, though, I'd need more hardware.

# Inspiration: Folding@Home
<a href="https://folding.stanford.edu">Folding@Home</a> is a crazy-awesome use case for demonstrating the power of distributed computing: in a nutshell, the project allows you to run a program on your computer that simulates protien folding.  The results of the simulation benefit research on Alzheimer's disease, Huntington's disease, and various forms of cancer.

# Idea: Hashtopodēs
Instead of sourcing additional hardware, what if I could just leverage existing hardware?  This is where Hashtopodēs comes in.  The following tasks have been identified to get started on the project:

1. Create a script to setup and install Hashtopus Server components
  1a. Plan for additional components needed for Hashtopodes Server
2. Create a script to setup and install Hashtopus Agent components
  2a. Plan for additional components needed for Hashtopodes Agent
