# TileBlitz Privacy Policy

**Effective:** 2026-05-11
**Last updated:** 2026-05-11

TileBlitz is a single-player puzzle game published by **OROT** (referred to as "we", "us", "our"). This policy explains exactly what data the app collects, why, and what rights you have over it.

Contact: **orotgames@gmail.com**

---

## 1. Summary (plain language)

- We do **not** ask for your name, email, address, phone, photos, contacts, or precise location.
- The only data that leaves your device is an anonymous identifier, your country (just the 2-letter country code), an auto-generated leaderboard nickname, and your score — and only when you submit a score to the online leaderboard.
- Advertising is served by Google AdMob. Google may collect device-level data per their own policy.
- For players in the EEA / UK / Switzerland, we show a Google consent dialog before any personalized advertising.

---

## 2. What we collect

### 2.1 Data we collect (stored in our Firebase backend)

| Data | Purpose | When collected |
|---|---|---|
| **Anonymous Firebase Auth UID** (a random ID, not tied to you) | Prevent score spoofing on the leaderboard | First time the leaderboard is used |
| **Country code** (2-letter, e.g. `KR`, `US`) | Country-tab leaderboard ranking | When you submit a score |
| **Auto-generated display name** (e.g. "Bold Tiger 7" — not user-typed) | Shown next to your leaderboard rank | When you submit a score |
| **Score + pieces placed** | Leaderboard ranking | When you submit a score |
| **Server logs** (timestamp, IP address) | Routine diagnostics + abuse prevention by Google Cloud Functions | Each leaderboard request |

We do **not** collect: real name, email, phone, contacts, photos, microphone, camera, precise location, browsing history, files, or any user-typed text. The leaderboard nickname is generated automatically by the app — players never type it.

### 2.2 Data stored only on your device (never transmitted)

- High score
- Audio / haptic preferences
- Games-played counter (used to time the rate-the-app prompt)
- Whether you tapped "Don't ask again" on the rate prompt

This data lives in standard Android app storage and is removed when you uninstall the app.

### 2.3 Data collected by third parties

When ads are shown, **Google AdMob** collects standard advertising data per Google's policy:

- Android Advertising ID
- IP address
- App / ad interactions

Google AdMob privacy: <https://policies.google.com/technologies/partner-sites>

Our **Firebase** backend (Google) processes the data in section 2.1 per Google's privacy policy:

- <https://firebase.google.com/support/privacy>

---

## 3. How we use the data

- Leaderboard data (UID, country, nickname, score) is used **only** to display rankings.
- We do **not** use any data for profiling, marketing, advertising targeting, or sale to third parties.
- Server logs are used only to keep the service running and stop abuse.

---

## 4. Advertising

We show **rewarded ads** through Google AdMob — you can choose to watch one in exchange for an in-game benefit. Ads are optional; the core game is fully playable without them.

For users in regions that require it (EEA, UK, Switzerland), we show a Google **Consent Management Platform** dialog when you first launch the app. Your choices apply going forward.

If you do not consent, you will see **non-personalized ads** (or no ads at all, depending on availability).

---

## 5. Children

TileBlitz is rated for general audiences. We do not knowingly collect personal information from children under 13 (under 16 in the EEA). If you believe a child has provided data, contact us and we will delete it.

---

## 6. Your rights

### Everyone
- You can stop using the app and uninstall it at any time. Local data is removed on uninstall.
- You can request your leaderboard entry be deleted by emailing **orotgames@gmail.com** — we will delete it within 30 days.

### EEA / UK / Switzerland users
You have additional rights under GDPR / UK-GDPR:
- **Access** — request a copy of your leaderboard entry
- **Erasure** — request deletion
- **Object** to processing relying on legitimate interest

To exercise these rights, email **orotgames@gmail.com**.

### California residents
You have rights under CCPA:
- Right to know what categories of personal information we collect
- Right to delete
- Right to non-discrimination

We do **not** sell personal information.

---

## 7. Data retention

- Leaderboard entries persist as long as the leaderboard exists. If you want yours deleted, contact us.
- Server logs are retained per Google Cloud Functions defaults (typically 30 days).

---

## 8. Security

All network traffic between the app and our backend uses HTTPS (TLS). Firebase access is gated by per-user tokens and Firestore Security Rules.

We are an indie studio — no security is perfect. If you discover an issue, please report it to **orotgames@gmail.com**.

---

## 9. Changes to this policy

If we change this policy materially, we will update the "Last updated" date above and announce the change inside the app or on the store listing.

---

## 10. Contact

**OROT**
TileBlitz support: **orotgames@gmail.com**
