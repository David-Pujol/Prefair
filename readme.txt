The experiments in prefair depend heavily on the version of PrivBayes and MST which can be found in the following git repositories respectively. 

DataSynthesizer(https://github.com/DataResponsibly/DataSynthesizer)
MST(https://github.com/ryan112358/private-pgm/tree/aae58df3dc27b9d7ceb9eeab75a02549b3bc870e)

In order for the notebooks to function correctly the files in additional_files/DataSynthesizer_files must be added to the root directory of DataSynthesizer and the files in additional_files/private-pgm_files must be added to the root directory of private-pgm. Replace any files that are duplicates as they have been edited to properly run the experiments for PreFair

All the experiments based off privbayes can be found in the DataSynthesizer__correlated_attribute_mode.ipynb file in the /DataSynthesizer/ directory. All outputs will be found in the /DataSynthesizer/out/correlated_attribute_mode/ directory.

The source for PrivBayes Prefair can be found in /DataSynthesizer/DataSynthesizer/lib/FairPrivBayes.py

All the MST based experiments can be found in the /private-pgm/src/ directory. The Data Generation notebook will create the synthetic data for each of the MST based mechanisms, GreedyPrefair, ExponentialPrefair and MST. This includes the compas, adult and KDD datasets. The output will be found in /privatePGM/src/data/

The evaluations for each dataset are in different notebooks. Evaluations, Evaluations-KDD, and Evaluations-compas run the same set of quality measures for the adult, KDD, and compas datasets respectively.

The source for GreedyPreFair can be found in /privatePGM/src/mst_fair_greedy.py.
The source for ExponentialPreFair can be found in  /privatePGM/src/mst_fair_optimal.py.
