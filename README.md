
<p align="center"> <img src="https://media1.giphy.com/media/ybl8C8bvrrzRq12f3F/giphy.webp" width="400" height="400"> </p>

<h1 align="center">MARBLE</h1> 

<h4 align="center">Transform your python-based malware into optimized binaries with advanced code protection and transformation capabilities.</h4>

## DESCRIPTION
Marble is a Python code obfuscation tool that transforms malware to resist analysis, avoid detection, and confuse forensic investigation. 
Based on ideas from the leaked CIA Marble Framework, this tool uses anti-forensic methods to make code look like it came from different parts of the world.

## Understanding Marble's Purpose

Marble is a Python code obfuscation and transformation framework built around the ideas shown in the CIA's Marble Framework. At its heart, Marble solves a real problem in cybersecurity and digital forensics: 
the difficulty of tracing where code comes from and analyzing it properly.

## The Attribution Challenge

When security researchers find malware or hacking tools, they try to figure out who made them. They look at code patterns, text strings, language choices, how the code was built, and even comments in the code. 
These clues can show who wrote the code, what organization they work for, what language they speak, and how they build software.

Marble breaks this investigation process. It systematically changes or hides these clues. It doesn't just make code harder to understand—it actively leads investigators to wrong conclusions about where the code came from.

## What Makes Marble Different: More Than Basic Obfuscation

### Most obfuscation tools only make code harder to read. Marble does much more:

  - Geographic Misdirection: Makes code look like it came from specific countries or language groups
  - Multiple Layers of Change: Applies several levels of transformation that must be undone one by one
  - Keeps Working Code: The code still works perfectly, but looks completely different when examined

## Features

  - Multi-language obfuscation: Russian, Chinese, Korean, Japanese, Greek, Zero-width character
  - Comment removal: Strip all comments and docstrings
  - Metadata stripping: Clean file metadata and timestamps
  - Variable/function name obfuscation: Dynamic deobfuscation at runtime
  - String encryption: Encrypted strings decrypted during execution
  - Packer integration: Custom runtime packer deobfuscation at runtime
  - Binary compilation: Convert Python to optimized binary elf
  - Ultra compression: Ultra Compress binary 
  - Broken headers: Corrupt header structures to fail automated EDR/AV analysis
  - False flag insertion: Insert misleading/dead code artifacts 
  - Multi-Layered Obfuscation: Apply multiple transformation layers including AST manipulation, bytecode obfuscation, and binary padding
  - False Flag Operations: Embed linguistic artifacts, compiler fingerprints
  - Static Analysis Evasion: Implement broken headers, corrupted metadata
  - Runtime Protection: environmental keying, and anti-debugging mechanisms
  - Geographic & Linguistic Masquerading – Make binaries appear as if written by developers from specific countries or organizations

### Use Cases:
- Security research and malware analysis
- Penetration testing and red team operations
- Evasion technique development
- Educational purposes in cybersecurity

### INSTALLATION
    git clone https://github.com/0xbitx/DEDSEC_MARBLE.git
    cd DEDSEC_MARBLE
    pip3 install tabulate
    chmod +x dedsec_marble
    sudo ./dedsec_marble
    
### TESTED ON FOLLOWING
* Kali Linux 
* Parrot OS 
  
## Legal Disclaimer

This tool is intended for educational and security research purposes only. Unauthorized usage may be illegal in your jurisdiction. The author is not responsible for any misuse of this tool.
