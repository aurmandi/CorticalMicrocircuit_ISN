## Overview
This project investigates the dynamic properties of a biologically-inspired cortical microcircuit using the NetPyNE simulation framework.
The study focuses on understanding gain control mechanisms and testing for Inhibition-Stabilized Network (ISN) properties through targeted optogenetic manipulations.

### The model simulates a network of 100 neurons comprising four distinct cell populations across cortical layers:

Exc_L23 & Exc_L5: Pyramidal excitatory neurons.

Inh_PV: Fast-spiking Parvalbumin-expressing inhibitory interneurons.

Inh_SOM: Somatostatin-expressing inhibitory interneurons.

### Project Structure
`cortical_microcircuit_assignment#2.ipynb`: The primary Jupyter Notebook containing the model definition, simulation code, and analysis.

`results/`: Directory where simulation data (JSON, CSV) and figures (Raster plots, traces) are saved.

`morph`: Contain 3 SWC files for realistic modeling of cells in our net. 
