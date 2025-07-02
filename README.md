# DAY-6
I am Jaskiran kaur from department of 'COMPUTER SCIENCE ENGINEERING'.
HELLO, Today we learn about :

🛡️ 1. Safe Mode
---
✅ What is Safe Mode?

![image](https://github.com/user-attachments/assets/a3c38c79-e590-465f-9629-4e75d7001cd2)

Safe Mode is a special diagnostic startup mode in Windows that loads only the essential system files and drivers.
🔧 When to Use:

    PC won’t boot properly

    BSOD (Blue Screen of Death)

    Malware infection

    Troubleshooting system errors

🚀 How to Enter Safe Mode (Windows 10/11):
If Windows Boots:

    Click Start → Settings → System → Recovery

    Under Advanced Startup, click Restart now

    Press 4 or F4 for Safe Mode

If Windows Doesn’t Boot:

    Turn on the PC and force shutdown (hold power button) 2–3 times to trigger Recovery Mode

    Then go to: Troubleshoot → Advanced options → Startup Settings → Restart
---
🛠️ 2. Recovery Tools: 

![image](https://github.com/user-attachments/assets/28dccc42-2497-4ca3-99f5-386f9e8e4f79)

Recovery tools are built-in or external utilities that help you repair, restore, or reset your operating system (OS) when something goes wrong—like startup failures, system crashes, virus damage, or corrupted files.
These tools are especially helpful when your PC won’t boot or Windows is malfunctioning.

🔧 Common Windows Recovery Tools:
| 🧰 Tool Name              | 🔍 Purpose                                                                |
| ------------------------- | ------------------------------------------------------------------------- |
| **Startup Repair**        | Fixes boot problems (e.g., black screen, stuck on logo).                  |
| **System Restore**        | Rolls your PC back to a previous working state without deleting files.    |
| **System Image Recovery** | Restores Windows from a full system backup image.                         |
| **Command Prompt**        | Lets you run repair commands like `sfc`, `chkdsk`, `bootrec`, etc.        |
| **Reset This PC**         | Reinstalls Windows (with or without keeping personal files).              |
| **Recovery Drive/USB**    | A bootable USB that can launch recovery tools when your PC won’t start.   |
| **Safe Mode**             | Starts Windows with minimal drivers/services to help troubleshoot issues. |

🖥️ How to Access Recovery Tools (Windows 10/11)
✅ If Windows Boots:

    Go to Settings > System > Recovery

    Click Restart now under “Advanced startup”
🔁 If Windows Won’t Boot:

    Force shutdown 2–3 times to enter Windows Recovery Environment (WinRE)

    Or boot from a Windows installation USB or recovery disk

⚙️ Common Recovery Tool Uses:
| Scenario             | Recovery Tool                                              |
| -------------------- | ---------------------------------------------------------- |
| PC won’t start       | **Startup Repair** or **Reset This PC**                    |
| Files gone/corrupted | **System Restore** or **System Image Recovery**            |
| Virus damage         | **Reset This PC** or use antivirus from **Command Prompt** |
| Fix boot errors      | Use **bootrec** in **Command Prompt**                      |
| Can't enter Windows  | Boot from a **Recovery USB** or use **Safe Mode**          |
---
🛠️ What Are OS Repair Tools?

![image](https://github.com/user-attachments/assets/15b3d817-c05b-41c3-994b-2334fca386f3)

OS (Operating System) repair tools are utilities that help fix problems with your Windows system—such as corrupt system files, boot errors, update failures, and system instability—without needing a full reinstall.

🧰 Essential Windows OS Repair Tools: 

| 🧪 Tool                                                | 💡 What It Does                                           | 🧭 How to Use                                               |
| ------------------------------------------------------ | --------------------------------------------------------- | ----------------------------------------------------------- |
| **SFC (System File Checker)**                          | Scans and repairs corrupted system files.                 | `sfc /scannow` in Command Prompt (Admin)                    |
| **DISM (Deployment Imaging Servicing and Management)** | Repairs Windows system image, often used after SFC fails. | `DISM /Online /Cleanup-Image /RestoreHealth`                |
| **Startup Repair**                                     | Fixes boot problems automatically (e.g., PC not booting). | From Advanced Startup > Troubleshoot > Startup Repair       |
| **System Restore**                                     | Reverts system to a previous working state.               | From Recovery Tools or via `rstrui.exe`                     |
| **Reset This PC**                                      | Reinstalls Windows (optionally keeping files).            | Settings > Recovery > Reset This PC                         |
| **Chkdsk (Check Disk)**                                | Scans and repairs disk errors.                            | `chkdsk C: /f /r` in Command Prompt (Admin)                 |
| **Bootrec**                                            | Fixes bootloader issues (MBR, BCD).                       | `bootrec /fixboot`, `/fixmbr`, `/rebuildbcd` (Advanced CMD) |
| **Windows Update Troubleshooter**                      | Fixes problems related to updates.                        | Settings > Troubleshoot > Additional troubleshooters        |
| **System Image Recovery**                              | Restores a previously created system backup image.        | In Advanced Recovery options                                |


🦠 What Are Viruses and Malware?

![image](https://github.com/user-attachments/assets/fec8164c-da0f-4e5f-be18-116c03af1803)


    Malware is a general term for malicious software (viruses, worms, trojans, spyware, ransomware, etc.) designed to harm or exploit your system.

    Virus is a type of malware that can replicate itself and spread to other files or systems.

🚨 Common Symptoms of Virus/Malware Infection:

| ⚠️ **Symptom**                          | 🧪 **Possible Cause**                         |
| --------------------------------------- | --------------------------------------------- |
| PC is unusually slow                    | Malware using system resources                |
| Random pop-ups or ads                   | Adware or browser hijacker                    |
| Programs crash or won’t open            | File corruption or active malicious processes |
| Unknown programs installed              | Trojan or bundleware silently installed       |
| Antivirus is disabled or missing        | Malware tries to hide from detection          |
| High network usage with no reason       | Malware using internet to communicate         |
| Browser homepage/search engine changes  | Browser hijacker                              |
| Files encrypted with strange extensions | Ransomware                                    |

🧹 Basic Malware Removal Steps
✅ Step 1: Boot Into Safe Mode

    Prevents most malware from auto-starting.

    Press Shift + Restart → Troubleshoot → Startup Settings → Safe Mode.

🛡️ Step 2: Run Antivirus/Malware Scans

Use trusted tools:

    ✅ Windows Defender (built-in)

    🛠 Malwarebytes (Download)

    🔍 Kaspersky Virus Removal Tool (Download)

🧹 Step 3: Remove Suspicious Apps

    Go to Control Panel → Programs → Uninstall a program

    Remove apps you don’t recognize or didn’t install

🌐 Step 4: Reset Browser Settings

For Chrome:

    Go to Settings → Reset and clean up → Restore settings to original defaults

For Edge:

    Settings → Reset Settings → Restore settings to their default values

💼 Step 5: Clean Startup Programs

    Press Ctrl + Shift + Esc → Open Task Manager

    Disable suspicious entries under the Startup tab
---
🧷 How to Prevent Future Infections
| ✅ Tip                                     | 💡 Why It Helps               |
| ----------------------------------------- | ----------------------------- |
| Keep Windows & antivirus updated          | Patches known vulnerabilities |
| Don’t download cracked software           | Often bundled with malware    |
| Be careful with email links/attachments   | Prevent phishing attacks      |
| Use a password manager + strong passwords | Avoid account hacks           |
| Enable Firewall and real-time protection  | Stops malware before it runs  |

---
🔌 What is an RJ45 Cable Connector?
RJ45 (Registered Jack 45) is a standard connector used primarily for Ethernet networking. It's the most common type of connector used to connect computers, routers, switches, and other network devices via Ethernet cables (usually Cat5, Cat6, or Cat7).

![image](https://github.com/user-attachments/assets/da47739d-f626-4868-b1a1-438b85c94812)

---
🧠 Key Facts About RJ45:
| 🔍 Feature              | 📄 Details                                     |
| ----------------------- | ---------------------------------------------- |
| 📦 **Type**             | 8-pin connector (8P8C – 8 Position, 8 Contact) |
| 📡 **Use**              | Ethernet networking, LAN connections           |
| 🔌 **Cable Types**      | CAT5, CAT5e, CAT6, CAT6a, CAT7                 |
| ⚙️ **Speed Support**    | Up to 10 Gbps (with CAT6/CAT7 cables)          |
| 🔄 **Wiring Standards** | T568A and T568B (defines wire color order)     |

🛠️ Common Uses of RJ45:
| Device A       | ➡️ Connected To  | Through RJ45        |
| -------------- | ---------------- | ------------------- |
| Computer       | Router or Switch | Ethernet cable      |
| Gaming Console | Modem            | Wired connection    |
| Printer        | Network switch   | LAN setup           |
| IP Camera      | NVR or Router    | Surveillance system |

----
![image](https://github.com/user-attachments/assets/8808f1ca-73c3-47bb-ac9b-f68ef361206d)

![image](https://github.com/user-attachments/assets/55c632bb-c978-4c59-b74b-c86e355f47e9)


