# Made by NeatPlaysAlt
# Neatnet@mail.com - [Email]
# padlad256@gmail.com - [Alternative Email]
# NeatPlaysAlt#0001 - [Discord]
# @WhitakerF18 - [Instagram]
# WhitakerF18 - [Snapchat]
# padlad256 - [facebook]

import os

def space():
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    print(" ")
def recall():
    ans3 = input("Would you like to do anything else? \n")
    if ans3=="yes":
        space()
        space()
        space()
        start()
    elif ans3=="Yes":
        space()
        space()
        space()
        start()
    elif ans3=="yEs":
        space()
        space()
        space()
        start()
    elif ans3=="yeS":
        space()
        space()
        space()
        start()
    elif ans3=="YEs":
        space()
        space()
        space()
        start()
    elif ans3=="YES":
        space()
        space()
        space()
        start()
    elif ans3=="yES":
        space()
        space()
        space()
        start()
    elif ans3=="yes":
        space()
        space()
        space()
        start()
    elif ans3=="Ye":
        space()
        space()
        space()
        start()
    elif ans3=="YE":
        space()
        space()
        space()
        start()
    elif ans3=="yE":
        space()
        space()
        space()
        start()
    elif ans3=="ye":
        space()
        space()
        space()
        start() 
    else:
        exit()
def qwertyuiop():
    q1 = input("Are you sure you want to bsod? [y/n]")
    if q1 == "y":
        bsod()
    else:
        exit()





def bsod():
    from ctypes import windll
    from ctypes import c_int
    from ctypes import c_uint
    from ctypes import c_ulong
    from ctypes import POINTER
    from ctypes import byref

    nullptr = POINTER(c_int)()

    windll.ntdll.RtlAdjustPrivilege(
        c_uint(19), 
        c_uint(1), 
        c_uint(0), 
        byref(c_int())
    )

    windll.ntdll.NtRaiseHardError(
        c_ulong(0xC000007B), 
        c_ulong(0), 
        nullptr, 
        nullptr, 
        c_uint(6), 
        byref(c_uint())
    )


def start():
    print("\n{>What would you like to do?<} \n")
    print("1. Shutdown Computer")
    print("2. Restart Computer")
    print("3. Log Out")
    print("4. Open A Webpage")
    print("5. Open An App")
    print("6. Flush DNS")
    print("7. Clear Temp Files")
    print("8. Renew IP")
    print("9. Trigger BSOD")
    print("10. Open Bin")
    print("11. Repair Files")
    print("12. Disk Cleanup")
    print("13. Computer Info")
    print("14. View Installed Apps")
    print("15. Exit")
    print("16. Credits")
    print(end="\n Enter Your Choice: ")
    choice = int(input())
    import os
    if choice==1:
        ans4 = input("Are you sure you want to Shutdown? \n")
        if ans4=="yes":
            os.system("shutdown /s /t 0")
        elif ans4=="Yes":
            os.system("shutdown /s /t 0")
        elif ans4=="yEs":
            os.system("shutdown /s /t 0")
        elif ans4=="yeS":
            os.system("shutdown /s /t 0")
        elif ans4=="YEs":
            os.system("shutdown /s /t 0")
        elif ans4=="YES":

            os.system("shutdown /s /t 0")
        elif ans4=="yES":
            os.system("shutdown /s /t 0")
        elif ans4=="yes":
            os.system("shutdown /s /t 0")
        elif ans4=="Ye":
            os.system("shutdown /s /t 0")
        elif ans4=="YE":
            os.system("shutdown /s /t 0")
        elif ans4=="yE":
            os.system("shutdown /s /t 0")
        elif ans4=="ye":
            os.system("shutdown /s /t 0")
        else:
            print("\n|------------------|")
            print("|Shutdown Cancelled|")
            print("|------------------| \n")
            space()
            space()
            space()
            start()
    elif choice==2:
        ans4 = input("Are you sure you want to restart? \n")
        if ans4=="yes":
            os.system("shutdown /r /t 0")
        elif ans4=="Yes":
            os.system("shutdown /r /t 0")
        elif ans4=="yEs":
            os.system("shutdown /r /t 0")
        elif ans4=="yeS":
            os.system("shutdown /r /t 0")
        elif ans4=="YEs":
            os.system("shutdown /r /t 0")
        elif ans4=="YES":
            os.system("shutdown /r /t 0")
        elif ans4=="yES":
            os.system("shutdown /r /t 0")
        elif ans4=="yes":
            os.system("shutdown /r /t 0")
        elif ans4=="Ye":
            os.system("shutdown /r /t 0")
        elif ans4=="YE":
            os.system("shutdown /r /t 0")
        elif ans4=="yE":
            os.system("shutdown /r /t 0")
        elif ans4=="ye":
            os.system("shutdown /r /t 0")
        else:
            print("\n|-----------------|")
            print("|Restart Cancelled|")
            print("|-----------------| \n")
            space()
            space()
            space()
            start()
    elif choice==3:
        ans4 = input("Are you sure you want to log out? \n")
        if ans4=="yes":
            import os
            os.system("shutdown -l")
        elif ans4=="Yes":
            import os
            os.system("shutdown -l")
        elif ans4=="yEs":
            import os
            os.system("shutdown -l")
        elif ans4=="yeS":
            import os
            os.system("shutdown  -l")
        elif ans4=="YEs":
            import os
            os.system("shutdown  -l")
        elif ans4=="YES":
            import os
            os.system("shutdown  -l")
        elif ans4=="yES":
            import os
            os.system("shutdown  -l")
        elif ans4=="Ye":
            import os
            os.system("shutdown  -l")
        elif ans4=="YE":
            import os
            os.system("shutdown -l")
        elif ans4=="yE":
            import os
            os.system("shutdown -l")
        elif ans4=="ye":
            import os
            os.system("shutdown -l")
        else:
            print("\n|----------------|")
            print("|Logout Cancelled|")
            print("|----------------| \n")
            space()
            space()
            space()
            start()
        os.system("shutdown -1")
    elif choice==4:
        ans1 = input("what webpage would you like to open? \n")
        import webbrowser
        webbrowser.open(ans1)
        recall()
    elif choice==5:
        ans2 = input("what app would you like to open? \n")
        import os
        recall()

        os.system(ans2)
    elif choice==6:
        ans4 = input("Are you sure you want to flush DNS? \n")
        if ans4=="yes":
            import os
            os.system('cmd /c "ipconfig/flushdns"')
            recall()
        elif ans4=="Yes":
            import os
            os.system('cmd /c "ipconfig/flushdns"')
            recall()
        elif ans4=="yEs":
            import os
            os.system('cmd /c "ipconfig/flushdns"')
            recall()
        elif ans4=="yeS":
            import os
            os.system('cmd /c "ipconfig/flushdns"')
            recall()
        elif ans4=="YEs":
            import os
            os.system('cmd /c "ipconfig/flushdns"')
            recall()
        elif ans4=="YES":
            import os
            os.system('cmd /c "ipconfig/flushdns"')
            recall()
        elif ans4=="yES":
            import os
            os.system('cmd /c "ipconfig/flushdns"')
            recall()
        elif ans4=="yes":
            import os
            os.system('cmd /c "ipconfig/flushdns"')
            recall()
        elif ans4=="Ye":
            import os
            os.system('cmd /c "ipconfig/flushdns"')
            recall()
        elif ans4=="YE":
            import os
            os.system('cmd /c "ipconfig/flushdns"')
            recall()
        elif ans4=="yE":
            import os
            os.system('cmd /c "ipconfig/flushdns"')
            recall()
        elif ans4=="ye":
            import os
            os.system('cmd /c "ipconfig/flushdns"')
            space()
            space()
            space()
            recall()
        else:
            print("\n|---------------|")
            print("|Flush Cancelled|")
            print("|---------------| \n")
            start()
    elif choice==7:
        ans4 = input("Are you sure you want to delete temp data? \n")
        if ans4=="yes":
            import os
            os.system('cmd /c " del /q /f /s %temp%\*"')
            recall()
        elif ans4=="Yes":
            import os
            os.system('cmd /c " del /q /f /s %temp%\*"')
            recall()
        elif ans4=="yEs":
            import os
            os.system('cmd /c " del /q /f /s %temp%\*"')
            recall()
        elif ans4=="yeS":
            import os
            os.system('cmd /c " del /q /f /s %temp%\*"')
            recall()
        elif ans4=="YEs":
            import os
            os.system('cmd /c " del /q /f /s %temp%\*"')
            recall()
        elif ans4=="YES":
            import os
            os.system('cmd /c " del /q /f /s %temp%\*"')
            recall()
        elif ans4=="yES":
            import os
            os.system('cmd /c " del /q /f /s %temp%\*"')
            recall()
        elif ans4=="yes":
            import os
            os.system('cmd /c " del /q /f /s %temp%\*"')
            recall()
        elif ans4=="Ye":
            import os
            os.system('cmd /c " del /q /f /s %temp%\*"')
            recall()
        elif ans4=="YE":
            import os
            os.system('cmd /c " del /q /f /s %temp%\*"')
            recall()
        elif ans4=="yE":
            import os
            os.system('cmd /c " del /q /f /s %temp%\*"')
            recall()
        elif ans4=="ye":
            import os
            os.system('cmd /c " del /q /f /s %temp%\*"')
            recall()
        else:
            print("\n|--------------------|")
            print("|Temp Clear Cancelled|")
            print("|--------------------| \n")
            space()
            space()
            space()
            start()
    elif choice==8:
        ans4 = input("Are you sure you want to renew your IP?, if it releases but doesn't renew, your file system may become corrupt \n")
        if ans4=="yes":
            import os
            os.system('cmd /c "ipconfig /release & ipconfig /renew"')
            recall()
        elif ans4=="Yes":
            import os
            os.system('cmd /c "ipconfig /release & ipconfig /renew"')
            recall()
        elif ans4=="yEs":
            import os
            os.system('cmd /c "ipconfig /release & ipconfig /renew"')
            recall()
        elif ans4=="yeS":
            import os
            os.system('cmd /c "ipconfig /release & ipconfig /renew"')
            recall()
        elif ans4=="YEs":
            import os
            os.system('cmd /c "ipconfig /release & ipconfig /renew"')
            recall()
        elif ans4=="YES":
            import os
            os.system('cmd /c "ipconfig /release & ipconfig /renew"')
            recall()
        elif ans4=="yES":
            import os
            os.system('cmd /c "ipconfig /release & ipconfig /renew"')
            recall()
        elif ans4=="yes":
            import os
            os.system('cmd /c "ipconfig /release & ipconfig /renew"')
            recall()
        elif ans4=="Ye":
            import os
            os.system('cmd /c "ipconfig /release & ipconfig /renew"')
            recall()
        elif ans4=="YE":
            import os
            os.system('cmd /c "ipconfig /release & ipconfig /renew"')
            recall()
        elif ans4=="yE":
            import os
            os.system('cmd /c "ipconfig /release & ipconfig /renew"')
            recall()
        elif ans4=="ye":
            import os
            os.system('cmd /c "ipconfig /release & ipconfig /renew"')
            recall()
        else:
            print("\n|---------------|")
            print("|Renew Cancelled|")
            print("|---------------| \n")
            space()
            space()
            space()
            start()
    elif choice==9:
        ans4 = input("Are You Sure you wanna trigger A blue screen of death?, This could break your PC \n")
        if ans4=="yes":
            qwertyuiop()
        elif ans4=="Yes":
            qwertyuiop()
        elif ans4=="yEs":
            qwertyuiop()
        elif ans4=="yeS":
            qwertyuiop()
        elif ans4=="YEs":
            qwertyuiop()
        elif ans4=="YES":
            qwertyuiop()
        elif ans4=="yES":
            qwertyuiop()
        elif ans4=="yes":
            qwertyuiop()
        elif ans4=="Ye":
            qwertyuiop()
        elif ans4=="YE":
            qwertyuiop()
        elif ans4=="yE":
            qwertyuiop()
        elif ans4=="ye":
            qwertyuiop()
        else:
            print("\n|------------|")
            print("|BSOD Aborted|")
            print("|------------| \n")
            space()
            space()
            space()
            start()
    elif choice==10:
        ans4 = input("Are you sure you want to open the bin? [it may be a bit smelly] \n")
        if ans4=="yes":
            import os
            os.system('cmd /c "start shell:RecycleBinFolder"')
            recall()
        elif ans4=="Yes":
            import os
            os.system('cmd /c "start shell:RecycleBinFolder"')
            recall()
        elif ans4=="yEs":
            import os
            os.system('cmd /c "start shell:RecycleBinFolder"')
            recall()
        elif ans4=="yeS":
            import os
            os.system('cmd /c "start shell:RecycleBinFolder"')
            recall()
        elif ans4=="YEs":
            import os
            os.system('cmd /c "start shell:RecycleBinFolder"')
            recall()
        elif ans4=="YES":
            import os
            os.system('cmd /c "start shell:RecycleBinFolder"')
            recall()
        elif ans4=="yES":
            import os
            os.system('cmd /c "start shell:RecycleBinFolder"')
            recall()
        elif ans4=="yes":
            import os
            os.system('cmd /c "start shell:RecycleBinFolder"')
            recall()
        elif ans4=="Ye":
            import os
            os.system('cmd /c "start shell:RecycleBinFolder"')
            recall()
        elif ans4=="YE":
            import os
            os.system('cmd /c "start shell:RecycleBinFolder"')
            recall()
        elif ans4=="yE":
            import os
            os.system('cmd /c "start shell:RecycleBinFolder"')
            recall()
        elif ans4=="ye":
            import os
            os.system('cmd /c "start shell:RecycleBinFolder"')
            recall()
        else:
            print("\n|------------------|")
            print("|Bin Open Cancelled|")
            print("|------------------| \n")
            space()
            space()
            space()
            start()
    elif choice==11:
        ans4 = input("Are you sure you want to Scan & Repair your files? \n")
        if ans4=="yes":
            import os
            os.system('cmd /k "sfc /scannow"')
            recall()
        elif ans4=="Yes":
            import os
            os.system('cmd /k "sfc /scannow"')
            recall()
        elif ans4=="yEs":
            import os
            os.system('cmd /k "sfc /scannow"')
            recall()
        elif ans4=="YEs":
            import os
            os.system('cmd /k "sfc /scannow"')
            recall()
        elif ans4=="yES":
            import os
            os.system('cmd /k "sfc /scannow"')
            recall()
        elif ans4=="yes":
            import os
            os.system('cmd /k "sfc /scannow"')
            recall()
        elif ans4=="Ye":
            import os
            os.system('cmd /k "sfc /scannow"')
            recall()
        elif ans4=="YE":
            import os
            os.system('cmd /k "sfc /scannow"')
            recall()
        elif ans4=="yE":
            import os
            os.system('cmd /k "sfc /scannow"')
            recall()
        elif ans4=="ye":
            import os
            os.system('cmd /k "sfc /scannow"')
            recall()
        else:
            print("\n|----------------|")
            print("|Repair Cancelled|")
            print("|----------------| \n")
            space()
            space()
            space()
            start()
    elif choice==12:
        ans4 = input("Are you sure you want to open the disk cleanup? \n")
        if ans4=="yes":
            import os
            os.system('cmd /c "cleanmgr.exe /sageset:112"')
            recall()
        elif ans4=="Yes":
            import os
            os.system('cmd /c "cleanmgr.exe /sageset:112"')
            recall()
        elif ans4=="yEs":
            import os
            os.system('cmd /c "cleanmgr.exe /sageset:112"')
            recall()
        elif ans4=="yeS":
            import os
            os.system('cmd /c "cleanmgr.exe /sageset:112"')
            recall()
        elif ans4=="YEs":
            import os
            os.system('cmd /c "cleanmgr.exe /sageset:112"')
            recall()
        elif ans4=="YES":
            import os
            os.system('cmd /c "cleanmgr.exe /sageset:112"')
            recall()
        elif ans4=="yes":
            import os
            os.system('cmd /c "cleanmgr.exe /sageset:112"')
            recall()
        elif ans4=="Ye":
            import os
            os.system('cmd /c "cleanmgr.exe /sageset:112"')
            recall()
        elif ans4=="YE":
            import os
            os.system('cmd /c "cleanmgr.exe /sageset:112"')
            recall()
        elif ans4=="yE":
            import os
            os.system('cmd /c "cleanmgr.exe /sageset:112"')
            recall()
        elif ans4=="ye":
            import os
            os.system('cmd /c "cleanmgr.exe /sageset:112"')
            recall()
            
        else:
            print("\n|----------------------|")
            print("|Disk Cleanup Cancelled|")
            print("|----------------------| \n")
            space()
            space()
            space()
            start()
    elif choice==13:
        ans4 = input("Are you sure you want to view senstive system information? \n")
        if ans4=="yes":
            import os
            os.system('cmd /k "ipconfig /all"')
            recall()
        elif ans4=="Yes":
            import os
            os.system('cmd /k "ipconfig /all"')
            recall()
        elif ans4=="yEs":
            import os
            os.system('cmd /k "ipconfig /all"')
            recall()
        elif ans4=="yeS":
            import os
            os.system('cmd /k "ipconfig /all"')
            recall()
        elif ans4=="YEs":
            import os
            os.system('cmd /k "ipconfig /all"')
            recall()
        elif ans4=="YES":
            import os
            os.system('cmd /k "ipconfig /all"')
            recall()
        elif ans4=="yES":
            import os
            os.system('cmd /k "ipconfig /all"')
            recall()
        elif ans4=="yes":
            import os
            os.system('cmd /k "ipconfig /all"')
            recall()
        elif ans4=="Ye":
            import os
            os.system('cmd /k "ipconfig /all"')
            recall()
        elif ans4=="YE":
            import os
            os.system('cmd /k "ipconfig /all"')
            recall()
        elif ans4=="yE":
            import os
            os.system('cmd /k "ipconfig /all"')
            recall()
        elif ans4=="ye":
            import os
            os.system('cmd /k "ipconfig /all"')
            recall()
            
        else:
            print("\n|-------------------|")
            print("|View Info Cancelled|")
            print("|-------------------| \n")
            space()
            space()
            space()
            start()
    elif choice==14:
        ans4 = input("Are you sure you want to view installed apps? \n")
        if ans4=="yes":
            import os
            os.system('cmd /k "wmic product get name"')
            recall()
        elif ans4=="Yes":
            import os
            os.system('cmd /k "wmic product get name"')
            recall()
        elif ans4=="yEs":
            import os
            os.system('cmd /k "wmic product get name"')
            recall()
        elif ans4=="yeS":
            import os
            os.system('cmd /k "wmic product get name"')
            recall()
        elif ans4=="YEs":
            import os
            os.system('cmd /k "wmic product get name"')
            recall()
        elif ans4=="YES":
            import os
            os.system('cmd /k "wmic product get name"')
            recall()
        elif ans4=="yES":
            import os
            os.system('cmd /k "wmic product get name"')
            recall()
        elif ans4=="yes":
            import os
            os.system('cmd /k "wmic product get name"')
            recall()
        elif ans4=="Ye":
            import os
            os.system('cmd /k "wmic product get name"')
            recall()
        elif ans4=="YE":
            import os
            os.system('cmd /k "wmic product get name"')
            recall()
        elif ans4=="yE":
            import os
            os.system('cmd /k "wmic product get name"')
            recall()
        elif ans4=="ye":
            import os
            os.system('cmd /k "wmic product get name"')
            recall()
            
        else:
            print("\n|--------------------|")
            print("|App Viewer Cancelled|")
            print("|--------------------| \n")
            space()
            space()
            space()
            start()
    elif choice==15:
        ans4 = input("Are you sure you want to exit \n")
        if ans4=="yes":
            exit()
        elif ans4=="Yes":
            exit()
        elif ans4=="yEs":
            exit()
        elif ans4=="yeS":
            exit()
        elif ans4=="YEs":
            exit()
        elif ans4=="YES":
            exit()
        elif ans4=="yES":
            exit()
        elif ans4=="yes":
            exit()
        elif ans4=="Ye":
            exit()
        elif ans4=="YE":
            exit()
        elif ans4=="yE":
            exit()
        elif ans4=="ye":
            exit()
        else:
            print("\n|--------------|")
            print("|Exit Cancelled|")
            print("|--------------| \n")
            space()
            space()
            space()
            start()
            
    elif choice==16:
        print("\n Made by NeatPlaysAlt")
        print("[Main Email] - Neatnet@mail.com")
        print("[Alt Email] - padlad256@gmail.com")
        print("[Discord] - ɴᴇᴀᴛᴘʟᴀʏsᴀʟᴛ#5937")
        print("[Snapchat] - @WhitakerF18")
        print("[Instagram] - @WhitakerF18")
        print("[Facebook] - @padlad256")
        from time import sleep
        sleep(10)
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        space()
        start()
        
    else:
        print("\n|---------------|")
        print("|Invalid Answer!|")
        print("|---------------| \n")
        from time import sleep
        sleep(2)
        space()
        space()
        space()
        start()
print("\n|-------------------------------|")
print("|>>>Welcome To System Options<<<|")
print("|-------------------------------| \n")
start()

# Made by NeatPlaysAlt
# Neatnet@mail.com - [Email]
# padlad256@gmail.com - [Alternative Email]
# NeatPlaysAlt#0001 - [Discord]
# @WhitakerF18 - [Instagram]
# WhitakerF18 - [Snapchat]
# padlad256 - [facebook]
