# GraphData
- [GraphData](#graphdata)
  - [Single Graph](#single-graph)
    - [Planetoid datasets: CORA, CiteSeer and PubMed](#planetoid-datasets-cora-citeseer-and-pubmed)
    - [Amazon Computers and Amazon Photo](#amazon-computers-and-amazon-photo)
    - [Coauthor CS and Coauthor Physics](#coauthor-cs-and-coauthor-physics)
    - [DBLP](#dblp)
    - [CiteSeer_Full](#citeseer_full)
    - [CORA_Full and CORA-ML](#cora_full-and-cora-ml)
    - [Reddit](#reddit)
    - [NELL](#nell)
    - [Flickr and BlogCatalog](#flickr-and-blogcatalog)
    - [KDD Cup 2020](#kdd-cup-2020)
    - [UAI2010](#uai2010)
    - [ACM](#acm)
## Single Graph
### Planetoid datasets: CORA, CiteSeer and PubMed

citation network datasets in https://github.com/kimiyoung/planetoid

nodes are documents and edges are citation links. Label rate denotes the number of labeled nodes that are used for training divided by the total number of nodes in each dataset. 

```bibtex
@article{SenNBGGE08,
  author    = {Prithviraj Sen and
               Galileo Namata and
               Mustafa Bilgic and
               Lise Getoor and
               Brian Gallagher and
               Tina Eliassi{-}Rad},
  title     = {Collective Classification in Network Data},
  journal   = {{AI} Mag.},
  volume    = {29},
  number    = {3},
  pages     = {93--106},
  year      = {2008}
}
```

### Amazon Computers and Amazon Photo

Amazon Computers and Amazon Photo are segments of the Amazon co-purchase graph,where nodes represent goods, edges indicate that two goods are frequently bought together, node features are bag-of-words encoded product reviews, and class labels are given by the product category. 

```bibtex
@inproceedings{McAuleyTSH15,
  author    = {Julian J. McAuley and
               Christopher Targett and
               Qinfeng Shi and
               Anton van den Hengel},
  editor    = {Ricardo Baeza{-}Yates and
               Mounia Lalmas and
               Alistair Moffat and
               Berthier A. Ribeiro{-}Neto},
  title     = {Image-Based Recommendations on Styles and Substitutes},
  booktitle = {Proceedings of the 38th International {ACM} {SIGIR} Conference on
               Research and Development in Information Retrieval, Santiago, Chile,
               August 9-13, 2015},
  pages     = {43--52},
  publisher = {{ACM}},
  year      = {2015}
}
```



### Coauthor CS and Coauthor Physics

Coauthor CS and Coauthor Physics are co-authorship graphs based on the Microsoft Academic Graph from the KDD Cup 2016 challenge. Here, nodes are authors, that are connected by an edge if they co-authored a paper; node features represent paper keywords for each author’s papers, and class labels indicate most active fields of study for each author.

```
https://kddcup2016.azurewebsites.net/
```



The above datasets are collected from

https://github.com/shchur/gnn-benchmark

```bibtex
@article{shchur2018pitfalls,
  title={Pitfalls of Graph Neural Network Evaluation},
  author={Shchur, Oleksandr and Mumme, Maximilian and Bojchevski, Aleksandar and G{\"u}nnemann, Stephan},
  journal={Relational Representation Learning Workshop, NeurIPS 2018},
  year={2018}
}
```

---

### DBLP

```bibtex
@inproceedings{PanWZZW16,
  author    = {Shirui Pan and
               Jia Wu and
               Xingquan Zhu and
               Chengqi Zhang and
               Yang Wang},
  editor    = {Subbarao Kambhampati},
  title     = {Tri-Party Deep Network Representation},
  booktitle = {Proceedings of the Twenty-Fifth International Joint Conference on
               Artificial Intelligence, {IJCAI} 2016, New York, NY, USA, 9-15 July
               2016},
  pages     = {1895--1901},
  publisher = {{IJCAI/AAAI} Press},
  year      = {2016}
}
```

### CiteSeer_Full

```bibtex
@inproceedings{GilesBL98,
  author    = {C. Lee Giles and
               Kurt D. Bollacker and
               Steve Lawrence},
  title     = {CiteSeer: An Automatic Citation Indexing System},
  booktitle = {Proceedings of the 3rd {ACM} International Conference on Digital Libraries,
               June 23-26, 1998, Pittsburgh, PA, {USA}},
  pages     = {89--98},
  publisher = {{ACM}},
  year      = {1998}
}
```

### CORA_Full and CORA-ML

CORA_Full, citation network dataset, an extended version of CORA

CORA-ML, extracted from the original data the entire network of CORA

```bibtex
@article{McCallumNRS00,
  author    = {Andrew McCallum and
               Kamal Nigam and
               Jason Rennie and
               Kristie Seymore},
  title     = {Automating the Construction of Internet Portals with Machine Learning},
  journal   = {Inf. Retr.},
  volume    = {3},
  number    = {2},
  pages     = {127--163},
  year      = {2000}
}
```



The above datasets are collected from

https://github.com/abojchevski/graph2gauss

```bibtex
@inproceedings{bojchevski2018deep,
title={Deep Gaussian Embedding of Graphs:  Unsupervised Inductive Learning via Ranking},
author={Aleksandar Bojchevski and Stephan Günnemann},
booktitle={International Conference on Learning Representations},
year={2018},
url={https://openreview.net/forum?id=r1ZdKJ-0W},
}
```

---

### Reddit

http://snap.stanford.edu/graphsage/

```bibtex
 @inproceedings{hamilton2017inductive,
     author = {Hamilton, William L. and Ying, Rex and Leskovec, Jure},
     title = {Inductive Representation Learning on Large Graphs},
     booktitle = {NIPS},
     year = {2017}
   }
```

### NELL

https://github.com/kimiyoung/planetoid

```bibtex
@inproceedings{CarlsonBKSHM10,
  author    = {Andrew Carlson and
               Justin Betteridge and
               Bryan Kisiel and
               Burr Settles and
               Estevam R. Hruschka Jr. and
               Tom M. Mitchell},
  editor    = {Maria Fox and
               David Poole},
  title     = {Toward an Architecture for Never-Ending Language Learning},
  booktitle = {Proceedings of the Twenty-Fourth {AAAI} Conference on Artificial Intelligence,
               {AAAI} 2010, Atlanta, Georgia, USA, July 11-15, 2010},
  publisher = {{AAAI} Press},
  year      = {2010}
```

```bibtex
@inproceedings{DBLP:conf/icml/YangCS16,
  author    = {Zhilin Yang and
               William W. Cohen and
               Ruslan Salakhutdinov},
  editor    = {Maria{-}Florina Balcan and
               Kilian Q. Weinberger},
  title     = {Revisiting Semi-Supervised Learning with Graph Embeddings},
  booktitle = {Proceedings of the 33nd International Conference on Machine Learning,
               {ICML} 2016, New York City, NY, USA, June 19-24, 2016},
  series    = {{JMLR} Workshop and Conference Proceedings},
  volume    = {48},
  pages     = {40--48},
  publisher = {JMLR.org},
  year      = {2016}
}
```

### Flickr and BlogCatalog

BlogCatalog : It is a dataset of a blog community social network, which contains 5,196 users as nodes, 171,743 edges indicating the user interactions, and 8,189 attribute categories denoting the keywords of their blogs. Users could register their blogs into six different predefined classes, which are set as labels. 

Flickr: It is a benchmark attributed social network dataset containing 7,575 nodes. Each node is a Flickr user and each attribute category is a tag related to the photos shared by users. There are 239,738 undirected edges in this network, which indicate the following relationships among users. The nine groups that users have joined are considered as target labels.

```bibtex
@inproceedings{LiHTL15,
  author    = {Jundong Li and
               Xia Hu and
               Jiliang Tang and
               Huan Liu},
  editor    = {James Bailey and
               Alistair Moffat and
               Charu C. Aggarwal and
               Maarten de Rijke and
               Ravi Kumar and
               Vanessa Murdock and
               Timos K. Sellis and
               Jeffrey Xu Yu},
  title     = {Unsupervised Streaming Feature Selection in Social Media},
  booktitle = {Proceedings of the 24th {ACM} International Conference on Information
               and Knowledge Management, {CIKM} 2015, Melbourne, VIC, Australia,
               October 19 - 23, 2015},
  pages     = {1041--1050},
  publisher = {{ACM}},
  year      = {2015}
}
```

both datasets are collected form

https://github.com/xhuang31/LANE

```bibtex
@inproceedings{HuangLH17,
  author    = {Xiao Huang and
               Jundong Li and
               Xia Hu},
  editor    = {Maarten de Rijke and
               Milad Shokouhi and
               Andrew Tomkins and
               Min Zhang},
  title     = {Label Informed Attributed Network Embedding},
  booktitle = {Proceedings of the Tenth {ACM} International Conference on Web Search
               and Data Mining, {WSDM} 2017, Cambridge, United Kingdom, February
               6-10, 2017},
  pages     = {731--739},
  publisher = {{ACM}},
  year      = {2017}
}
```

### KDD Cup 2020
+ KDDS1
https://www.biendata.xyz/competition/kddcup_2020/data/

+ KDDS2
https://www.biendata.xyz/competition/kddcup_2020_formal/data/

### UAI2010
Link: https://github.com/zhumeiqiBUPT/AM-GCN

```bibtex
@inproceedings{wang2018unified,
  title={A Unified Weakly Supervised Framework for Community Detection and Semantic Matching},
  author={Wang, Wenjun and Liu, Xiao and Jiao, Pengfei and Chen, Xue and Jin, Di},
  booktitle={Pacific-Asia Conference on Knowledge Discovery and Data Mining},
  pages={218--230},
  year={2018},
  organization={Springer}
}
```
### ACM
This network is extracted from ACM dataset where nodes represent papers and there is an edge between two papers if they have the same author. All the papers are divided into 3 classes (Database, Wireless Communication, DataMining). The features are the bag-of-words representa- tions of paper keywords.

Link1: https://github.com/Jhy1993/HAN
Cite: 
```bibtex
@article{han2019,
title={Heterogeneous Graph Attention Network},
author={Xiao, Wang and Houye, Ji and Chuan, Shi and  Bai, Wang and Peng, Cui and P. , Yu and Yanfang, Ye},
journal={WWW},
year={2019}
}
```
Link2: https://github.com/zhumeiqiBUPT/AM-GCN
Cite: 
```bibtex
@inproceedings{DBLP:conf/kdd/0017ZB0SP20,
  author    = {Xiao Wang and
               Meiqi Zhu and
               Deyu Bo and
               Peng Cui and
               Chuan Shi and
               Jian Pei},
  title     = {{AM-GCN:} Adaptive Multi-channel Graph Convolutional Networks},
  booktitle = {{KDD} '20: The 26th {ACM} {SIGKDD} Conference on Knowledge Discovery
               and Data Mining, Virtual Event, CA, USA, August 23-27, 2020},
  pages     = {1243--1253},
  publisher = {{ACM}},
  year      = {2020},
}
```
