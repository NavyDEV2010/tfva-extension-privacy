# Privacy Policy — VA Record Snapshot (Chrome Extension)

**Effective date:** August 24, 2026

This policy covers the **VA Record Snapshot** Chrome extension published by Task Force VA
(Restore the Warrior Inc., d/b/a Task Force VA). It applies to the extension specifically.
The Task Force VA website and platform are covered by our main privacy policy at
https://taskforceva.ai/privacy.

**Task Force VA is privately owned and is not affiliated with, endorsed by, sponsored by,
or officially connected to the United States Department of Veterans Affairs or any other
government agency.** This extension is an independent tool that helps you access your own
records. It is not a VA product, it does not act on VA's behalf, it does not replace
VA.gov, and it does not make decisions about your claim.

---

## What the extension does

VA Record Snapshot lets you take a point-in-time copy — a "snapshot" — of your own VA
disability record and read it in a clear dashboard. You may optionally send that snapshot
to your own Task Force VA account.

**You start every capture.** The extension does not monitor your browsing, does not run on
a schedule, and holds no standing access to VA systems. It reads your record only when you
ask it to, and only after you have accepted a consent notice inside the extension that
lists exactly what will be collected. Nothing is read before you accept that notice.

## We never see your sign-in

You sign in to VA.gov yourself, directly with VA. The extension uses the session you have
already established in your own browser. It never sees, stores, or transmits your VA.gov,
Login.gov, or ID.me username, password, or security codes, and it never automates that
sign-in on your behalf.

## What the extension reads

When you take a snapshot, the extension requests your own records from VA's API at
`api.va.gov`. It reads only from these read-only endpoints:

- Your VA profile name
- Your rated disabilities and combined rating
- Your benefits claims
- Your appeals
- Your claim letter listings — titles, dates, and document identifiers, **not** the
  contents of the letters
- Your service history
- Your VA payment history — amount, date, payment type, and delivery method

## What the extension deliberately does not collect

The following are excluded by design and are removed before anything is stored or
transmitted:

- Your Social Security number
- Your bank name and bank account number, and your routing number. We read payment amounts
  and dates; we never read where the money goes.
- Government identifiers: EDIPI, ICN, BIRLS ID, SEC ID, Login.gov and ID.me identifiers
- Your date of birth
- The contents of your decision letters

These exclusions are enforced in two independent ways: the extension copies only from a
fixed list of permitted fields, and a separate check inspects the data at every level of
nesting and refuses to store or send it if an excluded identifier is present.

## Where your snapshot is stored

**On your device, your snapshot is held in memory only.** It is never written to your hard
drive. It is kept in your browser's session storage while your browser is open, and it is
gone when you close your browser. You can also delete it yourself at any time from the
extension's Settings, under "Privacy & Data."

Only two things persist locally between sessions: the record that you accepted the consent
notice, and your display preferences. Neither contains your VA record.

You can export your snapshot to a file at any time if you want a copy you control.

## Optional: sending your snapshot to Task Force VA

If you have a Task Force VA account, you may choose to send your snapshot there so your
record is available in your Task Force VA dashboard.

**This is optional and you initiate it yourself**, from your own Task Force VA dashboard.
If you never do this, your record never leaves your browser.

When you do:

- The snapshot is transmitted over an encrypted HTTPS connection.
- Task Force VA is the only destination the extension can transmit to. That destination is
  fixed when the extension is built and cannot be changed by any website you visit. A web
  page can ask the extension to start a capture; it cannot tell the extension where to send
  the result.
- Only Task Force VA pages may make that request.
- Snapshots stored in your Task Force VA account are governed by our main privacy policy at
  https://taskforceva.ai/privacy, including its retention, security, and deletion terms.

The extension does not send your record to any third party, advertising network, analytics
provider, or data broker. We do not sell your data. We do not use or transfer your data for
purposes unrelated to the extension's core functionality, or to determine creditworthiness
or for lending purposes.

## Permissions the extension requests, and why

- **Storage** — to hold your snapshot in memory while your browser is open, and to remember
  your consent and display preferences.
- **Access to `api.va.gov`** — to read your own VA record, using the VA session you
  established yourself.
- **Access to the Task Force VA API** — to deliver your snapshot to your own Task Force VA
  account, if you choose to send it.
- **Messaging from Task Force VA pages** — so you can start a capture from a button on your
  own Task Force VA dashboard.

The extension does not request access to your browsing history, your tabs, your cookies, or
any website other than those named above.

## Your choices

- You may decline the consent notice, in which case nothing is read.
- You may delete your local snapshot at any time from the extension's Settings.
- You may export your snapshot to a file you control.
- You may uninstall the extension at any time, which removes all locally stored extension
  data.
- Deletion of snapshots already delivered to your Task Force VA account follows the
  deletion process described in our main privacy policy.

## Beta status

VA Record Snapshot is currently in **beta testing**. Beta builds connect to Task Force VA's
testing environment rather than our production environment. If you are participating in the
beta, this is disclosed to you at install time.

## Changes to this policy

If we change what the extension collects, stores, or transmits, we will update this policy
and the consent notice inside the extension before that change takes effect.

## Contact

Questions about this policy: **support@taskforceva.io**
