# EIT-Hardware-Design#

Electrical Impedance tomography(EIT) is widely regarded as a persistent non-invasive
technique holding the full potentiality to utilize in the field of chemical reactor.
Distinct parameters that are liable to change the catalyst inside a reactor can be
demonstrated with allowable spatial resolution. An extensive research over different
possible measurement schemes has been gone through and based on that a potential
approach (VC-EIT or voltage mode EIT) has been selected for data acquisition and
processing of the data gathered from a possible reactor environment.

In this project work, a complete hardware setup comprises of 3 distinct parts; power
generation, excitation creation, and data processing is designed based on the indepth
analysis of concerning design criteria.The whole design has been substantiated
through the ’System Level Verification’ process in Texas Instrument’s "TINA-TI"
software while precisely evaluating every associated active and passive component
value through analyzing the mathematical models and simulation diagrams. Additional
Noise models have been generated based on the values mentioned in the
data sheet and added with respective components to derive the noise margin. The
schematic contains more than 16 channels to check the feasibility of applying for
large number of electrodes in a certain system.

This designed hardware will be capable of measuring impedance ranging from 300Ωto
20kΩ for the frequency of 10KHz-100KHz.The converted voltages of the recorded
currents from the electrodes have sufficient peak to peak value reducing any problem
due to improper voltage headroom. The accumulated settling times of the components
of the whole signal chain is extremely low, in the nonoampere(nA) range which
is prompting to the faster measurement system. The system SNR can be achieved
above 91 dB with 2.5 MSPS sampling rate for ADC. Finally, a custom PCB layout
with 4 channels is designed in KICAD software as the prototype with a test bench
of different impedance values so that key specifications of hardware can be verified
without having a practical test platform.
