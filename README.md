### Routes
` POST /new_patient`

```python
{"name": str, "id": int, "age": int}
```


`POST /add_test`

```python
{"id": int, "test_name": str, "test_result": int}
``` 

`GET /get_results/<patient_id>`


<!---
### Database
A list of dictionaries, with each dictionary as follows:
```python
{
 "name": str, "id": int, "age": int, 
 "tests": list of tupples of (test_name: str, test_result: int)
}
```
--->