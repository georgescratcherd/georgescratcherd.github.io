---
layout: page
title: Privacy Policy
permalink: /privacy-policy/
---

_Last updated: 2026-08-25_

This privacy policy covers **Receipts Management**, a personal, single-user application
built and operated by George Scratcherd. It is not a public product or service — it exists
solely to help the developer organize and archive his own personal receipts, and no other
individuals use it or have accounts with it.

## What data this application accesses

Receipts Management connects to a single Google Drive folder, owned by the developer, that
he uses to store photos of paper receipts. With the developer's own authorization, the
application:

- Reads the contents of that folder to find newly added receipt images
- Downloads those images for processing
- Moves or removes (trashes) files within that folder once they have been safely archived
  elsewhere

It does not access any other files, folders, or data in the developer's Google account, and
it is not able to access any other person's Google account or data.

## How this data is used

Each receipt image is processed to extract structured information from it — for example the
vendor, date, amount, and itemized contents of the receipt — so that the developer can keep a
personal record of his own spending. This processing is performed using Anthropic's Claude
API. The image is sent to Anthropic solely to perform this extraction; Anthropic's use of
that data is governed by [Anthropic's own privacy policy](https://www.anthropic.com/legal/privacy).

The extracted data and the receipt images themselves are stored privately in a database and
file archive that the developer owns and operates on his own infrastructure. They are used
only for the developer's personal financial record-keeping.

## Data sharing

This application does not sell, rent, or share the data it accesses with any third party,
and does not use it for advertising or any purpose unrelated to the personal record-keeping
described above. The only outside service involved in processing this data is the Anthropic
API, used strictly to extract structured information from receipt images as described above.

## Data retention

Receipt images are removed from the source Google Drive folder once they have been safely
copied into the developer's private archive. Both the extracted data and the archived images
are otherwise retained indefinitely, as they form an ongoing personal financial record.

## Contact

Questions about this policy can be sent to
[george@georgescratcherd.com](mailto:george@georgescratcherd.com).
