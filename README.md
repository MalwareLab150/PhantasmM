# **Phantasm M - A Destructive Malware**

**Phantasm M** is an advanced and highly destructive malware that targets Windows systems. It encrypts files, corrupts system configurations, damages crucial components, and creates unsettling visual and audio effects, making recovery nearly impossible. This malware is designed as a challenge for cybersecurity experts, particularly tailored for the **nFire** YouTube channel, an Italian cybersecurity-focused platform.

---

## **1. Encryption and System Destruction**

Phantasm M begins by **encrypting essential files** and causing **system-wide destruction**:

- **System32 Encryption**: It encrypts critical **System32 files**, which are required for Windows to run. This prevents the OS from booting and leaves the system unresponsive.
- **Hard Disk Files**: The malware also targets files on other hard drives or partitions, rendering **backup data** inaccessible.
- **User Folder Encryption**: It locks away **user folders** such as **Documents**, **Pictures**, and **Videos**, making it impossible to recover personal data .

The encryption algorithm used is complex

---

## **2. User Profile Corruption**

Phantasm M doesn’t just encrypt files—it also corrupts **user profiles**:

- **Profile Deletion**
- **Loss of User Settings**

---

## **3. Disturbing Audio Effects**

- **Distorted Sounds**
- **Audio Interruptions**


---

## **4. Registry Corruption (Regedit)**

The **Windows Registry** is crucial to the smooth operation of the system, and Phantasm M targets it directly:

- **Modifies Critical Registry Keys**: It modifies or deletes key registry entries that control **startup processes**, **system drivers**, and important **configurations**.
- **No Easy Fix**: Phantasm M corrupts **restore points** and **recovery options**, making it impossible to use tools like System Restore to revert changes.

Fixing the registry manually is nearly impossible, and results in a system that is completely unbootable.

---

## **5. Damaging DLL Files**

**DLL files** (Dynamic Link Libraries) are essential for running programs, and Phantasm M corrupts them to further cripple the system:

- **Overwrites System DLLs**: The malware overwrites critical **system DLLs**, causing software crashes and system instability.
- **App Compatibility Failures**: Applications that depend on these DLLs stop working, causing errors and system slowdowns.
---

## **6. Overwriting the MBR (Master Boot Record)**

- **512-Byte Fractal Overwrite**: Phantasm M replaces the MBR with a **512-byte fractal** written in **Assembly** code. This prevents the system from booting .
- **Minimal Code**: The Assembly code is extremely small but highly effective at preventing the OS from loading.

## **7. Corrupting the BCD (Boot Configuration Data)**

The **Boot Configuration Data (BCD)** is essential for the system’s boot process:

- **Corrupting BCD Files**: Phantasm M alters the BCD, causing **boot errors** and preventing the system from starting in **safe mode** or recovery mode.
- **No Recovery Mode**: Even if the MBR is restored, the corrupted BCD makes recovery impossible without a fresh reinstall.

This makes it nearly impossible to repair the system without **reinstalling the entire OS**.

---

## **8. LSD TRIP**

- **Rotating Circles**: It displays **rotating circles** on the screen, distorting the UI and creating a disorienting effect.
- **Bitmap Manipulation**: The malware uses **StretchBlt** and other bitmap manipulation techniques to stretch and warp images on the screen.
- **Psychedelic Colors**: Phantasm M applies **intense HSL** values and **LSD-inspired** color effects that create a chaotic visual experience.

The distorted graphics make the device nearly impossible to use, and the constant visual changes cause confusion and disorientation.

---

## **9. Easter Egg: BSOD and New MBR with 2050 Date**

Phantasm M also includes a hidden **Easter Egg** that makes it even more dangerous:

- **BSOD (Blue Screen of Death)**: If the malware is executed with the system date set to **2050**, it triggers a **BSOD**, crashing the system entirely.
- **New MBR Overwrite**: After the BSOD, Phantasm M overwrites the MBR again but with a new MBR

---

## **10. Designed for nFire: Italian Cybersecurity YouTube Channel**

Phantasm M was created specifically as a challenge for **nFire**, an Italian YouTube channel focused on **cybersecurity**.
I love nFire :) 
---

### **GDI in C#**
The malware uses **C#** and **GDI** functions to create distorted, unsettling visuals:

- **Rotating Circles**
- **Bitmap Manipulation**
- **Intense Color Effects**


---
