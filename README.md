# Website_User_Authentication

This is a simple website based authentication, providing access to only trusted users with proper credentials.

This app provides following operations:-

1. Sign-In

2. Register

3. Sign-Out

4. Password Encryption using `bcryptjs`.

5. Uploading profile picture using `multer`.

The Sign-In and Sign-Out authenticatons were created with the help of `passportjs`.

`mongodb` was used for storing the user-data such as `e-mail`,`password`,`username`,`profile-picture`.

The `flash` module was used for giving error-success messages incurred to the system during the login or logout process.

For the usual-styling of the webpage and `nav-bar` designs `BootStrap 3.3.6` was used.

The following changes are needed to be made for the betterment of this project:-

1. Show the profile-page of the user.

2. Display the profile-picture on the profile-page, along with other details such as phone no., address,etc.

3. The min.length of characters for passowrd/username as well compulsory use of special characters in password.

4. Comparing the strength of password and asking the user to enter a string one of found weak.

5. Making the website product-based/content-sharing-based and hosting it online.