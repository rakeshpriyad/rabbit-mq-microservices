POST request
http://localhost:8080/
{
"id": 1,
"number": 123456,
"balance": 500,
"customerId": 1,

}


GET request
http://localhost:8080/1
{"id":1,"number":"1234567890","balance":50000,"customerId":1}


GET request
http://localhost:8080/customer/1
[{"id":1,"number":"1234567890","balance":50000,"customerId":1},{"id":2,"number":"1234567891","balance":50000,"customerId":1},{"id":3,"number":"1234567892","balance":0,"customerId":1},{"id":10,"number":"123456","balance":500,"customerId":1}]