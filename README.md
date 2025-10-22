# InDrive-OTP-Validation-Bypass-Sanitized-Write-up-
# InDrive-OTP-Validation-Bypass-Sanitized-Write-up-
🚗💥 The “0000” Magic Trick — InDrive OTP Bypass (Educational Report)

🧑‍💻 For learning purposes only — no real accounts were harmed!
Just a friendly bug hunter discovering some wild logic in the land of mobile apps.

🕵️‍♂️ What Happened

So, I was playing around with the InDrive app (yes, the one for rides 🚕).
I went to change my phone number — you know, normal stuff — and it said:

“We’ve sent you a 4-digit OTP! Please enter it to confirm.”

But then I thought: What if I just… don’t?

So instead of waiting for an SMS, I typed 0000 and hit Confirm.
And guess what? 🎉
The app said, “Cool, new number added!” 😳

Basically… it was like saying a secret password to the bouncer and he just lets you in without checking your ID.

⚙️ What It Means (Non-Tech Version)

Normally, OTPs (those little 4-digit codes you get by SMS) prove that you actually own the phone number.

But here, the app didn’t care!
It said “fine” to anyone entering 0000, meaning you could:

Change your number to anyone’s 📱

Lock someone out of their account 🔒

Even cancel trips that aren’t yours 😬

It’s like changing the locks on someone’s house and keeping the keys.

🧪 How I Found It (Simple Steps)

Opened the InDrive app.

Went to “Change Phone Number.”

Entered a new random number (no real person’s).

When it asked for an OTP, typed 0000.

Boom — phone number changed. 🪄

I even made a video for them (privately shared, not public 🫶).

💡 What Should Be Fixed

Dear InDrive devs,
👉 Please don’t let 0000, 1234, or other silly numbers act like VIP passes.
👉 Always check the OTP server-side, not just in the app.
👉 Maybe block obvious fake codes, and add rate limits.

In short: make OTPs mean something again 😂

🧠 Lesson for Everyone

This isn’t about “hacking” — it’s about showing how tiny oversights can break big systems.
It’s also why security testing (and bug bounties 🪙) are so important.

And don’t worry — I’m friendly, I reported this ethically ❤️
No accounts were harmed, no illegal activity, just good vibes and responsible disclosure.

Bonus

If you’re reading this and you work in Europe or France —
👋 Hi! I’m an international student (and immigrant) exploring cybersecurity.
Looking for internships in:

🧩 Pen Testing

🛡️ SOC Analysis

🧠 GRC

🔐 IAM

Let’s make security fun, ethical, and human again. 💙
feel free to email me : keshorpuresoul@gmail.com
#CyberSecurity #BugBounty #PenTesting #EthicalHacking #Internship #France #CyberTalent #InfoSec #AppSec #SecurityResearch #BugHunter #InDrive #EthicalHacker #SecurityAwareness
