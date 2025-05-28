---
title: Your iPhone Can Be Hacked Just by Receiving a Video - Here's How
date: 2025-05-28T22:11:36.018Z
---
If you think your iPhone is safe as long as you avoid suspicious links, think again. A newly discovered vulnerability (CVE-2025-31200) proves that even just receiving a media file could compromise your entire device—no clicks required.

For the full technical breakdown, security researcher Billy Ellis has an excellent [video](https://www.youtube.com/watch?v=nTO3TRBW00E). But since my friend Ethan asked for my take, I’ll break down why this exploit is so dangerous—and why Apple’s lack of transparency makes it worse.

Why This Exploit is Different (And Worse) Than Most

#### 1. Zero-Click Attacks: No Interaction Needed

Most hacks require you to do something—click a link, download a file, or enter a password. This one? Your phone can get hacked just by receiving a video or audio file.

* iMessage, Mail, or even AirDrop could deliver the payload.
* No warnings, no suspicious prompts—just silent exploitation.



#### 2. Media Files Are the Perfect Weapon

Unlike executable files (.exe), which security tools flag, media files (MP4, PDF, GIF) are considered "safe." That makes them ideal for bypassing filters.

Past examples of weaponized media files:

* 2016 ("Peekaboo") – Malicious PDFs bypassed iPhone security.
* 2019 (WhatsApp CVE-2019-3568) – MP4 files hijacked phones.
* 2023 (BLASTPASS) – WebP images installed spyware via iMessage.

#### 3. Apple’s Own Features Are Being Exploited

This latest attack abuses High Order Ambisonics (HOA)—Apple’s new 3D audio format for iPhone 16’s "spatial videos."

Why hackers love it:

* New & untested code, making it more likely to contain overlooked flaws.
* Deep system access, meaning it can bypass normal security checks.
* Most users don’t even know it exists, which makes it perfect for stealth attacks.

#### The Bigger Problem: Apple’s Lack of Transparency

Apple did patch this flaw in iOS 18.4.1, but their security notes are frustratingly vague:

❌ No details on how the exploit worked.

❌ No mention of who was targeted (though they admit it was used in real attacks).

❌ They quietly fixed a PAC bypass in the same update—meaning hackers likely had a full exploit chain.



#### Why This Silence Hurts Users

* Businesses & HR teams sending files to employees/candidates could unknowingly spread malware.
* High-risk individuals (journalists, activists, execs) remain in the dark about real threats.
* Security researchers can’t properly analyze risks without details.

#### What’s Next? (And How to Protect Yourself)

Future Threats on the Horizon

* I fully expect to see AI-generated weaponized media – A "harmless" AI voice note could trigger the next exploit.
* More 3D media flaws – As Apple pushes Vision Pro and spatial computing, I expect new vulnerabilities to be found and abused.

#### 3 Simple Steps to Stay Safe

* Update your iPhone immediately (iOS 18.4.1 patches this flaw).
* Disable auto-preview in Messages (Settings > Messages > Link Previews → Off).
* Be cautious with media files – Even from known contacts, think twice before opening.



#### Final Thoughts: A Wake-Up Call

This isn’t just another bug—it’s proof that "safe" files can be weapons. Until Apple becomes more transparent about real-world threats, we’re all playing defense in the dark.

Stay vigilant, stay updated, and don’t assume your iPhone is bulletproof.