# Predicting_Scalar_Coupling_Constant
"Predicting Molecular Properties" www.kaggle.com/c/champs-scalar-coupling 

The goal of competition is predicting constants of scalar coupling between two atoms in molecule
based on coordinates of atoms in molecule.

Presented two ways of predicting: using decision tree and neural network.
Features created are order of scalar coupling, distances from interacting atoms to each other
and their closest neighbours and interatomic angles.

Other features like dihedral angles and further distances were not taken because of computational costs.

Decision tree gives nice results but has a tendency to overfit, while neural network gives a nice predictions for
large interactions and sufficient mistakes for small ones beacuse other atoms are involved in interaction.
