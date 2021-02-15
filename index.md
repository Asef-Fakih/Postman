# Postman Scripting

## Postman Variables
### Types of variable
- Global
- Environment
- Collection
- Data
- Local
### Get , Set, unset format
For collectionVariables, environment, global use pm. format <br>
Get <br>
```
pm.variable.get('variable') 
```
Set <br>
```
pm.variable.set('variable') 
```
Unset <br>
```
pm.variable.unset('variable')
```
Replace (use the var) <br>
```
pm.variables.replaceIn("Hi, my name is {{variable}}");
```
## WOrking with Requests
The request URL:
<img src="2021-02-15_19h58_47.png" alt="hi" class="inline"/>

# Postman common pre requests

# Writing Postman Assertions
# Chaining Postman Requests
