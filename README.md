== Задача 2

высоконагруженная база данных MySQL критичная к отказу
физические сервера, решающее - “высоконагруженная”. по поводу критичности отказа, железо и штат специалистов будет не дешевым

различные web-приложения
виртуализация уровня ОС, либо паравиртуализация, зависит от самих приложения и бюджета, первое, кажется дешевле.

Windows-системы для использования бухгалтерским отделом
если тут речь про серверную часть для бухгалтерии, то тут помимо производительности нужно смотреть на требования безопасности, не факт что можно держать данные в облаке, ну и системы тоже бывают разные, так что нужно смотреть, можно ли вынести в виртуальную среду системы и какое требование у них по ресурсам. так что паравиртуализация, если нет, то физические сервера.

системы, выполняющие высокопроизводительные расчеты на GPU
затрудняюсь ответить, не сталкивался с подобными задачами, но кажется, дешевле арендовать мощности на конкретные вычисления, чем содержать парк такого оборудования. 



== Задача 3

Hyper-V - ? возможно VMware - затрудняюсь ответить
KVM (proxmox)
тут наверное xen
kvm - или даже лучше docker, но это про контейнеризацию 


== Задача 4



Опишите возможные проблемы и недостатки гетерогенной среды виртуализации (использования нескольких систем управления виртуализацией одновременно) и что необходимо сделать для минимизации этих рисков и проблем. Если бы у вас был выбор, создавали бы вы гетерогенную среду или нет?