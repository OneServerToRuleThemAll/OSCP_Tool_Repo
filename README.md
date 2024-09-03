# OSCP Tool Repo
Quick and dirty repo of tools for the OSCP. This list is not exhaustive, its pretty shit, but can get you running with (some of) the essentials from a fresh install.

This is just a copy/paste of all the tools/scripts that I had laying around in my OSCP folders after completing the training. Some may be widely useful, others may be extremely niche. I will not be including things installed by default on kali

Do your own research. If you're not sure what a tool is/does, Google it. I do not own or claim to have created any of these files/scripts/tools/etc.



# Categories:
AD Specific

Initial Access

Privilege Escalation (PrivEsc)

Utilities

WebShells

# AD Specific
This contains Kerbrute, adPEAS, SharpHound (bloodhound), and StandIn

With the exception of Kerbrute, these all require initial access to use.

# Initial Access
This contains nginxpwner, Grafana_PathTraversal.py, hashgrab.py, jdwp-shellifier.py, reversePress.py, snmp_shell.py, wifimouse_exploit.py, and wp_perfect_path.py

Most of these tools and scripts are niche, with the exception of hashgrab.py

Initial access (as it relates to OSCP) is likely to come from a specific version of an app/service/OS that is vulnerable to an exploit (path traversal, LFI, SQLi, etc.).

The tools in this section are probably not particularly useful in most cases.

# PrivEsc
This contains two categories: Linux and Windows

Linux:

This contains: LinEnum.sh, LinPEAS.sh, mimipenguin.sh, PwnKit, PwnKit.sh, PwnKit32

Windows:

This contains: JuicyPotato (both x64 and x86 variants), GMSAPasswordReader.exe (used for service accounts), mimikatz.exe, mimikatz_32.exe, PowerUp.ps1, PowerView.ps1, PrivescCheck.ps1, Seatbelt.exe, winPEASx64, and WSuspicious


# Utilities

These are general utilities. Some are completely benign while others are a bit more prone to misuse.

This contains: Ligolo-NG (proxy binary for Linux, and agent binaries for Linux/Windows), NetCat (x86 and x64 variants), PSTools (SysInternals tools like PsExec, Procmon, etc.), KeePass (useful if you get a Windows Standalone), Powercat.ps1, and pspy64


# WebShells

A lot of these can be found in /usr/share/webshells but I copied them all here for convienence. Make sure to change and IP/Port/target/etc in the file so it works as expected.

This includes shells for: asp, apsx, java, perl, and php.
