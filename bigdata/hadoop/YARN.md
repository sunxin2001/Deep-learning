#
YARN is a resource manage system and a negotiator platform.  
For example, if we want to analyze some data, we have to use RAM/CPU to process our data.  
YARN is to assign available ram and cpu for us to use.  

<img src="https://user-images.githubusercontent.com/111692657/210114911-60d31f4d-6d4b-4554-8fa2-a5948d41ec6f.png" width="500">  
YARN also used MASTER/SLAVE frame like HDFS.  
There are two nodes--one resource manager and many node manager.  

![image](https://user-images.githubusercontent.com/111692657/210117427-22b1497c-715d-484e-8ae9-5368db12128f.png)  
when we run an application, we first start mr application master to request resource from resource manager.  


![image](https://user-images.githubusercontent.com/111692657/210117612-43f2bc89-78dc-405a-9878-cd052936f656.png)  
what is inside RM---application manager and resource scheduler.  
there are three types of scheduler---FIFO, Capacity scheduler, and Fair scheduler.

![image](https://user-images.githubusercontent.com/111692657/210119848-240fa799-e3c8-4a1d-ace4-3915d82d76db.png)  
FIFO  
  
  
  
![image](https://user-images.githubusercontent.com/111692657/210119834-d2d39587-d03a-42da-90eb-149483da1ba4.png)  
![image](https://user-images.githubusercontent.com/111692657/210119863-443b8465-dc24-4d91-a9ce-9bf8e393c157.png)  
capacity scheduler  

![image](https://user-images.githubusercontent.com/111692657/210119894-de3678e2-7d7e-47c3-bdb7-bf31147d4666.png)  
Fair scheduler---two users got tasks, then they got equal resources to use. if A has two task, then A's resources were equally divided into two parts.









