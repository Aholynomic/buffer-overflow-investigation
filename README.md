# CMP320-Buffer-Overflow-Investigation
 Investigation of Stack-Based Buffer Overflow within CoolPlayer

## Overview 
The CoolPlayer software is a C-based application within Windows designed to play MP3 files and let users listen to music. As part of the assessment for CMP320, the application has been modified and is vulnerable to a buffer overflow exploit when loading skin files. The environment used to perform the testing is a modified Windows XP SP3. The report demonstrates in depth a tutorial to exploit this vulnerability. The format of the report is as follows:

* Exploit with DEP disabled:
    * Proof of Overflow
        * Analysis of Character Filtering and Space for Shellcode
    * Running Calculator
    * Introduce a More Advanced Payload, such as a remote shell.
    * Egg-Hunter Shellcode
* Exploit with DEP enabled:
    * Bypassing DEP with ROP Chains and Executing Shellcode
* Countermeasures to Buffer Overflows

Grade: A+