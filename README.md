Solver Program - April 8, 2014

Author: Thomas B. Ansill<br>
Email: tba6700(at)rit.edu

0. Compile the program if you haven't already did it.
1. Run the Driver class
2. Type 'help' to see which commands you can execute. (the help information changes when you create or load a graph)

The program uses adjacency list structure to display graphs. If you do not
understand adjacency list, please take time to study the image called GraphToAdjacencyList.png
picture (it should be in the directory).

Builder Program - type 'build' or 'builder' or 'generate' in the program to create common type of graphs.

The default list of vertex graph types you can create:

	Path Graph - type 'path'
	Cycle Graph - type 'cycle'
	Wheel Graph - type 'wheel'
	BiPartite Graph - type 'bipartite'
	Complete Graph - type 'complete'
	Grid Graph - type 'grid'

Loader Program - type 'load' to load a graph from text file
.
What to do with it: I have included basic graph text files in Graphs folder that is included with RedForce. You can load a graph by typing for example, 

    'load Graphs/petersen.txt' 
        
If you want to load a file that is not somewhere inside the same directory the program is in, you have to provide a full system path for load program like 

    'load C:\Users\Sample\My Documents\Graphs\petersen.txt'
	
If you want to create your own graphs, you can create a a text file and write an adjacency list. The first column should contain all vertex that you will use in your graph. Then all columns after the first will be used a neighbors vertices to a vertex in the first column and same row.
 
To fill a vertex, you apphend # to a vertex only in the first column.

FAQ:

Q: How to use the searcher in the program?
A: Run the program, load/build a graph and type findmax or findmin. You will be
	given choices for searcher types. I recommend using Union
	Searcher for fast results.

Q: How do I exit the program?
A: type 'quit' or 'exit' in the program.

Q: What if when program becomes stuck while using 'findmax'
	command and how do I stop it?
A: Use abort key, default is CTRL-C if you are using UNIX Terminal
	or Windows Command Prompt.

Q: The program crashes when I use 'load' command.
A: Check your text file you're trying to load for format. It is 
	possible that text file is incorrectly formatted. Otherwise,
	contact the programmer.

Q: How do I change the forcing number?
A: After you have loaded or built a graph, type forcingnumber to 
	change the forcing number.


Future Implementation:<br>
<a href='https://github.com/tomansill/BlueForce'>Blue Force</a> - Work-In-Progress superset of RedForce program that is able to solve graphs with vertex state higher than 2. 
