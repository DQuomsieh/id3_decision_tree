## ID3 Decision Tree using Python
------
Assignment for COMP4388 (Machine Learning)
---
### Main Functions 
* calculate_entropy -> returns entropy for values inside feature column
* calculate_information_gain -> returns target feature entropy minus split feature entropy
* build_tree -> recursive id3 algorithm to build tree
---
### Helper Functions
* prepare_data -> change from arff to pandas df
* get_unique_count -> pretty much np.unique
* get_max -> returns max element
* get_sum -> returns total sum
* predict -> create prediction column from tree built
* get_accuracy -> compares output of predict with target feature
---
### Improvements: Cross Validation k = 3
I was getting ~76% accuracy originally, after adding cross validation I was able to improve it to ~95% accuracy.
