#### Malware Essentials :

 * DLLs are designed to run from disk, which is unsuitable or undesirable in many scenarios.
 * DLLs are therefore paired with a 'loader', which is responsible for loading a DLL from memory (rather than of from disk).
 * The portable executable (PE) file format holds information about a program necessary for loading it into memory.  Both .exe and .dll files are PEs.<img width="771" height="1236" alt="1" src="https://github.com/user-attachments/assets/b2306a04-8ba1-4fd2-aeb8-0eaded26f60d" />
 * The DOS header is a fixed 64-byte structure, called `IMAGE_DOS_HEADER`, that exists at the start of every PE file.
 * The Windows SDK (software development kit) has two definitions for the NT header - `IMAGE_NT_HEADERS` for 32-bit PEs and `IMAGE_NT_HEADERS64` for 64-bit PEs.
