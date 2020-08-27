
GNU nano 5.2        terkey.py
import os
from time import sleep


a ='\033[92m'
b ='\033[91m'
c ='\033[0m'

def setup():
    try:
        os.mkdir('/data/data/com.termux/files/hom>
    except:
        pass
    key = "extra-keys = [['ESC','/','-','HOME','U>
    open('/data/data/com.termux/files/home/.termu>
    os.system('termux-reload-settings')


def banner():
    os.system('clear')
    print(a+'Shortcut for help you'.center(40))
    print(b+'YT-Real Videoos'.center(40))
    print("".join([i for i in "\n"*3]))



if __name__=='__main__':
    banner()
    from threading import Thread as td
    t = td(target=setup)
    t.start()
    while t.is_alive():
        for i in "-\|/-\|/":
            print('\rPlease wait '+i+' ',end="",f>
            sleep(0.1)
    banner()
    print(c+'selamat mencoba'+a+'jangan lupa like>
