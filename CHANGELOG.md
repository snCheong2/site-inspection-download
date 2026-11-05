# Changelog

Downloads for each version are on the [Releases page](https://github.com/snCheong2/site-inspection-download/releases).
Each release has the phone app (`SiteInspection.apk`) and the matching computer page (`Site-Inspection.html`).

## 1.2.1 (2026-11-05)

- Phone: fixed tapping a photo sometimes opening a different one. It could happen in findings with 3 or more photos.
- Computer: full-size photos now loop too. After the last photo comes the first again (and back the other way), with the arrows or the arrow keys.

## 1.2.0 (2026-10-30)

- Phone: swiping through photos now loops. After the last photo comes the first again (and back the other way).
- Phone: each inspection in the list shows a small picture of its first photo, like the list on the computer.
- Phone: **Import USB file** in Settings now also takes the phone's own **Export to USB** file (photos and all) without running out of memory, so it works as a backup you can import again.

## 1.1.0 (2026-10-29)

- Fixed "items need review" counting items that had nothing to choose: items deleted on both the phone and the computer, or changed the same way on both. Those flags clear by themselves when you open the new version.
- On the computer, the "items need review" notice is now a button. It lists every item still waiting for a choice, including ones inside deleted inspections, each with **Choose version**.

## 1.0.0 (2026-10-25)

First version for testing.

- Phone app: projects, inspections, numbered findings, in-app camera with Gallery button, linked photos with captions, search and filters, dark mode.
- Send to computer in three steps over Wi-Fi or the phone's hotspot, plus USB file export and import.
- Site Inspection on the computer: search and filters, report editing, 50% photo copies, originals on click, Print / PDF, Excel export with **Open in Excel**.
- Two-way sync with conflict marking.
