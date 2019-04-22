# Easy University Course Information System

### demo video
[youtube](https://youtu.be/yPkNbhXRk78)  

### Development Environment
Language: python3.6  
IDE: Pycharm  
database: SQLite

certifi==2018.11.29  
Django==2.1.5  
pytz==2018.9


### deployment
deployed at [pythonanywhere](http://yiqing5.pythonanywhere.com/about/)  

followed the instructions from [here](https://help.pythonanywhere.com/pages/DeployExistingDjangoProject)

### description
This is a easy-version university management system. 
- functions  
Instructor management  
![](https://ws4.sinaimg.cn/large/006tNc79ly1g2b8d5n1dgj31jj0u0dll.jpg)
course management  
![](https://ws1.sinaimg.cn/large/006tNc79ly1g2b8dbqax6j31k10u0agm.jpg)
students management  
![](https://ws1.sinaimg.cn/large/006tNc79ly1g2b8dgmgu2j31ki0u0q8q.jpg)
registration managment  
![](https://ws3.sinaimg.cn/large/006tNc79ly1g2b8djo512j31kw0u044d.jpg)
- roles
1) sysadmin  
work as superuser, with full access to database, free to do all CRUD operation  

2) registrar  
have access to student registration, update student and registration records  

3) scheduler  
have access to course scheduling, free to update course and section records  

4) clerk  
only have access to view all information  
