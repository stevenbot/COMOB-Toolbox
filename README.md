matlab-contam-toolbox
=====================

The `Matlab-CONTAM Toolbox` is an open-source software which operates within the Matlab environment, for providing a programming interface for [CONTAM](http://www.bfrl.nist.gov/IAQanalysis/CONTAM/), a multizone airflow and contaminant transport analysis software with Matlab, a  high-level technical computing software. The goal of the Toolbox is to serve as a common programming framework for research, which facilitates simulating multiple contamination events under varying conditions as well as to store computed data in data structures so that they can be reused by different algorithms.

The `Matlab-CONTAM Toolbox` features a user-friendly Graphical User Interface (GUI) and a modular architecture. It allows the creation of multiple scenarios by varying the different problem parameters (wind direction, wind speed, leakage path openings, source magnitude, evolution rate and onset time) as well as the storage of the computed results in data structures. The data from these scenarios are further analyzed by the developed algorithms for determining solutions for contaminant event monitoring and sensor placement. 

# Requirements #
* [Matlab](http://www.mathworks.com/)
* [CONTAM v3.1](http://www.bfrl.nist.gov/IAQanalysis/CONTAM/)

# How to cite this work #

Holmes House
* Wang, L.; Dols, W. & Chen, Q. (2010), 'Using CFD Capabilities of CONTAM 3.0 for Simulating Airflow and Contaminant Transport in and around Buildings', HVAC&R Research 16(6), 749--763.

# Licences #

## 1. Matlab-CONTAM Toolbox##
Copyright 2013 KIOS Research Center for Intelligent Systems and Networks, University of Cyprus (www.kios.org.cy)

Licensed under the EUPL, Version 1.1 or – as soon they will be approved by the European Commission - subsequent versions of the EUPL (the "Licence");
- You may not use this work except in compliance with the Licence.
- You may obtain a copy of the Licence at: (http://ec.europa.eu/idabc/eupl)

Unless required by applicable law or agreed to in writing, software distributed under the Licence is distributed on an "AS IS" basis, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.

See the Licence for the specific language governing permissions and limitations under the Licence.

## 2. CONTAM & SimRead3##

Software Disclaimer

This software was developed at the National Institute of Standards and Technology by employees of the Federal Government in the course of their official duties. Pursuant to title 17 Section 105 of the United States Code this software is not subject to copyright protection and is in the public domain. CONTAM is an experimental system. NIST assumes no responsibility whatsoever for its use by other parties, and makes no guarantees, expressed or implied, about its quality, reliability, or any other characteristic. We would appreciate acknowledgement if the software is used.

This software can be redistributed and/or modified freely provided that any derivative works bear some notice that they are derived from it, and any modified versions bear some notice that they have been modified.

Certain trade names or company products are mentioned in the text to specify adequately the experimental procedure and equipment used. In no case does such identification imply recommendation or endorsement by the National Institute of Standards and Technology, nor does it imply that the equipment is the best available for the purpose.

CVODE COPYRIGHT INFORMATION
The following copyright information is provided with regard to the implementation of the CVODE solver as a specific solution method within the CONTAM solver.

Copyright - 2002, The Regents of the University of California.
Produced at the Lawrence Livermore National Laboratory.
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
- Redistributions of source code must retain the above copyright notice, this list of conditions and the disclaimer below.
- Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the disclaimer (as noted below) in the documentation and/or other materials provided with the distribution.
- Neither the name of the UC/LLNL nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE REGENTS OF THE UNIVERSITY OF CALIFORNIA, THE U.S. DEPARTMENT OF ENERGY OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

Additional BSD Notice
- This notice is required to be provided under our contract with the U.S. Department of Energy (DOE). This work was produced at the University of California, Lawrence Livermore National Laboratory under Contract No. W-7405-ENG-48 with the DOE.
- Neither the United States Government nor the University of California nor any of their employees, makes any warranty, express or implied, or assumes any liability or responsibility for the accuracy, completeness, or usefulness of any information, apparatus, product, or process disclosed, or represents that its use would not infringe privately-owned rights.
- Also, reference herein to any specific commercial products, process, or services by trade name, trademark, manufacturer or otherwise does not necessarily constitute or imply its endorsement,  recommendation, or favoring by the United States Government or the University of California. The views and opinions of authors expressed herein do not necessarily state or reflect those of the United States Government or the University of California, and shall not be used for advertising or product endorsement purposes.
