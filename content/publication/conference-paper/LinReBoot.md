---
authors:
- admin
- Chi-Hua Wang
- Yuantong Li
- Guang Cheng
date: "2022-02-23T00:00:00Z"
doi: ""
featured: true
projects:
- exploration-bandit
publication: "*UAI2022*"
publication_short: ""
publication_types:
- "1"
publishDate: "2022-02-23T00:00:00Z"
summary: We propose a new bootstrap-based online algorithm for stochastic linear bandit problems. The key idea is to adopt residual bootstrap exploration, in which the agent estimates the next step reward by re-sampling the residuals of mean reward estimate. Our algorithm, residual bootstrap exploration for stochastic linear bandit (\texttt{LinReBoot}), estimates the linear reward from its re-sampling distribution and pulls the arm with the highest reward estimate. In particular, we contribute a theoretical framework to demystify residual bootstrap-based exploration mechanisms in stochastic linear bandit problems. The key insight is that the strength of bootstrap exploration is based on collaborated optimism between the online-learned model and the re-sampling distribution of residuals. Such observation enables us to show that the proposed \texttt{LinReBoot} secure a high-probability $\Tilde{O}(d \sqrt{n})$ sub-linear regret under mild conditions. Our experiments support the easy generalizability of the \texttt{ReBoot} principle in the various formulations of linear bandit problems and show the significant computational efficiency of \texttt{LinReBoot}.
tags:
- publications
- bandit algorithms
- nonparametric statistics
- uncertainty quantification
title: Residual Bootstrap Exploration for Stochastic Linear Bandit
url_pdf: https://arxiv.org/pdf/2202.11474.pdf
---