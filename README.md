# Домашнее задание к занятию "`Название занятия`" - `Фамилия и имя студента`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---
LESSON hw-02
Marchenko Vyacheslav

### Задание 1

Install zabbix and postgresql from Lesson "Install Zabbix Server" use zabbix.com
Made it on ubuntu 22.04

2. sudo apt install postgresql 
![proof postgresql was install](https://github.com/Takarigua/hw-02/blob/b812980b5a4cfc33eeb17fdf57290eb93d8f4123/screen/postgresql.png)
3. Istruction for ubuntu 22.04 (switch on PostgreSQL) (https://www.zabbix.com/download?zabbix=6.0&os_distribution=ubuntu&os_version=22.04&components=server_frontend_agent&db=pgsql&ws=apache)
4. ![proof zabbix server and agent was installed](https://github.com/Takarigua/hw-02/blob/17a49a9bd9ce90cbadd9a19cd9573428df947718/screen/adminka.png)

---

### Задание 2

1. ![proof Configuration - Hosts - ubu2 and Test Machine](https://github.com/Takarigua/hw-02/blob/c339715f2c712d0b3812070123f8757495b13b7b/screen/2%20hosts.png)
2. ![proof log file from both VM](https://github.com/Takarigua/hw-02/blob/04c918fe1b9a4f7c6dd2f31234c9133969444100/screen/LogFile%20VMs.png)
3. ![LatestData](https://github.com/Takarigua/hw-02/blob/9d9769bbc351345bde05d5964c1ec1c2d24bcc7d/screen/Latest%20data.png)
4.:  
Поле для вставки кода...
# sudo apt update
# sudo apt install zabbix-agent
# sudo nano /etc/zabbix/zabbix_agentd.conf
# Change Server= and Hostname=
# sudo systemctl restart zabbix-agent
# sudo systemctl enable zabbix-agent
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота 2](ссылка на скриншот 2)`


---

### Задание 3

`Приведите ответ в свободной форме........`

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`

### Задание 4

`Приведите ответ в свободной форме........`

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`
