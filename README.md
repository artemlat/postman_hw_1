# #1. Postman
*Here I learned how to create request in Postman.*
*General settings:*  
```
Protocol: http
IP: 162.55.220.72
Port: 5005
```
### EP_1 (/get_method)  
```
Method: GET
EndPoint: /get_method
request url params: 
 name: str
 age: int

response: 
[
    “Str”,
    “Str”
]
```
![EP_1](https://github.com/artemlat/postman_hw_1/blob/main/EP_1(HW_1).png)

### EP_2 (/user_info_3)
```
Method: POST
EndPoint: /user_info_3
request form data: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'u_salary_1_5_year': salary * 4}}
```
![EP_2](https://github.com/artemlat/postman_hw_1/blob/main/EP_2(HW_1).png)

### EP_3 (/object_info_1)
```
Method: GET
EndPoint: /object_info_1
request url params: 
 name: str
 age: int
 weight: int

response: 
{'name': name,
          'age': age,
          'daily_food': weight * 0.012,
          'daily_sleep': weight * 2.5}
```
![EP_3](https://github.com/artemlat/postman_hw_1/blob/main/EP_3(HW_1).png)
