# WSL-Ubuntu-Offline
WSL ubuntu offline only with some tools and coding

thanks to: https://github.com/DDoSolitary/LxRunOffline
and I help people for quick use of ubuntu wsl offline ready for development.

Readme first

This is just for fun of my personal WSL Ubuntu run on Windows. 


Software Requirement
- Windows 10 with September/October update (build 1803) or Windows Server 2016 with September/October update (build 1803)
- Chocolatey
- LxrunOffline
- this wsl ubuntu copy

Has been tested on Windows 10 Professional with update build 1803 (my laptop)

Prerequisite
-------------
1. Need to download chocolatey and installed on Windows. You can download and install from https://chocolatey.org/
2. Need to install lxrunoffline after intalling chocolatey. Just run : choco install lxrunoffline

=======================================================================================================================================================

How to install
--------------
1. Open powershell with elevate run as Administrator !!!!
2. run: install.ps1


========================================================================================================================================================

How to use
-------------
1. The installation folder of Ubuntu of Windows Subsystem for Linux Offline must be on c:\wsl. Otherwise you have to change folder at ubuntu.bat or ubuntu.ps1. You can copy to exactly to that folder

2. Open powershell with elevate run as Administrator !!!!!
3. run: Set-ExecutionPolicy remotesigned  and choose ALL
4. run: ubuntu.ps1 (powershell) with elevate run as Administrator !!!

Contents of this Ubuntu WSL
- Ubuntu 16
- Tools: autoconf, cmake, gdb, automake, python, nodejs, dotnet core, openjdk, supervisor, aptitude, mongodb clients, mssql tools, samba
- NodeJS with NVM. You can choose between

