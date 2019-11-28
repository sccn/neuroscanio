# neuroscanio
Import .CNT, .EEG Neuroscan binary files as well as Neuroscan epoch file (.DAT) and Neuroscan event files (.EV2) into EEGLAB. There are also functions to import Neuroscan ASCII (text) location files from the command line as well as a beta function to export continuous CNT files from the command line.	

Version 1.3 update
- loadcnt can now read events for files larger than 1Gb. Contribution from edauer1 on Github.

Version 1.2 update
- pop_writeeeg.m was removed and placed back in the main EEGLAB distribution (it was a mistake to include it in the first place as it is designed to export EDF and BDF files, not Neuroscan files)
