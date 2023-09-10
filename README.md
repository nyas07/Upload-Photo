# Upload-Photo

#### Video Demo:  https://www.youtube.com/watch?v=kjS4hO3aeP0&t=2s

#### Description:

A social media application where users can share photos and comments, built using Swift and Firebase.

This application was developed as a CS50 final project, inspired by the social media applications we use in our daily lives. 

I wanted to make a project like this to expand my knowledge of IOS development.



Technologies used:

* Xcode
  
* Swift
  
* Firebase Authentication
  
* Firebase Storage
  
* Firebase Firestore
  
* Other small libraries or packages

# How the App Works ? 

The idea is simple. The user must be signed up and then can access with log in button.During registration you need to enter these fields:

* E-mail
  
* Password

To describe the application, when it is first opened, there are buttons for creating an account and logging in. Users can create new accounts if they wish, but they cannot create another one on top of their existing account; an error message is displayed when attempted. After a successful registration process, users are prompted to log in, and similarly, if an incorrect login credential is entered or any other issue arises, the relevant error message is conveyed to the user.

# What's inside ?

Once logged in successfully, users can use the 'Upload' tab to share photos from their gallery along with comments, which will appear in the 'Feed' section.

In the 'Settings' tab, users have the option to log out. The application operates based on logins and logouts, meaning that if the user does not log out, it will continue from where it left off when reopened. If a user wants to log in with a different account or simply see the 'log in' screen, they must log out of their current account.

## Database

As I mentioned before i used firebase systems for database side.

# How to launch application
First of all you need a Mac system and Xcode required.

1. You need to install 'Podfile' and it must contains pods for Firebase and packages:

* pod 'Firebase/Auth'

* pod 'Firebase/Firestore'

* pod 'Firebase/Storage'

* pod 'SDWebImage', '~> 5.0'

You can open 'Podfile' with text editor etc. and then this podfiles must be in there.
Run Terminal, make cd and find the path where the 'Podfile' and then type 'pod install'.This will start the installation.

2.After the installation run 'uploadPhoto.xcworkspace' file. Project will be opened with Xcode and you can start button in the upper left side.

3.You are ready to go!

# Last Notes and hopefully future updates

* I want to update this app with UI/UX for better user-friendly interface.

* I want to add chatting tab.

* In feed there is no delete button for sharings.It will change.









