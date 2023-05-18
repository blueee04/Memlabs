# Memlabs

![](TVP_VolatilityLogo.png)

Let's talk a bit about Memory Forensics over here and how volatility can be used along with a few of it's plugins.
So Volatility specializes in analyzing the volatile memory of a system. Memory contains a wealth of information about running processes, network connections, loaded modules, and other artifacts that can be crucial in forensic investigations. Volatility allows analysts to extract and analyze this information to understand system activity, detect malware, and investigate security incidents.

Let's talk about a few important plugins:

```
pslist: Lists running processes and their details.

psscan: Scans for hidden or terminated processes.

dlllist: Lists loaded DLLs and their details.

handles: Displays open file handles and registry keys.

filescan: Scans for file objects in memory.

netscan: Lists network connections and related information.

timeliner: Creates a timeline of system activity based on various artifacts.

hivelist: Lists active registry hives in memory.

malfind: Detects and extracts injected or malicious code.

apihooks: Identifies API hooking techniques used by malware.

cmdline: Displays command-line arguments of processes.

svcscan: Lists Windows services and their details.

modscan: Scans for loaded kernel modules and drivers.

ssdt: Lists the System Service Descriptor Table (SSDT) and associated details.

envars: Displays environment variables for each process.

connections: Lists network connections and associated process information.

sockets: Provides information about open network sockets.

shimcache: Extracts information from the Application Compatibility Shim Cache.

getsids: Lists security identifiers (SIDs) associated with each process.

printkey: Displays the contents of a registry key.

userassist: Retrieves information about user-assist artifacts, indicating program execution history.

mftparser: Parses and extracts information from the Master File Table (MFT) on NTFS volumes.
```

These are mostly used plugins in volatility....One more thing while analysing memory dumps...you should mostly focus on four folders namely

1. Downloads
2. Desktop
3. Documents
4. Pictures

You can find important information in these folders

Having a good understanding of the operating system you are analyzing is crucial. Different versions of an operating system may have variations in data structures, process models, and memory layouts. Familiarize yourself with the internals of the relevant operating systems to interpret the artifacts extracted by Volatility correctly.

Volatility is a complex tool, and proficiency comes with practice. Experiment with different memory images, run various plugins, and analyze the results. There are online resources, forums, and books available that provide tutorials, case studies, and real-world examples to help you enhance your skills.

Goodluck, You're good to go :)
