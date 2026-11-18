# calibergaming.github.io

The public Caliber Gaming website, served by GitHub Pages at
<https://calibergaming.github.io/>.

It is a separate repository from the app because GitHub Pages needs a paid plan
to serve from a private repo, and the app source stays private. Only these
static pages are public.

| File | Served at | Why it exists |
|---|---|---|
| `index.html` | `/` | The homepage, and the APK download |
| `privacy.html` | `/privacy.html` | Required by Google Play |
| `delete-account.html` | `/delete-account.html` | Required by Google Play: account deletion must be reachable without signing in |

The download button points at
`https://github.com/calibergaming/releases/releases/latest/download/caliber-latest.apk`,
which always resolves to the newest release in the `releases` repo. See
`RELEASING.md` in the app repo before cutting a build — the asset filename matters.

These files are copied from `docs/` in the private `caliber-gaming` repo. Edit
them there and copy across, so the two do not drift.
