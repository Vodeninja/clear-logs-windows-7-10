rem this script was created by Vodeninja#2691
@ECHO OFF
REG DELETE "HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell\MuiCache" /va /f
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell\BagMRU" /f
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell\Bags" /f
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_CURRENT_USER\Software\Microsoft\Windows\Shell\BagMRU" /f
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_CURRENT_USER\Software\Microsoft\Windows\Shell\Bags" /f
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\RunMRU" /va /f
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32\FirstFolder" /va /f
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32\LastVisitedPidlMRU" /va /f
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32\LastVisitedPidlMRULegacy" /va /f
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32\OpenSavePidlMRU" /f
rem this script was created by Vodeninja#2691
REG ADD "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32\OpenSavePidlMRU"
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\UserAssist" /f
rem this script was created by Vodeninja#2691
REG ADD "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\UserAssist"
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\AppCompatCache" /va /f
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\Session Manager\AppCompatCache" /va /f
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\RADAR\HeapLeakDetection\DiagnosedApplications" /f
rem this script was created by Vodeninja#2691
REG ADD "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\RADAR\HeapLeakDetection\DiagnosedApplications"
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_USERS%usersid%\Software\Microsoft\Windows\CurrentVersion\Search\RecentApps" /f
rem this script was created by Vodeninja#2691
REG ADD "HKEY_USERS%usersid%\Software\Microsoft\Windows\CurrentVersion\Search\RecentApps"
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\bam\UserSettings%usersid%" /va /f
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\bam\UserSettings%usersid%" /va /f
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_USERS%usersid%\Software\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\Compatibility Assistant\Store" /va /f
rem this script was created by Vodeninja#2691
REG DELETE "HKEY_USERS%usersid%\Software\Microsoft\Windows\CurrentVersion\Explorer\MountPoints2" /f
rem this script was created by Vodeninja#2691
REG ADD "HKEY_USERS%usersid%\Software\Microsoft\Windows\CurrentVersion\Explorer\MountPoints2"
rem this script was created by Vodeninja#2691
DEL /f /q %APPDATA%\Microsoft\Windows\Recent*.*
rem this script was created by Vodeninja#2691
DEL /f /q %APPDATA%\Microsoft\Windows\Recent\CustomDestinations*.*
rem this script was created by Vodeninja#2691
DEL /f /q %APPDATA%\Microsoft\Windows\Recent\AutomaticDestinations*.*
rem this script was created by Vodeninja#2691
DEL /f /q %systemroot%\Panther*.*
rem this script was created by Vodeninja#2691
DEL /f /q %systemroot%\appcompat\Programs*.txt
rem this script was created by Vodeninja#2691
DEL /f /q %systemroot%\appcompat\Programs*.xml
rem this script was created by Vodeninja#2691
DEL /f /q %systemroot%\appcompat\Programs\Install*.txt
rem this script was created by Vodeninja#2691
DEL /f /q %systemroot%\appcompat\Programs\Install*.xml
rem this script was created by Vodeninja#2691
DEL /f /q %systemroot%\Prefetch*.pf
rem this script was created by Vodeninja#2691
DEL /f /q %systemroot%\Prefetch*.ini
rem this script was created by Vodeninja#2691
DEL /f /q %systemroot%\Prefetch*.7db
rem this script was created by Vodeninja#2691
DEL /f /q %systemroot%\Prefetch*.ebd
rem this script was created by Vodeninja#2691
DEL /f /q %systemroot%\Prefetch*.bin
rem this script was created by Vodeninja#2691
DEL /f /q %systemroot%\Prefetch*.db
rem this script was created by Vodeninja#2691
DEL /f /q %systemroot%\Prefetch\ReadyBoot*.fx
rem this script was created by Vodeninja#2691
DEL /f /q %systemroot%\Minidump*.*
rem this script was created by Vodeninja#2691
EXIT
rem this script was created by Vodeninja#2691
