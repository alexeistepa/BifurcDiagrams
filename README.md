# BifurcDiagrams

Code to generate bifurcation diagrams for chaotic dynamical systems such as the one shown below for the Poincar\'e section of a damped, driven Duffing oscillator.

 - The notebook `bifurcation_diagram_export.ipynb` generates .csv files containing the data for the diagrams (warning: this may take several hours).
 
 - The notebook `csv_to_datashader.ipynb` uses the package  [Datashader](https://github.com/holoviz/datashader) to generate the diagrams from the .csv files.
 
 <img src="https://github.com/alexeistepa/BifurcDiagrams/blob/main/fullbifurcx_wide.png?raw=true" width="1100" height="400">
