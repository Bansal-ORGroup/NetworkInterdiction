# Distributionally Risk-receptive and Risk-averse Network Interdiction Problem

## Sumin Kang and Manish Bansal

This repository is a companion repository for the paper titled "Distributionally Risk-receptive And Risk-averse Network Interdiction Problems With General Ambiguity Set." (Link to paper: http://www.optimization-online.org/DB_HTML/2021/12/8730.html)

### Abstract: 

In this paper, we introduce generalizations of stochastic network interdiction problem with distributional ambiguity. In particular, we consider a distributionally risk-averse (or robust) network interdiction problem (DRA-NIP) and a distributionally risk-receptive network interdiction problem (DRR-NIP) where a leader maximizes a follower's minimal expected objective value for either the worst-case or the best-case, respectively, probability distribution belonging to a given set of distributions (referred to as ambiguity set). The DRA-NIP arises in applications where a risk-averse leader is the main protagonist who interdicts a follower (opponent or evader) to cause delays in their supply convoy. In contrast, the DRR-NIP is applicable for network vulnerability analysis where a network user (or follower) also seeks to identify vulnerabilities in the network against potential disruptions by an adversary (or leader) who is receptive to risk for improving the expected objective values. We present exact and approximation algorithms for solving DRA-NIP and DRR-NIP with a general ambiguity set. We also provide conditions and family of ambiguity sets for which these approaches are finitely convergent. To evaluate the effectiveness and efficiency of the approaches for solving DRA-NIP and DRR-NIP, we provide results of our extensive computational experiments performed on instances known in the literature for (risk-neutral) stochastic NIP.

### Data:

In Instances folder, you will find the test instances generated based on the dataset available in Nguyen and Smith (link to their repository and paper: https://github.com/diHnguyen/IntAsymCostUnc; https://doi.org/10.1016/j.ejor.2021.04.055). The name of each folder denotes the following:

- US20: The interdiction attempts on around 20% of arcs are uncertain.
- US100: The interdiction attempts on all arcs are uncertain.

We consider instance categories with 40-, 60-, 80-, and 100-node networks, and label them as N40, N60, N80, and N100, respectively. Each instance category consists of 10 network instances. Each instance file contains the following data:

- (1st row) The number of nodes and arcs
- (2nd row) Arcs i j: an arc emanating from node i and going to node j
- (3rd row) Cost of each arc
- (4th row) Penalty cost of each arc
- (5th to last row) Random success of interdiction attempt on each arc - 1000 scenarios

The details of the instance generation are provided in the paper (http://www.optimization-online.org/DB_HTML/2021/12/8730.html).