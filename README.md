# NYU Metropolitan Mobile Bandwidth Trace 

## Summary
NYU Metropolitan Mobile Bandwidth Trace, a.k.a. NYU-METS, is a LTE mobile bandwidth dataset that were measured in New York City metropolitian area. It covers several transportation scenarios like Subway, Bus, Ferry etc.


## Access
Our dataset is FREE for public. But we kindly ask that should you mention any of our datasets that you would reference the following paper: 

*Lifan Mei, Runchen Hu, Houwei Cao, Yong Liu, Zifa Han, Feng Li & Jin Li. (2019, March). Realtime Mobile Bandwidth Prediction using LSTM Neural Networks. In International Conference on Passive and Active Network Measurement. Springer, Cham.*  

Or

*Mei, Lifan, Runchen Hu, Houwei Cao, Yong Liu, Zifan Han, Feng Li, and Jin Li. "Realtime mobile bandwidth prediction using LSTM neural network and Bayesian fusion." Computer Networks 182 (2020): 107515.*
  
## License:
This NYU Metropolitan Mobile Bandwidth Trace dataset (NYU-METS) is made available under the Open Database License: http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/
  

## Description 

We collected long bandwidth traces in New York City Metropolitan area. These traces are collected in Bus, Subway, Ferry and Rail Road etc. 

Bus:   
Bus B57 (Between IKEA Brooklyn and Flushing Ave & 61 st Street)   
B62 (Between MetroTech and Queensboro Plaza)  
NYU Campus Bus Route A (Between Downtown Brooklyn and NYU Bookstore)  

Subway:   
Subway 7 Train (Between Queensboro Plaza and Flushing Main Street)  
Subway Q Train (Between Prospect Park and Coney Island)  
Subway D Train (Between Prospect Ave and Stillwell Avenue)   

Ferry:  
Ferry (Between South Ferry and Staten Island)  

Car:   
Car (Between Downtown Brooklyn and LGA)

Long Island Rail Road:  
Long Island Rail Road (Between Woodside Station and Little Neck). 


For example,
![](https://github.com/NYU-METS/Main/blob/master/Sample_Traces/Scenarios.jpg)

For each experiment, we connect a LTE mobile phone to a remote server in our lab at NYU. 
We run iPerf and record TCP throughput every 1,000 millisecond for a long and successive time in the same scenario. All the bandwidth samples are logged on the server side. 

We are continuing this measurement campaign and keep adding new traces to our NYU-METS Dataset for future research.




## For Multivariate Traces in 2020, please enter /Multivariate_Dataset
https://github.com/NYU-METS/Main/tree/master/Multivariate_Dataset


## Acknowledgement
Thanks for their contribution for the measurement: 
Lifan Mei, Tongyu Zong, Jingrui Yang, Haoyu Deng, Siquan Wang and Jinrui Gou.

The site is still in construction.
