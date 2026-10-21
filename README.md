# keystone-updates

Release files for Keystone dev builds. GitHub Actions in the main Keystone repo publishes them; nobody edits them by hand.

- `dev-b{N}` releases: content packs (`keystone-dev-b{N}.pck`) and `manifest-dev.json`. The newest one is "latest", so dev APKs read `releases/latest/download/manifest-dev.json`.
- `apk-dev-b{N}` prereleases: dev APKs to install on a phone.

Don't edit, re-upload or rename release files: phones check every file's SHA-256 against the signed manifest.
