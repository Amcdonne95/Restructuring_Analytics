# Restructuring Analytics
### Important Files:
* Data_Dictionary.ipynb
* Agent_Network_Graph.ipynb
**Other files are just earlier versions of the files mentioned above**
#### Data_Dictionary File
* Designed to organize the raw data from a DIP CSV dump
* Can return 2 options:
1. A CSV file of organized data (selected via python code)
2. A JSON File **Used in JavaScript as a data container**
##### Going Forward
* The JSON File can be used by JavaScript programs to develop creative visualizations that can eventually be integrated with a website
* Users would be able to play with these visualizations to draw insights into that data that may not have been seen before
#### Agent_Network_Graph
* This file was built to utilize the cleaned DIP Data in the creation of a Network Graph using Plotly
* Plotly is essentially a Python Wrapper for JavaScript; meaning that the Python talks to JavaScript code in the back end to generate visualizations
##### Going Forward
* Instead of relying on Plotly to do the heavylifting, it is would be better to use JavaScript to develop the visualizations
* Python would sill be used to analyze and create the data containers for the network graph using Networkx, but the visualization part would be purely JavaScript that pulls in the data via JSON File
