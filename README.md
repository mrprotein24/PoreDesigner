# (c) Ratul Chowdhury. Developed 2018. Costas Maranas Lab @PennState
# Related article: Chowdhury, R., Ren, T., Shankla, M., Decker, K., Grisewood, M., Prabhakar, J., Baker, C., Golbeck, J.H., Aksimentiev, A., Kumar, M. and Maranas, C.D., 2018. PoreDesigner for tuning solute selectivity in a robust and highly permeable outer membrane pore. Nature communications, 9(1), pp.1-10. https://www.nature.com/articles/s41467-018-06097-1 

# PoreDesigner

This is an novel tool using the IPRO suite of programs that is capable of engineering constriction region of beta-barrel (and also alpha-helical) proteins to any desired pore size and make it hydrophobic. The hydrophobicity ensures high aqueous permeation rates of solutes of interest. The limit of attainable pore size is ~ 3 angstrom. This has been used to precisely tune Ompf (pore size 11 A) to any desired pore size between 3-10 A. The highly hydrophobicity of the resultant pores have been seen to access water permeation rates that are an order of magnitude higher than any reported aquaporin till date. A separate PoreAnalyzer module is also available to analyze the profile of any pore you might have.

This is currently set up such that it requires CHARMM and GAMS licenses and the protein to be aligned such that the pore axis coincides with the Y axis. 
Contact: ratul@psu.edu

### For downloads and usage: 
### Please contact Prof. Costas D. Maranas (costas@psu.edu) for information on using PoreDesigner

## See tutorial to use PoreDesigner (LINK: coming soon !)
Note: Please have the following ready before you move to the tutorial:
1) A valid CHARMM license in your cluster/ workstation/ local where you want to run PoreDesigner
2) A PDB file of a porin/ channel protein which you want to redesign
3) A target/ permeating molecule (PDB file) placed at the central cavity of the channel protein
4) (2) and (3) could be a part of the same PDB file but need to have different chain names
5) The target molecule governs the design objective: such as (i) just allow permeation, (ii) reject, (iii) interact with the pore wall - through the channel protein.
6) In the tutorial, we are using E.coli OmpF protein and aiming to reduce its pore size to just allow water.

# PoreAnalyzer
This is a standalone script used by PoreDesigner to analyze the pore cross-section profile of any beta-barrel or alpha-helical channel protein. Note: Your porin should be aligned such that the pore axis coincides with the Y-axis; this script does not handle that.
Contact: ratul@psu.edu
