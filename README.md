# Market-Basket-Analysis
A comparative study on apriori and fp-growth algorithm

## Conclusion
I was able to conclude with regards to the dataset, that thorough cleaning of the dataset is very essential to the good performance of the algorithms. It is obviously implied, but I would like to stress on the word thorough because a lot of times I missed some of the garbage transactions and it degraded the number of rules generated. The two algorithms I used gave me the same results, but FP-Growth performed way better when compared to Apriori and this makes a difference when massive datasets are involved. These association rule mining algorithms were only very useful for finding simple associations between our data items. They were easy to implement and had high explain-ability. However, for more advanced insights, we could use more complex algorithms, such as recommender systems.

## Future Work
These algorithms are only useful on simple case to case basis and it is a very simple way to get basic associations if that's all your use-case needs. I would like to explore using recommender systems to do Market Basket Analysis on transactional data.

## References
[1] Agrawal, Rakesh, and Ramakrishnan Srikant. “Fast algorithms for mining association rules.” Proc. 20th int. conf. very large data bases, VLDB. Vol. 1215. 1994.
[2] Han, Jiawei, Jian Pei, Yiwen Yin, and Runying Mao. “Mining frequent patterns without candidate generation. A frequent-pattern tree approach.” Data mining and knowledge discovery 8, no. 1 (2004): 53-87.
[3] Fachrul Kurniawan, Binti Umayah, Jihad Hammad, Supeno Mardi Susiki Nugroho, Mochammad Hariadi. “Market Basket Analysis to Identify Customer Behaviors by Way of Transaction Data” Knowledge Engineering and Data Science (KEDS) Vol 1, No 1, January 2018, pp. 20–25
[4] Agus Mansur, TriyosoKuncoro. “Product Inventory Predictions at Small Medium Enterprise Using Market Basket Analysis Approach-Neural Networks” Procedia Economics and Finance Volume 4, 2012, Pages 312-320
[5] Dataset Repository - https://archive.ics.uci.edu/ml/datasets/Online+Retail
