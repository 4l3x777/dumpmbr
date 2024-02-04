# Dump MBR

Windows native application for dumb MBR

## Пакеты сборки

+ пакет NDK <https://code.google.com/archive/p/native-nt-toolkit/downloads>
+ пакет WDK 7.1 <https://www.microsoft.com/en-us/download/details.aspx?id=11800>

## Установка

+ поместить `dumpmbr.exe` в `C:\Windows\System32`
+ добавить значение `dumpmbr` в ключ `BootExecute` ветки реестра `Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager`

## Запись результата

+ после перезагрузки, нажмите `ESC`, далее `C:\mbr.bin` будет содержать dump MBR

## Пример работы

![alt text](/img/dumpmbr.gif)
