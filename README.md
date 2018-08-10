# wP-BrutE

BruteForce WordPress with script BASH, These tools automatically will get the username and password generate.

You can change/add any kind of password that I created

```
admin@zerobyte.id:~/wP-BrutE$ cat Generate.txt
1
12
123
1234
12345
123456
1234567
12345678
123##@@
.....
```

And you can also add my wordlist
```
admin@zerobyte.id:~/wP-BrutE$ cat password/Password-World.txt
123456
password
12345678
qwerty
123456789
12345
1234
111111
.....
```

How to use?
```
admin@zerobyte.id:~$ git clone https://github.com/zerobyte-id/wP-BrutE.git
admin@zerobyte.id:~/wP-BrutE$ cd wP-BrutE
admin@zerobyte.id:~/wP-BrutE$ chmod +x exploit.sh && ./exploit.sh list.txt
```
