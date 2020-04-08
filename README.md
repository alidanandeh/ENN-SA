# ENN-SA
ENN-SA process:

1. Run ENN
2. Export bias and weight of ENN
3. Run SA by sa.m file
3. Optimize bias and weight of ENN by SA
4. Run ENN by optimized values of bias and weight
5. Result of ENN-SA

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

ENN file detail:

1. ENN.m ------------------------------------------------------> model runnig for multi-station drought prediction

#########################################################################################################################################

SA file details:

1. sa.m --------------------------------------------------------> Simulated annealing runnig
2. ApplyInsertion.m --------------------------------------------> Function of SA
3. ApplyReversion.m --------------------------------------------> Function of SA
4. ApplySwap.m -------------------------------------------------> Function of SA
5. CreateModel.m -----------------------------------------------> Function of SA
6. CreateNeighbor.m --------------------------------------------> Function of SA
7. CreateRandomSolution.m --------------------------------------> Function of SA
8. PlotSolution.m ----------------------------------------------> Function of SA
9. RouletteWheelSelection.m ------------------------------------> Function of SA
10. TourLength.m -----------------------------------------------> Function of SA
