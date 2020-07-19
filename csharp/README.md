# Introduction to the Files
+ 1. The ten folders each contains the implementation of one algorithm tested in our paper. 
+ 2. The implementation of each algorithm is based on IMM and thus follows the same pattern, where notably the algorithm is realized in Program..s; 
+ 3. Four datasets are included for test, i.e., Wiki-Vote, CA-CondMat, com-dblp, soc-LiveJournal1, covring networks that scales from thousands of nodes to millions of nodes.
+ 4. The files suffixed with "ini100" or "ini1000" are generated by "initial.py" and record the initial users, i.e., set X in the paper. "reform.py" converts undirected graphs to directed graphs as required in the paper; assign the seed probability type to each user; and generate the threshold value for each user that is used in adaptive algorithms.