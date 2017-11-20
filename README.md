#!/usr/bin/env python
# -*- coding: utf-8 -*-

import os
ascii = '\x1b[1;31m'##########################################################
ascii +='                                                               \r\n'#
ascii +='   ██████  ███▄ ▄███▓ ██▓  ██████  ██░ ██ ▓█████ ▓█████▄         \r\n'#
ascii +=' ▒██    ▒ ▓██▒▀█▀ ██▒▓██▒▒██    ▒ ▓██░ ██▒▓█   ▀ ▒██▀ ██▌       \r\n'#
ascii +=' ░ ▓██▄   ▓██    ▓██░▒██▒░ ▓██▄   ▒██▀▀██░▒███   ░██   █▌         \r\n'#
ascii +='   ▒   ██▒▒██    ▒██ ░██░  ▒   ██▒░▓█ ░██ ▒▓█  ▄ ░▓█▄   ▌         \r\n'#
ascii +=' ▒██████▒▒▒██▒   ░██▒░██░▒██████▒▒░▓█▒░██▓░▒████▒░▒████▓       \r\n'#
ascii +=' ▒ ▒▓▒ ▒ ░░ ▒░   ░  ░░▓  ▒ ▒▓▒ ▒ ░ ▒ ░░▒░▒░░ ▒░ ░ ▒▒▓  ▒       \r\n'#
ascii +=' ░ ░▒  ░ ░░  ░      ░ ▒ ░░ ░▒  ░ ░ ▒ ░▒░ ░ ░ ░  ░ ░ ▒  ▒       \r\n'#
ascii +=' ░  ░  ░  ░      ░    ▒ ░░  ░  ░   ░  ░░ ░   ░    ░ ░  ░       \r\n'#
ascii +='       ░         ░    ░        ░   ░  ░  ░   ░  ░   ░          \r\n'#
ascii +='                                   SMiSHED KiT v1 ░            \r\n'#
ascii +=' [1] Twilio SMS                                                \r\n'#
ascii +=' [2] HLR Lookup                                                \r\n'#
ascii +=' [3] Phone Generator                                           \r\n'# 
ascii +=' [4] EXIT                                                      \r\n'#
ascii +='                                                               \r\n'#
ascii +=' ~[  CAPTAIN! What bait are we phishing with today?  ]~        \r\n'#     
ascii +='\x1b[0m'#############################################################      
print ascii
method = raw_input("> ")

if method=='4':
    exit()
elif method=='3':
                # ask what prefix to generate (e.x. 1905344)
    os.system() # write to 2nd line of /phonegen/prefix.txt
    os.system(python /SMS/phonegen/phonegen.py)
elif method=='2':
    os.system() # run the hlrlookup agaisnt /sms/phonegen/wordlist.txt
elif method=='1':
    os.system() # run twilio, ask what message, send message to cleanphonelist.txt
else:
    print "[-] \x1b[0;31mInvalid method\x1b[0m"
    exit()                              
