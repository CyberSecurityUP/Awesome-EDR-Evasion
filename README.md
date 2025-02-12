# Awesome EDR Evasion

## 🛡️ EDR Evasion Techniques

### 🔹 Syscall Evasion
- **Direct Syscalls**: Calling syscalls directly to avoid API hooks.
- **Indirect Syscalls**: Using techniques like "Hell's Gate" or "Halo's Gate" to resolve and execute syscalls dynamically.
- **Recycled Gate**: Reusing a legitimate syscall from a different process.
- **Tartarus Gate**: A novel method of syscall obfuscation.
- **Syswhispers2/Syswhispers3**: Generating undetectable syscalls.

🔗 [Hell's and Halo's Gate](https://lnkd.in/difdeHPd)
🔗 [Recycled Gate](https://lnkd.in/dmBZBdMu)
🔗 [Tartarus Gate](https://lnkd.in/dn8hYxuJ)
🔗 [SysWhispers](https://github.com/jthuraisamy/SysWhispers)  


### 🔹 API Unhooking
- **Unhooking NTDLL**: Restoring the original NTDLL memory region.
- **Syscall Stubbing**: Using alternative API calls to bypass hooks.
- **Patch Unhooking**: Overwriting memory regions to remove hooks.
- **Manually Mapping DLLs**: Loading clean DLLs into memory.
- **Heavens Gate**: Transitioning between 32-bit and 64-bit code to bypass hooks.
- **Hookchain**

🔗 [Unhooking Patch](https://lnkd.in/d66KMvxg)
🔗 [Windows API for Red Team](https://lnkd.in/dRGSgj_q)
🔗 [Direct Syscalls & Unhooking](https://github.com/am0nsec/HellsGate)  
🔗 [Hookchain](https://github.com/helviojunior/hookchain)  

### 🔹 **Injection Techniques**  
- **APC Queue Injection**  
- **AddressOfEntryPoint Code Injection**  
- **Classic Code Injection (API Obfuscation)**  
- **Classic Code Injection (Local)**  
- **Classic Code Injection (Remote)**  
- **Classic Code Injection (Remote with VirtualProtect)**  
- **Classic DLL Injection**  
- **Early Bird Code Injection**  
- **Injection Through Fiber**  
- **Module Stomping**  
- **Mokingjay Injection**  
- **NTAPI Injection**  
- **NtCreateSection & MapViewOfSection Injection**  
- **PEB Walk API Obfuscation Injection**  
- **PEB Walk Injection**  
- **PE Code Injection**  
- **Process Ghosting**  
- **Process Hollowing**  
- **RWX Hunting Injection**  
- **Reflective DLL Injection**  
- **Reflective DLL Loading (Lagos Island)**  
- **Remote Thread Hijacking**  
- **Direct Syscalls Injection**  
- **Indirect Syscalls Injection**

🔗 [EDR Bypass Methods](https://lnkd.in/d7wiwZzr)
🔗 [Native .NET Code Injection](https://lnkd.in/dDNZ7Czr)

### 🔹 Sandbox & VM Evasion
- **Checking CPU Cores**: Many sandboxes run on a single core.
- **Timing Attacks**: Delaying execution to avoid automated analysis.
- **User Interaction Checks**: Requiring mouse movement or keystrokes.
- **Environment Artifacts**: Checking registry, MAC addresses, or system variables.
- **Hardware Fingerprinting**: Identifying VM artifacts like disk serial numbers.
- **Hypervisor Detection**: Using CPUID and other instructions.
- **Instruction Counting**: Detecting instruction execution anomalies in VMs.
- **Stealth Sleep**: Avoiding modified sleep functions used in analysis.

🔗 [al-khaser Anti-VM Toolkit](https://github.com/ayoubfaouzi/al-khaser)  

### 🔹 LOLBins & LOLDrivers
- **Living Off The Land Binaries (LOLBins)**: Using trusted Windows executables for malicious purposes.
- **BYOVD (Bring Your Own Vulnerable Driver)**: Exploiting signed vulnerable drivers to disable security products.
- **Abusing Windows Defender & Other Security Services**: Using native features against the system.

🔗 [EDR Bypass with LOLBins](https://lnkd.in/dr-ApKba)  
🔗 [Loldrivers](https://lnkd.in/dzCBh8bu)  
🔗 [BYOVD Kill EDR](https://lnkd.in/dAx3cmwv)  

## 🛠️ Tools for Evasion
- [Veil Evasion Framework](https://lnkd.in/d-F_689m)
- [Avet Project](https://lnkd.in/eAaAttW)
- [Avlator](https://lnkd.in/eVZrPGF)
- [Shellcode Templates](https://lnkd.in/drNaYnUy)
- [Mortar Evasion](https://lnkd.in/drh-zCj2)
- [AtomPePacker](https://lnkd.in/dMCqisAm)
- [Phantom Evasion](https://lnkd.in/dcYCSx95)
- [PEObfuscator](https://lnkd.in/dA5Hp7PF)
- [AMSI Bypass Powershell](https://lnkd.in/d9HC5R5C)
- [SharpBlock](https://lnkd.in/dWUY8f5Y)

### 🔹 LOLBins & LOLDrivers
- **Living Off The Land Binaries (LOLBins)**: Using trusted Windows executables for malicious purposes.
- **BYOVD (Bring Your Own Vulnerable Driver)**: Exploiting signed vulnerable drivers to disable security products.
- **Abusing Windows Defender & Other Security Services**: Using native features against the system.

🔗 [EDR Bypass with LOLBins](https://lnkd.in/dr-ApKba)  
🔗 [Loldrivers](https://lnkd.in/dzCBh8bu)  
🔗 [BYOVD Kill EDR](https://lnkd.in/dAx3cmwv)  


## 🛠️ Tools for Evasion
- [Veil Evasion Framework](https://lnkd.in/d-F_689m)  
- [Avet Project](https://lnkd.in/eAaAttW)  
- [Avlator](https://lnkd.in/eVZrPGF)  
- [Shellcode Templates](https://lnkd.in/drNaYnUy)  
- [Mortar Evasion](https://lnkd.in/drh-zCj2)  
- [AtomPePacker](https://lnkd.in/dMCqisAm)  
- [Phantom Evasion](https://lnkd.in/dcYCSx95)  
- [PEObfuscator](https://lnkd.in/dA5Hp7PF)  
- [AMSI Bypass Powershell](https://lnkd.in/d9HC5R5C)  
- [SharpBlock](https://lnkd.in/dWUY8f5Y)  
- [Process Injection Tools](https://github.com/boku7)  

## 📜 Articles & Resources
- [Cocomelonc Blog](https://cocomelonc.github.io/)  
- [SaadAhla’s GitHub](https://github.com/SaadAhla)  
- [boku7's GitHub](https://github.com/boku7)  
- [Awesome EDR Bypass](https://github.com/tkmru/awesome-edr-bypass)  
- [Pentesting - Defense Evasion Cheat Sheet](https://github.com/kmkz/Pentesting/blob/master/Defenses-Evasion-Cheat-Sheet)  
- [Javas Gate](https://lnkd.in/dSzD_-kf)  
- [Red Teaming Resources](https://github.com/HildeTeamTNT/Awesome-Red-Teaming)  
