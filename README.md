1. Test post man
   basic_auth.js
Trường hợp: app.get("/secure"
   http://localhost:3000/secure
   Username: admin
   Password: 12345
   KQ: You have accessed a protected resource 🎉
<img width="2584" height="1712" alt="image" src="https://github.com/user-attachments/assets/2a060415-c7cb-49cb-b5f2-315467ea5d13" />


   Username: admin
   Password: 1234
   KQ: Access denied.
   
   
   Username: adm
   Password: 12345
   KQ: Access denied.

   Username: admi
   Password: 1234
   KQ: Access denied.

   <img width="2568" height="1712" alt="image" src="https://github.com/user-attachments/assets/4f44a6a0-7e1b-4df4-965d-cf95dba39f45" />


Trường hợp: app.get("/"
  http://localhost:3000/
  Username: admin
   Password: 12345
   KQ: Welcome! Visit first public resource.
<img width="2565" height="1709" alt="image" src="https://github.com/user-attachments/assets/be9d952a-17d1-4df0-bc22-2b0d9cb2b95c" />

   

   Username: admin
   Password: 1234
   KQ: Welcome! Visit first public resource.
   
   Username: adm
   Password: 12345
   KQ: Welcome! Visit first public resource.

   Username: admi
   Password: 1234
   KQ: Welcome! Visit first public resource.

<img width="2582" height="1709" alt="image" src="https://github.com/user-attachments/assets/224b65f4-408f-4abd-aa59-38d3e75b1c42" />


Trường hợp: app.get("/public"
   http://localhost:3000/
   Username: admin
   Password: 12345
   KQ: Welcome! Visit second public resource.

<img width="2575" height="1717" alt="image" src="https://github.com/user-attachments/assets/3c9f9161-74a0-4700-b957-2e5b510d766c" />



   Username: admin
   Password: 1234
   KQ: Welcome! Visit second public resource.
   
   Username: adm
   Password: 12345
   KQ: Welcome! Visit second public resource.

   Username: admi
   Password: 1234
   KQ: Welcome! Visit second public resource.

<img width="2581" height="1716" alt="image" src="https://github.com/user-attachments/assets/55b9b6c5-457a-42d1-be73-86942a7b9485" />


. Test post man
   cookie_auth.js
  Trường hợp: app.post("/login"
   http://localhost:3001/login
   {
  "username": "admin",
  "password": "12345"
   }
   KQ: Logged in!
<img width="2586" height="1711" alt="image" src="https://github.com/user-attachments/assets/84a2ce14-ca2f-4608-8961-11498905bcb9" />

   {
  "username": "admin",
  "password": "123"
   }

   {
  "username": "adm",
  "password": "12345"
   }

   {
  "username": "adm",
  "password": "123"
   }
   
   KQ:
   <img width="2582" height="1713" alt="image" src="https://github.com/user-attachments/assets/0fc70abc-5852-4b5b-8af3-7753508b68ce" />

   

   


