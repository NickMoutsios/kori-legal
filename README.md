# kori-legal

Public pages for the **TeleKori** app, served by GitHub Pages.

| Page | URL | Used by |
|---|---|---|
| `privacy-policy.html` | /privacy-policy.html | Play Console → App content → Privacy policy; App Store Connect → App Privacy |
| `support.html` | /support.html | App Store Connect → Support URL; Play Console contact details |
| `index.html` | / | Landing page linking to both |

## This repository is public on purpose

It exists so the app's own repository can stay private. Put nothing here that is
not meant to be read by anyone.

## Source of truth

`privacy-policy.html` is maintained in the app repository at
`docs/privacy-policy.html` and copied here. Edit it there, then copy, so the
policy stays versioned alongside the app it describes.

## Before changing the privacy policy

Raise its version number and the "Last updated" date. If the change is material
— in particular if the app starts sending data off the device — users must be
told and asked to agree before the feature is switched on, as section 10 of the
policy commits us to.
