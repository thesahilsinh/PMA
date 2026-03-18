This chapter is about Basic Static analysis of Malware.

what i have learned in this chapter by doing labs and going through the lessons.

- in static we analyze code or structure of malware where in dynamic we run the malware.

three ways to extract information.

- using antivirus tools to confirm maliciousness.
- using hashes to indetify malware.
- gleaning info from file's strings, functions, and headers

Antivirus scanning

- we basically use virustotal for this

hashing: fingerprint of malware

- many algos are there majorly used is MD5 and SHA versions

Strings:

- explanation of ASCII and UNICODE syntax and how null terminator is used in both
- we use command called strings followed by program. eg strings sahil.malware

packed and obfuscated malware

- obfuscated malware are the ones whose execution has attempted to hide and packed is subset of obfuscated malware and it compressed so that this both technique make malware to possibly identified by static analysis
- to detect packer we use TOOl called PEiD. use to detect packer or compiler employed.

portable executable file format:

- using file type we can know that it is made for what like PE is for windows, ELF linux and mach-o or .app for macos

linked libraries and functions:

- imports: functions used by one program that are actually stored in a different program. like code libraries
- code libraries can be connected to main executable by linking.

<<<<<<< HEAD
static, runtime, and Dynamic Linking
=======
- static, runtime, and Dynamic Linking
>>>>>>> 10b349f0c06f580687512914bf8f5956aec8867b

-- 