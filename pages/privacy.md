---
layout: page-fullwidth
title: "Privacy"
subheadline: "Privacy and permissions"
permalink: "/privacy/"
announcement: "TODO: insert link to Chrome extension."

---

This page describes the permissions used by apps developed by Josh, and the
purpose for which those permissions are used.

## Clean URL Copy

### `active-tab`

This permission is required to allow the extension to read the URL of the
user's current active tab. Without this, the extension could not read the URL
in order to add it to the user's clipboard.

It activates once when the Chrome extension is clicked, to read the current
tab's URL.

### `clipboardWrite`

This permission is required to allow the extension to write to the user's
clipboard. Without this, the extension could not save the clean URL to the
user's clipboard.

It activates once when the Chrome extension is clicked, to save the current
tab's URL to the user's clipboard.
