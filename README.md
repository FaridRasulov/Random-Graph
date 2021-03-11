# Random-Graph

# CLICK HERE TO SEE THE NOTEBOOK: 

https://nbviewer.jupyter.org/github/FaridRasulov/Random-Graph/blob/master/NBD-DC-HW.ipynb?flush_cache=true

## Part 1:

  1 Write a script to generate an p-ER random graph.
  
  2 Write a script to generate an r-regular random graph.
  
  3 Write a script to check the connectivity of a given graph.
  
                algebraic method 1 (irreducibility);
                
                algebraic method 2 (eigenvalue of the Laplacian matrix);
                
                BFS algorithm;
                
  4 Compare the complexity as a function of n of the methods above by plotting curves of a complexity measure vs n.
  
  5 Let Pc(G) denote the probability that a graph G is connected.

  By running Monte Carlo simulations estimates Pc(G) and produce two curve plots:
  
                Pc(G) vs. p for Erdos-Renyi graphs with n = 100.
                
                Pc(G) vs. n, for n <= 100, for r -regular random graphs with r = 2 and r = 16.
                
## Part 2: Throughput performance

  By re-using the scripts of part 1, write a script that: 
  
                (i) generates a random graph describing the topology of the ToR switch network; 
                
                (ii) checks its connectivity; 
                
                (iii) finds shortest path routes; 
                
                (iv) estimates h.
                
  Use both the r -regular random graph model and the p-Erdos-Renyi random graph model. In either case let n be the number of nodes 
  (you can assume 9 <= n <= 100, r = 8 and p = 8/(n - 1)) 
  
  Plot the application-oblivious throughput bound TH (averaged over many generated graphs), as defined above, versus n for the two graph models.
