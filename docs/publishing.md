# Publishing checklist

## 1. Repository

- **Name:** `nova`
- **Description:** Steam idle, achievement, and library manager for Windows - .NET 8, no injectors.
- **Topics:** `steam idle steam-idler achievements steam-tool card-farming dotnet`
- **Visibility:** public

## 2. First push

```bash
git init
git add .
git commit -m "Nova 1.9.2 - initial release"
git branch -M main
git remote add origin https://github.com/<you>/nova.git
git push -u origin main
```

## 3. Release

1. Draft a release tagged `v1.9.2`.
2. Title: `Nova 1.9.2`.
3. Body: copy the top entry from `CHANGELOG.md`.
4. Attach the build archive.
5. Publish.

## 4. Settings

| Setting | Value |
| --- | --- |
| Website | the download folder |
| Discussions | enabled |
| Issues | enabled |
| Social preview | export `assets/hero.svg` at 1280x640 |

## 5. First week

- [ ] Release + pin
- [ ] Push a small follow-up commit
- [ ] Reply to every issue within 24 h
- [ ] Publish one screenshot or clip
- [ ] Ship 1.9.2 patch with a visible fix

Keep a 2-3 day commit cadence. Consistency beats volume.