# GRADIENT DESCENT  

This repository is  about gradient descent. 
Linear Regression was implemented from scratch.     

It is a great work to understand gradient descent's types.     

These types are compared in terms of running time and cost function. 

## BATCH GRADIENT DESCENT 
All data is used when calculating cost.Therefore, cost fucntion decreases smoothly.  
It works slower than other types but it is the type that most possible type to reach local minumum.  
Also, it is the type that needs the most memory.  

### BATCH COST FUNCTION 
![batch](https://user-images.githubusercontent.com/94362868/193311912-bcbd575d-093f-48cc-981b-28780f5cd900.png) 
### Running Time      

![batch](https://user-images.githubusercontent.com/94362868/193933719-16ccbaba-f2e7-4509-8475-fc617dd93c7b.png)


## MINI BATCH GRADIENT DESCENT    
Data was divided batches. Batch's number is generally a power of two.  
Cost function calculated by using these batches. Therefore, less data is used to calculate cost function.  
So, it is faster and it needs less memory. Because, all data isn't replace in RAM just one batch replaces.  
Cost function can be wavy, but generally approaches local minumum.   
It is the most common type espacially tasks which need more memory.   


###  MINI BATCH COST FUNCTİON 
![mini batch](https://user-images.githubusercontent.com/94362868/193311987-dc9cc0a4-cea7-443c-8063-9d655a71ffc5.png)
### Running Time       

![mini batch](https://user-images.githubusercontent.com/94362868/193933734-3056cbaa-d5d1-4fdd-a7e5-e59484b08350.png)

## STOCHASTIC GRADIENT DESCENT   
In stochastic gradient descent, cost function calculated by using just one samples.  
For that reason, can't be reach local minimum. Cost function decreases and increases all the time.  
However, this type need least memory, it can be used some tasks.  
Also, losses np.dot() fast therefore it is slower than mini-batch gradient descent.  


###  STOCHASTIC COST FUNCTION 
![sto cost](https://user-images.githubusercontent.com/94362868/193933788-d2df7a45-6c30-49bf-935a-ca47d3f36753.png)

### Running Time       

![stoc](https://user-images.githubusercontent.com/94362868/193933870-4ecdd640-c7c6-4e62-8a72-a7f90f451bda.png)
