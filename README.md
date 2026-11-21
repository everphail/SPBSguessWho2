SPBS Staff Guess Who — traditional online multiplayer

1. Firebase Authentication: enable Anonymous.
2. Firebase Realtime Database: paste database.rules.json into Rules and Publish.
3. Upload the contents of this folder to a public GitHub Pages repository (index.html and firebase-config.js at the root, assets/ as a folder).
4. Open the site, create a room, share the invitation link.

Security: players can read only their own secret. The opponent confirms a final guess, so this is a trust-based social game (not cheat-proof). Room membership is enforced by Realtime Database rules. Photos in public GitHub Pages are public; only publish with permission from pictured people. Do not use the earlier permissive database rules.
