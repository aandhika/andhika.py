# andhika.py

import random
import sys
import time
def mengetik(s):
    for c in s + '\n':
        sys.stdout.write(c)
        sys.stdout.flush()
        time.sleep(random.random() * 0.1)
mengetik("[<^><^><^><^><^><^><^><^><^><^><^><^><^><^><^>]")

import os
import sys

def main():
	os.system("figlet andhika")
	banner="""
	
	[=================]
	[+]owner : andhika
	[+]tgl        : 29/04/25
	[=================]
	"""
	print(banner)
	
main()

def menu():
	print(""" 
       1.clear
	2.tokopedia
	3.hack cam
	0.exit 
	""")
	
menu()
pilih = raw_input("nomor : ")
if pilih =="":
	print "pilihan tidak ada"
	os.system("")
	
if pilih =="1":
	print "membersihkan"
	os.system("clear")
	exit()
if pilih =="2":
    os.system("clear")
    print "menginstall"
    os.system("")
    os.system("")
    os.system("")
    os.system("")
    os.system("")
    os.system("")
    os.system("")
    
if pilih =="3":
    os.system("clear")
    print "menginstall"
    os.system("")
    os.system("")
    os.system("")
    os.system(")
    os.system("")
    os.system(")
    os.system("")
    
if pilih =="0":
    print "mau keluar makan coki coki"
    os.system("exit")
