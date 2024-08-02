### BACH
## Bitcoin Address Clustering based on multiple Heuristics
This project is structured into three main components:<br>
- **Database Generator**: Contains the code to analyze the blockchain and identify address clusters and store all the relationships between addresses within a database.<br>
- **Server API**: Provides the API endpoints for accessing clustering data in the database.<br>
- **Web Client**: A React application that consumes the API to visualize data inside a graph. The [3D Force-Directed Graph](https://github.com/vasturiano/3d-force-graph) web component is used to visualize the cluster graph.<br>
***
## Homepage
The Homepage presents the tool with a short description, detailing the heuristics used in constructing clusters.<br>
At the bottom of the page, there are examples of discovered clusters.
<p align="center">
<kbd><img src="https://raw.githubusercontent.com/semifredd0/BACH-tool/master/.github/images/Home.PNG" width="800"/></kbd>
</p>

## Display cluster graph
In the NavBar you can paste a Bitcoin address to view the cluster to which it belongs.<br>
This page lists all addresses within the same cluster and shows its 3D graph.<br>
The red node identifies the searched address.
<p align="center">
<kbd><img src="https://raw.githubusercontent.com/semifredd0/BACH-tool/master/.github/images/Graph.PNG" width="800"/></kbd>
</p>

## Display links of an address
By clicking on a node within the graph, you can see all its links to other addresses in the cluster in detail, along with the types of links.
<p align="center">
<kbd><img src="https://raw.githubusercontent.com/semifredd0/BACH-tool/master/.github/images/Links.PNG" width="800"/></kbd>
</p>

***
## Author
Matteo Costantini
***
