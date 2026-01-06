# M-O 
Short for Memory-Obliterator. This project is an immediate representation that optimally cleans up all heap-allocations without any safety rules or garbage collection. The project name is from a Wall-E character: Microbe-Obliterator.

# How it works
It uses exclusively zero-cost abstractions to meet the level of speed as the optimal C/assembly code that would do the same thing. These abstractions include automatically freeing all independent heap allocations at the end of their scope, checking heap variable dependencies using assignment, keeping track of aliases but not freeing them, and a lot more of really tedious but functional methods to keep everything safe and as leak-free as possible.
