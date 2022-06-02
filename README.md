# Graph Mining Reading List

## Static graphs: laws and patterns

* Deepayan Chakrabarti and Christos Faloutsos. Graph Mining: Laws, Tools and Case Studies, Morgan Claypool, 2012.
* D. Chakrabarti and C. Faloutsos, Graph Mining: Laws, Generators and Algorithms, in ACM Computing Surveys, 38(1).
* Reka Albert and Albert-Laszlo Barabasi. Statistical mechanics of complex networks, Reviews of Modern Physics, 74, 47 (2002).
* Power Laws and Rich-Get-Richer Phenomena. From the book Networks, Crowds, and Markets: Reasoning about a Highly Connected World. By David Easley and Jon Kleinberg. Cambridge University Press, 2010.
* M. Faloutsos, P. Faloutsos, C. Faloutsos. On Power-Law Relationships of the Internet Topology. In Proc. SIGCOMM, 1999.
* M.E.J. Newman. Power laws, Pareto distributions and Zipf's law. Contemporary Physics 46(5), 323-351, 2005.
* S. Goel, A. Broder, E. Gabrilovich, B. Pang. Anatomy of the Long Tail: Ordinary People with Extraordinary Tastes. In Proc. WSDM, 2010.
* U Kang, Charalampos E. Tsourakakis, Ana Paula Appel, Christos Faloutsos, and Jure Leskovec, Radius Plots for Mining Tera-byte Scale Graphs: Algorithms, Patterns, and Observations, SIAM International Conference on Data Mining (SDM) 2010, Columbus, Ohio, USA.
* C. E. Tsourakakis, Fast Counting of Triangles in Large Real Networks: Algorithms and Laws, ICDM, 2008.

## Dynamic graphs: laws and patterns

* J. Leskovec, L. Backstrom, R. Kumar, A. Tomkins. Microscopic Evolution of Social Networks. KDD 2008.
* J. Leskovec, D. Chakrabarti, J. Kleinberg, C. Faloutsos. Realistic, Mathematically Tractable Graph Generation and Evolution, Using Kronecker Multiplication. ECML/PKDD, 2005. Won 'test of time' award in ECML/PKDD (Porto, Sept. 2015).
* M. McGlohon, L. Akoglu, C. Faloutsos. Weighted Graphs and Disconnected Components: Patterns and a Generator. ACM SIGKDD, 2008.
* R. Kumar, J. Novak, A. Tomkins. Structure and evolution of online social networks. KDD, 2006.
* U Kang, M. McGlohon, L. Akoglu, and C. Faloutsos. Patterns on the Connected Components of Terabyte-Scale Graphs. ICDM, 2010.
* Jure Leskovec, Jon Kleinberg, Christos Faloutsos Graphs over Time: Densification Laws, Shrinking Diameters and Possible Explanations, KDD 2005, Chicago, IL, USA

## Random Walks, Pagerank, HITS

* Brin, S. and Page, L. (1998) The Anatomy of a Large-Scale Hypertextual Web Search Engine. In: Seventh International World-Wide Web Conference (WWW 1998), April 14-18, 1998, Brisbane, Australia.
* Hanghang Tong, Christos Faloutsos, and Jia-Yu Pan. Fast Random Walk with Restart and Its Application. ICDM 2006. Longer version (Technical report)
* Page, Lawrence and Brin, Sergey and Motwani, Rajeev and Winograd, Terry (1999). The PageRank Citation Ranking: Bringing Order to the Web. Technical Report. Stanford InfoLab. 
* Taher H. Haveliwala. Topic-Sensitive PageRank: A Context-Sensitive Ranking Algorithm for Web Search. IEEE Transactions on Knowledge and Data Engineering, 15(4):784-796, 2003.
* Jon M. Kleinberg. Authoritative Sources in a Hyperlinked Environment. Journal of the ACM (JACM), 46(5):604-632, 1999.
* Peter Doyle and James Laurie Snell. Random Walks and Electric Networks, volume 22. Mathematical Association America, New York, 1984. Book.

## Node Classification: Belief Propagation

* Shashank Pandit, Duen Horng Chau, Samuel Wang, and Christos Faloutsos. NetProbe: A Fast and Scalable System for Fraud Detection in Online Auction Networks. In Proceedings of the 16th International Conference on World Wide Web (WWW), Alberta, Canada, pages 201-210, 2007.
* Danai Koutra, Tai-You Ke, U Kang, Duen Horng (Polo) Chau, Hsing-Kuo Kenneth Pao, and Christos Faloutsos. Unifying Guilt-by-Association Approaches: Theorems and Fast Algorithms. ECML PKDD, Athens, Greece, Sep. 2011. Easier to read chapter 4 of "Exploring and Making Sense of Large Graphs." (dissertation).
* Jonathan S. Yedidia, William T. Freeman, and Yair Weiss. Understanding Belief Propagation and its Generalizations. In Exploring artificial intelligence in the new millennium, pages 239-269, 2003.
* Wolfgang Gatterbauer, Stephan Guennemann, Danai Koutra, Christos Faloutsos. Linearized and Single-Pass Belief Propagation. Proceedings of the VLDB Endowment, Volume 8(4) (VLDB'15), August 2015. (Chapter 5 of "Exploring and Making Sense of Large Graphs." (dissertation))
* Duen Horng Chau, Aniket Kittur, Jason I. Hong, and Christos Faloutsos. Apolo: Making Sense of Large Network Data by Combining Rich User Interaction and Machine Learning. CHI 2011.

## Node Classification: Semi-Supervised Learning

* Avrim Blum and Shuchi Chawla. Learning from Labeled and Unlabeled Data Using Graph Mincuts. In Proceedings of the 18th International Conference on Machine Learning, pages 19–26. Morgan Kaufmann, San Francisco, CA, 2001.
* Dengyong Zhou, Bernhard Schölkopf, Thomas Hofmann. Semi-supervised Learning on Directed Graphs. NIPS 2004: 1633-1640
* Xiaojin Zhu. Semi-Supervised Learning Literature Survey, 2006. Survey.

## Node Similarity

* Glen Jeh and Jennifer Widom. SimRank: A Measure of Structural-Context Similarity. In Proceedings of the 8th ACM International Conference on Knowledge Discovery and Data Mining (SIGKDD), Edmonton, Alberta, pages 538-543. ACM, 2002.
* Laura Zager and George Verghese. Graph Similarity Scoring and Matching. Applied Mathematics Letters, 21(1):86-94, 2008.
* Ioannis Antonellis, Hector Garcia Molina, and Chi Chao Chang. 2008. Simrank++: query rewriting through link analysis of the click graph. Proc. VLDB Endow. 1, 1 (August 2008), 408-421.
* Weiren Yu, Xuemin Lin, Wenjie Zhang, Lijun Chang, and Jian Pei. More is Simpler: Effectively and Efficiently Assessing Node-Pair Similarities Based on Hyperlinks. Proceedings of the VLDB Endowment, 7(1):13-24, 2013.
* Cuiping Li, Jiawei Han, Guoming He, Xin Jin, Yizhou Sun, Yintao Yu, and Tianyi Wu. Fast Computation of SimRank for Static and Dynamic Information Networks. In Proceedings of the 13th International Conference on Extending Database Technology, EDBT'10, pages 465-476, New York, NY, USA, 2010.

## Graph Similarity

* Danai Koutra, Neil Shah, Joshua Vogelstein, Brian Gallagher, and Christos Faloutsos. DeltaCon: A Principled Massive-Graph Similarity Function with Attribution. ACM Transactions on Knowledge Discovery from Data, Sept. 2015.
* Papadimitriou, Panagiotis and Dasdan, Ali and Garcia-Molina, Hector (2010) Web Graph Similarity for Anomaly Detection. Journal of Internet Services and Applications, Volume 1 (1). pp. 19-30.
* Horst Bunke, Peter J. Dickinson, Miro Kraetzl, and Walter D. Wallis. A Graph-Theoretic Approach to Enterprise Network Dynamics (PCS). Birkhauser, 2006.
* Sucheta Soundarajan, Tina Eliassi-Rad, Brian Gallagher.A Guide to Selecting a Network Similarity Method. SDM 2014: 1037-1045.

## Graph Alignment

* Arvind Narayanan and Vitaly Shmatikov. 2009. De-anonymizing Social Networks. In Proceedings of the 2009 30th IEEE Symposium on Security and Privacy (SP '09). IEEE Computer Society, Washington, DC, USA, 173-187.
* Danai Koutra, Hanghang Tong, and David Lubensky. Big-Align: Fast Bipartite Graph Alignment. In Proceedings of the 14th IEEE International Conference on Data Mining (ICDM), Dallas, Texas, 2013.
* Shinji Umeyama. An Eigendecomposition Approach to Weighted Graph Matching Problems. IEEE Transactions on Pattern Analysis and Machine Intelligence, 10(5):695-703, 1988.
* Mohsen Bayati, David F. Gleich, Amin Saberi, and Ying Wang. 2013. Message-Passing Algorithms for Sparse Network Alignment. ACM Trans. Knowl. Discov. Data 7, 1, Article 3 (March 2013).

## Graph Clustering and Communities

* M. E. J. Newman and M. Girvan, Finding and evaluating community structure in networks, Physical Review E, vol. 69, p. 026113, 2004.
* J. Ugander, Lars Backstrom. Balanced Label Propagation for Partitioning Massive Graphs. In Proceedings of the sixth ACM international conference on Web search and data mining (WSDM '13). ACM, New York, NY, USA, 507-516.
* Jialu Liu, Chi Wang, Marina Danilevsky, Jiawei Han. Large-Scale Spectral Clustering on Graphs. IJCAI 2013
* J. Leskovec, K. Lang, M. Mahoney. Empirical Comparison of Algorithms for Network Community Detection. In Proc. WWW, 2010.
* Isabelle Stanton and Gabriel Kliot. Streaming graph partitioning for large distributed graphs. In Proceedings of the 18th ACM SIGKDD international conference on Knowledge discovery and data mining (KDD '12). ACM, New York, NY, USA, 1222-1230.
* Charalampos Tsourakakis, Christos Gkantsidis, Bozidar Radunovic, and Milan Vojnovic. 2014. FENNEL: streaming graph partitioning for massive scale graphs. In Proceedings of the 7th ACM international conference on Web search and data mining (WSDM '14). ACM, New York, NY, USA, 333-342.
* R. Andersen, F. Chung, K. Lang. Local graph partitioning using pagerank vectors. In Proc. FOCS, 2006.
* G. Karypis, V. Kumar, and V. Kumar, Multilevel k-way partitioning scheme for irregular graphs, Journal of Parallel and Distributed Computing, vol. 48, pp. 96-129, 1998.
* M. E. J. Newman, Fast algorithm for detecting community structure in networks, Physical Review E, vol. 69, no. 6, p. 066133, 2004.
* D. Kuang, H. Park, and C. Ding, Symmetric nonnegative matrix factorization for graph clustering, in SDM, 2012, pp. 106-117.
* Ghristos Giatsidis. Graph mining and community evaluation with degeneracy. Dissertation, Ecole Polytechnique, 2013.
* Miguel Araujo, Stephan Guennemann, Spiros Papadimitriou, Christos Faloutsos, Prithwish Basu, Ananthram Swami, Evangelos Papalexakis, Danai Koutra. Discovery of `comet' communities in temporal and labeled graphs (Com2). Knowledge and Information Systems (KAIS, Springer), 2015.
* M. Granovetter. The strength of weak ties. American Journal of Sociology, 78(6):1360-1380, 1973.
* Strong and Weak Ties. From the book Networks, Crowds, and Markets: Reasoning about a Highly Connected World. By David Easley and Jon Kleinberg. Cambridge University Press, 2010. (Chapter 3).
* A. Rajaraman, J. Ullman, J. Leskovec. Chapter 10.4 of Mining Massive Datasets. 2013.
* G. Palla, I. Derenyi, I. Farkas, T. Vicsek. Uncovering the overlapping community structure of complex networks in nature and society. Nature 435, 814-818, 2005.
* J. Leskovec, K. Lang, A. Dasgupta, M. Mahoney. Community Structure in Large Networks: Natural Cluster Sizes and the Absence of Large Well-Defined Clusters. Internet Mathematics, 2009.
* Steve Harenberg, Gonzalo Bello, L. Gjeltema, Stephen Ranshous, Jitendra Harlalka, Ramona Seay, Kanchana Padmanabhan and Nagiza Samatova. Community detection in large-scale networks: a survey and empirical evaluation. WIREs Computational Statistics, Wiley. 2014.

## Graph Summarization

* D. Koutra, U. Kang, J. Vreeken, C. Faloutsos. Summarizing and Understanding Large Graphs. Special Issue of Statistical Analysis and Data Mining, "Best of SDM 2014". October 2014.
* Neil Shah, Danai Koutra, Tianmin Zou, Brian Gallagher, Christos Faloutsos. TimeCrunch: Interpretable Dynamic Graph Summarization. Conference on Knowledge Discovery and Data Mining (KDD), August 2015.
* Diane J. Cook and Lawrence B. Holder. Substructure Discovery Using Minimum Description Length and Background Knowledge. Journal of Artificial Intelligence Research, 1:231-255, 1994.
* Nikhil S. Ketkar, Lawrence B. Holder, and Diane J. Cook. 2005. Subdue: compression-based frequent pattern discovery in graph data. In Proceedings of the 1st international workshop on open source data mining: frequent pattern mining implementations (OSDM '05).
* S. Navlakha, R. Rastogi, and N. Shrivastava, Graph summarization with bounded error, in SIGMOD. ACM, 2008, pp. 419-432
* Y. Tian, R. A. Hankins, and J. M. Patel, Efficient aggregation for graph summarization. in SIGMOD, 2008, pp. 567-580.

## Anomaly Detection

* Leman Akoglu, Hanghang Tong, Danai Koutra. Graph-based Anomaly Detection and Description: A Survey. Data Mining and Knowledge Discovery (DAMI), April 2014. Survey.
* Bryan Perozzi, Leman Akoglu, Patricia Iglesias Sánchez, and Emmanuel Müller. 2014. Focused clustering and outlier detection in large attributed graphs. In Proceedings of the 20th ACM SIGKDD international conference on Knowledge discovery and data mining (KDD '14).
* Caleb C. Noble and Diane J. Cook. 2003. Graph-based anomaly detection. In Proceedings of the ninth ACM SIGKDD international conference on Knowledge discovery and data mining (KDD '03). ACM, New York, NY, USA, 631-636.
* Jay-Yoon Lee, U Kang, Danai Koutra, Christos Faloutsos. Fast anomaly detection despite the duplicates. WWW 2013, Rio de Janeiro, Brazil, May 2013.
* Deepayan Chakrabarti. 2004. AutoPart: parameter-free graph partitioning and outlier detection. In Proceedings of the 8th European Conference on Principles and Practice of Knowledge Discovery in Databases (PKDD '04).
* Markus M. Breunig, Hans-Peter Kriegel, Raymond T. Ng, and Jörg Sander. 2000. LOF: identifying density-based local outliers. SIGMOD Rec. 29, 2 (May 2000), 93-104.
* Danai Koutra, Di Jin, Yuanchi Ning, Christos Faloutsos. Perseus: An Interactive Large-Scale Graph Mining and Visualization Tool. Proceedings of the VLDB Endowment (VLDB'15 Demo), August 2015
* U Kang, Jay-Yoon Lee, Danai Koutra, Christos Faloutsos. Net-Ray: Visualizing and Mining Web-Scale Graphs. PAKDD 2014, Tainan, Taiwan, May 2014.
* Jimeng Sun, Yinglian Xie, Hui Zhang, and Christos Faloutsos. 2008. Less is More: Sparse Graph Mining with Compact Matrix Decomposition. Stat. Anal. Data Min. 1, 1 (February 2008), 6-22.
* Jimeng Sun, Dacheng Tao, and Christos Faloutsos. 2006. Beyond streams and graphs: dynamic tensor analysis. In Proceedings of the 12th ACM SIGKDD international conference on Knowledge discovery and data mining (KDD '06).
* Jimeng Sun, Christos Faloutsos, Spiros Papadimitriou, and Philip S. Yu. 2007. GraphScope: parameter-free mining of large time-evolving graphs. In Proceedings of the 13th ACM SIGKDD international conference on Knowledge discovery and data mining (KDD '07).
* Papadimitriou, Panagiotis and Dasdan, Ali and Garcia-Molina, Hector (2010) Web Graph Similarity for Anomaly Detection. Journal of Internet Services and Applications, Volume 1 (1). pp. 19-30.

## Link Analysis

* J. Leskovec, D. Huttenlocher, J. Kleinberg. Predicting Positive and Negative Links in Online Social Networks. WWW 2010.
* L. Backstrom, J. Leskovec. Supervised Random Walks: Predicting and Recommending Links in Social Networks. WSDM, 2011.
* A. Clauset, C. Moore, M.E.J. Newman. Hierarchical structure and the prediction of missing links in networks. Nature, 2008.
* M. Kim, J. Leskovec. The Network Completion Problem: Inferring Missing Nodes and Edges in Networks. SIAM SDM, 2010.
* D. Liben-Nowell, J. Kleinberg. The Link Prediction Problem for Social Networks. CIKM, 2004.

## Streaming graphs and algorithms

* Isabelle Stanton and Gabriel Kliot. Streaming graph partitioning for large distributed graphs. In Proceedings of the 18th ACM SIGKDD international conference on Knowledge discovery and data mining (KDD '12). ACM, New York, NY, USA, 1222-1230.
* Charalampos Tsourakakis, Christos Gkantsidis, Bozidar Radunovic, and Milan Vojnovic. 2014. FENNEL: streaming graph partitioning for massive scale graphs. In Proceedings of the 7th ACM international conference on Web search and data mining (WSDM '14). ACM, New York, NY, USA, 333-342.
* Andrew McGregor. 2014. Graph stream algorithms: a survey. SIGMOD Rec. 43, 1 (May 2014), 9-20.

## Deep learning for graphs

* Bryan Perozzi, Rami Al-Rfou, and Steven Skiena. 2014. DeepWalk: online learning of social representations. In Proceedings of the 20th ACM SIGKDD international conference on Knowledge discovery and data mining (KDD '14).
* Fei Tian, Bin Gao, Qing Cui, Enhong Chen, Tie-Yan Liu. Learning Deep Representations for Graph Clustering. AAAI 2014: 1293-1299

## Recommendation Systems

* Badrul Sarwar, George Karypis, Joseph Konstan, and John Riedl. 2001. Item-based collaborative filtering recommendation algorithms. In Proceedings of the 10th international conference on World Wide Web (WWW '01). ACM, New York, NY, USA, 285-295.
* Xiao Yu, Xiang Ren, Yizhou Sun, Quanquan Gu, Bradley Sturt, Urvashi Khandelwal, Brandon Norick, and Jiawei Han. Personalized entity recommendation: a heterogeneous information network approach. In Proceedings of the 7th ACM international conference on Web search and data mining (WSDM '14). ACM, New York, NY, USA, 283-292.
* Paul Resnick and Hal R. Varian. 1997. Recommender systems. Commun. ACM 40, 3 (March 1997), 56-58.3410 citations.
* Robin Burke. Hybrid Recommender Systems: Survey and Experiments.User Modeling and User-Adapted Interaction 12, 4 (November 2002), 331-370. 2567 citations.

## Large-scale social science

* C. Danescu-Niculescu-Mizil, R. West, D. Jurafsky, J. Leskovec, C. Potts.No Country for Old Members: User lifecycle and linguistic change in online communities. ACM International Conference on World Wide Web (WWW), 2013. Best paper award.
* A. Anderson, D. Huttenlocher, J. Kleinberg, J. Leskovec. Engaging with Massive Online Courses. ACM International Conference on World Wide Web (WWW), 2014. Best paper runner-up.
* J. McAuley, J. Leskovec. Discovering Social Circles in Ego Networks. ACM Transactions on Knowledge Discovery from Data (TKDD), 2014.
* L. Backstrom, J. Kleinberg. Romantic Partnerships and the Dispersion of Social Ties: A Network Analysis of Relationship Status on Facebook. Proc. 17th ACM Conference on Computer Supported Cooperative Work and Social Computing (CSCW), 2014.
* L Backstrom, P Boldi, M Rosa, J Ugander, S Vigna. Four Degrees of Separation. Proc. 4th ACM Int'l Conf. on Web Science (WebSci), 2012. Best Paper Award.
* I. Kloumann, L. Adamic, J. Kleinberg, S. Wu. The Lifecycles of Apps in a Social Ecosystem. Proc. 24th International World Wide Web Conference, 2015.
* S. Myers, J. Leskovec. The Bursty Dynamics of the Twitter Information Network. ACM International Conference on World Wide Web (WWW), 2014.
