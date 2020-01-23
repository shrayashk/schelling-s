# schelling-s
A visualization of Schelling's Model of Segregation.
Uses matplotlib, networkx and 'random' libraries. <br>
The script first plots a 10x10 grid of red nodes representing the initial state of all occupants being "satisfied" with their neighbours.<br> 
Then the script generates another plot where in we have 3 varieties of neighbours represented by colors (namely red, green and white). Taking the parameter "t" as the number of neighbours needed to be of the same color to saitsfy a given node and fixing it as 3 for our script, the script generates a 3rd plot after it reaches a state where the nodes have been segregated into communities of the same color and each node has "t" number of neighbors.

Done as a part of NPTEL Social Networks course https://nptel.ac.in/courses/106/106/106106169/
