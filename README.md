# Network Simulation

## Description

Personal interest project in Python: network simulation and analysis using NetworkX (__WIP__).

## Table of Contents

* [Motivation](#motivation)
* [Progress](#progress)
* [Installation](#installation)
* [Working Code](#working-code)

## Motivation

Primarily using the __NetworkX__ package, this personal WIP simulates a network of N-nodes to explore
financial contagion in webs of leverage. Analyzing the long-run dynamics of the network and comparing
stabilizing mechanisms across parameters may offer some insight into how contagion spreads and who is
at greatest risk. From these foundations, I hope to delve into other interesting areas of complexity, such conditional updating,
nested networks, and mean field approximation. 

## Progress

___Current status__: preliminary set-up of an N-node network with random connections and a "has path" criterion (all nodes must have some way of reaching every other node to restrict attention to one interconnected mass); set-up basic network visualization._

___Next milestone__: clean-up code; set-up Node and Network classes; experiment with network visualization._

![Financial Network](https://user-images.githubusercontent.com/68624142/210494279-a70a3d0f-ee09-47fd-8ad6-cb3f53e30a15.png)

## Installation

Required packages (__Python__): 

1. NetworkX
2. Matplotlib.pyplot
3. Random
4. Numpy

## Working Code

[Financial Contagion.txt](https://github.com/NetworkGestalt/Network-Simulation/files/10341797/Financial.Contagion.txt)

https://github.com/NetworkGestalt/Network-Simulation/blob/main/Financial%20Contagion.ipynb
