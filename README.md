# anti-money-laundering (aml)


Money laundering is the process used to disguise the source of money or assets derived from criminal activity. Money laundering involves approximately  $590  billion to  $1.5  trillion USD per year worldwide. In 2018,  $46.7  billion was laundered through Canada with  $7.4  billion accounted in British Columbia. Canadian real state is a prime target for money laundering. For banks, it is important to comply the legislation from FINTRAC and OSFI.

In terms of the model, it is important to reduce the false positive alarms while having very low tolerance to false negatives. False negatives, are critical because they may be problematic for the bank in terms of legislation and affect the reputation of the bank. It is important to analyze the context of the transactions/users relationships to improve effectiveness of the alarms.


## Data: Elliptic Data Set
### Link: https://www.kaggle.com/artgor/elliptic-data-eda/data
The Elliptic Dataset is a graph network of Bitcoin transactions with handcrafted features. All features are constructed using only publicly available information.

The Elliptic DataSet maps Bitcoin transactions to real entities in two categories:

Licit: exchanges, wallet providers, miners, licit services, etc.
Ilicit: scams, malware, terrorist, organization, ransomware, Ponzi shcemes, etc
A given transaction is licit if the entity that generated it was licit.

Nodes and Edges 203,769 node transactions and 234,355 directed edge payments flows. 2% are ilicit (Class 1), 21% are licit (Class 2)
Features Each node has associated 166 features. 94 represent local information (timestep, number of inputs/outputs, transaction fee, output volume and aggregated figures) and 72 features represent aggregated features (obtained by aggregating transaction information such as maximum, minimum, standard deviation, correlation coefficients of neighbor transactions).
Temporal Information A time step is associated with each node, representing an stimated of the time when the transaction is confirmed. There are 49 distinct timesteps evenly spaced with an interval of 2 weeks.


