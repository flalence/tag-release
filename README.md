# Try auto-release

Try GitHub Actions to automatically create releases
when you push tags to your repository.

```bash
git tag v1.0.0
git push origin v1.0.0
```

To check that the intended tag is pointing to the HEAD, use:

```bash
git tag --points-at HEAD
```

## Check

```bash
git config user.name
git config user.email
```

Windows Credential Manager may interfere.

Open the Control Panel, search "Credential Manager", and select "Windows Credentials".
Delete any entries related to GitHub.

Then try pushing again.
