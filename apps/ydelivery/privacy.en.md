---
layout: page
title: "YDelivery — Privacy Policy"
lang: en
permalink: /apps/ydelivery/privacy/
---

{% include lang-switcher.html %}

*Effective date: October 2, 2026 · This page is versioned in Git — every change
is a reviewed commit.*

YDelivery is an unofficial client for delivery providers — the first integration
is Yandex Delivery's Express API. It is built by an independent developer
("we" below) and is not affiliated with or endorsed by Yandex.

## What the app collects

When you place or draft a delivery, you enter:

- **Names** — sender and recipient names.
- **Phone numbers** — for contacts at each stop.
- **Physical addresses** — pickup and delivery points.
- **Precise location** — only when you pick a point on the map or let the app
  suggest addresses around you.

The app also reads file timestamps (for ordering recent places and files) and
keeps local diagnostic logs on your device.

All of this is entered by you, inside order, share, or compose flows. The app
collects nothing in the background and gathers nothing it does not show you.

## Why

One purpose: **app functionality** — placing deliveries with the provider,
tracking their status, and letting you repeat past orders. The data is never
used for advertising, profiling, analytics, or sale.

## Where your data lives

- **On your device** — the orders database and diagnostic logs.
- **In your private iCloud database** — CloudKit syncs your orders, library, and
  places across your devices. This is your own iCloud storage; the developer
  cannot see its contents.
- **Keychain** — your Yandex Delivery API token is stored in the iOS Keychain,
  never in plain files or preferences.

## Who receives data

- **Yandex Delivery's Express API** — order details (route, items, contacts,
  price) are sent to the provider to execute your delivery, under your business
  account's terms.
- **Apple CloudKit** — carries sync between your devices, inside your private
  database.

No advertising networks, no analytics SDKs, no tracking, no sale of personal
data.

## Retention and deletion

You delete orders, library entries, and places inside the app. Data in your
private iCloud database is governed by your own iCloud account. Removing the
API token in Settings signs the app out and stops all provider access.

## Contact and changes

Questions: [github.com/laconicman/YDelivery/issues](https://github.com/laconicman/YDelivery/issues).
Changes to this policy land here first, dated above.
