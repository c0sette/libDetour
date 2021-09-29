# libDetour
- Detour for hooking

- SigScan.h for scan Pattern

```
DWORD func_Addr = 0;
SigScan scan;
func_Addr = scan.FindPattern("program_name.exe","",""); //Using SigMaker to get code pattern
```


