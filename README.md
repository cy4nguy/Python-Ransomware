<head><meta name="google-site-verification" content="it2bAv6scwvZZ_b9HaZpANvjOjkmASVEjloeUnVLtcA" /></head>

# Python-Ransomware

Complete Python RansomeWare Source Code With Full Decoumetions.

<pre>
   ____ ____ _  _ ____ ____ _  _ _ _ _ ____ ____ ____  ___  _   _ 
   |__/ |__| |\ | [__  |  | |\/| | | | |__| |__/ |___  |__]  \_/  
   |  \ |  | | \| ___] |__| |  | |_|_| |  | |  \ |___ .|      |   
</pre>


About: This is a Classic Example Of RansomWare Written in python.<br>
Tested On: Windows 10 / Windows7 <br>
Suport : +Windows7 <br>
Date of Publish : 10/31/2019 <br>
Last Update : 11/3/2019 <br>
Went Find out about what is Ransomware<br>

<pre>   When Find out about what is Ransomware ? -> <a href="https://en.wikipedia.org/wiki/Ransomware">Click Hare</a> <- </pre><br><br>



To Convet the .py to exe You can use <a href="https://www.pyinstaller.org">pyinstaller</a>.<br>
To install pyinstaller: <code>https://www.pyinstaller.org</code><br>
To Convet .py File to exe : <code>pyinstaller --onefile -w --icon YourIcon.ico Ransomware.py </code><br>
<b>Before Converting File to exe Run :</b> <code>pip install --user --requirement requirements.txt</code>
# To Decrypt Files :
Run DeRansomware.py On line 29 From : 
<img src="https://github.com/cy4nguy/Python-Ransomware/blob/master/R7.png?raw=true"></img><br>
To Your Key (example):<br>
<code><pre><br>
                Key     = b"\xbd\xb6\x80'4z\x9c\xb53{\xe3\xd7\xf4\xc2\\\x08\xbd\xbb\xdb\xd6\xb2.\xfa\xe1o\x1f\xcd\x80AM\xd5>"<br>
</code></pre><br>
OR :<br>
<code><pre><br>
                Key     = b'T\xb5\xc4\x14\xe4\xa7\x18\x0b8T\xdb\xec\xf0.v>t\xce\x91w5y1\xce\xa3\x1a;J<SKD'<br>
</code></pre><br>
Replace Key Betwen " " or ' ' with your own key<br>

# Change Log

<b>(11/3/2019) Change_log:<br><br></b>
<li>Switching from cryptography Lib to pynacl.<br></li>
<li>Adding Decryptor script for Batter File decryption<br><br></li>
<b>Path Note:</b> So on my research, i found out that pynacl  <br>
is faster and stronger it is using <a href="https://en.wikipedia.org/wiki/Salsa20">Salsa20 stream cipher</a>
algorithm, and if your using old version I recommend  you 
to switch from it because This version use More secure encryption<br>
~ More updates or in the way :)<br>


#
<br><li>P.S: This is just Concept and its still work in the progress</li>
<b>NOTE: THIS SOURCE CODE IS For Educational Purposes Only.<br>
IM NOT RESBONBLE FOR ANY BAD & MALICIOUS USE OF IT.</b>
