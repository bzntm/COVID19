# COVID19
This is the open-source malware, based on the popular virus in this moment, COVID19


Note:

1. Windows Only, starting from WindozeXP/Sorbor 2003 (Not tested yet on RektOS) or later
2. For Educational Purpose Only, don't try to use this as cyberweapon, for cybercrime, or just for trying to be a childrenfucking dickhead
3. Licensed using GNU-GPL3
4. ALWAYS READ THE COMMENTS BEFORE SLAMMING YOUR OWN CODE!1!1
5. If you want to test this malware, USE VIRTUAL PC WITH PROPRIETARY DISK FORMAT [SUCH AS VDI (VIRTUALBOX), VMDK (VMWARE), HDS/HDD (COREL PARALLELS), NOT VHD(X) NOR RAW/IMG]! If you point your finger to me for fucking your device, i'll cumshot to you

How to clone and build:

1. Click Clone or Download, choose Download ZIP (Note, this only works in Windoze, not Unyx Family such as Bee Ass Dee or Lynyx)
2. Extract the zip, make sure you remember the path
3. Make sure you have a properly set compiler (MinGW or Visual Studio) System PATH, and make sure you set the System Classpath to "." (without quotation mark), so the compiler accessible everywhere (GooLag/Dick-Dick-Go is your friend, however, it may automagically set if you install Visual Studio)
4. You need to do some fine tuning, such as:
<br>a. Set webpages/IP addresses that you want to ping</br>
<br>b. Insert some code [Keylogging with Email, selective file encryption (only encrypt file with determined file extensions, read comment before you slam your code) in ALL drive, spread malware automatically with AutoRun in all removable disks, MBR/EFI overwriting, and any function that you wish to get in]</br>
<br>c. If you're using Visual Studio (2017 or later), remove:</br>
<br>#define WIN32_WINNT 0x0502</br>
<br>and replace with (by removing comment):</br>
<br>#define _WIN32_WINNT 0x0502</br>
<br>d. If you're using MinGW, remove:</br>
<br>#define _WIN32_WINNT 0x0502</br>
<br>Instead, keep this exist:</br>
<br> #define WIN32_WINNT 0x0502</br>

5. If you are using MinGW, build using these commands:</br>
<br>g++ -pthread --std=c++17 -mwindows -Wno-unknown-pragmas -Wall -o "%e" "%f"</br>
<br>Where %e is the executable file name (with .exe extensions), and %f is the covid19.cpp file location</br>
<br>You don't childrenfucking understand? Let me strip the %e and %f, replace that shits to something that you more understand:</br>
g++ -pthread --std=c++17 -mwindows -Wno-unknown-pragmas -Wall -o "your-exe-file-name-with-exe-extension" "where-the-fuck-you-place-the-COVID19-source-code"</br>

6. List of Supported and not-supported/untested Compiler(s):
<br>MinGW (works, tested by me)</br>
<br>Visual Studio [2017 or later] (works, tested by @IDCPLC on Telegram)</br>
<br>Other C++ compiler on Windows that aren't mentioned here means they're not tested or may not works
