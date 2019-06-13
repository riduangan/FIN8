# FIN8
Hacker Group using ShellTea malwares


ShellTea looks for explorer.exe process in multiple ways to find the process id of the current desktop window. Once it locates the process id it uses standard functions to write within the memory of explorer.

According to researchers following are the list of the process it searched for 
WINDBG.EXE, WIRESHARK.EXE, PROCEXP.EXE, PROCMON.EXE, TCPVIEW.EXE,
OLLYDBG.EXE, IDAG.EXE, IDAG64.EXE, DUMPCAP.EXE, FILEMON.EXE, IDAQ64.EXE, IDAQ.EXE,
IMMUNITYDEBUGGER.EXE, PETOOLS.EXE, REGMON.EXE, SYSER.EXE, TCPDUMP.EXE,
WINDUMP.EXE, APIMONITOR.EXE, APISPY32.EXE, IRIS.EXE, NETSNIFFER.EXE,
WINAPIOVERRIDE32.EXE, WINSPY.EXE
