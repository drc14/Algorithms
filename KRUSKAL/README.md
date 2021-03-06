# Kruskal's Algorithm

Kruskal's Algorithm computes the minimal spanning tree (MST)

# Input
*  Size of Adjacency Matrix
*  Adjacency Matrix

## Example
```
9
0	4	999	999	999	999	999	8	999
4	0	8	999	999	999	999	11	999
999	8	0	7	999	4	999	999	2
999	999	7	0	9	14	999	999	999
999	999	999	9	0	10	999	999	999
999	999	4	14	10	0	2	999	999
999	999	999	999	999	2	0	1	6
8	11	999	999	999	999	1	0	7
999	999	2	999	999	999	6	7	0

```

*  Note, 999 = infinity

# Output
*  List of edges
  *  Source
  *  Destination
  *  Weight 
*  Total weight

## Example
```
Source | Destination | Weight
6 	7 	1
5 	6 	2
2 	8 	2
0 	1 	4
2 	5 	4
2 	3 	7
0 	7 	8
3 	4 	9

Total weight:
37	
```