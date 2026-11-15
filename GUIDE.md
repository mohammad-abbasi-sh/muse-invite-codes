# How to Sign Up for Muse from Iran — Waitlist, Region Lock & What Actually Works

> **Short version:** Meta Muse is officially available only in the **United
> States and Canada**. No invite code skips the waitlist or the region lock.
> The waitlist is per-country, not a queue — and Meta has announced no dates
> for any other country. This guide states the real situation; it promises
> no shortcut.

نسخهٔ فارسی: [GUIDE-fa.md](GUIDE-fa.md)

## 1. The current situation

- Muse launched in the US on September 8, 2026 and in Canada on
  September 29, 2026.
- Meta has announced no third country and no dates for a global rollout.
- Signing in at muse.ai from Iran shows either "not available in your
  country" or the waitlist screen.

## 2. How the waitlist works

- The waitlist is **per-country, not a queue**. There is no position and no
  wait time, and joining it does not unlock access early.
- After joining, the screen still says Muse "isn't available in your
  country or region yet."
- Meta says it will let you know when Muse becomes available to you — with
  no date attached.
- Many people stay on the waitlist for months without activation. That
  means their country hasn't launched yet, not that their turn hasn't come.

## 3. Does an invite code skip the waitlist?

**No.** An invite code only grants tokens **after the account is active**:

- Redemption happens inside account settings (mobile: Settings → Redeem
  token; web: Settings → General → Usage → Redeem invite code) — so the
  account must be active first.
- A code does not bypass the region lock and does not take you off the
  waitlist.
- Each account can redeem only once, and each code works up to 30 times
  (per the [muse-protocol](https://github.com/duwqijlk/muse-protocol)
  research).

The invite code on this page — **ZV55CE** — is for people whose accounts
are already active and want free tokens, not for skipping the waitlist.

## 4. How the region lock is decided

According to the open-source research project
[muse-protocol](https://github.com/duwqijlk/muse-protocol), the server
returns a geo status during session bootstrap:

- If `resolvedDestination` is `waitlist` or `isGeoGated` is `true`, the
  region is restricted: registration completes and the account is kept, but
  access is not activated.
- This is a server-side check, not a simple IP filter — which is why
  workarounds give inconsistent results for different people.

## 5. What people report (no guarantees)

These are scattered user and guide reports, not verified methods. I have
not tested any of them from Iran, and none is guaranteed:

- **US VPN for the whole signup:** some sources say the entire registration
  must run from a US connection. Other sources say the lock is tied to the
  **Meta account region and app-store region**, not the IP — in which case a
  VPN does not open the door. The two claims contradict each other.
- **US cloud desktop:** running the whole signup inside a cloud computer
  located in a supported region. Same uncertainty as above.
- **Japan node:** the muse-protocol notes mention that with a JP node, no
  card binding is required. That is one observation recorded in that
  project.

**Warning:** using a VPN to sign up from a country where Muse hasn't
launched may break Meta's terms of service, and Meta can limit or close
accounts. Consider any workaround with that risk in mind.

## 6. The official path (the only reliable one)

1. Sign in at muse.ai with a Meta account.
2. If the waitlist screen appears, tap **Join waitlist**.
3. Wait for the launch in your country. Meta says it will notify you.

One reported tip: some sources recommend signing up with an email that is
not linked to your Facebook or Instagram account, since linking to Meta
accounts can tie the signup to your real region.

## 7. Scam warning

- Nobody can sell "early access." Anyone charging money to activate your
  account cannot change your account's region — treat them as a scam risk.
- Invite codes are free. Don't pay for one.
- Any page giving an exact launch date for Iran or any other country made
  that date up; Meta has announced none.

## 8. Sources

- Protocol research project: https://github.com/duwqijlk/muse-protocol
- Muse waitlist page: https://metamuseai.site/muse/waitlist/
- Signup & waitlist guide: https://upgpts.com/en/tutorials/muse/how-to-use-muse-ai
- Country-availability check: https://www.toolvena.com/en/muse-ai-availability-checker/
- "Bypassing the waitlist" (with a ToS warning): https://frostrank.com/muse-ai-waitlist-bypass

---

Built by [Mohammad Abbasi](https://github.com/mohammad-abbasi-sh) — [Almanibama](https://almanibama.ir) · [mabbasi.ir](https://mabbasi.ir)
