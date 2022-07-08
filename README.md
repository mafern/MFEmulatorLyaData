# MFEmulatorLyaData
Select simulation data and emulator predictions from arXiv:####.#####

Simulation data sets, in HDF5 format, include Lyman-$\alpha$ forest flux power spectra for three sets of simulations; low resolution (LF_flux_vectors.hdf5), high resolution (HF_flux_vectors.hdf5), and testing (TEST_flux_vectors.hdf5).
Each HDF5 file has an associated parameter file in JSON format (LF_params.json, HF_params.json, TEST_params.json).

Redshifts are from 
$z=5.4-2$ spaced by 
$\Delta$z$=0.2$.

Multi-fidelity folders (MF-30-5, MF-40-6) contain Lyman-$\alpha$ forest flux power spectra for select multi-fidelity emulators, in plain text format (for use with the multi-fidelity emulation code in [lya_emulator_full](https://github.com/sbird/lya_emulator_full)).

Prediction files in plain text format include emulator mean and std for select single-fidelity (LF40_preds.txt, HF6_preds.txt) and multi-fidelity emulators (MF-30-5_preds.txt, MF-40-6_preds.txt). The note gives details on the structure of the predicition files.
