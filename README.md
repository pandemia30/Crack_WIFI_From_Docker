# Crack_WIFI_From_Docker
Взлом wi-fi сети с Windows OS, используя Docker &amp; Airgeddon Установка Bash - скрипта Airgeddon в Docker. Для этого нам понадобится установленный Docker ( инструкция по установке https://docs.docker.com/toolbox/toolbox_install_windows/)      запускаем Docker. в командной строке пишем команды через Enter: ~# docker run     --rm     -ti     --name airgeddon     --net=host     --privileged     -p 3000:3000     -v /path/to/some/dir/on/your/host:/io     -e DISPLAY=$(route print | grep 0.0.0.0 | awk '{print $4}' | head -n 1):0     v1s1t0r1sh3r3/airgeddon     Начинается процесс загрузки пакетов
