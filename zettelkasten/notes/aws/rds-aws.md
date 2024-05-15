
## Tittle: RDS amazon 
# date: 2024-05-06
# tags:
      - aws


## Relational database service

# Store auto scaling
    we can set automated rules to let amazon know how to scale our databases, we have to set maximun storage treshold so aws knows how to scale our databse

# read replicas
in your application you can have read replicas in the case that you do not want to slow down the normal flow for the main db instance i.e when you want to run a reporting application that is going to read from a replica instead that form the instace.
the replicas ar async which means that if the application is reading from the replica before it gets the chance to replicate the data, you may get all the data.Read replica is jsut for quering, no for deleting, inserting, deleting datal




