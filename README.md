# SmartCrypto
<br><br>
SmartView2 Handshake API implementation in pure python3 with an example of how to use the handshake to send commands to the TV

Works with Samsung Smart TV H/J (2014/2015) models using the SmartView2 Crypto Handshake C/Python implementation.

<br><br>

How to use:

go into smartcrypto.py and edit the ip address on line 15 to your tvs address <br>
run smartcrypto.py

After pairing it will print a ctx and session id 

On the last line of smartcrypto.py you can see the method send_command

If you save the ctx and sessionid from the previous pairing session you can write code to call send_command again without needing to repair. just use the ctx and session id from before.

This repo is in support mode and no longer being developed or maintained.<br> 
For better support consider trying out https://github.com/kdschlosser/samsungctl
   
Note: H & J series tv's cannot be turned on over the network so the on command will not work. 
