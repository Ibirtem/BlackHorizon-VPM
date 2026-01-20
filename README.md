# BlackHorizon Systems (VPM Repository)

Official VRChat Package Manager listing for BlackHorizon tools and systems.

**[🌐 Visit the Repository Website](https://ibirtem.github.io/BlackHorizon-VPM/)** to add packages to VCC.

---

## 🛠 Maintenance (For Developers and Me)

### How to add a new package

To add a new repository to this listing, edit `vpm.json`:

```json
"packages": {
  "com.blackhorizon.newpackage": {
    "url": "https://github.com/Ibirtem/New-Package-Repo"
  }
}
```

The GitHub Action will automatically:

1. Scan the linked repository.
2. Find the latest releases.
3. Update `index.json` and the website.

### Updates

The listing updates automatically:

- Every 4 hours via Schedule.
- On every push to the `main` branch.
- Can be triggered manually via [Actions tab](../../actions).
