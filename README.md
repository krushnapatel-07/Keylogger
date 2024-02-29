# Keylogger

Keyloggers are programs that capture your key strokes. They can be used to keep logs of everything you press on the keyboard but on the flip side it can be used for malicious purposes as well.

This keylogger is a basic keylogger, that when explicitely called, captures your keystrokes and saves them in a file "keylogger.txt".
It then sends the contents of the file(i.e. the keystrokes) to your email id.

SYNTAX : python keylogger.py
Needed: pynput, smtplib, ssl
