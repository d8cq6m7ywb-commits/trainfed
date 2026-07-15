# TrainFed™ — trademark use / first-use evidence trail

**Mark:** TrainFed™ (unregistered; ™ used, never ®)
**Goods/services:** training-aware nutrition / fueling software for endurance athletes
**Domain:** trainfed.co (registrar: name.com) — `.com` was registered by a third party ~1 hour prior; no affiliation, no claim asserted against it.
**Compiled:** 2026-07-15 (see git history of this file for the authoritative timestamp).

> Purpose: document genuine advertising of the service in commerce (a public,
> live, branded site describing the offering + a private-beta waitlist), as a
> supporting record. This is evidence of use, not a registration. The stronger
> protection remains a filed Intent-to-Use (§1(b)) application — see "Next steps".

---

## 1. Deployment commit(s)  ✅ captured
Source repo: `github.com/d8cq6m7ywb-commits/trainfed` (public), branch `main`.

| Commit | Date (author, ISO) | Message |
|--------|--------------------|---------|
| `50270ea` | 2026-07-14 19:17:00 -0700 | TrainFed holding page — trainfed.co (initial) |
| `6fd587a` | 2026-07-14 20:34:53 -0700 | Add CNAME for GitHub Pages custom domain (trainfed.co) |

(EVIDENCE.md itself adds a third dated commit.)

## 2. Server / deployment logs  ✅ link recorded
GitHub Pages "pages build and deployment" workflow:
`https://github.com/d8cq6m7ywb-commits/trainfed/actions/runs/29386974861`
Deployment environment: `github-pages`. First successful deploy: 2026-07-15 (UTC).
→ *Manual:* open that run and "Download logs" (gear menu) to keep an offline copy.

## 3. SSL certificate  ✅ captured
Issuer: Let's Encrypt (C=US, O=Let's Encrypt, CN=YR1)
Subject: CN=trainfed.co
notBefore: **Jul 15 02:38:33 2026 GMT**
notAfter:  Oct 13 02:38:32 2026 GMT
(Cert auto-renews ~monthly; the notBefore above is the first issuance date and
the meaningful "HTTPS live since" marker.)

## 4. Live-state proof  ✅ captured
`GET https://trainfed.co/` → `HTTP/2 200`, `server: GitHub.com`,
response `date: Wed, 15 Jul 2026 03:45:31 GMT`. `http://` 301-redirects to `https://`.

## 5. DNS records  ✅ captured
- Apex `trainfed.co` A records → GitHub Pages: 185.199.108.153 / .109 / .110 / .111
- Ownership verification TXT `_github-pages-challenge-d8cq6m7ywb-commits.trainfed.co`
  = `11615347bb50b1cfe54358e048c848` (GitHub domain verification passed).

## 6. Archived snapshot (third-party timestamp)  ✅ captured
Wayback Machine: **`https://web.archive.org/web/20260715034619/https://trainfed.co/`**
(snapshot taken 2026-07-15 03:46:19 UTC). Independent, tamper-evident capture of
the live branded page + service description + beta waitlist.

---

## Still to capture (manual — one-time)
- [ ] **Domain purchase receipt** — download the name.com invoice for `trainfed.co`
      (Account → Order History) and save a PDF alongside this file / in cloud backup.
- [ ] **Offline copy of the GitHub Actions deploy log** (link in §2).
- [ ] **Dated screenshot** — optional; the Wayback snapshot (§6) already serves as a
      third-party-dated visual. A local full-page PDF/screenshot is a nice belt-and-braces.
- [ ] **Defensive registrations** — consider trainfed.app / .io / .fit before someone
      repeats the `.com` grab.

## Next steps (priority order)
1. **File an Intent-to-Use (§1(b)) application** in the relevant classes (likely
   Class 9 software + Class 42 SaaS, possibly Class 44 nutrition guidance) via a
   trademark attorney. This establishes nationwide priority as of the filing date —
   far stronger than this evidence file alone. Decide jurisdictions: USPTO (US),
   EUIPO (EU), UKIPO, and note **China (CNIPA) is first-to-file** and squatter-prone.
2. **Run the genuine private beta** (the concierge pilot in the product plan) — a
   handful of invited athletes actually using the service is the strongest possible
   "use in commerce" evidence *and* validates whether the daily fueling loop works.
3. Build under **trainfed.co** for now; watch what appears on the `.com`; don't let
   the domain situation rush the product. Product validation > name anxiety.

*Not legal advice — for the actual filing and class selection, use a trademark attorney.*
