# LandMod

**LandMod** is a grid-based forest landscape change simulator developed for
western Oregon. It simulates the dynamics of live trees and dead wood over
large spatial extents (18,000+ ha) and temporal periods (500+ yrs) at
relatively fine spatial scales (>0.04 ha) in an efficient manner.

## Overview

At the core of the simulator is a unique forest projection model that tracks
individual tree species by 5-cm size classes on a 5-yr time step. Enveloped
around this core are modules that simulate anthropogenic and natural
disturbance processes. All processes are spatially integrated to accommodate
dynamic feedbacks over time and space.

## Intended Use

LandMod is intended to aid in the assessment of land-management strategies and
in landscape-scale research. Alternative land-use strategies can be simulated
and compared in terms of timber production and landscape structure. Assumptions
related to the long-term responses of key ecosystem properties (carbon
sequestration, habitat diversity, wood delivery to streams) to landscape change
can be investigated with modeled experiments.

Like most landscape simulators, LandMod is best used to explore the relative
differences among land-use strategies, and as a heuristic tool for
pattern-process research studies.

## Distinguishing Features

LandMod differs from other landscape simulators through the integration of
three important features:

1. **Forest gap model core** — The forest dynamics module is based on a forest
   gap model and thus can model trees of any size over long time frames
   (500+ yrs).
2. **Fine scale over large extent** — LandMod operates at a relatively fine
   spatial scale over a large spatial extent. This allows reasonable predictions
   at the scales of proposed regional forest-management options (e.g., 0.25-ha
   leave islands), of relevant natural disturbance processes (e.g., wildfire
   effects), and of processes influencing key ecosystem properties (e.g., tree
   fall into streams). Higher-order processes (e.g., wildfire spread, seed
   dispersal) are directly integrated in the simulation of fine-scale processes.
3. **Dynamic process simulation** — Landscape trajectories are not based on
   look-up tables or pre-conceived pathways, but instead develop in response to
   feedbacks among climatic conditions, landscape pattern, and disturbances.

## Citations

Garman, S. L. 2004. Design and evaluation of a forest landscape change model
for western Oregon. *Ecological Modelling* 175(4):319–337.
([Pub No. 3780](https://andrewsforest.oregonstate.edu/publications/3780))

Garman, Steven L. 2003. LandMod 2.0 — Documentation. Corvallis, OR: Oregon
State University; model documentation, 64 p.
([Pub No. 4954](https://andrewsforest.oregonstate.edu/publications/4954))
