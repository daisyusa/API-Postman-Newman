# API-Postman-Newman

# Tutorial
 https://testautomationu.applitools.com/exploring-service-apis-through-test-automation/ 

# Example API site

https://restful-booker.herokuapp.com/

# API Doc
https://restful-booker.herokuapp.com/apidoc/index.html

Covered
1: Auth: CreateToken 

 (1): Auth: Cookie
 
delete
https://restful-booker.herokuapp.com/booking/1

Example 1 (Cookie):

curl -X DELETE \
  https://restful-booker.herokuapp.com/booking/1 \
  -H 'Content-Type: application/json' \
  -H 'Cookie: token=abc123'
  
(2): Auth: Basic

Example 2 (Basic auth):
curl -X DELETE \
  https://restful-booker.herokuapp.com/booking/1 \
  -H 'Content-Type: application/json' \
  -H 'Authorization: Basic YWRtaW46cGFzc3dvcmQxMjM='
  
2: GET, POST, PUT, PATCH, DELETE, PING

 
