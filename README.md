linux-* = files initially created from linux
*-index-* = git update-index --chmod=+x linux-index-exec.sh


mingw64
checkout from windows:

-rw-r--r-- 1 Стас 197121  4 ноя 13 09:37 linux-index-exec.bat
-rw-r--r-- 1 Стас 197121  3 ноя 13 09:37 linux-index-exec.sh
-rw-r--r-- 1 Стас 197121  4 ноя 13 09:37 linux-noindex-exec.bat
-rw-r--r-- 1 Стас 197121  3 ноя 13 09:37 linux-noindex-exec.sh
-rw-r--r-- 1 Стас 197121  4 ноя 13 09:37 linux-noindex-notexec.bat
-rw-r--r-- 1 Стас 197121  3 ноя 13 09:37 linux-noindex-notexec.sh

mingw64
$ git ls-files --stage
100644 4e1776b0b31e767e12c259a0510f5602bbe013b7 0       README.md
100755 0d2ecd7fd0bf6293aea541433522dc60a9236bf8 0       linux-index-exec.bat
100755 9e2740c64c87bbad948da2c70c659d9bb26f1dda 0       linux-index-exec.sh
100755 0d2ecd7fd0bf6293aea541433522dc60a9236bf8 0       linux-noindex-exec.bat
100755 9e2740c64c87bbad948da2c70c659d9bb26f1dda 0       linux-noindex-exec.sh
100644 0d2ecd7fd0bf6293aea541433522dc60a9236bf8 0       linux-noindex-notexec.bat
100644 9e2740c64c87bbad948da2c70c659d9bb26f1dda 0       linux-noindex-notexec.sh

----------- before checkin from windows
Стас@Home MINGW64 ~/osrights (master)
$ git ls-files --stage
100644 15c362b1b81c2b49020f0643658774cbb373e9ad 0       README.md
100755 0d2ecd7fd0bf6293aea541433522dc60a9236bf8 0       linux-index-exec.bat
100755 9e2740c64c87bbad948da2c70c659d9bb26f1dda 0       linux-index-exec.sh
100755 0d2ecd7fd0bf6293aea541433522dc60a9236bf8 0       linux-noindex-exec.bat
100755 9e2740c64c87bbad948da2c70c659d9bb26f1dda 0       linux-noindex-exec.sh
100644 0d2ecd7fd0bf6293aea541433522dc60a9236bf8 0       linux-noindex-notexec.bat
100644 9e2740c64c87bbad948da2c70c659d9bb26f1dda 0       linux-noindex-notexec.sh
100755 0d2ecd7fd0bf6293aea541433522dc60a9236bf8 0       windows-index-exec.bat
100755 9e2740c64c87bbad948da2c70c659d9bb26f1dda 0       windows-index-exec.sh
100644 0d2ecd7fd0bf6293aea541433522dc60a9236bf8 0       windows-noindex-exec.bat
100644 9e2740c64c87bbad948da2c70c659d9bb26f1dda 0       windows-noindex-exec.sh
100644 0d2ecd7fd0bf6293aea541433522dc60a9236bf8 0       windows-noindex-noexec.bat
100644 9e2740c64c87bbad948da2c70c659d9bb26f1dda 0       windows-noindex-noexec.sh

Стас@Home MINGW64 ~/osrights (master)
$ ls -l
total 16
-rw-r--r-- 1 Стас 197121    4 ноя 13 09:37 linux-index-exec.bat
-rw-r--r-- 1 Стас 197121    3 ноя 13 09:37 linux-index-exec.sh
-rw-r--r-- 1 Стас 197121    4 ноя 13 09:37 linux-noindex-exec.bat
-rw-r--r-- 1 Стас 197121    3 ноя 13 09:37 linux-noindex-exec.sh
-rw-r--r-- 1 Стас 197121    4 ноя 13 09:37 linux-noindex-notexec.bat
-rw-r--r-- 1 Стас 197121    3 ноя 13 09:37 linux-noindex-notexec.sh
-rw-r--r-- 1 Стас 197121 1117 ноя 13 09:57 README.md
-rw-r--r-- 1 Стас 197121    4 ноя 13 09:59 windows-index-exec.bat
-rw-r--r-- 1 Стас 197121    3 ноя 13 10:00 windows-index-exec.sh
-rw-r--r-- 1 Стас 197121    4 ноя 13 09:59 windows-noindex-exec.bat
-rw-r--r-- 1 Стас 197121    3 ноя 13 10:00 windows-noindex-exec.sh
-rw-r--r-- 1 Стас 197121    4 ноя 13 09:59 windows-noindex-noexec.bat
-rw-r--r-- 1 Стас 197121    3 ноя 13 10:00 windows-noindex-noexec.sh
