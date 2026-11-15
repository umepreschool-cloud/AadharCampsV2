# AadharCampsV2

Reset procedure (admin only)

The reset function resetAadharCounter() is deliberately not linked to any button, so a visitor can’t trigger it by accident.

Open the registration page in a desktop browser.
Open the developer console:
Windows / Linux: press F12 (or Ctrl + Shift + J in Chrome)
Mac: press Cmd + Opt + J
Type the following and press Enter:
js
resetAadharCounter()
Check the console for this message:
Token counter reset. New value: 0
The next person to click Save receives token #1.

If the console shows Could not reset counter: instead, the counter service was unreachable. Check your internet connection and try again.
