The first step of k mean clustering is randomly guess--- cluster centroid.  
<br>
<br>
then assign each point to its closetest centroid.  
<br>
<br>
![image](https://user-images.githubusercontent.com/111692657/210696489-5612ec2c-9163-4072-8144-c9a77c561706.png)  
the recompute the centroid.  
![image](https://user-images.githubusercontent.com/111692657/210696521-7bf97bb5-3b50-4bcf-9d53-5d7914e3a239.png)  
<br>
<br>
repeat sceond step and third step.  
![image](https://user-images.githubusercontent.com/111692657/210696886-fcd78305-883b-4d33-a9e0-42df747e839c.png)  
<br>
<br>
cost function/optimization objective
![image](https://user-images.githubusercontent.com/111692657/210697497-56fefa38-090a-41db-8ee1-cc4233e113b1.png)  

![image](https://user-images.githubusercontent.com/111692657/210697632-cf5a9f43-eda1-4faa-9aa7-2fa77f472e5e.png)  
![image](https://user-images.githubusercontent.com/111692657/210697722-eee187cc-de32-414b-b48d-31feb5a59105.png)  
<br>
<br>
<br>
<br>
<br>
# how randomly choose a cluster centroid.   
randomly pick a train example as centroid.--- however, this method may be lead a local minimum.   
we can randomly select centroids for serveral times, and compute the cost function or distortion function and then select the least cost function as initial centroid.  
![image](https://user-images.githubusercontent.com/111692657/210700128-8b6d384f-a058-4be3-868a-baddfb2dcf9f.png)  

 

