# Autonomous Air Traffic Control Tasks using Deep Reinforcement Learning
## Marc Brittain
### mwb AT iastate DOT edu

Fork of the BlueSky Air Traffic Simulator developed by TU Delft.The original ReadMe can be seen below.

There are currently 2 branches: **lstm** and **N_Closest** to correspond to the following papers,

(1) [One to Any: Distributed Conflict Resolution with Deep Multi-Agent Reinforcement Learning and Long Short-Term Memory](https://www.researchgate.net/publication/338084245_One_to_Any_Distributed_Conflict_Resolution_with_Deep_Multi-Agent_Reinforcement_Learning_and_Long_Short-Term_Memory)

(2) [Autonomous Air Traffic Controller: A Deep Multi-Agent Reinforcement Learning Approach](https://arxiv.org/abs/1905.01303)


Please see the individual branch for intructions on running. 


If any of this work helped in your project or research I would love to hear about it! Please send me and email at the address listed above for comments, questions, or just to say hi.

Please make sure to cite the papers in your work :) 


------------------------------------------------------------------------------------------------------------------------------




# BlueSky - The Open Air Traffic Simulator

BlueSky is meant as a tool to perform research on Air Traffic Management and Air Traffic Flows, and is distributed under the GNU General Public License v3.

The goal of BlueSky is to provide everybody who wants to visualize, analyze or simulate air
traffic with a tool to do so without any restrictions, licenses or limitations. It can be copied,
modified, cited, etc. without any limitations.

**Citation info:** J. M. Hoekstra and J. Ellerbroek, "[BlueSky ATC Simulator Project: an Open Data and Open Source Approach](https://www.researchgate.net/publication/304490055_BlueSky_ATC_Simulator_Project_an_Open_Data_and_Open_Source_Approach)", Proceedings of the seventh International Conference for Research on Air Transport (ICRAT), 2016.

## BlueSky Releases
If you are not (yet) interested in reading and editing the source of BlueSky, you can also download a release version of BlueSky, that you can install directly, without having to worry about python and library dependencies. You can find the latest release here:
https://github.com/TUDelft-CNS-ATM/bluesky/releases

## BlueSky Wiki
Installation and user guides are accessible at:
https://github.com/TUDelft-CNS-ATM/bluesky/wiki

## Some features of BlueSky:
- Written in the freely available, ultra-simple-hence-easy-to-learn, multi-platform language
Python 3 (using numpy and either pygame or Qt+OpenGL for visualisation) with source
- Extensible by means of self-contained [plugins](https://github.com/TUDelft-CNS-ATM/bluesky/wiki/plugin)
- Contains open source data on navaids, performance data of aircraft and geography
- Global coverage navaid and airport data
- Contains simulations of aircraft performance, flight management system (LNAV, VNAV under construction),
autopilot, conflict detection and resolution and airborne separation assurance systems
- Compatible with BADA 3.x data
- Compatible wth NLR Traffic Manager TMX as used by NLR and NASA LaRC
- Traffic is controlled via user inputs in a console window or by playing scenario files (.SCN)
containing the same commands with a time stamp before the command ("HH:MM:SS.hh>")
- Mouse clicks in traffic window are use in console for lat/lon/heading and position inputs

## Contributions
BlueSky is still under heavy development. We would like to encourage anyone with a strong interest in
ATM and/or Python to join us. Please feel free to comment, criticise, and contribute to this project. Please send suggestions, proposed changes or contributions through GitHub pull requests, preferably after debugging it and optimising it for run-time performance.
