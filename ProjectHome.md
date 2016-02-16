fbootloader is a bluetooth experiment with Nokia Symbian Operating System and PC Interface. It is pretty useful for communicating bluetooth as "serial" protocol, this is enables you to sending/receiving data via bluetooth in "RAW" format and/or "HEX" format. also you available to access fs in phone and control it remotely.

we are working to communicating smartphone via GPRS packet data, it's pros&cons here:

pros:
-communicate with phone anywhere and anytime without starting the firstboot application (server).
-with using GPRS, the Bluetooth port will be free and usable and you also send specific command of Bluetooth protocol and you can handle the Bluetooth port.
-you can get the phone's location information,camera lens,speaker and microphone,personal data such as messaging - contacts - scheduler etc.. anywhere and speedly,if you want to use your browser instead of serial communicator client (fbootloader-client) you can configure phone settings to creating virtual httpd server and switch the "socket bootloader executable" instead of "serial bootloader executable" -> (fbootloader-serial and fbootloader-socket)

cons:
-high usage packet data can be expensive, so if your mobile operator provide you economic www packages, you may use it.
-pretty good battery killer. you must have great battery or create your solutions such as connecting many batteries in a auto battery switcher hub... (this works in this sequence: if active battery's current lesser than x amper, then automatically switch the next battery, ... )
-if the connection is drops before "terminating" the active connection, phone side still stay conneccted in internet and this is probably cause high cost of gprs usage.


current versions:

fbootloader-client (C Sharp): v0.97
fbootloader-client (Python 2.x) : v0.11
fbootloader-server-serial (mShell 3.x) : v0.97
fbootloader-server-socket (mShell 3.x) : v0.00

by fatalblade