---
abstract: Learning on Graphs (LoG) is widely used in multi-client systems when each client has insufficient local data, and multiple clients have to share their raw data to learn a model of good quality. 
  One scenario is to recommend items to clients with limited historical data and share common preferences with other clients in a social network. 
  On the other hand, due to the increasing demands for the protection of clients' data privacy, Federated Learning (FL) has been widely adopted. FL requires models to be trained in a multi-client system and restricts sharing of raw data among clients. 
  The underlying potential data-sharing conflict between LoG and FL is under-explored and how to benefit from both sides is a promising problem. 
  In this work, we first formulate the Graph Federated Learning (GFL) problem that unifies LoG and FL in multi-client systems and then propose sharing hidden representation instead of the raw data of neighbors to protect data privacy as a solution. 
  To overcome the biased gradient problem in GFL, we provide a gradient estimation method and its convergence analysis under the non-convex objective. 
  In experiments, we evaluate our method in training graph neural network models of classification tasks. 
  Our experiment shows a good match between our theory and the practice.
authors:
- admin
- Mingxuan Zhang
- Yuantong Li
- Carl Yang
- Pan Li
date: "2022-06-21T00:00:00Z"
doi: ""
featured: true
projects:
- graph-FL
publication: "*Preprint*"
publication_short: ""
publication_types:
- "3"
publishDate: "2022-06-20T00:00:00Z"
tags:
- publications
- machine learning on graphs
- federated learning
- optimization
title: Graph Federated Learning with Hidden Representation Sharing
url_pdf: https://arxiv.org/pdf/2212.12158.pdf
---