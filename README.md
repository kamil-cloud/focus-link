# Focus — permanent link

This tiny site gives Focus a link that never changes: https://kamil-cloud.github.io/focus-link/

- `?join=CODE` sends a student to the invite page of class `CODE`.
- `?teach=1` sends a teacher to the sign-in page.
- `server.json` holds the current address of the Focus server. The Focus launcher
  (`Start-Focus-public-test.command` in the private `focus-app` repo) updates it automatically
  every time the server starts. Don't edit it by hand.

The Focus app also reads `directory.json` to find the server again when its address changes.
