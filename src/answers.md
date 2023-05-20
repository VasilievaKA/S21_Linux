## Часть 1
Установить Ubuntu 20.04 Server LTS без графического интерфейса. Узнайте версию Ubuntu.   

![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0_20221027_120737.png)

## Часть 2
Создать пользователя, отличного от пользователя, который создавался при установке. Пользователь должен быть добавлен в группу adm.    
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0_20221027_121543.png)

Новый пользователь должен быть в выводе команды    
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0_20221027_121512.png)

## Часть 3

Задать название машины вида user-1    
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0_20221027_122139.png)  

Установить временную зону, соответствующую вашему текущему местоположению.     
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0_20221027_123016.png)    

Вывести названия сетевых интерфейсов с помощью консольной команды.      
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0_20221027_122315.png) ![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0_20221027_125156.png)    

`Интерфейс lo` является локальной петлёй, имеющей IP-адрес 127.0.0.1. Она предназначена для обеспечения сетевого доступа к компьютеру. В принципе, этот интерфейс не требует дополнительных настроек.   
`Dynamic Host Configuration Protocol (DHCP)` — это протокол прикладного уровня, который помогает назначать IP-адреса устройствам при подключении к серверу. Протокол DHCP автоматизирует выдачу адресов, а также их передачу следующим пользователям после отключения устройств или их перехода из одной подсети в другую.    

Используя консольную команду получить ip адрес устройства, на котором вы работаете, от DHCP сервера.   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0_20221027_1302111.png)    

Перед настройкой с помощью команды `ifconfig` вывела на экран внешний ip-адрес шлюза (ip) и внутренний IP-адрес шлюза, он же ip-адрес по умолчанию (gw).   
Далее приступила к настройке.  
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_12-10-51.jpg)  

Пинг 1.1.1.1  
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/Screenshot_1.png)


## Часть 4

После обновления системных пакетов, если ввести команду обновления повторно, должно появится сообщение, что обновления отсутствуют.    
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_12-27-18.jpg)


## Часть 5

`sudo` — это утилита, предоставляющая привилегии root для выполнения административных операций в соответствии со своими настройками. Она позволяет легко контролировать доступ к важным приложениям в системе.    
Таким был hostname    
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_12-29-24.jpg)   

Таким он стал    
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_12-29-46.jpg)  

## Часть 6

Вывести время, часового пояса, в котором вы сейчас находитесь.   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_12-32-46.jpg)  

Вывод следующей команды должен содержать `NTPSynchronized=yes`:   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_12-32-46%20(2).jpg) 


## Часть 7

Используя каждый из трех выбранных редакторов, создайте файл test_X.txt. Напишите в нём свой никнейм, закройте файл с сохранением изменений.

Из каждого редактора с содержимым файла перед закрытием.
* nano   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/Screenshot_3.png)     
* joe  
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/Screenshot_4.png)    
* vim   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/Screenshot_21.png)    

В отчёте укажите, что сделали для выхода с сохранением изменений.
* nano - `ctrl + X + Y`
* joe - `ctrl + K + Q + y `
* vim - `esc + :wq`

Используя каждый из трех выбранных редакторов, откройте файл на редактирование, отредактируйте файл, заменив никнейм на строку "21 School 21", закройте файл без сохранения изменений.

Из каждого редактора с содержимым файла после редактирования.
* nano   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/Screenshot_3.png)   
* joe  
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/Screenshot_4.png)    
* vim   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/Screenshot_21.png)    

В отчёте укажите, что сделали для выхода без сохранения изменений.
* nano - `ctrl + X + N`
* joe - `ctrl + K + Q + n ` 
* vim - `esc + :q!`

Используя каждый из трех выбранных редакторов, отредактируйте файл ещё раз, а затем освойте функции поиска по содержимому файла и замены слова на любое другое.

Из каждого редактора с результатами поиска слова. 
* nano   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_13-02-49%20(2).jpg)   
* joe  
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_13-02-49%20(4).jpg)    
* vim   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_13-02-49.jpg)    

Из каждого редактора с командами, введёнными для замены слова на другое.   
* nano   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_13-02-49%20(3).jpg)   
* joe   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_13-02-49%20(5).jpg)   
* vim    
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_13-02-48.jpg)   

## Часть 8

Установить службу SSHd. Добавить автостарт службы при загрузке системы.   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_13-15-53.jpg)   

Перенастроить службу SSHd на порт 2022.   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_13-15-53%20(2).jpg)

Используя команду `ps`, показать наличие процесса sshd. Чтобы посмотреть все активные на данный момент процессы в linux, используется сочетание опций aux.    
`-a` - вывести информацию обо всех наиболее часто запрашиваемых процессах   
`-u` - показывать процессы только определенного пользователя       
`-x` - cнимите ограничение в стиле BSD «должен иметь tty», которое накладывается на набор все процессы, когда используются некоторые опции в стиле BSD (без "-") или когда ps настройка личности похожа на BSD. Набор процессов, выбранных таким образом, равен в дополнение к набору процессов, выбранных другими способами.       
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_13-17-35.jpg)   

Перезагрузить систему. Вывод команды `netstat -tan` должен содержать  
__tcp__ - протокол   
__0__ - количество полученных пакетов   
__0__ - количество отправленных пакетов   
__0.0.0.0:2022__ - текущий адрес   
__0.0.0.0:*__ - адрес пересылки   
__LISTEN__ - статус      
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_13-19-03.jpg)    

```
-t: связанный с протоколом TCP;   
-a: все статусы;   
-n: отображать IP и порт в цифрах, запрещать обратный запрос DNS.   
```
## Часть 9

По выводу команды `top` определить и написать в отчёте:

* uptime - 1:45
* количество авторизованных пользователей - 1
* общую загрузку системы - 0.44
* общее количество процессов - 185 
* загрузку cpu - 12.0
* загрузку памяти - 1976.1
* pid процесса занимающего больше всего памяти - 1008 
* pid процесса, занимающего больше всего процессорного времени - 1008    

![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_15-14-04.jpg)   


В отчёт вставить скрин с выводом команды `htop`:

* отсортированному по PID   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_16-09-52.jpg)   

* отсортированному по PERCENT_CPU   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_16-09-52%20(2).jpg)  

* отсортированному по PERCENT_MEM   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_16-09-53.jpg)   

* отсортированному по TIME  
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_16-09-53%20(2).jpg)    


* отфильтрованному для процесса sshd     
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_16-11-40.jpg)   

* с процессом syslog, найденным, используя поиск   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_16-11-41.jpg)   

* с добавленным выводом hostname, clock и uptime
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_16-14-57.jpg)

## Часть 10

Запустить команду `fdisk -l`, написать   

* название жесткого диска - dev/sda     
* размер - 34359738368 б     
* количество секторов - 67108864   
* размер swap - 31.5 G     
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_15-21-05.jpg)   

## Часть 11

Запустить команду `df`, написать для корневого раздела (/):

* размер раздела - 32328496 б    
* размер занятого пространства - 10426960 б   
* размер свободного пространства - 20233800 б   
* процент использования - 35%    
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_15-22-41.jpg)   

Запустить команду `df -Th`, написать для корневого раздела (/):

* размер раздела - 31 G   
* размер занятого пространства - 10 G     
* размер свободного пространства - 20 G   
* процент использования - 35%    
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_15-23-21.jpg)    


## Часть 12

Запустить команду `du`.

Вывести размер папок `/home`, `/var`, `/var/log` (в байтах, в человекочитаемом виде)   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_15-36-01.jpg)   

Вывести размер всего содержимого в `/var/log`    
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_15-36-36.jpg)   

## Часть 13

Вывести размер папок `/home`, `/var`, `/var/log`.    
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_15-40-01.jpg)     
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_15-40-02%20(2).jpg) 
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_15-40-02.jpg)

## Часть 14

Время последней успешной авторизации, имя пользователя и метод входа в систему.     
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_15-48-53.jpg)   

Перезапустить службу SSHd. Вставить скрин с сообщением о рестарте службы.   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_15-48-53%20(2).jpg)     


## Часть 15 

Используя планировщик заданий, запустите команду `uptime` через каждые 2 минуты. Найти в системных журналах строчки о выполнении.    
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/photo_2022-12-20_16-02-31.jpg)   

Удалите все задания из планировщика заданий. Вывести на экран список текущих заданий для CRON.   
![](https://github.com/VasilievaKA/S21_Linux/blob/main/src/images/Screenshot_2.png)     

