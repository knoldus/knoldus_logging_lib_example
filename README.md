# knoldus_logging_lib_example

Rollbar UI tips

``` 
  rollbarLogger.error("User doesn't have an access!")
  rollbarLogger.info("Joined the server!")
  rollbarLogger.debug("Debug message again!")
``` 
In UI u can find all of the logs in a list
![Screenshot from 2023-02-08 05-53-20](https://user-images.githubusercontent.com/112972026/217509784-15b025ea-a3b2-4b7e-9763-46005765fef1.png)

if you open exact log  you will be able to see the detailed description with whole information

![Screenshot from 2023-02-08 05-51-54](https://user-images.githubusercontent.com/112972026/217509490-f41f7c4a-87f7-4653-b823-b577b1f9a8a4.png)
``` 
    .withKeyValue("company", Company("Knoldus inc.", "Canada, ON, Mississauga", "Software Development"))
    .withKeyValue("employee", Employee("Vlad Marinychev", "5062", "Software engineer", "Scala Studio"))
``` 
In Occurences tab below you can see additional data. In our case its company and employee information.
![Screenshot from 2023-02-08 05-52-37](https://user-images.githubusercontent.com/112972026/217509599-63d0927e-2bde-4458-985e-38e9e38db378.png)

Also you able to make a small tasks from the issues in your application logs and assign it to your team members to solve!
![Screenshot from 2023-02-08 05-54-57](https://user-images.githubusercontent.com/112972026/217510216-a08fda8c-853a-4a26-8db7-b1d766fa552f.png)
