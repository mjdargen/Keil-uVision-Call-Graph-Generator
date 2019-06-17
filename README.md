# Keil-uVision-Call-Graph-Generator
This program is a Python script that takes a default .txt call graph from Keil uVision, parses it, and transforms it into a .gv Graphviz gvedit file to visually display the call graph for your project.

In order to use the program, run the script. A dialog box will pop up to prompt you to select your .txt Keil uVision MDK5 Call Graph. Another dialog box will then pop up to prompt you to name and save your file as a Graphviz .gv file. Import the .gv file into Graphviz and run it to see the visualization of the call graph for your project.

Info and download link for Graphviz: https://graphviz.gitlab.io/download/ <br />
Keil uVision information: http://www2.keil.com/mdk5/uvision/

Example input .txt file, output .gv file, and images in example folder.

Keil uVision configuration for outputting .txt call graph file:
<p align="center">
  <img src="https://github.ncsu.edu/mjdargen/Keil-uVision-Call-Graph-Generator/blob/master/example/uVision_config.PNG" width="600">
</p>
