1. Test post man
   basic_auth.js
Trường hợp: app.get("/secure"
   http://localhost:3000/secure
   Username: admin
   Password: 12345
   KQ: You have accessed a protected resource 🎉

   Username: admin
   Password: 1234
   KQ: Access denied.
   
   Username: adm
   Password: 12345
   KQ: Access denied.

   Username: admi
   Password: 1234
   KQ: Access denied.

Trường hợp: app.get("/"
  http://localhost:3000/
  Username: admin
   Password: 12345
   KQ: Welcome! Visit first public resource.

   Username: admin
   Password: 1234
   KQ: Welcome! Visit first public resource.
   
   Username: adm
   Password: 12345
   KQ: Welcome! Visit first public resource.

   Username: admi
   Password: 1234
   KQ: Welcome! Visit first public resource.

Trường hợp: app.get("/public"
   http://localhost:3000/
   Username: admin
   Password: 12345
   KQ: Welcome! Visit second public resource.

   Username: admin
   Password: 1234
   KQ: Welcome! Visit second public resource.
   
   Username: adm
   Password: 12345
   KQ: Welcome! Visit second public resource.

   Username: admi
   Password: 1234
   KQ: Welcome! Visit second public resource.

. Test post man
   cookie_auth.js
  Trường hợp: app.post("/login"
   http://localhost:3001/login
   
