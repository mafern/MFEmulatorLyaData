# MFEmulatorLyaData
Select simulation data and emulator predictions from arXiv:####.#####

Simulation data sets, in HDF5 format, include Lyman-$\alpha$ forest flux power spectra for three sets of simulations; low resolution, high resolution, and testing.
Each HDF5 file has an associated parameter file in JSON format.
Redshifts are from $z=5.4$ to $z=2$ spaced by $\Delta z = 0.2$.

Multi-fidelity folders contain Lyman-$\alpha$ forest flux power spectra for select multi-fidelity emulators, in plain text format (for use with the multi-fidelity emulation code in [lya_emulator_full](https://github.com/sbird/lya_emulator_full)).

Prediction files in plain text format include emulator mean and std for select single- and multi-fidelity emulators.
