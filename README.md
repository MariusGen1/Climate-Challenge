# Climate Challenge
An iOS app that aims to inspire people to take action to be more environmentally responsible through fun challenges

Compete against your friends to see who is able to complete the most environmentally responsible actions!

How it works:
There are daily and weekly challenges (for example: "use public transports" or "plant a seed") that grant you a certain amount of points based on difficulty upon completion. By creating and participating in leagues, you can compete against your friends to earn the highest possible amount of points!

## Mockups

Here are the mockups of what the final product could look like:
<img width="394" alt="Screen Shot 2022-09-21 at 7 41 59 AM" src="https://user-images.githubusercontent.com/59290941/191535077-5d33d7a4-7f00-408a-80c1-6e337294a59a.png">

## Current state of development


## Technical details
The app is build using Swift and Xcode and implements services from Google Firebase (Firestore)

Data structure: 
The project makes use of 3 important custom objects: 
- User -> Stores information about a user (such as name, id, completed tasks and leagues the user is a part of)
- Task -> Stores information about a specific task
- League -> Stores all the leagues and their members

The application uses the REMA font and vivd colors (selected using flatuicolors.com) to make for a playful UI.
