# file-functions
This is project for users to login/create an account to share(upload/download) files on a web application
## homepage
When the user runs the server the homepage is loaded. It displays all the available posts uploaded by many
users and those posts can only be accessed(downloaded/viewed) when the user has logged in.
The homepage contains the function:
1. Login button (for users to login)
2. Signup button (for new users to register)
3. Search bar (for users to search for specific post or to get the number of users and posts)

## Loginpage
when the user selects the login button from homepage he is redirected to login page.
The login page contains:
1. Username (entered by user)
2. Password (entered by user)
3. Submit button(checks for authentication redirects to the next page if credentials match else displays error message)

## User Profile button
On selecting the user profile the user is given options of Upload, Home and Profile.By default Home would be selected when the user is logged in.

## Upload option
On selecting the upload option from user profile the user is redirected to upload page where the user uploads his files/posts.
The upload page contains:
1. Choose button (user can browse and select the file to be uploaded)
2. Name filed (user needs to enter the name of the file which is displayed to other users)
3. Descrption filed (gives the description of file)
4. Upload button (for user to upload)

## homes option
The home screen consits of :
1. All the posts of all the users which the logged in user can downoad and view
2. Logout button (for user to logout when he is done)

## profile option
The profile screen consists of :
1. All the posts uploaded by the logged in user
2. Delete option (so the authenticated user can remove his posts)
3. Download and view buttons
