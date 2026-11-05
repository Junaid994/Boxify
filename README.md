# Boxify

A secure, lightweight file uploading service that automatically destroys files and revokes access links based on custom token expiry limits.

Sharing sensitive files securely shouldn't require complex configurations or heavy cloud infrastructure. Boxify is a developer-first utility that manages file uploads by sealing them inside time-locked "boxes." Each upload is bound to a cryptographic token that enforces strict lifetime limits, download caps, and automated file system purging the exact millisecond the token expires.
