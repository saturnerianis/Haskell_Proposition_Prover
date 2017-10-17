# Haskell_Proposition_Prover

Authors, Robert Fleischman, Steven Tvardzik

The goal of this project is to create a program in Haskell which takes in a sequence of assumptions expressed as statements of propositional logic and a goal statement and, using the rules of propositional logic, attempts to generate a sequence of intermediate statements together with a justification for those statements, linking the assumptions to the goal and thus proving the goal. For example suppose the assumptions are, {if A then B, if B then C, A} and the goal is C, the solver might output {if A then C: by hypothetical syllogism, C: by modus ponens} thus proving C from the initial assumptions.
