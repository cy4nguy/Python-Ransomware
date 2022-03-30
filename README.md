# Python-Ransomware

Complete Python RansomeWare Source Code With Full Decoumetions.

~~~
   ____ ____ _  _ ____ ____ _  _ _ _ _ ____ ____ ____  ___  _   _ 
   |__/ |__| |\ | [__  |  | |\/| | | | |__| |__/ |___  |__]  \_/  
   |  \ |  | | \| ___] |__| |  | |_|_| |  | |  \ |___ .|      |   
~~~

| About: | Tested On: | Suport : | Publish : | Last Update : |
| :----- | :----- | :----- | :----- | :----- |
| RansomWare Written in python. | Windows 10 / Windows7 | + Windows7 | 10/31/2019 | 11/3/2019 |


Find out about what is Ransomware [Here](https://en.wikipedia.org/wiki/Ransomware)

## Installation

`pip install --user --requirement requirements.txt`

## Usage

- Convert `.py` File to `exe` : 

`pyinstaller --onefile -w --icon YourIcon.ico Ransomware.py`


### Decrypt Files :

Run `python DeRansomware.py`

### Encrypt Files :

Run `python Ransomware.py`

![](R7.png)

Key (example):

~~~
Key     = b"\xbd\xb6\x80'4z\x9c\xb53{\xe3\xd7\xf4\xc2\\\x08\xbd\xbb\xdb\xd6\xb2.\xfa\xe1o\x1f\xcd\x80AM\xd5>"<br>
~~~

OR :

~~~
Key     = b'T\xb5\xc4\x14\xe4\xa7\x18\x0b8T\xdb\xec\xf0.v>t\xce\x91w5y1\xce\xa3\x1a;J<SKD'<br>
~~~

Replace Key Betwen `" "` or `' '` with your own key



# Change Log

`Change_log (11/3/2019)` :

- Switching from cryptography Lib to pynacl.
- Adding Decryptor script for Batter File decryption
- Path Note: So on my research, i found out that pynacl is faster and stronger it is using <a href="https://en.wikipedia.org/wiki/Salsa20">Salsa20 stream cipher</a>
algorithm, and if your using old version I recommend  you to switch from it because This version use More secure encryption ~ More updates on the way :)

### NOTE:

P.S: This is just Concept and its still work in the progress For Educational Purposes Only.
