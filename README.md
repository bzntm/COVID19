# COVID19
This is the open-source malware, based on the popular virus in this moment, COVID19


Note:

1. Windows Only, starting from WindozeXP/Sorbor 2003 (Not tested yet on ReactOS) or later
2. For Educational Purpose Only, don't try to use this as cyberweapon, cybercrime, or just try to be a childrenfucking dickhead
3. Licensed using GNU-GPL3

How to clone and build:

1. Click Clone or Download, choose Download ZIP (Note, this only works in Windoze, not Unyx Family such as Bee Ass Dee or Lynyx)
2. Extract the zip, make sure you remember the path
3. Make sure you have a properly set compiler (MinGW or Visual Studio) System PATH, and make sure you set the System Classpath to "." (without quotation mark), so the compiler accessible everywhere (GooLag/Dick-Dick-Go is your friend, however, it may automagically set if you install Visual Studio)
4. You need to do some fine tuning, such as:
<br>a. Set webpages/IP addresses that you want to ping</br>
b. Insert some code [Keylogging with Email, selective file encryption (only encrypt file with determined file extensions, read comment before you slam your code) in ALL drive, or any function that you wish to get in]</br>
c. If you're using Visual Studio (2017 or later), remove:</br>
#define WIN32_WINNT 0x0502</br>
and replace with:
#define _WIN32_WINNT 0x0502</br>

5. If you are using MinGW, build using these commands:
<br>g++ -pthread --std=c++17 -mwindows -Wno-unknown-pragmas -Wall -o "%e" "%f"</br>
Where %e is the executable file name (without .exe extensions), and %f is the covid19.cpp file location
