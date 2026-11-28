# eclectica
#### {...}
"""
https://envjacobs.github.io/eclectica/
"""

## Firebase rules

The app uses Firestore rules for account data, public decks, and administrator-only shared format changes. Custom printing images are stored in Firebase Storage under the signed-in user's account. Deploy both rule sets with:

```powershell
firebase deploy --only firestore:rules,storage --project eclectica-676ae
```
