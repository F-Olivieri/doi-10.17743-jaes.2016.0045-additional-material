# Comparative analysis of beamforming methods for the reproduction of a target signal - Audio demonstration

Copyright 2016 Ferdinando Olivieri

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License version 3 published by the Free Software Foundation. 

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with BeamformingTargetSig_Listen. If not, see <http://www.gnu.org/licenses/>.

If you use this software, please cite the paper below and share any modifications you make (as per license) with the author either by contributing to this repository or by sending an email to F-Olivieri@users.noreply.github.com

## Intro
BeamformingTargetSig_Listen is a software written in Cycling 74 MaxMSP by Ferdinando Olivieri (F-Olivieri@users.noreply.github.com). 

The software is associated to the paper:
F. Olivieri, F. M. Fazi, P. A. Nelson, and S. Fontana, “Comparison of Strategies for Accurate Reproduction of a Target Signal with Compact Arrays of Loudspeakers for the Generation of Zones of Private Sound and Silence,” J. Audio Eng. Soc., vol. 64, no. 11, pp. 905–917, 2016. DOI: 10.17743/jaes.2016.0045. <http://www.aes.org/e-lib/browse.cfm?elib=18527>

This MaxMSP patch allows the reader to listen to the simulated responses of the beamforming filters presented in the paper above. The responses of the filters are calculated using the measured in the ISVR anechoic chamber. More details about the filter design and measurement of their responses are given in the paper above.

The software uses the multiconvolve object by By Alex Harker and Pierre Alexandre Tremblay CeReNeM - The University of Huddersfield
https://github.com/HISSTools/HISSTools_Impulse_Response_Toolbox - http://eprints.hud.ac.uk/14897/ - 
Harker, Alexander and Tremblay, Pierre Alexandre (2012) The HISSTools Impulse Response Toolbox: Convolution for the Masses. In: ICMC 2012: Non-cochlear Sound. The International Computer Music Association, pp. 148-155. ISBN 9780984527410

[![DOI](https://zenodo.org/badge/20316/F-Olivieri/BeamformingTargetSig_Listen.svg)](https://zenodo.org/badge/latestdoi/20316/F-Olivieri/BeamformingTargetSig_Listen)

Tested with Win and OSX 64-bit versions of MaxMSP 7.x.

## Instructions
1. Download ZIP file from Github repo and extract it on your machine.
2. Download the audio files from http://eprints.soton.ac.uk/id/eprint/396931 and extract them in the media folder of the MaxMSP project
3. Open AccReprTargetField_Listen.maxproj
