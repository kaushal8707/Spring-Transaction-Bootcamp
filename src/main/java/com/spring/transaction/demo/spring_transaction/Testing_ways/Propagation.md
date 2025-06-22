
In Transaction context Propagation defines How Transactions are Managed when a method is invoked with 
another Transaction.

If one transaction within another transaction then only you can play with Propagation behavior.

** To Validate or see the Transaction Log add in properties file-

## Enable transaction debug logs
#logging.level.org.springframework.transaction=DEBUG
#logging.level.org.hibernate.transaction=DEBUG
#logging.level.org.springframework.orm.jpa.JpaTransactionManager=DEBUG



    Propagation.REQUIRED - 
                Let's proved that while you are using Propagation.REQUIRED it will create a single
                Transaction and re-use it.

                use an existing transaction or create a new one if not exist.

    

