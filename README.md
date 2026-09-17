# Super-Liquid-Soccer

## Firebase Hosting

This repository is configured as a static Firebase Hosting site. The two games are available at:

- `/super-liquid-soccer/`
- `/fear-response/`

Install the Firebase CLI, sign in, select the Firebase project, and deploy from the repository root:

```sh
npm install -g firebase-tools
firebase login
firebase use --add
firebase deploy --only hosting
```

`firebase use --add` writes the project-specific `.firebaserc` file locally. Keep that file out of shared source control if different environments deploy this repository.