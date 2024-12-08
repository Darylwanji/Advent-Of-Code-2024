# Advent of Code 2024

My solutions for Advent of Code 2024 challenges.

## Daily Challenges

### Day 1: [Hystorian Hysteria]
Description: 
1. Context: The Chief Historian is missing, and Elvish Senior Historians are checking historically significant locations.   
2. Part One: Calculate the total distance between paired numbers from both lists by summing the absolute differences of sorted pairs.
3. Part Two: Compute a similarity score by multiplying each number in the left list by its frequency in the right list and summing these products.

4. Implementation: Python code is provided to read input, process the lists, and compute distances and similarity scores.
   
[[Day 1]](https://github.com/Darylwanji/Advent-Of-Code-2024/tree/main/Day1)

### Day 2: [Red Nosed Reports]
Description: 
1. Context: The engineers at the Red-Nosed Reindeer nuclear plant need help analyzing reports of levels, which are lists of numbers.
2. Part One: A report is considered safe if:
    - The levels are either strictly increasing or strictly decreasing.
    - The difference between any two adjacent levels is between 1 and 3.
3. Part Two: Introduces the Problem Dampener, which allows for one bad level to be removed from an otherwise safe report. The updated criteria still apply.
4. Implementation: Python code is provided to read input, check the safety conditions, and compute the number of safe reports for both parts.
   
[[Day 2]](https://github.com/Darylwanji/Advent-Of-Code-2024/tree/main/Day2)

### Day 3: Mull It Over
Description: 
1. Context: The North Pole Toboggan Rental Shop's computer is malfunctioning, and you need to analyze corrupted memory containing multiplication instructions.
2. Part One: The goal is to find valid mul(X,Y) instructions in the corrupted memory, ignoring invalid characters. The sum of the results from valid multiplications is calculated, yielding a total of 173,529,487.
3. Part Two: Introduces do() and don't() instructions that enable or disable future mul instructions. The final sum of enabled multiplications, after considering these instructions, is calculated to be 99,532,691.
4. Implementation: Python code is provided to read the input, extract valid instructions, and compute the results for both parts.
   
[[Day 3]](https://github.com/Darylwanji/Advent-Of-Code-2024/tree/main/Day3)

### Day 4: Ceres Search
Description: 
1. Context: You are a data analyst on the Ceres-1 mission, tasked with analyzing a grid of characters to find occurrences of the word "XMAS".
2. Part One: Count the total number of occurrences of "XMAS" in the grid.
3. Part Two: Count the total number of occurrences of "MAS" in all X-shaped directions
4. Implementation: Python code is provided to read the input, analyze the grid, and compute the counts for both parts.
   
[[Day 4]](https://github.com/Darylwanji/Advent-Of-Code-2024/tree/main/Day4)

### Day 5: Print Queue
Description: 
1. Context: The Elves are printing out a bunch of reports, but they need to be in the right order.
2. Part One: Find the sum of the middle numbers of the correctly ordered updates.
3. Part Two: Find the sum of the middle numbers of the not correctly ordered updates, order the updates considering the page ordering rules.
4. Implementation: Python code is provided to read the input, check the order, and compute the results for both parts.
   
[[Day 5]](https://github.com/Darylwanji/Advent-Of-Code-2024/tree/main/Day5)

### Day 7: Bridge Repair
Description: 
1. Context: The engineers need to repair the bridge to the North Pole, but they need to figure out the correct order of operations for the calculations.
2. Part One: Find the sum of the left side of the equation for which the operator conditions are met.
3. Part Two: Find the sum of the left side of the equation for which the operator conditions are met, but this time a third operator is added.
4. Implementation: Python code is provided to read the input, evaluate the expressions, and compute the results for both parts.
   
[[Day 7]](https://github.com/Darylwanji/Advent-Of-Code-2024/tree/main/Day7)