# Genetic-Algorithm-and-Tabu-Search-for-K-Graph-Coloring-Problem
 <sub> By Sta Abdelhamid & Gao Jinmei  <sub> 

This repository includes the source code for the implementation of a Genetic Algorithm and tabu search for the K graph coloring problem.

It has been developed as coursework for the Algorithms and Combinatorial Optimisation course as part of the Master 2 GENIOMHE under the supervision of researcher Franck Delaplace.

## Definition of the problem: 

The k-graph coloring problem (K – GCP) consists in assigning a color ( from a number in { 
1, …. ,k} to each vertex of a graph G =(V, E) where V is the number of vertices and E the 
number of edges and K a positive integers. The followed K-coloring graph will be the 
assignment of K distinct colors to each vertex v ∈ V in the graph, so that no two adjacent 
vertices (linked by an edge e ∈ E) are given the same color, ∀{Vi,Vj} ∈ E, c(i) != c(j). The 
problem is to determine if a graph that can be assigned a proper K-coloring or less exists. If 
such a color exists, G is called K-colorable.

## Improvement of the algorithm 

Different Fitness function ; aspiration criteria ; neighbors solution generation and other parameters have been used with the aim to reduce the number of iteration / generation needed to found a given solution . Take a look at the report if you want to know more ! 
