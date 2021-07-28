## Procedures
A procedure is a combination of SQL statements written to perform a specified tasks. It helps in code re-usability and saves time and lines of code.

## Triggers :
A trigger is a special kind of procedure which executes only when some triggering event such as INSERT, UPDATE, DELETE operations occurs in a table.


## Difference between Triggers and Procedures :

### Triggers	
> 1. A Trigger is implicitly invoked whenever any event such as INSERT, DELETE, UPDATE occurs in a TABLE.
> 2. Only nesting of triggers can be achieved in a table. We cannot define/call a trigger inside another trigger.	
> 3. In a database, syntax to define a trigger: CREATE TRIGGER TRIGGER_NAME.
> 4. Transaction statements such as COMMIT, ROLLBACK, SAVEPOINT are not allowed in triggers.	
> 5. Triggers are used to maintain referencial integrity by keeping a record of activities performed on the table.
> 6. We cannot return values in a trigger.Also, as an input, we cannot pass values as a parameter.	

### Procedures
> 1. A Procedure is explicitly called by user/application using statements or commands such as exec, EXECUTE, or simply procedure_name.
> 2. We can define/call procedures inside another procedure.	
> 3. In a database, syntax to define a procedure: CREATE PROCEDURE PROCEDURE_NAMEAll 
> 4. transaction statements such as COMMIT, ROLLBACK are allowed in procedures.	
> 5. Procedures are used to perform tasks defined or specified by the users. 
> 6. We can return 0 to n values. However, we can pass values as parameters.
