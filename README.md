# VarianProBeamTOPASModel
Varian ProBeam beam model beyond the snout of the machine.

The snout is located at z= +42 cm upstream from the isocenter. Each of the folders includes files that simulate the beam source for each of the commissioned energies of the Varian ProBeam (e.g. Energy70MeV, Energy80MeV, etc.). The "PhaseSp.zip" files include the phase space files in ASCII format at the snout. It can also be produced from each of the "BeamSource...txt" files by running the file on TOPAS MC toolkit. The phase space files produce a beam of 1 MU based on protons/MU results and dose measured at 2 cm depth in water. The ReadASCII.txt gives an example of how to run simulations using the phase space beam source files.

"Beam_Lookup_Table.xlsx" provides a look up table with all the beam parameters (e.g. spot size, angular spread, correlation coefficient, mean energy, standard deviation of energy)  of the commissioned energies. This can be used to produce beam parameter of in-between energies (e.g. 75.5 MeV energy beam) and specify as energy distribution and emmittance parameters for beam shaping.


The details and development of the model is described in: Rahman M, Bruza P, Lin Y, Gladstone DJ, Pogue BW, Zhang R. Producing a Beam Model of the Varian ProBeam Proton Therapy System using TOPAS Monte Carlo Toolkit. Medical Physics. Published online October 8, 2020. doi:10.1002/mp.14532
