
# IHxExec

POC to execute arbitrary code on behalf of another user. U can read more about the technique here:
- https://cicada-8.medium.com/process-injection-is-dead-long-live-ihxhelppaneserver-af8f20431b5d
- https://www.youtube.com/watch?v=bK3ufqZxkxc


Note the attached video:
- https://github.com/CICADA8-Research/IHxExec/blob/main/demo.mkv

# Usage 
```shell
.\IHxExec.exe -s <session> -c <target executable>

# Ex
  .\IHxExec.exe -s 1 -c c:/windows/system32/calc.exe
```
![explorer_DrFNrRODWT](https://github.com/user-attachments/assets/eb4c1786-585a-4c09-ad55-b979d1639db5)
