# Argus Gateware

`argus-gateware` contains FPGA gateware for the Argus Cybernetics platform, focused on real-time neural signal processing, 
adaptive decoding, and closed-loop brain-computer interface research. The long-term goal of this repository is to provide 
the hardware-accelerated signal-processing layer for future Argus systems. This may include acquisition interfaces, 
filtering pipelines, event/spike detection, feature extraction, decoder acceleration, stimulation-control support logic, 
and reconfigurable processing modules. In the broader Argus architecture, this gateware is intended to operate under the 
supervision of the Argus Safety Controller. The safety controller will be responsible for coordinating system-level 
constraints, validating operating modes, enforcing safety boundaries, and determining when FPGA-based processing or 
control paths are allowed to participate in the larger closed-loop system. This repository is intentionally early-stage 
and hardware-description-language agnostic. Its structure and implementation details may evolve as the Argus safety model, 
neural-interface architecture, and target FPGA platforms become more clearly defined.

Currently exploring how I can apply my existing embedded knowledge to the Zync FPGA-SoCsand if the Zynq chip family is right for the Argus project.

## Todos 

1. Flash Arty 7Z 20 with JTAG: https://chatgpt.com/g/g-p-68d7f48dab6c8191a3f9e510a895cf77/c/6a430505-ed54-83e8-ad73-c749f0c0dc39c0dc39

2. Generate a new overview for the project after the previous step has been completed

## Glossary

Xilinx Support Archive(XSA): A *.xsa file is a Vivado generated handoff file that tells Vitis what hardware exists on the FPGA-SoC design for building a matching embedded software platform. 
