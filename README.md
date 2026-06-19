# John Lombardi - IT Support Portfolio

CompTIA A+ certified IT support specialist focused on Windows troubleshooting, hardware, and end-user support with a knack for explaining technical problems in plain language. Below are hands-on projects that show how I work.

**Certifications:** CompTIA A+ (2025) · Salesforce Certified Associate (2024)
**Contact:** johnlombardi389@gmail.com · [[ LinkedIn ]](https://www.linkedin.com/in/johnlombardi389/)

---

## 🛠️ IT Support Home Lab

A personal lab I built and maintain to practice and document real Tier-1 support work, the same kinds of issues that fill a help-desk queue.

**What I built**
- A Windows environment (Windows 10/11) for hands-on troubleshooting and configuration.
- Multiple PCs assembled from components, with hardware diagnostics, RAM/storage upgrades, and clean OS installs.
- User accounts, file permissions, and system settings configured and tested.
- A growing knowledge base of ticket-style write-ups documenting each problem and its fix.

**Skills demonstrated**
Hardware assembly & diagnostics · Windows install/config/troubleshooting · account & permission management · printer, peripheral, and Wi-Fi/network troubleshooting · clear technical documentation.

**A few "problem → fix" examples**
- *Problem:* A user couldn't sign in after a password change because the new password kept getting rejected. *Fix:* Found the account was locked from repeated failed attempts against cached old credentials; unlocked it, confirmed the new password worked, and wrote up the cause so it'd take a minute to spot next time.
- *Problem:* A user signed in to a blank "temporary" desktop with their files and settings missing. *Fix:*  Traced it to a corrupted user profile, restored it so their data returned, and documented the steps.
- *Problem:* A user couldn't open a shared folder they were supposed to have access to. *Fix:* Checked NTFS permissions, found their group wasn't on the access list, granted the correct level, and verified they could open and save.
- *Problem:* A network printer showed "offline" and wouldn't print for anyone. *Fix:* Found its IP had changed, re-added it by the correct IP, updated the driver, and ran a test page to verify end to end.
- *Problem:* Print jobs piled up and nothing came out. *Fix:* Restarted the Print Spooler service and cleared the stuck spool files, then confirmed the queue cleared and printing resumed.
- *Problem:* A PC could reach sites by IP address but not by name. *Fix:* Recognized a DNS issue, flushed the cache with ipconfig /flushdns, corrected the DNS server setting, and confirmed name resolution.
- *Problem:* A freshly built PC powered on but showed no display. *Fix:* Reseated the RAM and GPU and confirmed the monitor was plugged into the dedicated GPU rather than the motherboard, got POST and boot; logged it as the first thing to check on "no display" builds.
- *Problem:* A system kept randomly shutting down under load. *Fix:* Monitored temperatures, found it thermal-throttling, reseated the cooler with fresh thermal paste, and confirmed stable temps under stress.

> *Why this matters:* I treat the lab like a real job: reproduce the issue, isolate the cause, test the fix, verify it, and write it down. That habit is what keeps a support queue moving.

---

## 💻 Freelance Project — Genomics Data Tool

A paid freelance build for a genomics researcher who needed to turn large, messy CSV data exports into clean, organized Excel workbooks, without installing anything on their machine.

**The problem**
The researcher was hand-processing large CSV exports into spreadsheets: slow, repetitive, and error-prone. They needed it automated, but couldn't run local scripts or install software, so the solution had to work entirely in a web browser.

**What I built**
A browser-based tool (HTML / JavaScript) that:
- Reads and parses large CSV exports in-browser using **PapaParse**.
- Reorganizes the data and generates formatted, multi-sheet **Excel** workbooks using **ExcelJS**, a clean summary plus supporting detail on separate sheets.
- Produces a master index so the researcher could navigate everything at a glance.

**Problems I solved along the way**
- Diagnosed and fixed a parsing bug where certain summary fields weren't being captured correctly.
- Tracked down and corrected a data-merge issue that was throwing off the order of combined records.

**Tools:** JavaScript · ExcelJS · PapaParse · HTML
**Outcome:** A working, reusable tool that replaced a tedious manual process, delivered under a real constraint (browser-only, no local install).

> *Why this matters:* This is the core of support work — someone had a frustrating, repetitive problem, and I built something practical that fixed it and kept working after I was done.

---

## What I'm working toward
Currently studying for **CompTIA Security+** and expanding the home lab with Active Directory and a ticketing system. Open to help-desk and desktop-support roles in the Northern NJ / NYC metro area.
