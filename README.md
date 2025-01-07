Hi all,

The information of one-to-one correspondence between indexes and elements is stored in line 6 and 7. The rule is: in the example XDATCAR file, the first four lines after 
line 8 belong to the hydrogen atoms, the next 49 lines belong to the oxygen atoms, etc. Columns 1 to 3 correspond to atoms x, y, and z, respectively.
The visualization tool we are using "ase gui" in a python package called Atomic Simulation Environment (ASE).
By using this tool, you can identify the actual atoms that correspond to the index. 

The zeolite framework is not rigid. No atom was fixed or constrained during the simulation.

The main Zheng's file is: XDATCAR_mlff_1h2o2alafi_1_istart0
