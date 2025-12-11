# TryHackMe — Windows Fundamentals 1

## Overview
This room will specially focus on learning the Windows desktop, the NTFS file system, UAC, the control panel, and more...

## Key Concepts Learned
- As of December 4th 2025, Windows 11 is the current Windows operating system for end-users. It came in 2 flavors, Home and Pro. The main difference between them is that Pro can enable BitLocker encryption when device is lost or stolen (puts everything on lockdown).
- File System: on-disk data structures and logic an OS uses to organise, name, store, and retrieve files. Windows is currently using _NTFS_

## Methodology
Step-by-step with your thought process (NOT just answers).

## Screenshots
<img width="450" height="646" alt="image" src="https://github.com/user-attachments/assets/4a28dc0b-0a62-4cf3-b9a9-d4dfc88524d6" />
<img width="1175" height="756" alt="image" src="https://github.com/user-attachments/assets/3d39a49e-d5d6-4254-8aee-b16e9fa58e99" />



## Final Takeaways
- Windows is the dominant operating system in both home use and corporate networks, making it targeted by hackers & malware writers.
- Malware writers have used ADS, which is a feature in NFTS to contain more than one stream of data, to hide data.
- Deleting any folders or files within System32 can affect the entire Windows OS
- Using UAC (User Account Control) could help prevent privilege-escalation and in consequence, having malware running in the user's account.
