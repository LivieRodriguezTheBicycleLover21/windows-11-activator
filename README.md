# windows-11-activator
Activator for Windows 11. Works great with Windows 11 Pro.

@echo off
title Windows 11 ALL version activator&cls&echo ************************************&echo Supported products:&echo - Windows 11 Home&echo - Windows 11 Professional&echo - Windows 11 Enterprise, Enterprise LTSB&echo - Windows 11 Education&echo.&echo.&echo ************************************ &echo Windows 11 activation...
cscript //nologo c:\windows\system32\slmgr.vbs /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX >nul
cscript //nologo c:\windows\system32\slmgr.vbs /ipk MH37W-N47XK-V7XM9-C7227-GCQG9 >nul
cscript //nologo c:\windows\system32\slmgr.vbs /ipk NRG8B-VKK3Q-CXVCJ-9G2XF-6Q84J >nul
echo ************************************ &echo.&echo.&set i=1
:server
if %i%==1 set KMS_Sev=skms s8.uk.to
if %i%==2 set KMS_Sev=skms kms8.msguides.com
if %i%==6 exit
cscript //nologo c:\windows\system32\slmgr.vbs /skms %KMS_Sev% >nul
cscript //nologo c:\windows\system32\slmgr.vbs /ato | find /i "successfully" && (echo.& echo ************************************ & echo. & choice /n /c YN /m "Do you want to restart your PC now [Y,N]?" & if errorlevel 2 exit) || (echo The connection to the server failed! Trying to connect to another one... & echo Please wait... & echo. & echo. & set /a i+=1 & goto server)
shutdown.exe /r /t 00
[NOTE: I have linked a TXT file, where you just save it as a CMD file, and execute WITH ADMIN PRIVILEGES. Also, ddon't foret to disable
your antivirus before you run the file.

DOWNLOAD THE FILE HERE:

[activatorforwin11.txt](https://github.com/LivieRodriguezTheBicycleLover21/windows-11-activator/files/11431821/activatorforwin11.txt)
