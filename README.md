# Android-Note-Application
- An android note application following the MVP architecture with repository pattern and using the Firebase framework.


## Description
- The application saves notes under a personal email account to keep it safe and be retrieved in any other android mobile device.
## Features
- This applications uses the Firebase authentication and real time database. This allows users to store their notes under their email account and allows them to see all their notes in any android device the user decides to log in. It also has the ability to save notes if the user loses internet connection and once the user reconnects to the internet, it updates the realtime database with all the new notes.
## Prerequisities
- Internet is required in order to log in but not fully necessary once the user has already logged in.
## Functionality
- User can register with their email account and unique password, which is used to access the application.
- User has the ability to recover their account's password if forgotten.
- User can create notes of their own by pressing on the circular + floating button where either a title or a description is required to be filled in order to be shown in the recyclerview.
- User can update notes by simply pressing on the note they wish to update. The user will be presented with a new screen containing the title and the description of the note and by pressing the check mark, the note will be updated.
- User can delete notes by either swiping left or right on the desired note they wish to remove.

