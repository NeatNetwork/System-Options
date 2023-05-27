# Made by NeatPlaysAlt
# [Email] - info@neatnet.org
# [Discord] - NeatPlaysAlt#8111
# [Instagram] - @neatnetwork

################################ Help1 Function ##########################################

def help1():
    input("[System Options Ver 1.30]\n>Press enter to continue<")
    print("\nSystem options is a project designed to help you")
    print("have more control over your computer. an explanation ")
    print("of what each option does are as follows;")
    print("--------------------")
    print("1. Shutdown Computer")
    print("shuts the computer down and stops the power to the")
    print("computer, you will have to turn it on manually afterwards")
    print("if you select this")
    print("--------------------")
    print("2. Restart Computer")
    print("restarts the computer down and stops the power to the")
    print("computer but then turns it on again automatically")
    print("if you select this you will be required to login again")
    print("--------------------")
    print("3. Log Out")
    print("logs you out of the computer")
    print("if you select this you will be required to login again")
    print("--------------------")
    print("4. Open A Webpage")
    print("asks you what website you want to go to and then opens")
    print("that website in the browser, the exact thing you typed")
    print("make sure you include http://www. or https://www. at the")
    print("beginning of the adress to make it work")
    print("--------------------")
    print("5. Open An App")
    print("asks you what app you want to go to and then opens")
    print("that app on your computer, if the name isn't the name")
    print("of the app then nothing will happen \n")
    print("-------------------------")
    print("Input \"home\" to go back")
    print("-------------------------\n")
    page1h = input(" Page 1 of 3 >\n")
    if page1h == ">":
        for i in range(3):
            space()
        help2()
    elif page1h == ">>":
        for i in range(3):
            space()
        help3()
    elif page1h.lower() == "home":
        for i in range(3):
            space()
        startpage1()
    elif page1h == "2":
        for i in range(3):
            space()
        help2()
    elif page1h == "3":
        for i in range(3):
            space()
        help3()
    else:
        print("\n /---------------\ ")
        print(" |Invalid Answer!| ")
        print(" \---------------/ \n")
        from time import sleep
        sleep(2)
        for i in range(3):
            space()
        help1()
################################ Help2 Function ##########################################

def help2():
    print("6. Flush DNS")
    print("clears residual data from your browser, from all time")
    print("and removes it permanently")
    print("--------------------")
    print("7. Clear Temp Files")
    print("gets rid of files in you computer which are stored")
    print("as residual data to make sure apps open quicker")
    print("choosing this will not break your computer.")
    print("--------------------")
    print("8. Renew IP")
    print("sends a request to the wifi you are on to give you a")
    print("new ip address on that network and will not affect your")
    print("connection but may temporarilaly disable it but it will come back")
    print("--------------------")
    print("9. Trigger BSOD")
    print("causes what you call a blue screen of death on your computer")
    print("which is the screen on your computer which is blue with a white")
    print("smily face when your computer crashes, this may get rid of unsaved data")
    print("--------------------")
    print("10. Open Bin")
    print("goes to the default bin directory on your computer where")
    print("deleted files are stored and can be recovered")
    print("this does not require admin permissions")
    print("-------------------------")
    print("Input \"home\" to go back")
    print("-------------------------\n")
    page2h = input("< Page 2 of 3 >\n")
    if page2h == ">":
        for i in range(3):
            space()
        help3()
    elif page2h == "<":
        for i in range(3):
            space()
        help1()
    elif page2h.lower() == "home":
        for i in range(3):
            space()
        startpage1()
    elif page1h == "1":
        for i in range(3):
            space()
        help1()
    elif page1h == "3":
        for i in range(3):
            space()
        help3()
    else:
        print("\n /---------------\ ")
        print(" |Invalid Answer!| ")
        print(" \---------------/ \n")
        from time import sleep
        sleep(2)
        for i in range(3):
            space()
        help2()
################################ Help3 Function ##########################################

def help3():
    print("11. Repair Files")
    print("this requires admin permissions and will scan your")
    print("computer for broken files and repairs them")
    print("--------------------")
    print("12. Disk Cleanup")
    print("opens a dialog box which will give you the option")
    print("to clear spare data that the computer doesn't need")
    print("this will just clear data and will not break anything")
    print("--------------------")
    print("13. Computer Info")
    print("opens command prompt and shows you information about")
    print("your computer and may or may not requre admin permissions")
    print("--------------------")
    print("14. View Installed Apps")
    print("also opens command prompt but shows you all of the apps which")
    print("are installed on your computer [even hidden apps]")
    print("this may or may not require admin permissions")
    print("--------------------")
    print("15. Exit")
    print("closes the system options program, to re open")
    print("system options, you will have o find where ever")
    print("you downloaded it to.")
    print("--------------------")
    print("16. Credits")
    print("shows credits for system options and details of")
    print("contact for contacting the owner of this to suggest")
    print("imporvements or to report bugs or send thanks etc.")
    print("-------------------------")
    print("Input \"home\" to go back")
    print("-------------------------\n")
    page3h = input("< Page 3 of 3 \n")
    if page3h == "<":
        for i in range(3):
            space()
        help2()
    elif page3h == "<<":
        for i in range(3):
            space()
        help1()
    elif page3h.lower() == "home":
        for i in range(3):
            space()
        startpage1()
    elif page1h == "2":
        for i in range(3):
            space()
        help2()
    elif page1h == "1":
        for i in range(3):
            space()
        help1()
    else:
        print("\n /---------------\ ")
        print(" |Invalid Answer!| ")
        print(" \---------------/ \n")
        from time import sleep
        sleep(2)
        for i in range(3):
            space()
        help3()
    
################################ Space Function ##########################################

def space():
    for i in range(68):
        print(" ")
################################ Recall Function ##########################################

def recall():
    ans3 = input("Would you like to do anything else? \n")
    if ans3.lower() == "yes":
        for i in range(4):
            space()
        startpage1()
    elif ans3.lower() == "ye":
        for i in range(4):
            space()
        startpage1()
    else:
        exit()
################################ Qtyuiop Function ##########################################

def qwertyuiop():
    q1 = input("Are you sure you want to bsod? [y/n]\n[This will crash your computer so make sure everything has been saved]\n")
    if q1 == "y":
        bsod()
    else:
        startpage1()

################################ Ver Function ##########################################

def ver():
    print("Version 1;")
    print("- Project started")
    print("09/08/2022")
    print("-----------------")
    print("Version 1.2;")
    print("- Added options 1-5")
    print("29/08/2022")
    print("-----------------")
    print("Version 2.0;")
    print("- Added options 6-10")
    print("20/09/2022")
    print("-----------------")
    print("Version 3.0;")
    print("- Added options 10-15")
    print("01/02/2023")
    print("-----------------")
    print("Version 4.0;")
    print("- Added option 16 (credits)")
    print("10/02/2023")
    print("-----------------")
    print("Version 5.0;")
    print("- Added toggleable menus")
    print("12/02/2023")
    print("-----------------")
    print("Version 5.1;")
    print("- Added fast toggle to menu")
    print("15/02/2023")
    print("-----------------")
    print("Version 5.2;")
    print("- Added This help menu")
    print("09/03/2023")
    print("-----------------")
    print("Version 6.0;")
    print("- Polished off bits and fixed menus")
    print("23/05/2023")
    input("\n---Press enter to return to start---")
    space()
    startpage1()
################################ BSOD Function ##########################################

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

##########################################################################################
#--------------------------------Start Page 1--------------------------------------------#
##########################################################################################
def startpage1():
    print("\n{>What would you like to do?<} \n")
    print("1. Shutdown Computer")
    print("2. Restart Computer")
    print("3. Log Out")
    print("4. Open A Webpage")
    print("5. Open An App")
    print("--------------------")
    print("       Page 1 >")
    print("{Use >> to quick toggle}")
    print(" ")
    print("<[?] for 1-5 help or [??] for all help>")
    print(" ")
    print(end="\n Enter Your Choice: ")
    choice = input()
    if choice == ">":
        space()
        startpage2()
    elif choice == ">>":
        space()
        startpage3()
    elif choice == "??":
        help1()
    elif choice == "?":
        input("[System Options Ver 1.30]\n>Press enter to continue<")
        print("\nSystem options is a project designed to help you")
        print("have more control over your computer. an explanation ")
        print("of what each option does are as follows;")
        print("--------------------")
        print("1. Shutdown Computer")
        print("shuts the computer down and stops the power to the")
        print("computer, you will have to turn it on manually afterwards")
        print("if you select this")
        print("--------------------")
        print("2. Restart Computer")
        print("restarts the computer down and stops the power to the")
        print("computer but then turns it on again automatically")
        print("if you select this you will be required to login again")
        print("--------------------")
        print("3. Log Out")
        print("logs you out of the computer")
        print("if you select this you will be required to login again")
        print("--------------------")
        print("4. Open A Webpage")
        print("asks you what website you want to go to and then opens")
        print("that website in the browser, the exact thing you typed")
        print("make sure you include http://www. or https://www. at the")
        print("beginning of the adress to make it work")
        print("--------------------")
        print("5. Open An App")
        print("asks you what app you want to go to and then opens")
        print("that app on your computer, if the name isn't the name")
        print("of the app then nothing will happen \n")
        a = input("\n>Press Enter to return<\n")
        space()
        startpage1()

    elif choice == "2":
        for i in range(3):
            space()
        startpage2()
    elif page1h == "3":
        for i in range(3):
            space()
        startpage3()
    
    ################################ V Shutdown V ##########################################
    elif choice=="1":
        ans4 = input("Are you sure you want to Shutdown? \n")
        if ans4.lower() == "yes":
            import os
            os.system("shutdown /s /t 0")
        elif ans4.lower() == "ye":
            import os
            os.system("shutdown /s /t 0")
        else:
            print("\n|------------------|")
            print("|Shutdown Cancelled|")
            print("|------------------| \n")
            for i in range(4):
                space()
                startpage1()
    ################################ V Restart V ##########################################
    elif choice=="2":
        ans4 = input("Are you sure you want to restart? \n")
        if ans4.lower() == "yes":
            import os
            os.system("shutdown /r /t 0")
        elif ans4.lower() == "ye":
            import os
            os.system("shutdown /r /t 0")
        else:
            print("\n|-----------------|")
            print("|Restart Cancelled|")
            print("|-----------------| \n")
            for i in range(3):
                space()
            startpage1()
    ################################ V Log Out V ##########################################
    if choice=="3":
        ans4 = input("Are you sure you want to log out? \n")
        if ans4.lower() == "yes":
            import os
            os.system("shutdown -l")
        elif ans4.lower() == "ye":
            import os
            os.system("shutdown -l")
        else:
            print("\n|----------------|")
            print("|Logout Cancelled|")
            print("|----------------| \n")
            for i in range(3):
                space()
            startpage1()
    ################################ V Website Open V ##########################################
    elif choice=="4":
        ans1 = input("what webpage would you like to open? \n")
        import webbrowser
        webbrowser.open(ans1)
        recall()
    ################################ V App Open V ##########################################
    elif choice=="5":
        ans2 = input("what app would you like to open? \n")
        import os
        os.system(ans2)
        recall()
    ################################ Startpage1 Else Statment ##########################################
    else:
        print("\n /---------------\ ")
        print(" |Invalid Answer!| ")
        print(" \---------------/ \n")
        from time import sleep
        sleep(2)
        for i in range(3):
            space()
        startpage1()
##########################################################################################
#--------------------------------Start Page 2--------------------------------------------#
##########################################################################################
def startpage2():
    print("\n{>What would you like to do?<} \n")
    print("6. Flush DNS")
    print("7. Clear Temp Files")
    print("8. Renew IP")
    print("9. Trigger BSOD")
    print("10. Open Bin")
    print("--------------------")
    print("       < Page 2 >")
    print(" ")
    print("<[?] for 6-10 help or [??] for all help>")
    print(" ")
    print(end="\n Enter Your Choice: ")
    choice = input()
    if choice == ">":
        space()
        startpage3()
    elif choice== "<":
        space()
        startpage1()
    elif choice == "??":
        help1()
    elif choice == "?":
        input("[System Options Ver 1.30]\n>Press enter to continue<")
        print("\nSystem options is a project designed to help you")
        print("have more control over your computer. an explanation ")
        print("of what each option does are as follows;")
        print("--------------------")
        print("6. Flush DNS")
        print("clears residual data from your browser, from all time")
        print("and removes it permanently")
        print("--------------------")
        print("7. Clear Temp Files")
        print("gets rid of files in you computer which are stored")
        print("as residual data to make sure apps open quicker")
        print("choosing this will not break your computer.")
        print("--------------------")
        print("8. Renew IP")
        print("sends a request to the wifi you are on to give you a")
        print("new ip address on that network and will not affect your")
        print("connection but may temporarilaly disable it but it will come back")
        print("--------------------")
        print("9. Trigger BSOD")
        print("causes what you call a blue screen of death on your computer")
        print("which is the screen on your computer which is blue with a white")
        print("smily face when your computer crashes, this may get rid of unsaved data")
        print("--------------------")
        print("10. Open Bin")
        print("goes to the default bin directory on your computer where")
        print("deleted files are stored and can be recovered")
        print("this does not require admin permissions")
        a = input("\n>Press Enter to return<\n")
        space()
        startpage2()
    elif choice == "1":
        for i in range(3):
            space()
        startpage1()
    elif page1h == "3":
        for i in range(3):
            space()
        startpage3()
    ############################### V Flush DNS V ##########################################
    elif choice=="6":
        ans4 = input("Are you sure you want to flush DNS? \n")
        if ans4.lower() == "yes":
            import os
            os.system('cmd /c "ipconfig/flushdns"')
            recall()
        elif ans4.lower() == "ye":
            import os
            os.system('cmd /c "ipconfig/flushdns"')
            recall()
        else:
            print("\n|---------------|")
            print("|Flush Cancelled|")
            print("|---------------| \n")
            for i in range(3):
                space()
            startpage2()
    ############################### V Delete Tempory Data  V ##########################################
    elif choice=="7":
        ans4 = input("Are you sure you want to delete temp data? \n")
        if ans4.lower() == "yes":
            import os
            os.system('cmd /c " del /q /f /s %temp%\*"')
            recall()
        elif ans4.lower() == "ye":
            import os
            os.system('cmd /c " del /q /f /s %temp%\*"')
            recall()
        else:
            print("\n|--------------------|")
            print("|Temp Clear Cancelled|")
            print("|--------------------| \n")
            for i in range(3):
                space()
            startpage2()
    ############################### V IP Renew V ##########################################
    elif choice=="8":
        ans4 = input("Are you sure you want to renew your IP?, if it releases but doesn't renew, your file system may become corrupt \n")
        if ans4.lower() == "yes":
            import os
            os.system('cmd /c "ipconfig /release & ipconfig /renew"')
            recall()
        elif ans4.lower() == "ye":
            import os
            os.system('cmd /c "ipconfig /release & ipconfig /renew"')
            recall()
        else:
            print("\n|---------------|")
            print("|Renew Cancelled|")
            print("|---------------| \n")
            for i in range(3):
                space()
            startpage2()
    ############################### V Trigger Bsod V ##########################################
    elif choice=="9":
        ans4 = input("Are You Sure you want to trigger A blue screen of death?, This could break your PC \n")
        if ans4.lower() == "yes":
            import os
            qwertyuiop()
        elif ans4.lower() == "ye":
            import os
            qwertyuiop()
        else:
            print("\n|------------|")
            print("|BSOD Aborted|")
            print("|------------| \n")
            for i in range(3):
                space()
            startpage2()
    ############################### V Bin Open V ##########################################
    elif choice=="10":
        ans4 = input("Are you sure you want to open the bin? [it may be a bit smelly] \n")
        if ans4.lower() == "yes":
            import os
            os.system('cmd /c "start shell:RecycleBinFolder"')
            recall()
        elif ans4.lower() == "ye":
            import os
            os.system('cmd /c "start shell:RecycleBinFolder"')
            recall()
        else:
            print("\n|------------------|")
            print("|Bin Open Cancelled|")
            print("|------------------| \n")
            for i in range(3):
                space()
            startpage2()
    ################################ Startpage2 Else Statment ##########################################
    else:
        print("\n /---------------\ ")
        print(" |Invalid Answer!| ")
        print(" \---------------/ \n")
        from time import sleep
        sleep(2)
        for i in range(3):
            space()
        startpage2()
##########################################################################################
#--------------------------------Start Page 3--------------------------------------------#
##########################################################################################
def startpage3():
    print("\n{>What would you like to do?<} \n")
    print("11. Repair Files")
    print("12. Disk Cleanup")
    print("13. Computer Info")
    print("14. View Installed Apps")
    print("15. Exit")
    print("16. Credits")
    print("--------------------")
    print("       < Page 3")
    print("{Use << to quick toggle}")
    print(" ")
    print("<[?] for 11-16 help or [??] for all help>")
    print(" ")
    print(end="\n Enter Your Choice: ")
    choice = input()
    if choice == "<":
        space()
        startpage2()
    elif choice == "<<":
        space()
        startpage1()
    elif choice == "??":
        help1()
    elif choice == "?":
        input("[System Options Ver 1.30]\n>Press enter to continue<")
        print("\nSystem options is a project designed to help you")
        print("have more control over your computer. an explanation ")
        print("of what each option does are as follows;")
        print("--------------------")
        print("11. Repair Files")
        print("this requires admin permissions and will scan your")
        print("computer for broken files and repairs them")
        print("--------------------")
        print("12. Disk Cleanup")
        print("opens a dialog box which will give you the option")
        print("to clear spare data that the computer doesn't need")
        print("this will just clear data and will not break anything")
        print("--------------------")
        print("13. Computer Info")
        print("opens command prompt and shows you information about")
        print("your computer and may or may not requre admin permissions")
        print("--------------------")
        print("14. View Installed Apps")
        print("also opens command prompt but shows you all of the apps which")
        print("are installed on your computer [even hidden apps]")
        print("this may or may not require admin permissions")
        print("--------------------")
        print("15. Exit")
        print("closes the system options program, to re open")
        print("system options, you will have o find where ever")
        print("you downloaded it to.")
        print("--------------------")
        print("16. Credits")
        print("shows credits for system options and details of")
        print("contact for contacting the owner of this to suggest")
        print("imporvements or to report bugs or send thanks etc.")
        a = input("\n>Press Enter to return<\n")
        space()
        startpage3()
    elif choice == "2":
        for i in range(3):
            space()
        startpage2()
    elif page1h == "1":
        for i in range(3):
            space()
        startpage1()
    import os
    ############################### V Scan & Repair V ##########################################
    if choice=="11":
        ans4 = input("Are you sure you want to Scan & Repair your files? \n")
        if ans4.lower() == "yes":
            import os
            os.system('cmd /k "sfc /scannow"')
            recall()
        elif ans4.lower() == "ye":
            import os
            os.system('cmd /k "sfc /scannow"')
            recall()
        else:
            print("\n|-----------------------|")
            print("|Scan & Repair Cancelled|")
            print("|-----------------------| \n")
            for i in range(3):
                space()
            startpage3()
    ############################### V Disk Cleanup V ##########################################
    elif choice=="12":
        ans4 = input("Are you sure you want to open the disk cleanup? \n")
        if ans4.lower() == "yes":
            import os
            os.system('cmd /c "cleanmgr.exe /sageset:112"')
            recall()
        elif ans4.lower() == "ye":
            import os
            os.system('cmd /c "cleanmgr.exe /sageset:112"')
            recall()
        else:
            print("\n|----------------------|")
            print("|Disk Cleanup Cancelled|")
            print("|----------------------| \n")
            for i in range(3):
                space()
            startpage3()
    ############################### V View System Info V ##########################################
    elif choice=="13":
        ans4 = input("Are you sure you want to view senstive system information? \n")
        if ans4.lower() == "yes":
            import os
            os.system('cmd /k "ipconfig /all"')
            recall()
        elif ans4.lower() == "ye":
            import os
            os.system('cmd /k "ipconfig /all"')
            recall()
        else:
            print("\n|-------------------|")
            print("|View Info Cancelled|")
            print("|-------------------| \n")
            for i in range(3):
                space()
            startpage3()
    ################################ V View Installed Apps V ##########################################
    elif choice=="14":
        ans4 = input("Are you sure you want to view installed apps? \n")
        if ans4.lower() == "yes":
            import os
            os.system('cmd /k "wmic product get name"')
            recall()
        elif ans4.lower() == "ye":
            import os
            os.system('cmd /k "wmic product get name"')
            recall()
        else:
            print("\n|--------------------|")
            print("|App Viewer Cancelled|")
            print("|--------------------| \n")
            for i in range(3):
                space()
            startpage3()
    ################################ V Exit V ##########################################
    elif choice=="15":
        ans4 = input("Are you sure you want to exit \n")
        if ans4.lower() == "yes":
            exit()
        elif ans4.lower() == "ye":
            exit()
        else:
            print("\n|--------------|")
            print("|Exit Cancelled|")
            print("|--------------| \n")
            for i in range(3):
                space()
            startpage3()
    ################################ V Credits V ##########################################
    elif choice=="16":
        print("\n Made by NeatPlaysAlt")
        print("[Email] - info@neatnet.org")
        print("[Discord] - NeatPlaysAlt#8111")
        print("[Instagram] - @neatnetwork")
        from time import sleep
        sleep(10)
        for i in range(35):
            space()
        startpage3()
    ################################ Startpage3 Else Statment ##########################################   
    else:
        print("\n /---------------\ ")
        print(" |Invalid Answer!| ")
        print(" \---------------/ \n")
        from time import sleep
        sleep(2)
        for i in range(3):
            space()
        startpage3()
##########################################################################################
#--------------------------------START OF PROGRAM----------------------------------------#
##########################################################################################
print("  ____            _                    ___        _   _                  ")
print(" / ___| _   _ ___| |_ ___ _ __ ___    / _ \ _ __ | |_(_) ___  _ __  ___  ")
print(" \___ \| | | / __| __/ _ \ '_ ` _ \  | | | | '_ \| __| |/ _ \| '_ \/ __| ")
print("  ___) | |_| \__ \ ||  __/ | | | | | | |_| | |_) | |_| | (_) | | | \__ \ ")
print(" |____/ \__, |___/\__\___|_| |_| |_|  \___/| .__/ \__|_|\___/|_| |_|___/ ")
print("        |___/                              |_|                           \n")
print(" __  _   _    _  _  ___  __  ___  __  _     __  _   _  ___  __  _    ___")
print("|__]  \_/     |\ | |___ |__|  |  |__] |    |__|  \_/  [__  |__| |     | ")
print("|__]   |      | \| |___ |  |  |  |    |___ |  |   |   ___] |  | |___  | \n")
startpage1()

# Made by NeatPlaysAlt
# [Email] - info@neatnet.org
# [Discord] - NeatPlaysAlt#8111
# [Instagram] - @neatnetwork

#Line 795 -> <-
