## About Me
![photo](./0.jpeg)


**Columbia University**  
M.S. in EE         
`But mostly, I focus on DB, OS, AI and Cloud.`    
```  ̄\_(ツ)_/ ̄ which is more promising ```

**University of Electronic Science and Technology of China**  
B.S. in IoT  

## TECH STACK
- Python, Java, C, JavaScript
- TensorFlow, Keras, Scikit-learn
- React, Express(Node.js), Flask
- Linux, Embedded System
- PostgreSQL, MySQL, DynamoDB, MongoDB, HBase
- Spark, Beam, Hadoop, Hive

## PROFESSIONAL EXPERIENCE


[**CS W4111: INTRODUCTION TO DATABASES**](http://w4111.github.io)                                                                                               
Teaching Assistant
Spring 2019

* Mentored 20+ students in designing Relational Database model, writing SQL, understanding Index, Concurrency, Optimizer, Logging, Column Stores and Spatial Searching in Database

* Designing tutorials about building back end using Postgres and Flask, maintained an AWS RDS for holding 40 websites      

* Instructed social network graph analysis such as centrality, distances, PageRank, clustering on Twitter dataset using Google BigQuery. 

* This course is freely available online at [https://w4111.github.io](https://w4111.github.io)


[**JD.COM INC.**](http://x.jdwl.com/drone/index)    
Software Engineering Intern in JD X – An innovation lab for unmanned packages delivery 
Beijing, 2016
         
* Co-designed a scalable monitor system for large number of drones, which supports real-time automatic defects and deviation detection. It processed streaming data from sensors such as GPS, power, accelerometer using Spark Streaming

* Visualized location and status based on Baidu Map API, Flask and MongoDB, which was used for a demo in JD drone controlling center

## SELECTED PROJECTS

[**QALite**](https://github.com/zw2497/QAlite)     
Full-stack Web Application, Cloud Computing    
Columbia, 2018      

* Designed a Q&A platform like Piazza with scalable Microservices Architecture based on AWS Elastic Beanstalk and Lambda

* Made REST APIs with Swagger and API Gateway for recourses, built automatic Email notification service by AWS SNS and SES, supported Google OAth2, address autocomplete, used Travis-CI and Pytest for continuous integration

* Built front end by Bootstrap and React, generated Token using JWT to maintain login status, used Fetch to get data from back end, placed static content on S3 and CloudFront to accelerate distribution

**Linux Kernel Hacking**
Operating System    
Columbia, 2018

* [Android orientation synchronization System call](https://github.com/zw2497/Android-Orientation-Synchronizer): Wrote an Android user-space daemon to pass device orientation info to kernel, used Wait Queue, Spinlock, IDR to allow multiple processes registering, destroying orientation events and getting notified when certain event happens    

* [Multi-core Weighted Round-Robin Scheduler](https://github.com/zw2497/Linux-Weight-Round-Robin-scheduler): An O (1) CPU Affinity Multicore Scheduler which supports keeping track of weight on each CPUs, idle load balancing by pulling tasks, assigned same CPU affinity on each thread groups

* [Simple Shell](https://github.com/zw2497/Linux-Simple-Shell): Implemented in C which supports built-in commands as well as `pipes, !, !string, history, chdir`

* [In-memory Proc File System](https://github.com/zw2497/Linux-Proc-File-System): Constructed a pseudo file system in Linux which can present process hierarchy in directory

[**Databass**](https://github.com/zw2497/DatabassEngine)      
a Python-based database for instruction
Columbia, 2018

* Implemented a Query Compiler which directly compiles SQL to Python code for execution which improves 50x faster than original interpreter. It supports operation such as Project, Scan, Filter, Count

* Added support on Offset, Limit, Orderby and Count function, implemented a Selinger Optimizer for multi-table join which supports predicate pushdown and dynamic programming

        
**Deep Neural Network (Current Project)**
* [Landmark Recognition](https://zw2497.github.io): Classify landmarks in Columbia using Keras, VGG16 with Fine-Tuning, support phone browsers using TensorFlow.js (Working on)

* [GANS tutorial](https://github.com/tensorflow/tensorflow): Design GANS tutorial for incoming Tensorflow 2.0 such as DCGAN, CycleGAN (Working on)

* [Phoneme_recognition_with_neural_networks](https://github.com/zw2497/Keras_LSTM_Tutorial): Use LSTM training on TIMIT linguistic dataset for English speech recognition, train Auto Encoder for noise reduction (Working on)



[**Airlock**](https://zw2497.github.io)            
Embedded System                                                                                                                                         UESTC, 2016     

* It is a Bluetooth lock for delivery packages sponsored by Chengdu Pangod Inc. This smart lock has AES-128 encryption and GPS tracking. It supported BLE Stack using TI CC2541. Patent No. 2016201342833
