LTspice Control Library
===========================
LTspice Control Library provides a set of control elements, that allow to design a controller of a circuit by drawing
a control block diagram and simulate the circuit and the controller on LTspice IV.

![3PhaseInverter example](examples/DC-ACConverter/3PhaseInverter.png)

Installation
==============
1. Run the script "LTspiceControlLibrary\install.bat" as Administrator.  
  This script works as below:
  * Search the installation directory of LTspice IV. (default: LTSPICE_DIR=C:\Program Files\LTC\LTspiceIV)
  * Copy "LTspiceControlLibrary\lib\sub\LTspiceControlLibrary" to "%LTSPICE_DIR%\lib\sub\LTspiceControlLibrary".
  * Copy "LTspiceControlLibrary\lib\sym\LTspiceControlLibrary" to "%LTSPICE_DIR%\lib\sym\LTspiceControlLibrary".
2. Restart LTspice IV. The library should be now usable. 
3. Try examples in "LTspiceControlLibrary\examples" to confirm installation and learn how to use this library.
