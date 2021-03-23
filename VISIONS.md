# Visions

This document describes our vision for the Gemini Simulation Platform.
 
Gemini is an open source project targeted on simulation and visualisation of autonomous marine applications. It functions as a toolbox developed in the Unity game engine, where it uses Unity’s entity-component-system to configure both the enviroment 
and the ownships actuators and sensors.
At the moment Gemini has implemented 4 GPU accelerated EMR sensors of maritime interest, including radar. Lidar and RGB cameras and infrared.
Using Geminis API, one is able to connect to external softwares. From this, software outside Gemini are able to model actions outside Unity
In addition to making perceptions available by an autonomous agent

Gemini is envisioning to support usage from the open simulation platform to encourage researchers and Industry partners to share models with eachother. 
Using this as a ground base, Autonomous Agents can be deployed in the enviroment driven by component models from OSP and synthetic sensor data from Gemini. 
The internals workings of the agent can from this be studied without consequences for human lives and material compensations if something unfortunate where to happen.

## Roadmap Features

* Hydrodynamics
* API to interact with vessels and the environment (Weather, Day/Night etc)
* API to configure traffic scenarios
* Support functionality needed to generate data related to training of Deep learning models
* User interface to set up vessel configuration
* The Gemini Simulator Platform will always be open-source to encourage trust in its implementation
