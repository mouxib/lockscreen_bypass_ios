# lockscreen_bypass_ios
PoC for Safari Access Exploit on iCloud-Locked iPhones This repository contains a Proof-of-Concept (PoC) demonstrating a vulnerability that allows access to Safari on iCloud-locked iPhones without authentication. The exploit involves modifying backup files to bypass system restrictions.
#iOS 17.7+ Lock Screen Bypass via Shortcuts Exploit.
This repository documents a newly discovered iCloud lock screen bypass method affecting iOS 17.7 and later. While Apple patched a similar exploit in iOS 17.7 that leveraged TalkBack gestures, we have identified an alternative approach that remains functional.

🔍 Exploit Overview:
In any text input field, type: icloud.com/shortcuts.
Select the entire text and choose "Open Link".
The device automatically launches the Shortcuts app.
From here, various system functionalities can be accessed, including:
Camera (via Notes app).
Safari (for browsing Instagram, YouTube, and other sites).
Other system features that can be leveraged for partial device control.
⚠️ Security Impact
This exploit does not fully bypass iCloud activation lock.
However, it allows unauthorized users to interact with system apps under certain conditions.
Apple has not yet classified this as a critical security risk.
🚀 This research aims to highlight the security implications of locked device accessibility loopholes.


