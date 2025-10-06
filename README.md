# 🕒 Meds Timer

**Offline** web app to track children’s medicines (**Ibuprofen / Paracetamol**) with a **6-hour countdown** per dose.  
Supports **multiple children profiles**, **Take now**, **manual entry**, **undo last dose**, **local history**, and **export/import** (JSON).  
Shows **in-page notifications** while the tab is open.

**Live site:** (enable GitHub Pages → the link will appear here)

## How to use (offline)
1) Open the site (or `index.html` locally).
2) Add a child profile.
3) Choose medicine → **Take now** or add a **manual entry**.
4) Countdown shows **time until next allowed dose** (6h).
5) Use **Export** to share data; **Import** on another device to merge.

> Note: Browsers can’t send background notifications when the site is closed.  
> Keep the tab open (even in the background) to receive reminders.  
> For true background alerts, we can add Calendar export or an iPhone Shortcut later.

## Tech
- 1 file: `index.html` (HTML/CSS/Vanilla JS)
- Data stored in `localStorage` (per browser).
- No frameworks, no build, works offline.

## License
MIT
