# firebase-example:
1- Download or clone the repository by using the command "git clone project directory" and open it to VS code editor
2- Go to Firebase.google.com
     Add project --> Enter name of project --> Next --> Add project
  
 3- Follow the instruction and click the web icon.
 ![image](https://user-images.githubusercontent.com/88589230/170124112-ed9af3ac-ef4c-47f6-aaec-44b8783b9789.png)

4- Register app name --> Go to Add Firebase SDk and update "firebaseConfig"  value in index.html

     var firebaseConfig = {
        apiKey: "",
    authDomain: "",
    projectId: "",
    storageBucket: "",  
    messagingSenderId: "",
    appId: ""
      };
      
5- Go to Firebase Dashboard, Click on Authentication --> Click "Get Started"
6- Inside "Additional providers", click "Google". Enable the button and select the "project support email" and Save it. 

7- Go back to VS code editor and select View --> Extensions option and find "Live Server" and install it
8- After installation, Right click on "index.html" and choose option "Open with live server"
9- A browser will open showing front-end of web app with Google Authentication button.
10- Here you can test your Firebase Google Authentication service.

11- Just to make sure that authentication is successful, go to Firebase,

     On Dashboard --> Click Authentication --> Check "Users" Tab and you can find your authenticated user.
