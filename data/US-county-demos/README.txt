This is a county-level election map network. Each node is a county and two nodes
are connected if they share a border. The edge list file is:
county_graph.csv

The node features are constructed from USDA demographic data:
https://www.ers.usda.gov/data-products/county-level-data-sets/
as well as county-level U.S. presidential election statistics formatted by Tony McGovern:
https://github.com/tonmcg/US_County_Level_Election_Results_08-16

The nodes in the edge list are identified by FIPS county codes. The node
features for 2012 and 2016 are contained the following files:
county_stats_2012.csv
county_stats_2016.csv

If you use this data, please cite our paper:
Outcome Correlation in Graph Neural Network Regression, Junteng Jia and Austin R. Benson, arXiv:2002.08274, 2020
and acknowledge the above hyperlinks.

