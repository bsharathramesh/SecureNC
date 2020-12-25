README FILE:
------------

Operating System Used:
Ubuntu 18.04

Programming Language Used:
Python 3.6.9

Packages to install:
sudo apt install python3-pip
pip3 install pycryptodome

Give permission:
chmod 777 snc

Command to run Client and Server:

[client]$ ./snc --key CSC574ISAWESOME server.add.ress 9999 < some-file.txt
[server]$ ./snc --key CSC574ISAWESOME -l 9999 > some-file.txt

Two way Bidirectional
[client]$ ./snc --key CSC574ISAWESOME server.add.ress 9999 < file1-in.txt > file2-out.txt
[server]$ ./snc --key CSC574ISAWESOME -l 9999 > file1-out.txt < file2-in.txt

REFERENCE:
---------

1. https://www.pycryptodome.org/en/latest/
2. https://www.pycryptodome.org/en/latest/src/api.html
3. https://www.pycryptodome.org/en/latest/src/vs_pycrypto.html
4. https://www.pycryptodome.org/en/latest/src/examples.html# SecureNC
Secure NC, providing confidentiality integrity and Authentication for NC
