# Домашнее задание к занятию «Инструменты Git»

### Цель задания

В результате выполнения задания вы:

* научитесь работать с утилитами Git;
* потренируетесь решать типовые задачи, возникающие при работе в команде. 

### Инструкция к заданию

1. Склонируйте [репозиторий](https://github.com/hashicorp/terraform) с исходным кодом Terraform.
2. Создайте файл для ответов на задания в своём репозитории, после выполнения прикрепите ссылку на .md-файл с ответами в личном кабинете.
3. Любые вопросы по решению задач задавайте в чате учебной группы.

------

## Задание

В клонированном репозитории:

1. Найдите полный хеш и комментарий коммита, хеш которого начинается на `aefea`.
2. Ответьте на вопросы.

* Какому тегу соответствует коммит `85024d3`?
* Сколько родителей у коммита `b8d720`? Напишите их хеши.
* Перечислите хеши и комментарии всех коммитов, которые были сделаны между тегами  v0.12.23 и v0.12.24.
* Найдите коммит, в котором была создана функция `func providerSource`, её определение в коде выглядит так: `func providerSource(...)` (вместо троеточия перечислены аргументы).
* Найдите все коммиты, в которых была изменена функция `globalPluginDirs`.
* Кто автор функции `synchronizedWriters`? 

*В качестве решения ответьте на вопросы и опишите, как были получены эти ответы.*

---

## РЕШЕНИЕ
1. Найдите полный хеш и комментарий коммита, хеш которого начинается на `aefea`.


   ![aefea](https://github.com/sash3939/Git-Tools/assets/156709540/52fab9d6-d37d-4f3f-8f73-79bc0a600450)
   ----
   ![aefea full](https://github.com/sash3939/Git-Tools/assets/156709540/ac049783-332b-4f84-9aee-52c1e6c8b49b)
   ----

3. Какому тегу соответствует коммит `85024d3`?
   Ближайший тег к указанному коммиту 85024d3.

   [85024d3](https://github.com/sash3939/Git-Tools/assets/156709540/0383e395-f108-4e8f-8db3-6ed875c3c4a9)
   ----

4. Сколько родителей у коммита `b8d720`? Напишите их хеши.
   Выведет хеши всех родителей коммита b8d720.

   [parents](https://github.com/sash3939/Git-Tools/assets/156709540/2a305932-5058-411d-8003-0afbb917ca10)
   ----

5.  Перечислите хеши и комментарии всех коммитов, которые были сделаны между тегами  v0.12.23 и v0.12.24.
    Эта команда выведет хеши и комментарии всех коммитов, сделанных между тегами v0.12.23 и v0.12.24.
    
    [between tags](https://github.com/sash3939/Git-Tools/assets/156709540/ce98962d-b0f7-4002-a43b-1d59ec042fab)
    ----

6. Найдите коммит, в котором была создана функция `func providerSource`, её определение в коде выглядит так: `func providerSource(...)` (вместо троеточия перечислены аргументы).

    [commits](https://github.com/sash3939/Git-Tools/assets/156709540/0ecce018-d5f8-4f22-8585-058feb80e962)
    ----

    [function](https://github.com/sash3939/Git-Tools/assets/156709540/e4767bfe-7757-4b2d-be76-c0aee2d6d889)
    ----
    [function1](https://github.com/sash3939/Git-Tools/assets/156709540/8e6a6950-3b69-424e-a744-07af1f28b0d0)
    ----

8. Найдите все коммиты, в которых была изменена функция `globalPluginDirs`.

   [globalPluginDirs](https://github.com/sash3939/Git-Tools/assets/156709540/ba23c74c-6bec-40c0-8572-284056baff9e)
   ----

   [pretty-format](https://github.com/sash3939/Git-Tools/assets/156709540/3f7d4605-0d83-4b81-8d76-22c3aece8336)
   ----

9.  Кто автор функции `synchronizedWriters`?
    Эта команда выведет имя автора последнего коммита, в котором была изменена функция synchronizedWriters.
    
    [authors](https://github.com/sash3939/Git-Tools/assets/156709540/6d1a720b-ceb6-4f57-a587-e01509b588a8)
    ----
   

### Правила приёма домашнего задания

В личном кабинете отправлена ссылка на .md-файл в вашем репозитории.

### Критерии оценки

Зачёт:

* выполнены все задания;
* ответы даны в развёрнутой форме;
* приложены соответствующие скриншоты и файлы проекта;
* в выполненных заданиях нет противоречий и нарушения логики.

На доработку:

* задание выполнено частично или не выполнено вообще;
* в логике выполнения заданий есть противоречия и существенные недостатки.
