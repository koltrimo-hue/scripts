HOLLIS HOLLER — где лежат проекты

Локальная папка проектов Hollis на Mac пользователя:
  /Volumes/HDD/CapcutAuto/jobs/Hollis Holler
Проекты Hollis класть ТОЛЬКО туда, не в корень /Volumes/HDD/CapcutAuto/jobs.
(Проекты Otis Greer — отдельно, в их собственной папке.)

В этом репозитории сценарии Hollis лежат в hollis/ (Hollis_NN_Title_VO.txt).
Копирование на Mac после git pull:
  rsync -av --include='Hollis_*_VO.txt' --exclude='*' hollis/ "/Volumes/HDD/CapcutAuto/jobs/Hollis Holler/"
