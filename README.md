# Angloroth

Selected Windows releases of Angloroth, shared here for easy downloading.

## Current shared version: 1.1.0

**[Download Angloroth 1.1.0 for Windows x64](https://github.com/slexx/Angloroth/releases/tag/v1.1.0)**

Audio fishing is now the default. No bobber teaching, fishing-area selection or sound training is required. Better Fishing handles casting and reeling; Speedy AutoLoot handles looting. The previous vision mode remains available under Advanced options.

## Highlights

- **Stats / Tracker** has Catches and Sessions tables with item, location, date and mode filters, item quantities and session outcomes.
- The included bridge now journals catch receipts. **Use STEP 0 → Install all 3 addons again, then restart WoW** to upgrade it.
- Catch records sync from disk after you manually **/reload** or log out. The app never forces reloads; unsaved data can be lost on a client crash.

- Success rate counts **loot-confirmed catches / completed casts**. Cancelling unfinished fishing does not lower it.

- Separate logout/PC shutdown timers and cancellation buttons. **PC shutdown is opt-in, off by default**, with an editable five-minute delay after timed logout. Save work first; Windows delayed shutdown can close unsaved apps.

- Optional cursor HUD for success, state and timer status.

- Clean/Debug console toggle; configurable consecutive failure limit (default 3).

- Editable bite threshold: **lower = more sensitive**, default 86%; try 82% if needed.

## Download and run

1. Download **Angloroth-v1.1.0-windows-x64.zip** from the release above and extract the complete **Angloroth** folder to a new location.

2. Close any older Angloroth copy, then run **Angloroth.exe**. Keep the extracted folder contents together; Python is not required.

3. Open **STEP 0: SETUP FIRST** and choose **Install all 3 addons**: Better Fishing, Fishing State Checker (our included bridge) and Speedy AutoLoot. The app detects WoW Forever or lets you choose its client/AddOns folder. The bridge needs no separate download.

4. Restart WoW once after installation. In **Keybindings → Better Fishing → Cast and Interact**, manually set the key selected in the app dropdown (default **F6**). The app never assigns or overwrites game bindings.

5. Enable Auto Loot and sound effects, keep the small Fishing State Checker strip visible, and select the sound output WoW uses. Go to your fishing spot, focus WoW and press **F8**.

After setup: **open app → fishing spot → F8**. **F8** starts/stops; **F9/Escape** stops. The app always opens stopped and retains its settings and run totals.

Addon author pages are also linked in Step 0: [Better Fishing](https://www.curseforge.com/wow/addons/better-fishing) and [Speedy AutoLoot](https://www.curseforge.com/wow/addons/speedyautoloot).

The automatically generated “Source code” archives contain this distribution page, not the Windows app. Choose the named Windows ZIP asset instead. Each shared release includes release notes and a SHA-256 checksum for its ZIP.

## Updating and privacy

Keep your previous installation as a backup. With both copies closed, copy your own **data** folder to retain settings, totals and tracker history. Shared packages include no personal database or exports. Audio preferences/totals remain separate from vision calibration/library/totals. Shared downloads do not contain another person's settings, images, recordings or logs. The app makes no automatic uploads.

## Current limitations

Similar sounds from other programs or nearby anglers can confuse audio detection. Native interaction range, client compatibility, sound output and bag space affect catches. Use **Test audio** without game input, and **Save session diagnostics** to retain decision metadata if something fails. 449 full-suite source regression tests passed; updated tracker and fishing UI checks also passed. Windows shutdown commands and game input were simulated during development; live outcomes remain dependent on your client and setup.

Automatic play can violate the game's rules and lead to account penalties. Screen-only operation does not establish permission or prevent detection.

## About this page

This is the public distribution home for hand-picked releases. Application development and source history are maintained separately. Publishing a development build does not automatically publish it here.

