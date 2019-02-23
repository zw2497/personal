## EDUCATION
Aug. 2018 - Dec. 2019 | New York   
**Columbia University**  
M.S. in Electrical Engineering   
GPA: 3.92 

Sep. 2013 - Jun. 2017 | Chengdu, China   
**University of Electronic Science and Technology of China**  
B.S. in Internet of Things  
GPA: 3.82   

## TECH STACK
- Python, Java, C/C++, JavaScript
- TensorFlow, Keras, Scikit-learn
- React, NodeJS, Flask
- Linux, Embedded System
- PostgreSQL, MySQL, DynamoDB, MongoDB
- Spark, Beam

## PROFESSIONAL EXPERIENCE


[**CS W4111: INTRODUCTION TO DATABASES**](http://w4111.github.io)                                                                                               
Teaching Assistant
Spring 2019

* Mentored 20+ students in designing Database model and building Web applications, focused on Postgres and Flask, maintained an AWS RDS for holding 40 websites as course database

* Gave instructions on social network graph analysis on Twitter dataset such as PageRank, Clustering using Google BigQuery. This course is freely available online at [w4111](http://w4111.github.io)


[**JD.COM INC.**](http://x.jdwl.com/drone/index)    
Software Engineering Intern in JD X – An innovation lab for unmanned packages delivery 
Beijing, 2016
         
* Worked on a real-time scalable monitor system for large number of drones, which supports automatic defects and deviation detection, used Spark to process streaming data from sensors such as GPS, power

* Visualized location and status based on Baidu Map API, Flask back-end and MongoDB, which was used for a demo in JD drone controlling center

## SELECTED PROJECTS

[**QALite**](https://github.com/zw2497/QAlite)     
Full-stack Web Application, Cloud Computing    
Columbia, 2018      

* It is a Q&A platform like Piazza with scalable Microservices Architecture based on AWS Elastic Beanstalk and Lambda

* Made REST APIs with Swagger and API Gateway for users, courses, posts and comments, built automatic Email notification service by AWS SNS and SES, supported Google OAth2, used Travis-CI and Pytest for continuous integration

* Built Front-end by Bootstrap and React which was placed on S3 and CloudFront to accelerate distribution

**Linux Kernel Hacking**
Operating System    
Columbia, 2018

* [Android orientation synchronization System call](https://github.com/zw2497/Android-Orientation-Synchronizer): Used Spinlock, IDR, Wait Queue to allow multiple processes registering, destroying orientation events and getting notified when certain orientation event happens
* [Multi-core Weighted Round-Robin Scheduler](https://github.com/zw2497/Linux-Weight-Round-Robin-scheduler):  Built prior to Linux Fair scheduler, supported CPU Affinity on multi-threads in the same process and load balancing on processors by pushing and pulling processes from run queue
* [Simple Shell](https://github.com/zw2497/Linux-Simple-Shell): Implemented in C which supports fork and execute built-in commands, pipes and command history
* [In-memory Proc File System](https://github.com/zw2497/Linux-Proc-File-System):  Constructed a pseudo file system in Linux which can present process information in directory, correctly handling reparenting and termination of processes as well as acquiring mutexes

[**Databass**](https://github.com/zw2497/DatabassEngine)      
a Python-based database for instruction
Columbia, 2018

* Implemented a Query compiler which directly compiles query to python for execution improves 50x faster than original interpreter. It supports Project, Scan, Filter, Count and Where clause
* Added offset and limit function in SQL syntax parser using Parsimonious, Regex
* Wrote a Selinger optimizer for multi-table join which supports predicate pushdown and Dynamic Programming

[**Landmark Recognition**](https://zw2497.github.io)        
Computer Vision, CNN       
Columbia, 2019    

* Classified landmarks in Columbia University based on Keras, supporting smartphone browsers based on TensorFlow.js 
* Collected dataset from self-captured videos and images from Google, used pretrained model VGG16 to train with Data augmentation, Dropout and Fine-Tone

[**Airlock**](https://zw2497.github.io)            
Embedded System                                                                                                                                         UESTC, 2016     

* It is a Bluetooth lock for delivery packages sponsored by Chengdu Pangod Inc. This smart lock has AES-128 encryption and GPS tracking. It supported BLE Stack using TI CC2541. Patent No. 2016201342833
