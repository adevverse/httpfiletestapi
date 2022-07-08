# httpfiletestapi
file .http test api rest api (post / get) vs code
> Extention REST-CLIENT
> https://marketplace.visualstudio.com/items?itemName=humao.rest-client



<p>
@baseUrl = http://localhost:5000
@apiname = users
@username = {{$dotevn RDP_USERNAME}}
@password = {{$dotevn RDP_PASSWORD}}
  
# Test
POST {{baseUrl}}/{{apiname}} HTTP/1.1
Content-Type: application/json
  
  {
  "fname":"fname",  
  "lname":"lname",   
  "username":"email.com",
  "password":"1234",
  "avatar":"http://localhost:5000/public/images/users/user1.jpg"
}

</p>
