# Kairos beta — tester guide

Thank you for trying Kairos, a calm planner for your tasks and events. Your planner lives on your computer. Kairos only goes online if you turn on its optional smart features, and once a day to check for a newer version (you can switch that off in Settings › Updates).

## 1. Install (2 minutes)

Download the file for your computer from **[Releases](https://github.com/ibrahimhere1995-hue/kairos-releases/releases)** (under *Assets*).

### Windows 10 or 11

1. Double-click **Kairos_0.3.0_x64-setup.exe**.
2. Windows may say **"Windows protected your PC"**. This beta isn't signed yet, which is normal for test versions. Click **More info**, then **Run anyway**.
3. Follow the installer. Kairos opens when it's done.

### Mac (Intel or Apple Silicon)

1. Open **Kairos_0.3.0_universal.dmg** and drag **Kairos** into **Applications**.
2. The first time, **right-click** Kairos in Applications and choose **Open**, then **Open** again. (The Mac blocks test apps that aren't from the App Store or signed by Apple yet.) If that doesn't work: **System Settings › Privacy & Security**, scroll down, and click **Open Anyway**.
3. If the Mac says Kairos **"is damaged and can't be opened"**, open **Terminal** and paste this once, then try again:
   `xattr -cr /Applications/Kairos.app`

On a Mac, reminders appear without Done/Snooze buttons. Everything else works.

## 2. Try it your way (about 20 minutes)

Use it for your real day if you like. Some ideas:

- Add a few things you need to do this week, and one thing that repeats.
- Put something on the calendar at a set time.
- Tick something off. Then change your mind and undo it.
- Find something again using the search box at the top.
- Close the window, then find Kairos again.
- Try **Focus** (the timer in the top bar) or the **Weekly review** in the sidebar.
- On Windows: click in any text box, press **Windows key + H**, and say what you need to do.

There is no wrong way to use it. If you get stuck, that's useful to us: please don't look anything up.

Optional: **Settings › Smart features** can read screenshots and plan your day using your own free Google Gemini key. Only try this if you're comfortable; it's not needed for the test.

## 3. Tell us (5 minutes)

Write down, in your own words:

1. What was **confusing** or made you hesitate?
2. What did you **expect** to happen that didn't?
3. What did you **like**?
4. Would you use it every day? Why or why not?

Screenshots are very welcome (Windows: **Windows key + Shift + S**; Mac: **Cmd + Shift + 4**). You can also use **Wishlist › Suggest a feature** inside Kairos and then **Email to the developer**.

## Uninstall

- **Windows:** Settings › Apps › Installed apps › Kairos › Uninstall. Your planner data stays in `%APPDATA%\com.kairos.app` until you delete that folder.
- **Mac:** drag Kairos from Applications to the Bin. Your data stays in `~/Library/Application Support/com.kairos.app` until you delete that folder.
