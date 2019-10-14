```
root@kali:~# pwd
/root
root@kali:~# cd ..
root@kali:/# pwd
/
root@kali:/# ^c
bash: :s^c: substitution failed
root@kali:/# ls
0     dev   initrd.img      lib32   lost+found  opt   run   sys  var
bin   etc   initrd.img.old  lib64   media       proc  sbin  tmp  vmlinuz
boot  home  lib             libx32  mnt         root  srv   usr  vmlinuz.old
root@kali:/# 
```

### 測驗:說明底下程式的意義
```
root@kali:/bin# cd .. <==回到上一層目錄
root@kali:/# cd       <==變換目錄
root@kali:~# 
```

