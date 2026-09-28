# Privacy Policy for Recall

**Effective date:** September 3, 2026
**Contact:** ContactRecallApp@gmail.com

## The short version

Recall has no accounts, no sign-up, and no ads. It does not ask for your name,
your email, or your location, and it does not track you across apps or
websites. The camera is used only to read a barcode; no photo is taken, stored,
or uploaded.

You can erase everything Recall has stored about your device from inside the
app, at any time, without contacting anyone: **Settings → Delete my data**.

The rest of this document is the precise version.

## Who we are

Recall is an independent app. It is not affiliated with, endorsed by, or
operated by the U.S. Food and Drug Administration, the U.S. Department of
Agriculture, the Centers for Disease Control and Prevention, or any other
government agency.

## What Recall stores about you

Recall creates an **anonymous device identifier** the first time you open it.
This is a random identifier issued by our backend provider. It is not your
name, your email, your phone number, or your advertising ID, and it is not
linked to any real-world identity. It exists so that your saved items and
alert settings can follow you between app launches.

Tied to that anonymous identifier, Recall stores:

| What | Why | Where |
|---|---|---|
| Anonymous device identifier | So saved items and alerts belong to your install | Our server and your device |
| Push notification token | To deliver recall alerts you asked for | Our server and your device |
| Saved items (the labels and search terms you save) | To re-check them against new recalls | Our server and your device |
| Allergen selections | To alert you about recalls disclosing those allergens | Our server and your device |
| Quiet hours and time zone | So an alert doesn't arrive at 3am your local time | Our server and your device |
| Theme preference | To remember light/dark mode | Your device only |

## What Recall does not collect

Recall does not collect or store your name, email address, phone number,
postal address, date of birth, precise or approximate location, photographs,
videos, audio, contacts, calendar, medical records, financial or payment
information, browsing history, or a list of other apps on your device.

**One exception worth stating plainly:** if you turn on allergen alerts, the
allergens you select are stored on our server, because the job that checks new
recalls runs there rather than on your phone. Choosing "Nut Allergy" therefore
tells us something about your health. It is attached to the anonymous device
identifier and to nothing that identifies you, it is never shared, and clearing
your selections or using **Settings → Delete my data** removes it. If you would
rather we held nothing of the kind, leave allergen alerts off — every other
part of the app works without them.

Recall contains no advertising and no third-party analytics or tracking SDKs.
It does not collect an advertising identifier, and it does not track you across
other companies' apps or websites.

## What leaves your device when you use Recall

Some features work by asking an outside service a question. Those requests
necessarily contain what you searched for, so they are listed here plainly:

- **When you search**, the words you type are sent to the U.S. Food and Drug
  Administration's public openFDA service to look for matching recalls.
- **When you scan a barcode**, the barcode number is sent to Open Food Facts
  (a public, non-profit food database) to turn it into a product name. The
  camera image itself never leaves your device; only the decoded number does.
- **When you save an item or set an allergen alert**, that item or selection is
  stored on our backend so it can be re-checked when new recalls are published.

Recall does not attach your identity to these requests, because it does not
have one.

## Service providers

Recall relies on these third parties to function. Each receives only what is
needed for its role:

- **Supabase** hosts our database and issues the anonymous device identifier.
  It stores the data listed in the table above.
- **Expo and Google Firebase Cloud Messaging** deliver push notifications. They
  receive your push token and the alert text.
- **Open Food Facts** receives scanned barcode numbers.
- **openFDA (FDA), USDA FSIS, and CDC** receive your search terms when you
  search. These are U.S. government services publishing public-domain data.

Recall does not sell your data, does not share it for advertising, and does not
transfer it to data brokers.

## How long data is kept, and how to delete it

Saved items, allergen selections, and quiet hours are kept until you delete
them or delete your data. There is no scheduled expiry, because a saved item is
only useful if it keeps being checked.

**Settings → Delete my data** removes your device record and everything
attached to it from our server, signs out the anonymous session, and clears
local storage. The next launch starts fresh with a new anonymous identifier.
This is immediate and cannot be undone.

Deleting the app from your device removes everything stored locally, but does
not by itself remove the server-side record. Use the in-app deletion first, or
email ContactRecallApp@gmail.com and we will delete it for you.

## Security

All network traffic uses HTTPS. Device-scoped data is protected by row-level
security rules so that one device's session cannot read or modify another's.
No system is perfectly secure, but Recall reduces the risk by holding as little
as possible: there are no passwords to steal, no email addresses to leak, and
no location history to expose.

## Children

Recall is not directed at children under 13 and does not knowingly collect
information from them. It has no social features, no user-to-user content, and
no personalized advertising. If you believe a child has provided information
through the app, email ContactRecallApp@gmail.com and it will be deleted.

## Your rights

Because Recall holds no identifying information, we cannot look you up by name
or email. You can exercise the practical equivalent of access, correction, and
erasure rights directly in the app: your saved items and settings are visible
and editable there, and **Settings → Delete my data** erases them.

If you are in a jurisdiction granting additional rights (for example the GDPR
or the CCPA), email ContactRecallApp@gmail.com. Note that we may be unable to
tie a request to a specific device record without the device itself, since we
hold no identifier that maps to a person.

## Not medical or safety advice

Recall reports what FDA, USDA, and CDC have published, plus recalls confirmed
by a human reviewer from public reporting. It is an information tool. It is not
medical, health, or safety advice, and it is not a substitute for the official
notice or for professional guidance.

Recall data is not always complete or immediate. Agencies publish on their own
schedules, some recalls are announced by companies before any agency lists
them, and some are never listed at all. **A result of "no recall found" is not
a guarantee that a product is safe.** Always follow the instructions on the
official recall notice, and contact a healthcare provider about any illness.

## Changes to this policy

If this policy changes materially, the effective date above will change and the
updated version will be published at this address. Continuing to use Recall
after an update means you accept the revised policy.

## Contact

Questions, deletion requests, or privacy concerns: **ContactRecallApp@gmail.com**
