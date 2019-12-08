# ST05 (Oracle has more options than any other database) 

Set the parameters 
![](ST05_1.png)

Execute the process what you want to do the performance analisys 

Combine SQL statements
![](ST05_15.png)

The duration column measure is microseconds. You can use https://convertlive.com/u/convert/microseconds/to/seconds to convert. 
In this case was 12.386.327 microsends, in seconds is 12,38s. 

![](ST05_14.png)

To see the CPU/Process usage, click in the 'Explain' (F9) option.

![](ST05_17.png)

Details without index usage: 

![](ST05_18.png)

Details with index usage: 

![](ST05_19.png)

# Important things to analyze: 

# 1- DDIC Information (F2)

This analyze the index available for the table. 
![](ST05_13.png)

For the literal name fields click in the 'Index Table Fields' 
![](ST05_12.png)

# 2 - What fields is being selected at the statement (SHIFT + F2)

Some of databases in ST05 show all the columns when * is used, another show only the * . 

![](ST05_5.png)

# ST05 fields and screen can be different based on the database of the server. 

Example:

Informations of ddic and abap statement
![](ST05_16.png)

In some other databases:
![](ST05_4.png)

Sumarize SQL statements in other database:
![](ST05_7.png)



