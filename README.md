# Awesome EDR Evasion

## 🛡️ EDR Evasion Techniques

### 🔹 Syscall Evasion
- **Direct Syscalls**: Calling syscalls directly to avoid API hooks.
- **Indirect Syscalls**: Using techniques like "Hell's Gate" or "Halo's Gate" to resolve and execute syscalls dynamically.
- **Recycled Gate**: Reusing a legitimate syscall from a different process.
- **Tartarus Gate**: A novel method of syscall obfuscation.

🔗 [Hell's and Halo's Gate](https://lnkd.in/difdeHPd)
🔗 [Recycled Gate](https://lnkd.in/dmBZBdMu)
🔗 [Tartarus Gate](https://lnkd.in/dn8hYxuJ)

### 🔹 API Unhooking
- **Unhooking NTDLL**: Restoring the original NTDLL memory region.
- **Syscall Stubbing**: Using alternative API calls to bypass hooks.
- **Patch Unhooking**: Overwriting memory regions to remove hooks.

🔗 [Unhooking Patch](https://lnkd.in/d66KMvxg)
🔗 [Windows API for Red Team](https://lnkd.in/dRGSgj_q)

### 🔹 Process Injection Techniques
- **Classic DLL Injection**
- **Thread Hijacking**
- **Process Hollowing**
- **Early Bird Injection**
- **Queue User APC Injection**
- **Atom Bombing**
- **Parent PID Spoofing**

🔗 [EDR Bypass Methods](https://lnkd.in/d7wiwZzr)

### 🔹 Sandbox Evasion
- **Checking CPU Cores**: Many sandboxes run on a single core.
- **Timing Attacks**: Delaying execution to avoid automated analysis.
- **User Interaction Checks**: Requiring mouse movement or keystrokes.
- **Environment Artifacts**: Checking registry, MAC addresses, or system variables.

### 🔹 LOLBins & LOLDrivers
- **Living Off The Land Binaries (LOLBins)**: Using trusted Windows executables for malicious purposes.
- **BYOVD (Bring Your Own Vulnerable Driver)**: Exploiting signed vulnerable drivers to disable security products.

🔗 [EDR Bypass with LOLBins](https://lnkd.in/dr-ApKba)
🔗 [Loldrivers](https://lnkd.in/dzCBh8bu)
🔗 [BYOVD Kill EDR](https://lnkd.in/dAx3cmwv)

## 📜 Articles & Resources
- [Bypass-AV](https://github.com/matro7sh/BypassAV/blob/main/Bypass-AV.md)
- [Awesome EDR Bypass](https://lnkd.in/dahyXpNg)
- [Awesome AV, EDR and XDR Bypass](https://lnkd.in/dsTg4chU)
- [EDR Techniques Bypass Articles](https://lnkd.in/dPB6qcy3)
- [Javas Gate](https://lnkd.in/dSzD_-kf)
- [Pentesting - Defenses Evasion Cheat Sheet](https://github.com/kmkz/Pentesting/blob/master/Defenses-Evasion-Cheat-Sheet)
- [Awesome Red Teaming - Defense Evasion](https://github.com/HildeTeamTNT/Awesome-Red-Teaming?tab=readme-ov-file#-defense-evasion)
- [Awesome EDR Bypass](https://github.com/tkmru/awesome-edr-bypass)
