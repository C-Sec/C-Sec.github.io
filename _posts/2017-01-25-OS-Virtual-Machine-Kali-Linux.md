---
title:  "Установка Kali Linux на виртуальную машину"
excerpt: ""
date:   2017-01-25T00:00:00+03:00
categories:
   - OS
tags:
   - OS
   - Kali Linux
   - Virtual Machine
author_profile: true
---

{% include toc icon="file-text" %}

Наиболее популярные системы виртуализации:

* Свободно распространяемая [Oracle VM VirtualBox](https://www.virtualbox.org/)
* [VMware Workstation](http://www.vmware.com/ru/products/workstation.html) и его бесплатная версия [VMware Player]() для некоммерческого использования

## VirtualBox

В меню "File -> Preferences" (Ctrl+G) можно настроить папку по умолчанию для расположения виртуальных машин "Default Machine Folder" во вкладке General:
![VirtualBox Preferences](http://i.imgur.com/G4aMaek.png)

В том же меню во вкладке Extensions следует установить "Oracle VM VirtualBox Extension Pack", предварительно скачав его с официального сайта [Oracle VM VirtualBox Extension Pack](https://www.virtualbox.org/wiki/Downloads).

Рассмотрим два варианта установки Kali Linux на виртуальную машину:

* С использованием готового образа для виртуальной машины
* Создание виртуальной машины и ручная установка в ней Kali Linux

### Готовый образ для виртуальной машины

Скачиваем с официального сайта готовый образ Kali Linux для VirtualBox [Kali Linux VirtualBox Images](https://www.offensive-security.com/kali-linux-vmware-virtualbox-image-download/)

После чего остаётся импортировать данный образ, открыв меню  "File -> Import Appliance..." (Ctrl+I) и выбрав скаченный образ Kali Linux.

Виртуальная машина готова к работе. Остаётся только запустить её. Данные для входа по умолчанию:

* Username: root
* Password: toor

### Ручная установка

Скачиваем с официального сайта образ Kali Linux [Download Kali Linux Images](https://www.kali.org/downloads/), выбрав, например, "Kali Linux 64 bit".

#### Создание виртуальной машины VirtualBox

Создаём виртуальную машину со следующими настройками, нажав на "New" (Ctrl+N):

![Create Virtual Machine](http://i.imgur.com/rQP7sQQ.png)

Создаём виртуальный жёсткий диск для виртуальной машины:

![Create Virtual Hard Disk](http://i.imgur.com/eYFBx8t.png)

Настраиваем созданную виртуальную машину, выбрав её и нажав на "Settings" (Ctrl+S):

и т.д.



## VMware
