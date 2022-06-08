# issue 3720
### GitHub link
- https://github.com/firebase/firebase-android-sdk/issues/3720
### Prerequisite
- Run the app on a Windows machine
- Add google-services.json
- Enable App Distribution in Firebase Console
### Steps to reproduce
- create a `release-notes.txt`
- go to your app `build.gradle`, add the path of your `release-notes.txt` to the `releaseNotesFile` parameter at line 26. (see reference on line 27) 
### Summary
-  Running the app will immediately show the error that the path is incorrectly processed.
