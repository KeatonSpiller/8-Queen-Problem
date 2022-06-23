# 8-Queen-Problem
8 Queen Problem Using a Genetic Algorithm

1. Change the hyper parameters
PopulationSize to change the size of the random states of queen boards to begin with.
MutationPct takes a percentage to mutate the children randomly, (only accepting whole percentages).
iterations is how many iterations to generate children from parents.
samples_wanted to determine how many random samples you want from the initial and final population.

PopulationSize = 1000 # experiment with 10, 100, 500, 1000
MutationPct = 0.05 # 5 percent mutate rate
iterations = 1000 # iterations to run
samples_wanted = 3 # How many samples

2. Run the genetic_algorithm( PopulationSize, MutationPct, iterations)
The code is seperated into three code blocks, one to run the genetic algorithm based on the specifications,
the second to print out the different samples of the results.
And the third code block is to plot the results.

3. Print samples of the pool of board states, and the final children/parents generated

4. Visualize the plot of average fitness
