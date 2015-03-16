CSPP_DIM extends the CSPP_Core package of the CS++-Project. 

It contains a derived classes of
- CS++PVConnection
- CS++PVMonitor
- and two example classes: 
  - CS++DIM-Server (actor)
  - CS++DIM-Client (actor)

Refer to https://github.com/HB-GSI/CSPP for CS++ project overview, details and documentation.

LabVIEW 2014 is the currently used development environment.

Related documents and information
=================================
- README.txt
- Release_Notes.txt
- EUPL v.1.1 - Lizenz.pdf
- Contact: H.Brand@gsi.de or D.Neidherr@gsi.de
- Download, bug reports... : http://github.com/HB-GSI/CSPP_DIM
- Documentation:
  - Refer to package folder
  - Project-Wiki: https://github.com/HB-GSI/CSPP/wiki
  - NI Actor Framework: https://decibel.ni.com/content/groups/actor-framework-2011?view=overview

GIT Submodules
==============
This package can be used as submodule
- Packages\CSPP_DIM:
  - CS++DIMConnection
  - CS++DIMMonitor
  - Example\CS++DIM-Server
  - Example\CS++DIM-Client

External Dependencies
---------------------
- CSPP_Core: http://github.com/HB-GSI/CSPP_Core
- Dim-Stuff: https://github.com/HB-GSI/DimLVEvent

Optional submodules
-------------------

Getting started:
=================================
- Add DimLVEvent\LVDimInterface\LVDimInterface.lvlib into your own LabVIEW project.
- Add CSPP_DIM\CS++DIMContent.vi into your desired case of the CS++UserContents.vi
- You need to extend your project specific ini-file.
  - A sample ini-file should be available on disk in the corresponding package folder.


Author: H.Brand@gsi.de, D.Neidherr@gsi.de

Copyright 2015  GSI Helmholtzzentrum für Schwerionenforschung GmbH

Planckstr.1, 64291 Darmstadt, Germany

Lizenziert unter der EUPL, Version 1.1 oder - sobald diese von der Europäischen Kommission genehmigt wurden - Folgeversionen der EUPL ("Lizenz"); Sie dürfen dieses Werk ausschließlich gemäß dieser Lizenz nutzen.

Eine Kopie der Lizenz finden Sie hier: http://www.osor.eu/eupl

Sofern nicht durch anwendbare Rechtsvorschriften gefordert oder in schriftlicher Form vereinbart, wird die unter der Lizenz verbreitete Software "so wie sie ist", OHNE JEGLICHE GEWÄHRLEISTUNG ODER BEDINGUNGEN - ausdrücklich oder stillschweigend - verbreitet.

Die sprachspezifischen Genehmigungen und Beschränkungen unter der Lizenz sind dem Lizenztext zu entnehmen.