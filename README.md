# Introduction 
This is a project implemented as part of the final exam of the course [IOT STREAM DATA MINING ](http://albertbifet.com/dk-iot-stream-data-mining-2017-2018/) thought by Prof. [Albet Bifet](http://albertbifet.com/) at Telecom Paristech.  
# Objectives 
The goal of this project is to build teams of 3 people to work together on an open source implementation of streaming algorithms that can be used with scikit-learn in Python. 

https://scikit-multiflow.github.io/scikit-multiflow/

The deliveries of the project are:
1. Source code following scikit-learn guidelines:              
 a. http://scikit-learn.org/stable/developers/contributing.html#coding-guidelines
2. Documentation following scikit-learn guidelines:          
http://scikit-learn.org/stable/developers/contributing.html#documentation   
 2. Presentation slides with experimental results 
 # Some basic theory 
 A **Hoeffding tree (VFDT)** is an incremental, anytime decision tree induction algorithm that is capable of learning from massive data streams, assuming that the distribution generating examples does not change over time. Hoeffding trees exploit the fact that a small sample can often be enough to choose an optimal splitting attribute. This idea is supported mathematically by the Hoeffding bound, which quantifies the number of observations (in our case, examples) needed to estimate some statistics within a prescribed precision (in our case, the goodness of an attribute).     
 A theoretically appealing feature of Hoeffding Trees not shared by other incremental decision tree learners is that it has sound guarantees of performance. Using the Hoeffding bound one can show that its output is asymptotically nearly identical to that of a non-incremental learner using infinitely many examples. For more information see:   
 *Geoff Hulten, Laurie Spencer, Pedro Domingos: Mining time-changing data streams. In: ACM SIGKDD Intl. Conf. on Knowledge Discovery and Data Mining, 97-106, 2001.* 
 # Given material   
 The teacher provided us with some material for helping us in developping the project:   
1. [Paper describing the implementation](/elena_ikonomovska.pdf)
2. [An example dataset, based on the IMDB data](https://www.dropbox.com/s/kol9wtbzql0laga/imdb.csv.gz?dl=0/)
3. [Original Moa Java Source code](/JavaRegressionHoeffdingTree.java)
