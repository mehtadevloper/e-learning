# SQL Triggers
A trigger is a stored procedure in database which automatically invokes whenever a special event in the database occurs. 
For example, a trigger can be invoked when a row is inserted into a specified table or when certain table columns are being updated.

## Syntax
> create trigger [trigger_name] 
> [before | after]  
> {insert | update | delete}  
> on [table_name]  
> [for each row]  
> [trigger_body]

1. create trigger [**trigger_name**]: Creates or replaces an existing trigger with the trigger_name.
2. [**before | after**]: This specifies when the trigger will be executed.
3. {**insert | update | delete**}: This specifies the DML operation.
4. on [**table_name**]: This specifies the name of the table associated with the trigger.
5. [**for each row**]: This specifies a row-level trigger, i.e., the trigger will be executed for each row being affected.
6. [**trigger_body**]: This provides the operation to be performed as trigger is fired

### Before Trigger
BEFORE triggers run the trigger action before the triggering statement is run.

### After Trigger
AFTER triggers run the trigger action after the triggering statement is run.

