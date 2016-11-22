# cmatrix Effect

The matrix effect on windows through windows power shell

![Mareix](https://github.com/matriex/cmatrix/blob/master/cmatrix.PNG "Matrix effect")

## How to

1) Open Windows Powershell with Admin Privillege

2) Download and save cmatrix.psm1 to desktop

3) Create a folder cmatrix on "C:\Windows\System32\WindowsPowerShell\v1.0\Modules\"

4) Copy cmatrix.psm1 to "C:\Windows\System32\WindowsPowerShell\v1.0\Modules\cmatrix\cmatrix.psm1"

5) Type the commands on terminal
  
   **set-executionpolicy remotesigned**
   
   **import-module cmatrix**
   
   **Set-screenSaverTimeout -Seconds 5**
   
   **EnableScreensaver**

_Author: Oisin Grehan_
