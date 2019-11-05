# Rest-api
Rest api til user management

Get all users:
http://localhost/crud/api.php
Method Get
Returns json data with: id,username,email,password

Get single user:
Method get
Parameteres: "ID" value integer (user id from data)
Returns json data with: id,username,email,password

Make new user:
Method post
Body: jsonformateret: username,email,password
returns json formateret errorcode

Update user
Method put
Body json foramtteret: 

Koden vil blive brugt i en central fil, der inkluderer databasen

http://localhost/crud/api.php entry pointet er en speciel api fil, der er forbundet til databasen
Der vil være kernefunktioner:
Get, post, put og delete

Get vil kunne finde alle brugere eller en brugere hvis der sendes id med
Get uden id echoer alle rows i databasen
get med id tjekker for dette id og udskriver den bestemte bruger

Post skal bruge brugernavn, kodeord og email
tjekekr for ekesisterende brugere i databasen
og indskriver hvis den ikke eksisterer

Delete vil slette en bruger ud fra ID
delete sletter ud fra id

put wil bruge update funktionen til at insætte nye brugerdata ud fra id


