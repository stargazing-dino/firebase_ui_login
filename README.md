# firebase_ui_login

To recreate the firebase UI login issue.

## Setup

(This was run and tested on ios device)

1. Create a new project in Firebase.
2. Run `flutterfire configure` to configure your project. Select the firebase project you created in step 1. Run with defaults.
3. Enable Google auth in the Firebase Console
4. Follow steps from https://pub.dev/packages/google_sign_in to get the google sign in plugin (including adding GoogleService-Info.plist).
5. Add your own clientId to `main.dart`
6. Run the app.
7. Sign in with google then cancel the sign in. "An unknown error occurred" will display.
8. Similar issue happens when you create have an account and attempt again to sign in.

