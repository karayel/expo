---
'@expo/cli': patch
---

Request a development code signing certificate only when the credentials used for the request have the `PUBLISH` permission on the account that owns the project. A scoped access token or session without `PUBLISH` no longer requests a certificate.
