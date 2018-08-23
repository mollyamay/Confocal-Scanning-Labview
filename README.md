# Confocal Labview
Integrates communication with Physike Instrumente scanner, Princeton Instruments spectrometer, and WindFreak technologies RF generator to enable confocal and MW scanning.

The main branch of this code is designed to measure the emission of NV centers under RF drive. It scans the RF frequency and records spectra from each point. It can also take a spatio-spectral confocal scan of a sample which can be processed by the code in the hyperspectral imaging repo.

Other branches simplify the functionality to just confocal scanning. There is also an option to take a step in the z direction half way through a scan which was added to look at a sample with a discrete step in its thickness.
