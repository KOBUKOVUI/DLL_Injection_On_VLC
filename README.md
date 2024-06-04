# DLL Injection and CVE-2010-3124
____

## Description :seedling:
This project explores the topic of DLL (Dynamic Link Library) injection and specifically   
focuses on the CVE-2010-3124. 

CVE-2010-3124 refers to an untrusted search path vulnerability found in VLC Media Player   
version 1.1.3 and earlier.  

Here are key points that can help you have a better overview about this project: 
- **Vulnerability**: The issue arises due to an insecure search path used by  
VLC Media Player when loading dynamic link libraries (DLLs).
- **Attack Scenario**: An attacker places a malicious Trojan horse wintab32.dll in the   
same folder as an innocent-looking .mp3 file.
- **Exploitation** : When VLC Media Player attempts to load the .mp3 file, it accidentially   
loads the malicious DLL, allowing the attacker to execute arbitrary code.
- **Impact**: Successful exploitation can lead to arbitrary code execution and potentially   
allow an attacker to take control of the affected system.

**Attention** :warning: :warning: :warning:

> Feel free to explore our code, documentation, and any additional resources within this   
repository. Remember to use this knowledge responsibly and ethically. Happy hacking! 🚀🔍🔐
> 