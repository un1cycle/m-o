<p align="center">
<img width="150" height="173" alt="image-removebg-preview(7)" src="https://github.com/user-attachments/assets/4e3a355c-df8c-4e36-b8de-941d0913dd40" />      
<br><b>M-O</b> - Memory-Obliterator<br></p>

#### Description:
- This project is an immediate representation that optimally cleans up all heap-allocations without any safety rules or garbage collection. The project name is from a Wall-E character: Microbe-Obliterator.

#### Methodology:
- It uses exclusively zero-cost abstractions to meet the level of speed as the optimal C/assembly code that would do the same thing. These abstractions include automatically freeing all independent heap allocations at the end of their scope, checking heap variable dependencies using assignment, keeping track of aliases but not freeing them, and a lot more of really tedious but functional methods to keep everything safe and as leak-free as possible.
