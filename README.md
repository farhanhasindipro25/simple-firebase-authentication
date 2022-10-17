# Getting started with Firebase Authentication

# INITIAL SETUP

1. Visit 'console.firebase.google.com'.
2. Click 'Go To Console' on the top right corner and create a new project.
3. Visit docs. (Build > Authentication > Web > Get Started).
4. Register web app app. (Firebase project home > Web > Give name according to project name and register)
5. Install SDK and initialize firebase.
```npm install firebase```
### 6. DANGEROUS
- Get firebase config and put in 'firebase.init.js' file.
7. Export app from the 'firebase.init.js' file.

# SETTING UP THE AUTHENTICATION PROVIDER

8. Create auth using getAuth from firebase by using app from 'firebase.init.js'.
9. Create a google auth provider.
10. Go to Firebase Home Page > Build > Authentication > Sign in method.
11. Enable Google Sign in method.
12. Create a button for google sign in method with a click handler.
13. Inside the event handler call signInWithPopUp with auth, provider.
14. After signInWithPopUp .then result, error.

### Adding a new sign-in method

1. Enable the sign in method from firebase.
2. Create Github, Twitter, Facebook, etc. app.
3. Get ClientID and Client Secret.