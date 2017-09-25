### **string2opcode.py**

> Usage:
```
[*] Convert string to Opcode (v1.0)
[*] Author Amonsec

[*] Usage: python string2opcode.py [options] <values>
[*] Options: 
	 -f; --file	 Convert string(s) in a given file
	 -r; --raw	 Convert the given string in argument

[*] Usage Examples: 
	 python string2opcode.py --file test.txt
	 python string2opcode.py --file /root/Desktop/test.txt
	 python string2opcode.py --raw lulzing
	 python string2opcode.py --raw 'Opcode to OP'

[*] Badchars Examples: 
	 Badchars: \x41
	 Badchars: \x00\x0a\x0d\x20
```

> Example:
```
root@ths-amonsec:~/Desktop# python string2opcode.py --raw 'Opcode for lulz'
[*] Convert string to Opcode (v1.0)
[*] Author Amonsec

[*] Badchars: \x65
[+] Hexchain lenght: 32 bytes
[+] Hexchain: :

207a6c756c20726f662065646f63704f

[+] Your Opcode: 

push 207a6c75 ;  zlu
push 6c20726f ; l ro
push 66206564 ; f ed
push 6f63704f ; ocpO

[-] Badchars detected: \x65
[*] Have Fun 1337
root@ths-amonsec:~/Desktop# 
```