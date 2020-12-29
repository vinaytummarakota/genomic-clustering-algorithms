# genomic-clustering-algorithms
Why do winemakers seal barrels of yeast with grape juice to produce wine? The answer lies in a biological process known as diauxic shift. In the presence of glucose (e.g. grape juice), yeast consumes the glucose to produce ethanol. However, in the presence of oxygen, a "diauxic shift" occurs whereby yeast consumes ethanol to produce glucose. To ensure that the diauxic shift does not occur, winemakers seal out oxygen while allowing the yeast to consume grape juice. 

Biologists can understand the underlying mechanisms of diauxic shift through measuring the expression of many yeast genes at different time intervals. From there, data scientists can apply clustering algorithms to categorize genes based on their expression patterns. To categorize the yeast genes, I implemented the Lloyd Algorithm, Soft K-Means Clustering Algorithm, and Hierarchical Clustering Algorithm from scratch. The results of the first two algorithms are shown as follows. 

Lloyd Algorithm: 
![Lloyd Algorithm Clustering]('lloyd.png')

Soft K-Means Algorithm: 
![Soft K-Means Clustering]('softkmeans.png')

