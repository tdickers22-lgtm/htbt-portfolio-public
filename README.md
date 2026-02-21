# Had To Be There (HTBT) - Product + Engineering Portfolio

This is a public portfolio companion for **Had To Be There**, a hyper-local social app with iOS wrapper + web app + Firebase backend.

## What this public repo is
- Product case-study
- Architecture overview
- Selected implementation details
- Screenshots and launch notes

## What this public repo is NOT
- Full private production source code
- Secrets, keys, or deploy credentials

## Product Summary
Had To Be There is an ephemeral location-based social app for sharing short local "pings". Core loop:
- See pings on map
- React/comment/share
- Post within local boundary
- Pings expire automatically

## Stack
- Frontend: Vanilla JS + CSS + Leaflet
- Mobile wrapper: Capacitor + iOS (Xcode)
- Backend: Firebase Auth, Firestore, Storage, Cloud Functions
- Payments/auth extensions integrated as needed

## My Role
Solo builder (product + frontend + backend integration + iOS wrapper + QA iteration + release prep).

## Links
- App/Web: https://had-to-be-there-18cd7.web.app

## Screenshot Gallery
### iOS App
**Main map (signed-in)**
![iOS main map](assets/screenshots/IMG_1129.png)

**Crosshair location placement flow**
![iOS crosshair](assets/screenshots/IMG_1124.png)

**Create ping modal**
![iOS create ping modal](assets/screenshots/IMG_1125.png)

**Share modal**
![iOS share modal](assets/screenshots/IMG_1126.PNG)

### Sharing and Preview
**iMessage preview card**
![iMessage preview](assets/screenshots/IMG_1127.PNG)

**Shared ping opened on web**
![Shared ping on web](assets/screenshots/IMG_1128.jpeg)

### Web App
**Desktop web map/feed**
![Desktop web](assets/screenshots/Screenshot%202026-02-21%20at%203.05.28%E2%80%AFPM.png)

**Firebase backend/data view**
![Firebase backend](assets/screenshots/Screenshot%202026-02-21%20at%203.15.35%E2%80%AFPM.png)

**Mobile web map/feed**
![Mobile web](assets/screenshots/IMG_1126.PNG)

## Internship Positioning
- End-to-end solo build across product, frontend, backend integration, and iOS wrapper.
- Real user feedback loop with rapid iteration on UX, reliability, and shipping.
- Production-minded thinking: auth states, sharing flows, edge-case handling, and release prep.

See:
- `ARCHITECTURE.md`
- `IMPACT.md`
- `CODE-SAMPLES.md`
