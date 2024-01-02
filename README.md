<h1>Keylogger⌨️</h1>


<h2>Description</h2>
In this demonstration, we will cover the basis of a keylogger and show how to open the source code, customize it, and deploy the keylogger to other computers, and have the logs automatically emailed to the address of your choosing.
<br />
<br/>**DISCLAIMER** This is strictly for education purposes only. Please dont use this for any malicious or ill intentions. Thank you.<br/>
<br />


<h2>Languages and Applications Used</h2>

- <b>Visual Studio Code</b> 
- <b>C+</b>
- <b>Python</b>

<h2>What is a Keylogger?</h2>

- A keylogger is a piece of software that reads and records keystrokes as input is entered on the keyboard. This software has alot of usage in cyber crime which is why this software is mostly frowned upon. This can record information typed such as login credentials,
payment information, web searches, and conversational information as well. There are other usage regarding monitoring employees or surveilling potential criminals. This software is a breach of privacy.

<h2>Program walk-through:</h2>

<p align="center">
First let us launch our code editor (Visual Studio Code) and create a new folder labeled "Keylogger". <br/>
<img src="https://i.imgur.com/cD5A2B0.png" height="80%" width="80%" alt="Keylogger"/>
<br />
<br />
From Here, create a new file called "keylogger.py". Now if you dont have the python extension added to your editor, please install.<br/>
<img src="https://i.imgur.com/0sRpndJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next we are going to install pynput. Pynput allows you monitor and control input devices. This will be the base of our keylogger.
Open your terminal and type "py -m pip install pynput". Hit enter.<br/>
<img src="https://i.imgur.com/IzUlbCn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now type the following syntax in your 'keylogger.py'. This is will give instructions to record any keystrokes and compile all recorded data
to a 'keyfile.txt' document.<br/>
<img src="https://i.imgur.com/GXquvnA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now that we have our base code completed, lets play our python. The play button is in the upper right side of the screen.<br/>
*Heads Up* Your computer might block you from running due to your Anti-Virus. If this does happen, you can allow it through your firewall options
but this is to your discretion. If so, please unallow after demonstration.<br/>
Now that our script is running, lets test it. Lets type 'Hello world' and see what happens.<br/>
<img src="https://i.imgur.com/ofoEzw3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
As you can see, the terminal is printing back what im typing and also a 'keyfile.txt' file was created to record our input.<br/>
<img src="https://i.imgur.com/DMSOL1G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now let's assume this was installed on a computer and someone didn't know. We can see personal information and gain access to things we aren't supposed to have.<br/>
<img src="https://i.imgur.com/avP6cQc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Thank you for checking out my keylogger demonstration and hope this was helpful and informational. Have a good day!<br/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
