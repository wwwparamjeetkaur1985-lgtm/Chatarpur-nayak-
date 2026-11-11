CHATARPUR NAYAK - Firebase connected web project

Included:
- index.html: Hindi-first responsive web app (works in Android Chrome)
- firebase-config.js: Firebase Web App config supplied by the owner
- firestore.rules: Firestore security rules
- storage.rules: Storage rules for candidate photos

IMPORTANT:
1. This is a web app project, not yet an installable APK and not yet deployed online.
2. Create Firestore Database and enable Firebase Storage in the Firebase console.
3. In Authentication > Sign-in method, enable Email/Password.
4. Create the owner's Admin user in Authentication, then copy that user's UID.
5. Replace PASTE_ADMIN_UID_HERE in firestore.rules with that UID before publishing rules.
6. Publish firestore.rules in Firestore > Rules, and storage.rules in Storage > Rules.
7. Host these files on Firebase Hosting or another HTTPS static host. Do not open index.html as a local file because browser module imports need a web server.
8. The Firebase web config's apiKey is a project identifier, not an admin password. Security depends on the rules above.
9. Public complaints show name (if entered), subject, details, status and date. Phone is written to a separate admin-only collection.
10. Candidate phone numbers are public after approval. Only submit a candidate's phone/photo with their permission.

No Admin UID is prefilled because it must come from the actual Firebase Authentication account.
