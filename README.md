# RDKit
This project focuses on determining the RDKit molecules for the following molecules Propane, Ethene, Cyclohexane and
Buckminsterfullerene. The number of atoms, the chemical symbol, the number of aromatic bonds, and atomic weight of each 
atom in the molecule will also be determined. The molecules will also be drawn for better visualization of the structure
of the molecule. 

## Dataset
When creating the RDKit Molecules, the PubChem CID for the compunds needs to be accessed using the get_compounds function
so that we can be able to utilize the isomeric_smiles function from pubchempy library that will allow us to get the smiles
of each compound. After the accessing of smiles, the conversion of those smiles to RDKit molecules can take place. The number 
of atoms in each molecule can now be determined followed by the chemical symbol, atomic weight and number of aromatic bonds.

## Molecule drawing
Now we can see the structure of the molecules in the below screenshot:

![image](https://github.com/user-attachments/assets/74c4e8ad-03c1-4585-8806-957729fb27d6)

### Requirements
To run the project, ensure you have the following installed:

- **Python 3.8+**
- **Libraries**
  - **pandas**
  - **numpy**
  - **pubchempy**
  - **RdKit**
  - **matplotlib**

### Future Work
  - Add more molecules.
  - Integrate the model into a web application for real-time interactivity.
