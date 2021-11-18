# Qiskit Global Hackaton 2021
### VARIATIONAL QUANTUM CIRCUITS IN A PROTEIN NETWORK GRAPH
##### To map biochemical interactions inside a 3D-protein structure into a graph network to find bounding amino acids function using a VQA
### Objectives
- To find bounding amino acids function on a delimited network graph approach that characterized a chemical structure using a variational quantum circuit.
- To apply quantum circuits used in graph theory and optimization problems to map 3D-protein structure into chemical interaction network.
- Using the QAOA variational form to find an approximate solution for the protein folding quadratic program.
- To encourage people to push into quantum computing and solve real molecular biology problems faster than classical methods.


### With number of atoms in the molecule (YA., A., and HA, 2006).
- Hydrophobic.Disulfide (bridnge)
- Hydrogen bonds
- Ionic and aromatic (partial)
- Cation-π.Peptide bond

## Graph network methodology
Graph network of 1Plxa. Each edge corresponds to one of the following biochemical interactions:

*   Hydrophobic 
*   Disulfide (bridnge)
*   Hydrogen bonds
*   Ionic and aromatic (partial)
*   Cation 
*   Peptide bond
<p align="center">
  <img src="https://user-images.githubusercontent.com/55018955/142352830-bd68821f-3e7a-44b8-80fa-3adfcd642b8f.png" alt="Formula"/>
  </p>
  
  
First we represent Amino Acids asnodes of graph network. Then we perform its graph reduction.
### Classic solution
We implement a classical solution using the algorithm travelingsalesman as an NP-complete problem. for protein folding problembased on a protein network graph to find bounding amino acids, themain objective is to find the nodes with more interactions orweights (proteins with more connections)

### Brute force Approach 


### Quantum Computing Approach
Protein folding problem base on the travelling salesman.
### Quadratic program to QUBO
In this case we need to maximize the cost function:
## Running on a Quantum Computer
