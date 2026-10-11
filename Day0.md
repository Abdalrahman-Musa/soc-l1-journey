Day 0 is setup only. Budget 3–5 hours and don’t start studying yet. When you finish, you should have a place for notes, a place to publish, the core tools installed, and a schedule.

**1. Notes vault (30 min)**  
Use Obsidian or Notion. Obsidian is the better choice here because its notes are plain markdown, so they can go straight into your GitHub repo. Create these three pages now, even if they stay empty:

- Detection Cookbook
- Event ID Cheat Sheet
- Playbooks

**2. GitHub repo (20 min)**

- Create a repo named `soc-l1-journey`.
- Write a short README with your goal and the six phases.
- Add folders: `cheatsheets/`, `writeups/`, `detections/`, `lab/`.
- Rule from day one: publish methods and write-ups, never flags.

**3. Install tools (1–2 h)**

- **VirtualBox** or **VMware Workstation Pro** (free for personal use).
- **Wireshark.** On Windows, keep Npcap ticked during install. Quick test: start a capture, open a website and confirm you see DNS and TLS packets.
- **CyberChef.** It runs in the browser. Download the offline copy as well.
- **Virtualization in the BIOS.** Check that VT-x/AMD-V is enabled. If it’s off, VMs will fail later.

**4. Bookmarks and accounts (20 min)**

- Make a “Threat Intel” bookmark folder with VirusTotal, AbuseIPDB, URLScan.io, ANY.RUN and Hybrid Analysis.
- Create the free accounts you’ll need anyway: LetsDefend, CyberDefenders and Blue Team Labs Online. Doing it now saves friction later.

**5. Reality checks (20 min)**

- **RAM:** check how much you have. Under 16 GB means planning the cloud option for the week 21 capstone.
- **Bootcamp overlap:** compare the Archon Vanguard syllabus against the 26 weeks. Mark any week it already covers, so you can jump straight to that week’s checkpoint.

**6. Schedule and tracker (20 min)**

- Block 5 weekday sessions of 1.5 h each, plus one protected 4-hour weekend lab block.
- Start a progress sheet with columns for week, hours, rooms done, artifacts published and checkpoint passed.

You’re done when Wireshark captures traffic, the repo exists with a README, the vault has its three pages, and next week’s study sessions are in your calendar.

Week 1 starts with OSI and subnetting drills alongside TryHackMe’s Pre Security path.

I can build the progress tracker for you now, pre-filled with all 26 weeks, the phases and the checkpoints, if you’d like.