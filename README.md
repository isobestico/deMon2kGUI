# deMon2kGUI

Author: Jonathan Kung

Dennis Salahub, Mauricio Chagas da Silva

University of Calgary

### Purpose
Create a simple GUI to allow users to easily make a demon2k input
![](https://github.com/jankangle/Python/blob/master/Programs/deMon2kGUI/demon2k%20input.jpg)

### Required Information
* Must not leave any entries blank
* Can input your own XC Functional, Basis set, Auxis set,and ECP by inputting into the box and pressing 'Enter'
* Must put tolerance in the format X.YE-5 example: `1.0E-5`
* If Shift is 0, input `0` into the entry to not have it show up in the input
* Frequency calculation is required for Thermo calculation
* Geometry input file must only contain coordinates. example: delete the first 2 lines from a Molden, Jmol, or Avogadro xyz output
* Max number of atom coordinates from geometry input is set at 101

### Additional Information
* Default basis set is DZVP
* Default auxis set is A2
* Default VXCTYP is auxis
* Default max iterations for scf is 200
* Default KS type for closed-shell system is RKS, and for open-shell systems it is ROKS
* Default guess is TB
* Default Tolerance is 1.0E-5
* Default multiplicity is 1 for closed and 2 for open-shell systems
* Default charge is 0
* Default for Grid setting is 'Do not fix'. Default grid fix setting is 'Medium'


### Future Work
* Max iterations for Optimization
* More organized Layout for GUI
* Checkbox options that would show more options (ie. ECP Y/N, if Y then show ECP settings)


