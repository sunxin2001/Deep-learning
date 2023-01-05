entropy as a measure of purity  

take 2022 deeping learning cats and dogs as examples--after we create decision tree, we use entropy as a measure of purity.  
![image](https://user-images.githubusercontent.com/111692657/210664964-e0286c99-9e78-4197-b9d6-df8269de9207.png)  
entropy should be like this. as 50-50 is the least pure!  
the puriest combination is we got all cats or dogs.  
![image](https://user-images.githubusercontent.com/111692657/210678923-5cc2dd38-a773-4807-bb69-5e0d30761fe5.png)  
usually, we use log2x instead of ln because ln are not canvex:  
![image](https://user-images.githubusercontent.com/111692657/210680750-1da6e079-3e52-4081-913c-9164f84fb4bd.png)  
<br>
<br>
<br>
how we choose a split?
we choose the reduction of weighted average entropy from original(information gain) as the best split.  
![image](https://user-images.githubusercontent.com/111692657/210681544-dec7b803-9512-4140-ae45-eac761e0b973.png)   
![image](https://user-images.githubusercontent.com/111692657/210681707-faec0b25-bc74-4dc9-8cb8-4ef421e5865d.png)  
<br>
<br>
![image](https://user-images.githubusercontent.com/111692657/210683940-5b560012-f5a0-49c4-8b5e-bf9cb661f7a5.png)  
one-hot code!  
![image](https://user-images.githubusercontent.com/111692657/210684107-5cf345aa-c49e-4c87-86bd-1614f4a37fb0.png)  
<br>
<br>
<br>
regression tree:  
how to choose a split based on variance.  
![image](https://user-images.githubusercontent.com/111692657/210686221-4f7be052-4d98-4e7a-873c-c5b50fe6923d.png)  
![image](https://user-images.githubusercontent.com/111692657/210686836-a2896e84-6bd7-4968-b1b7-003ee1050274.png)  
<br>
<br>
<br>
sampling with replacement.  
<br>
<br>
<br>
bagged decision tree:  
![image](https://user-images.githubusercontent.com/111692657/210688347-f2b0f473-7ce8-41ac-9606-610e8e08afb7.png)  
random the feature choice:  
![image](https://user-images.githubusercontent.com/111692657/210689146-7ef75b9b-c03f-43aa-8c4a-e40b065c869e.png)  
<br>
<br>
<br>
xgboost algo is to train the example which performs worse in last iteration.   
![image](https://user-images.githubusercontent.com/111692657/210689979-dc06c529-f56f-495d-b67e-9a7666e72dde.png)  







