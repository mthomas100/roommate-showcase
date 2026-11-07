# Roommate

**A robot dog that lives in a physics twin of my apartment and walks through my real rooms in Apple Vision Pro,
hidden behind my real walls.**

> The source code is private. This page shows what Roommate does. For access, a demo or a conversation, contact me through my GitHub profile.

## What it is

I scanned my apartment with LiDAR and turned it into a physics simulation. A robot dog lives in it. Its brain is
[DimOS](https://github.com/dimensionalOS/dimos), the open robotics OS that drives real Unitree robots, with Claude
as its voice. When I put on my Vision Pro, the headset recognizes which room I'm in, and the dog walks through my
real rooms, behind my real walls. I can talk to it, point where it should go, pat it and play fetch.

It works both ways: the dog sees me too, and reacts to where I am and what my hands do.

## What it can do

| | |
|---|---|
| **Go to a room** | "Come to the living room": it plans a route, walks there and says when it has arrived |
| **Hidden by real walls** | it disappears behind your real walls and furniture |
| **Pinch to go** | look at the floor and pinch |
| **See what it sees** | a live window into the robot's camera, and a tabletop 3D map of the home with its route |
| **Pats and hearts** | pat its head and hearts float up |
| **Fetch** | throw a ball; it watches, chases it and brings it back |
| **Tricks** | a paw for your hand, a finger heart, a spin learned from real dog motion |
| **Carry it** | pick it up and put it down somewhere else |
| **Find itself in the room** | look around for about 15 seconds and the headset lines up with the scan |
| **Ask Siri** | "Where is Roommate?", "Roommate, come here" |

## By the numbers

| | |
|---|---|
| Built in | about 3 days, directing a team of AI coding agents |
| Body updates streamed to the headset | 100 a second, drawn 1:1 in the room |
| Headset lined up with the scan | within about 2 cm of the scanned walls |
| Simulation speed | real time (1.00×) in the full apartment |
| Apartment tour | every reachable place visited, 0 falls |
| An hour of the dog's mind on Claude Haiku | about $0.014 |
| Automated tests | nearly 2,000 |

## Built with

Apple Vision Pro (visionOS, RealityKit, ARKit) · DimOS · MuJoCo · Claude · an iPad Pro LiDAR scan

Credits: DimOS by Dimensional; the Shiba Inu model by Quaternius (CC0); the iPad capture app is based on
[3D Model Anything](https://github.com/wesbos/3d-model-anything) by Wes Bos (MIT).

## Status

A working prototype, tested in a real apartment on a real Vision Pro. Some features are still being tested on the
device.

## Licence

Copyright (c) 2026 Matthew Thomas. All rights reserved. See [LICENSE](LICENSE).
