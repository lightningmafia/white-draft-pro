# White Draft Pro — App Store ship list

Do these in order. Do not submit until the Pages URLs load in a private window.

## 1. Public URLs

1. GitHub → lightningmafia/white-draft-pro → Settings → Pages.
2. Source: Deploy from a branch.
3. Branch: `main`. Folder: `/docs`.
4. Save. Wait until https://lightningmafia.github.io/white-draft-pro/ loads.
5. Check:
   - https://lightningmafia.github.io/white-draft-pro/
   - https://lightningmafia.github.io/white-draft-pro/privacy.html
   - https://lightningmafia.github.io/white-draft-pro/support.html

Paste those three into App Store Connect from `STORE.txt`.

## 2. App Store Connect metadata

Paste `STORE.txt` fields. Category Productivity. Age 4+. Privacy nutrition: Data Not Collected. Tracking off.

Price: $14.99 one-time unless you already decided otherwise. Do not ship free+IAP for v1.

## 3. Binary

- Bundle ID `com.whitedraftpro.app`
- macOS 15+
- App Sandbox on
- Hardened runtime on
- No outgoing network entitlement
- `PrivacyInfo.xcprivacy` present
- In-app link to the privacy policy (Help menu or About)
- 1024×1024 icon
- Copyright year 2026, seller name matching the developer account

## 4. Screenshots

Five Mac shots from the script in `STORE.txt`. No competitor names on the images.

## 5. Do not claim

- “Better than Word” in the listing
- `.docx` unless the submitted build opens and saves it
- Cloud, accounts, or collaboration
- The name Drafts (different app)

## 6. After submit

Watch App Review for Privacy Policy URL and Support URL. If they bounce the markdown GitHub links, these HTML Pages URLs are the fix.
