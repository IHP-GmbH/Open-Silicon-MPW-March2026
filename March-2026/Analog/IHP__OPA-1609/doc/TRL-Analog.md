# Analog IP Quality Assessment using TRL scale

The provided set of the quality assessment criteria, using TRL (Technology Readiness Level) scale, is a tool for designers to auto evaluate a submitted design. The purpose of this tool is to
have a short overview of IP in terms of its maturity.

---

## TRL1 - Basic principles observed

- [ ] Is the IP functionality clearly described?
- [ ] Is the IP principle of operation explained in detail?
- [ ] Are the IP architecture design equations fully listed?
- [ ] Do authors supply any HDL functional model (e.g. Verilog-A) of the IP?
- [ ] Are functional simulation results of the IP reported for a typical case?

## TRL2 - Concept formulation

- [ ] Is the IP architecture described at block level?
- [ ] Are the specifications of each individual block of the IP architecture clearly identified?
- [ ] Do authors supply a complete test bench to validate the IP block-level architecture?
- [ ] Is any verification procedure given to check the IP block-level performance figures?
- [ ] Are architectural simulation results of the IP reported for a typical case?

## TRL3 - Proof of concept at schematic level

- [ ] Are the IP schematics available at transistor level?
- [ ] Are all dependencies of the IP schematics on device libraries declared?
- [ ] Are the analog IP ports fully specified at electrical level?
- [ ] Is any verification procedure given to check the IP performance figures?
- [ ] Are simulation results of the IP reported for a typical case?

## TRL4 - Full design at schematic level

- [ ] Are the simulation results of the IP extended to process, supply and temperature (PVT) corners?
- [ ] Are the simulation results of the IP extended to technology mismatching?
- [ ] Are the authors defining the supply domains of the IP and their individual power requirements?
- [ ] Does the IP description include any power consumption model (e.g. as a function of input stimuli or applied load)?

## TRL5 - Full design at layout level

- [ ] Is the IP complete layout available?
- [ ] Do authors supply a clean DRC report?
- [ ] Do authors supply a clean LVS report?
- [ ] Is a PEX netlist available?
- [ ] Are post-layout simulation results of the IP reported for PVT corners?

## TRL6 - Full design for SoC integration

- [ ] Does the IP come with suitable descriptors for analog-on-top integration (e.g. schematics, GDS, LEF)?
- [ ] Is the IP incorporating any pinout diagram?
- [ ] Does the IP document fully define its analog interface?

## TRL7 - Lab demonstrator prototype

- [ ] Has any dedicated test chip been designed for the hard IP?
- [ ] Is the hard IP test chip fully documented (e.g. pad ring)?
- [ ] Are experimental results available from the IP dedicated test chip (Silicon proven)?
- [ ] Do authors supply any comprehensive comparison between IP test chip and post-layout results?

## TRL8 - In-field demonstrator prototype

- [ ] Has the hard IP been integrated in a SoC context?
- [ ] Are experimental IP results available from this SoC (Silicon proven)?
- [ ] Do authors supply any comprehensive comparison between IP SoC and test-chip results?

## TRL9 - Commercial application

- [ ] Are the IP authors providing support for bug fixing or enhancement requests?
- [ ] Does the IP documentation include any training materials?
- [ ] Are the EDA tools and versions used for developing the IP documented?
- [ ] Is the hard IP integrated in any commercial IC?
