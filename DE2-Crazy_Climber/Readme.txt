Crazy Climber Arcade for the Altera DE2-35 Dev Board.

Notes:
Setup for 1 player arcade controls (10 switches) (coin-start-lup-ldown-lleft-lright--rup-rdown-rleft-rright).
Each switch is connected one side to DE2 I/O Pin and other side to DE2-Gnd pin (pin12 on GPIO(0)Pin Header).
Pin Header locations are specified in the "crazy_climber_de2.qsf" File.

Build:
* Obtain correct roms file for crazy climber "cclimber.zip", see script in tools/cclimber_unzip folder for rom filenames.
* Unzip rom files to tools/cclimber_unzip folder.
* Run the make crazy climer proms script in the tools/cclimber_unzip folder.
* Open the crazy_climber_de2 project file using Quartus and compile.
* Program DE2 Board.
