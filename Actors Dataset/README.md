# Elliptic++ Actors (Wallet Addresses) Dataset: A Graph Network of Bitcoin Blockchain Wallet Addresses

The Elliptic++ dataset consists of 822k wallet addresses to enable the detection of illicit addresses (actors) in the Bitcoin network by leveraging graph data.

If you have any questions or create something with this dataset, please let us know by email: [yelmougy3@gatech.edu](mailto:yelmougy3@gatech.edu).

## Dataset Summary 

|  |  |
|---|---|
| # Wallet addresses | 822,942 |
| # Nodes (temporal interactions) | 1,268,260 |
| # Edges (addr-addr) | 2,868,964 |
| # Edges (addr-tx-addr) | 1,314,241 |
| # Time steps | 49 |
| # Illicit (class-1) | 14,266 |
| # Licit (class-2) | 251,088 |
| # Unknown (class-3) | 557,588 |
| # Features | 56 |

## Dataset Tutorials

We are sharing tutorial notebooks for users and researchers to explore, study, and learn from. The tutorial notebooks cover dataset statistics, graph visualization, model training and classification, and feature refinement.

[`Actors dataset statistics`](Elliptic++_Actors_Dataset_Statistics.ipynb) : overall actors data statistics.  
<p align="center">
    <img src="../images/addrstats.jpg" width="650" alt="addrstats" /><br>
</p>  

[`Actors graph visualization (Actor Interaction)`](Elliptic++_Actors_ActorInteraction_Graph_Viz.ipynb) : visualizations of the Actor Interaction graph (addr-addr graph).  
<p align="center">
    <img src="../images/actorvizaddr.jpg" width="800" alt="actorvizaddr" /><br>
</p> 

[`Actors graph visualization (Address-Transaction)`](Elliptic++_Actors_AddrTx_Graph_Viz.ipynb) : visualizations of the Address-Transaction graph (addr-tx-addr graph).  
<p align="center">
    <img src="../images/actorvizaddrtx.jpg" width="550" alt="actorvizaddrtx" /><br>
</p> 

[`Actors classification`](Elliptic++_Actors_Classification.ipynb) : model training and classification on the actors data.  
<p align="center">
    <img src="../images/classification.jpg" width="550" alt="actorclassification" /><br>
</p> 

[`Actors feature analysis`](Elliptic++_Actors_Feature_Analysis.ipynb) : feature importance analysis of the actors data.
<p align="center">
    <img src="../images/actorsfeatureanalysis.jpg" width="680" alt="actorsfeatureanalysis" /><br>
</p> 


## Top-Level Directory Organization

    .
    ├── wallets_features.csv                                # Feature data for all actors
    ├── wallets_features.csv                                # Feature data for all actors
    ├── wallets_classes.csv                                 # Class data for all actors
    ├── AddrAddr_edgelist.csv                               # Address-Address graph edgelist
    ├── AddrTx_edgelist.csv                                 # Address-Transaction graph edgelist
    ├── TxAddr_edgelist.csv                                 # Transaction-Address graph edgelist
    ├── Elliptic++ Actors Dataset Statistics.ipynb          # Tutorial notebook: dataset statistics
    ├── Elliptic++ Actors ActorInteraction Graph Viz.ipynb  # Tutorial notebook: address-address graph visualization
    ├── Elliptic++ Actors AddrTx Graph Viz.ipynb            # Tutorial notebook: address-transaction-address graph visualization
    ├── Elliptic++ Actors Classification.ipynb              # Tutorial notebook: model training and classification
    ├── Elliptic++ Actors Feature Analysis.ipynb            # Tutorial notebook: feature importance analysis
    └── README.md


# Citation

If you use our dataset in your work, please cite [our paper]().

> Youssef Elmougy and Ling Liu. 2023. Demystifying Fraudulent Transactions and Illicit Nodes in the Bitcoin Network for Financial Forensics.

# Acknowledgement

Released by: [Youssef Elmougy](https://www.yelmougy.com), [Ling Liu](https://www.cc.gatech.edu/home/lingliu/)

School of Computer Science, Georgia Institute of Technology


If you have any questions or create something with this dataset, please let us know by email: [yelmougy3@gatech.edu](mailto:yelmougy3@gatech.edu).
