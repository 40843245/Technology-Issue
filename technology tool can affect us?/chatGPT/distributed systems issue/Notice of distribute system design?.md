# Notice of distribute system design?
There are four requirements we have to followed.
1. Consistently.
2. Scability.
3. Latency.
4. Availiability.

 1. Consistently refers can the datas are consistency.
 When the one part of data changes, can other data we put it in also change immediatly?
 
 2. Scability refers the size of data to handle with.

 3. Latency does NOT refer to slow down something.
 
  If refers the time it waits until it get started to evaluate.
  
  Latency= first wait tine = first start time - first time to wait for it.
  
  4. Availability is a knid of measure that represent the availibity to access one data.
  
  The higher availabilty we have, the higher fault toleronce and possiblity to occur we can have.
  
  Availability = uptime / (uptime + downtime).
  
  ![image](https://user-images.githubusercontent.com/75050655/222011707-918a0ba1-6274-4d3c-b1f6-8af7ff64c845.png)
  
  What obstacles to make us NOT easily to scale of the distributed systems?
  
  1)We have many to modes.
      
  2)Each node distances too far.
  
  5. Intelligently, how smart it is, can we do it quickly with the quickstart?
  
  
  ## Ref
  https://medium.com/the-bayesian-trap/7-%E8%88%88%E8%B6%A3%E4%BD%BF%E7%84%B6%E5%9C%B0%E5%AD%B8%E7%BF%92%E5%88%86%E6%95%A3%E5%BC%8F%E7%B3%BB%E7%B5%B1-1-167180ca7152
