# Hybridia — App Privacy & Support Pages

One GitHub Pages site for the privacy policies and support pages of all Hybridia iOS apps, replacing the per-app repos.

## Structure

```
index.html                      → hub listing all apps
assets/style.css                → shared stylesheet
<app-slug>/index.html           → per-app privacy & support page
```

## Deploy

1. Create a repo (e.g. `apps`) under the Hybridia account and push these files to `main`.
2. Repo → **Settings → Pages** → Source: *Deploy from a branch* → `main` / `/ (root)` → Save.
3. Site goes live at `https://hybridia.github.io/apps/`.

> Tip: name the repo `Hybridia.github.io` instead and the URLs drop the `/apps` prefix
> (e.g. `https://hybridia.github.io/taprush/`).

## Update App Store Connect URLs

| App | Old Pages repo | New URL (repo named `apps`) |
|---|---|---|
| AltKey Codes | `AltKey-Codes` | `https://hybridia.github.io/apps/altkey-codes/` |
| Comix Reader | `Comix-Reader` | `https://hybridia.github.io/apps/comix-reader/` |
| Coverlog | `coverlog` | `https://hybridia.github.io/apps/coverlog/` |
| Garbage Pickup Calendar | `Garbage-Pickup-Calendar-Privacy-Policy` | `https://hybridia.github.io/apps/garbage-pickup-calendar/` |
| Lessenrooster | `lessenrooster` | `https://hybridia.github.io/apps/lessenrooster/` |
| MediPlanner / Pro | `MediPlanner` | `https://hybridia.github.io/apps/mediplanner/` |
| MiVaulty | `MiVaulty` | `https://hybridia.github.io/apps/mivaulty/` |
| Morse Beacon | `Morse-beacon` | `https://hybridia.github.io/apps/morse-beacon/` |
| Remindy | `Remindy` | `https://hybridia.github.io/apps/remindy/` |
| SplitXpense | `SplitXpense` | `https://hybridia.github.io/apps/splitxpense/` |
| TapRush | `TapRush` | `https://hybridia.github.io/apps/taprush/` |
| WiFizer | `WiFizer` | `https://hybridia.github.io/apps/wifizer/` |

⚠️ Update the **Privacy Policy URL** (and Support URL) for each app in App Store Connect
**before** disabling Pages on the old repos, so reviewers never hit a dead link.
Keep the old repos' Pages enabled for a week or two of overlap, then archive them.
