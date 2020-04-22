# Project-2

## Automaton

### Rule getRule()
Returns the rule that the Automaton is on
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### Generation getGeneration(int stepNum)
Returns the generation number that Automaton is on
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### BoundaryConditions getBoundaryConditions()
Returns the BoundaryConditions that the Automaton is using
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### evolve(int numSteps)
Creates a method to evolve the Automaton a given number of steps
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### int getTotalSteps()
Returns the total number of steps the method has gone
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### String toString()
Returns a string in a specific format for the Automaton to output
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### String getHistory()
Returns the history of the Automaton
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

## AutomatonMeasurements

### int hammingDistance(Generation g1, Generation g2)
Calculates the hamming Distance between two generations
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### int hammingDistance(int stepNum, Automaton a)
Calculates the hamming distance between two successive generations
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### int[] hammingDistances(Automaton a)
Calculate the Hamming distance for each pair of successive generations
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### int[] subruleCount( int stepNum, Automaton a)
Count the number of times each subrule is applied during the given evolution step.
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### int[][] subruleCounts(Automaton a)
Return the subrule counts for every evolution step
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

## Cell

### Cell getState()
Return the state of the cell
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### String toString()
Return the String format of the cell
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### Cell getNeighbor(int cellIdx, int offset, Generation gen)
Returns a cell with a specific index
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

## ElementaryRule
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### int getNumSubrules()
Gets the number of subRules that can be used
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### Cell[] getNeighborhood(int cellIdx, Generation gen gen, BoundaryConditions bc bc)
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### EvolvedCell evolve(Cell[] neighborhood)
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### String toString()
Return a two-line string representation of the rule table, using the characters that represent CellState.OFF and CellState.ON
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### EvolvedCell int getSubruleNum()
Gets the subRuleNum
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

## FixedBoundaryConditions

### CellState getLeftState()
Gets cellstate to the left of cell
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### CellState getRightState()
Gets cell state to the right of cell
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### Cell getNeighbor(int cellIdx, int offset, Generation gen)
Returns state of all cells around cell
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

## Generation
### Generation(CellState[] states)
Construct a Generation of regular Cell objects from an array of CellStates
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### Generation(Cell[] cells)
 A reference to an array of Cells
 - [] (before:) test
- [] (after:) test
- [] (and later:) implement

### Generation(String states)
Construct a Generation of regular Cell objects from a String of characters representing cell states
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### Cell getCell(int idx)
 Construct a Generation from an array of Cells.
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

## Rule

### int getRuleNum()
Return the number of subrules used to determine the next state of a cell from its neighborhood 
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### Generation evolve(Generation gen,BoundaryConditions bc)
Apply the rule to a given Generation, subject to the given boundary conditions, to calculate the next Generation
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

## TotalistRule

### TotalistRule(int ruleNum)
If the given integer is not a valid rule number, throw an InvalidRuleNumException
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### int getNumSubrules()
Gets number of sub rules which is 6
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### Cell[] getNeighborhood(int cellIdx, Generation gen gen, BoundaryConditions bc bc) 
Returns the getter for the neighborhood of the cell
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### EvolvedCell evolve(Cell[] neighborhood)
Will evolve the cell
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

### String toString() 
Return a string representation of the rule table
- [] (before:) test
- [] (after:) test
- [] (and later:) implement

