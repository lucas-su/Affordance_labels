# Affordance labels for RGBD datasets
This repository contains affordance labels for the NYU, Sun 3D, Sun RGBD, Scene NN, Building Parser, and (partially) the Matterport dataset. 

The data is encoded in json files in the `json` folder. As described in _Macro and Object level Affordance Data Collection to Enrich multiple RGBD Datasets_, the affordances are encoded on a high and a low level. Transfer tables for the high level affordances, for the low level affordances and for both the high and low level affordances are available for all the datasets. The encoding represents the following affordances:

High level 
- Constraind movement 
- Unconstrianed_movement
- Direct interaction
- Indirect interaction
- Observation
- Social role
- No affordances

Low level
- Rollable
- Pushable
- Draggable
- Thethered
- Carryable 
- Pourable
- Fragile
- Openable
- Graspable
- Pullable
- Pressable (button press)
- Stackable
- Cuttable/scoopable
- Supports other object
- Media transfer
- Requires other object
- Provides information
- Provides decoration
- Requires other people
- No interaction
- Provides warmth
- Provides illumination
- Traversable 
  
The procedure for collecting this data is described in _Macro and Object level Affordance Data Collection to Enrich multiple RGBD Datasets_, Luc Schoot Uiterkamp & Gwenn Englebienne, _in print_
