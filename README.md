# musical-guacamole
1.	Run python script split_pdb_to_chain.py in the PDB initial coordinates. This script will split to different chain and to ligands, and write them to different files:
2.	Run python script extract_symmetry.py in the PDB initial coordinates directory. This script will create *dat file that CHARMM will read in step #.
For the Proteins structures:  
3.	Run bash script step1_fixpdb.sh, this script will run the pdbfix.pl (Perl script) that should be in the same directory. The pdbfix.pl will modify the HIS to the corrects protonation state. 
4.	 Run bash step2_createinput_and_ligands.sh (change the name) 
