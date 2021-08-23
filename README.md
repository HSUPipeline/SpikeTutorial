# SpikeTutorial

This is a tutorial for working with spiking data, in particular single-unit data collected from human subjects.

## Overview

For a related list of relevant tools and resources, see the 
[SpikeResources](https://github.com/openlists/SpikeResources)
open list.

## Data

There are two data files associated with this tutorial:
- `object_data.nwb` is an example data file with a visual object recognition task
- `spatial_data.nwb` is an example data file with a spatial task

Note that these datafiles are organized in the
[NWB](https://www.nwb.org/)
format.

For examples and resources relating to storing human single neuron data in NWB files, see these
[NWB Examples](https://github.com/TomDonoghue/NWBExamples).

## Requirements

As well as standard scientific Python modules (numpy, matplotlib, etc), this repository requires:
- [pynwb](https://github.com/NeurodataWithoutBorders/pynwb)

The full set of requirements is described in the `requirements.txt` file.
