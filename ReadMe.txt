#Image Hoster

Changed the username and password in the stub file in the ‘src/main/java/imageHoster/config/JpaConfig.java’ file and ‘src/main/resources/META-INF/persistence.xml’ file according to your PostgreSQL username and password. 

Part A: Fixing Issues
If you upload an image with the same exact title as of a previously uploaded image, it will get uploaded.
But then, if you try to navigate to one of the images with the same title, the image uploader will display an error.
Please fix this issue, so that the application should not show an error and take you to respective image’s page.

After logging into the application, it is possible to edit/delete the image which is posted by some other user. This is a bug in the application. Now, fix this bug in the application, such that only the owner of the image can edit/delete the image.

Part B: Implement a new feature
1.  Password Strength
Up till now, there is no check on the strength of the password entered by the user at the time of registration. Let us try to keep a check on the strength of the password entered by the user at the time of registration. You need to implement a feature wherein the password entered by the user must contain at least 1 alphabet (a-z or A-Z), 1 number (0-9) and 1 special character (any character other than a-z, A-Z and 0-9). The user must only be registered if the password contains 1 alphabet, 1 number, and 1 special character. And after successful registration, you must directly return 'users/login.html' file. Otherwise, the user must not be registered and again return the ‘users/registration.html’ file. You also need to display a message ‘Password must contain at least 1 alphabet, 1 number & 1 special character’. Carefully add all the required attributes in the Model type object needed by ‘users/registration.html’ file.

2.  Comments
Now, implement a feature wherein a user can add a comment to any image in the application after he is logged in the application, and, to implement this feature, you’ll have to add the following to the image uploader application.