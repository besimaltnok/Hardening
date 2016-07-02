#### Windows Güvenliği İpuçları


**1** Zararlı yazılımların kalıcı olmak amacı ile sistem üzerinde kullanabilecekleri noktalar sürekli denetim altında tutulmalıdır.

Bu noktalar aşağıdaki gibidir : 

* Registry girdileri

HKEY_LOCAL_MACHINESoftwareMicrosoftWindowsCurrentVersionRun
HKEY_CURRENT_USERSoftwareMicrosoftWindowsCurrentVersionRun
HKEY_LOCAL_MACHINESoftwareMicrosoftWindowsCurrentVersionRunOnce
HKEY_CURRENT_USERSoftwareMicrosoftWindowsCurrentVersionRunOnce
HKEY_LOCAL_MACHINESoftwareMicrosoftWindowsCurrentVersionRunServices
HKEY_LOCAL_MACHINESoftwareMicrosoftWindowsCurrentVersionRunServicesOnce
HKEY_LOCAL_MACHINESoftwareMicrosoftWindowsCurrentVersionRunOnceSetup

* Başlangıç klasörü

%ALLUSERSPROFILE%Start MenuProgramsStartup
 %USERPROFILE%Start MenuProgramsStartup
 
* Görev Zamanlayıcı (Schedule Tasks)

* Yeni eklenen servislerin kontrolü (Process hacker)

* Paylaşımlı dosyaları kısıtlamak

**2** Sistem üzerindeki kullanıcılar sürekli denetim altında tutulmaldır.

* "net users" komutu ile kullanıcılar görüntülenebilir.
