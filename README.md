# Site Inspection

Two pieces that work together:

| Piece | Where | What it does |
|---|---|---|
| **Phone app** | Android now, iPhone later | Record projects, inspections and numbered findings, and take photos. The app stores only your notes and *links* to gallery photos, never copies. |
| **Site Inspection on the computer** | Any computer, in the web browser | Search, filter, read and edit reports, view 50% photo copies, click to open originals, export to Excel. Nothing to install. |

The phone and the computer sync **both ways**, over Wi-Fi or the phone's hotspot, or with a USB file. No cloud is involved.

---

## 1. Install the phone app (Android)

1. On the phone, open the [latest release](https://github.com/snCheong2/site-inspection-download/releases/latest) and tap **SiteInspection.apk** to download it. (Or copy the file to the phone by USB.)
2. Open the downloaded file. If Android asks, allow **Install unknown apps** for the app you opened it with.
3. Open **Site Inspection** and enter your name. It's stamped on every inspection.

**Updating:** download the newer `SiteInspection.apk` from the [Releases page](https://github.com/snCheong2/site-inspection-download/releases) and install it over the old one. Your inspections are kept. What changed in each version is in [CHANGELOG.md](CHANGELOG.md).

## 2. Daily use on the phone

- **Projects → New project** sets the name and location once.
- **New inspection** sets the title, location and date. The created time and your name are added automatically.
- **Add finding** → type the description → **Save & take photos**.
  - The camera opens inside the app. Every press of the shutter keeps the photo straight away, with no OK/Retry step.
  - Tap the screen to focus, pinch to zoom, and use the flash button at the top.
  - **Gallery** (next to the shutter) adds photos you already have.
  - Tap **Back** to return to the inspection.
  - The photos are saved to your gallery (album *Site Inspection*) at the camera's full resolution and linked to the finding.
- **Gallery** on a finding links photos you've already taken.
- Tap a photo to see the original full screen (pinch to zoom, swipe for the next; after the last photo it starts again from the first). Long-press it to add a caption or unlink it.
- **⚠ Photo not found** means the photo was deleted or moved in the gallery. Tap it to find it again or re-link it.
- Use the search bar on top, and the filter button for dates.
- **Settings (⚙)** has your name and **Dark mode**.

## 3. Send to computer

On the phone, tap the round **Send to computer** button (next to the search bar) and follow the three steps on screen:

1. **Connect the computer and the phone to the same Wi-Fi.** No Wi-Fi? Turn on the phone's hotspot and connect the computer to it.
2. **On the computer, open Site Inspection in the web browser** (from your bookmark).
   - **First time?** Type the address shown on the phone, for example `http://192.168.43.1:8737`, and click **Get Site Inspection**.
   - Open the downloaded **Site Inspection.html** and bookmark it (Ctrl+D).
   - Choose a folder to keep your inspections in, such as `Documents\Inspections`.
3. **Click "Sync with phone"** and enter the address and code shown on the phone.

Keep the phone screen open until the computer says it's finished. The computer receives the phone's changes, sends back its own edits, and copies any photos it doesn't have yet. If something is interrupted, sync again; it carries on where it stopped.

When you install a newer phone app, the next sync offers the matching newer Site Inspection for the computer. The same file, `Site-Inspection.html`, is also on the [Releases page](https://github.com/snCheong2/site-inspection-download/releases) if you prefer to download it there.

Each computer keeps its own copy and syncs with the phone separately. Edits flow between computers through the phone.

**Computer can't connect?**
- Some office Wi-Fi networks block devices from talking to each other. Use the phone's hotspot instead.
- If Site Inspection says the browser blocked the connection, open the phone's address in the browser and use **Transfer with a file** on that page.

## 4. Sync with a USB cable (backup route)

1. Phone: **Settings → Export to USB**. This saves `SiteInspection-<date>.inspsync` in the phone's Download folder.
2. Connect the cable, choose **File transfer** on the phone, and copy the file to the computer.
3. Computer: in Site Inspection click **Import file** and choose it, or drag it onto the window.
4. To send the computer's edits back: **Sync with phone → Save return file (USB)**, copy that file to the phone, then on the phone go to **Settings → Import USB file**.

## 5. Conflicts

If the same item was edited on the phone *and* on a computer between syncs, nothing is thrown away. It's marked ⚠ on both sides; open it, compare the two versions, and pick one. Your choice syncs everywhere. On the computer, click the **item(s) need review** notice above the list to see every item waiting for a choice.

## 6. Excel

**Excel** in Site Inspection on the computer exports what you're looking at: the open report, or all inspections matching the current search and filters.
- It has one row per finding, plus a thumbnail per photo. Clicking a thumbnail opens the original.
- It's saved in the library's `Exports` folder. **Open in Excel** opens it straight away.


## 7. Backup and restore

- **On the computer:** the folder you chose for Site Inspection holds every inspection and a copy of every photo. Copy that folder (for example to a USB drive) to back it up. To use a backup, open that folder in Site Inspection.
- **On the phone:** **Settings → Export to USB** saves one file with everything, photos included. Keep it somewhere safe.
- **Putting inspections back on a phone** (for example after reinstalling the app): on the phone go to **Settings → Import USB file** and choose either a phone export or a computer return file (**Sync with phone → Save return file (USB)**, which holds every inspection). Photos show again if they are still in the phone's gallery. On a new phone, first copy the photos into its gallery, then tap any **⚠ Photo not found** and choose **Find it again**.
