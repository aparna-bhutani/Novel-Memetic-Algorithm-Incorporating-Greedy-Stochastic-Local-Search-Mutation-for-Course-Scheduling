# Novel-Memetic-Algorithm-Incorporating-Greedy-Stochastic-Local-Search-Mutation-for-Course-Scheduling

#### Code for the paper
[A Novel Memetic Algorithm Incorporating Greedy Stochastic Local Search Mutation for Course Scheduling](https://ieeexplore.ieee.org/abstract/document/8919584)

#### Description
A new memetic algorithm is proposed in this work that hybridizes the global search strategies of Genetic Algorithm (GA) with the local search heuristics of Simulated Annealing (SA), and incorporates a greedy randomized local search mutation in GA. The basic framework of our memetic algorithm is that of GA. The population of chromosomes in every generation of GA is first refined by a local neighbourhood search for each chromosome as defined by the SA procedure, prior to the selection, crossover and mutation steps of GA. The mutation step in GA is randomized, with a greedy stochastic local search mutation being randomly selected over normal swap mutation of the fittest chromosome in each iteration of GA. The convergence of the fitness function and the stopping criterion are as determined by SA. As proved from the experimental results, this hybridization presents highly optimal solutions with fast convergence for university course scheduling which is the optimization problem addressed in this paper. Comparison to the state-of-the-art, on a benchmark dataset for university course scheduling, proves the efficacy of our approach.

#### Dataset
The dataset we used was Track 3 of International Timetabling Competition- 2007: Curriculum- based Course Timetabling (ITC-2007) dataset. It can be found here:
[http://www.cs.qub.ac.uk/itc2007/curriculmcourse/course_curriculm_index.htm](http://www.cs.qub.ac.uk/itc2007/curriculmcourse/course_curriculm_index.htm)


#### Citation
If using this code, please cite our work using :

Susan, Seba, and Aparna Bhutani. "A Novel Memetic Algorithm Incorporating Greedy Stochastic Local Search Mutation for Course Scheduling." In *2019 IEEE International Conference on Computational Science and Engineering (CSE) and IEEE International Conference on Embedded and Ubiquitous Computing (EUC)* , pp. 254-259. IEEE, 2019.
