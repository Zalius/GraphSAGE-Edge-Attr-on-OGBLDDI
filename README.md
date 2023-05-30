# GraphSAGE-Edge-Attr-on-OGBLDDI
Jing Yang's GraphSAGE + Edge Attr on ogbl-ddi dataset

# ogbl-ddi


Paper: 
https://github.com/lustoo/OGB_link_prediction/blob/main/Link%20prediction%20with%20structural%20information.pdf

They use multiple anchor sets selected from random sampling to encode distance information for edges on graph. Theu also modify the aggregation stage of GraphSAGE to incorporate edge information.


## Results

|            Model             |   Test Hits@20    |    Val Hits@20    |
| :--------------------------: | :---------------: | :---------------: |
|   GraphSAGE+Edge Attr(k=1)   |   0.8633±0.0313   |   0.7916±0.0324   |
| **GraphSAGE+Edge Attr(k=3)** | **0.8781±0.0474** | **0.8044±0.0404** |
|   GraphSAGE+Edge Attr(k=5)   |   0.8527±0.0247   |   0.7839±0.0278   |
