# automatedinterviewtool

This code implements a simple Kivy-based GUI application for recording and submitting video interviews. 
The app consists of three screens: a registration screen, a video recording screen, and a summary screen.

The registration screen allows users to input their name, email, and date of birth, and upload their ID proof. 
Upon registration, a new User instance is created and registered.

The video recording screen allows users to start and stop recording a video interview and submit the recorded video.

The summary screen displays a summary of the recorded interview and allows users to go back to the registration screen.

The app is built using the KivyMD framework and ScreenManager for screen navigation. 
It also includes a file chooser dialog for selecting ID proof and uses shutil for copying files.
