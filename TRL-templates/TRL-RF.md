# RF IP Quality Assessment using TRL scale

The provided set of the quality assessment criteria, using TRL (Technology Readiness Level) scale,
is a tool for designers to auto evaluate a submitted design. The purpose of this tool is to
have a short overview of IP in terms of its maturity.

---

## TRL1 - Basic principles observed

- [x] Is the IP functionality clearly described?
- [x] Is the system application defined (radar, communication etc.)?
- [x] Is the specification available (architecture, frequency bands etc.)?
- [ ] Are the basic calculations like link budget available?

## TRL2 - Concept formulation

- [ ] Is the system described at block level (EIRP, SNR, Modulation type, port specification, power budget, chip area, measurement procedure)?
- [ ] Is the IP targeting specific technology (CMOS, BiCMOS etc.)?
- [ ] Are the specifications of each individual block (amplifier, mixer, VCO, PLL, antenna) clearly identified and compatible with the proposed technology?
- [ ] Do authors supply a complete test bench to validate the IP block and system (Gain, output power, bandwidth etc.)?
- [ ] Is any verification procedure given to check the IP block-level performance figures of merit?
- [ ] Are system level simulation results of the IP reported for a typical conditions?

## TRL3 - Proof of concept at schematic level

- [ ] Is the specifications for the tools, PDK's and flows available?
- [ ] Are the IP schematics available at device level?
- [ ] Are the RF components (inductors, transmission lines, transformers) validated using EM simulation?
- [ ] Are the ports (single, differential, dc coupled, ac coupled) fully specified at electrical level (impedance, amplitude levels)?
- [ ] Is the power budget clearly defined (supply voltage, current consumption)?
- [ ] Are the verification procedures (test benches) given to check the IP performance figures of merit (gain, output power, bandwidth, stability, etc.)?
- [ ] Are simulation results of the IP reported for a typical case?

## TRL4 - Detailed design at schematic level

- [ ] Are the simulation results of the IP extended to process, supply and temperature (PVT) corners and mismatch analysis?
- [ ] Is thermal budget defined?
- [ ] Is ESD protection evaluated and implemented?
- [ ] Are simulation results of the IP reported using statistical modeling (Monte Carlo, Worst Case)?

## TRL5 - Full design at layout level

- [ ] Is the IP complete layout available?
- [ ] Do authors supply a clean DRC report?
- [ ] Do authors supply a clean LVS report?
- [ ] Are post-layout RF simulation results of the IP layout reported for PVT corners?

## TRL6 - Full design for SoC integration

- [ ] Does the IP come with design files (schematic libraries, symbol, test benches, final GDS)?
- [ ] Does the IP comes with documentation, which contains: (schematic library description. simulation results, layout description, IO pads specification, integration howto, pin configuration)?

## TRL7 - Lab demonstrator prototype

- [ ] Has this IP been manufactured?
- [ ] Is the IP test chip fully documented (test field documentation)?
- [ ] Are experimental results available from the IP dedicated test chip (mdm files, measurement reports)?
- [ ] Do authors supply any comprehensive report comparing IP test chip measurements results against post-layout simulations?

## TRL8 - In-field demonstrator prototype

- [ ] Has the hard IP been integrated in a SoC context?
- [ ] Are experimental IP results available from this SoC (Silicon proven)?
- [ ] Do authors supply any comprehensive comparison between IP SoC and test-chip results?

## TRL9 - Commercial application

- [ ] Are the IP authors providing support for bug fixing or enhancement requests?
- [ ] Does the IP documentation include any training materials?
- [ ] Are the EDA tools and versions used for developing the IP documented?
- [ ] Is the hard IP integrated in any commercial IC?
