#27-homeWork. 40 - Динамический веб  

## В процессе сделано:
Настроен Vagrantfile и плейбук ansible для развертки следующей конфигурации:
- проект c django висит на порту localhost:8000 и проксирутся nginx с порта 83
- проект с go висит на порту localhost:8800 и проксирутся nginx с порта 81
- проект с react висит на порту localhost:7777 и проксирутся nginx с порта 82


1. GO

![Image 1](https://github.com/ballrak86/28-homeWork/blob/main/screenshots/go.jpg) 

--------
2. React

![Image 2](https://github.com/ballrak86/28-homeWork/blob/main/screenshots/react.jpg) 

--------
3. Django

![Image 3](https://github.com/ballrak86/28-homeWork/blob/main/screenshots/django.jpg) 

## Как запустить:
 ```
 vagrant up
 ```

## Как проверить работоспособность:
Можно перейти по ссылкам после разворачивания стенда: 
- http://192.168.100.20:83 
- http://192.168.100.20:82 
- http://192.168.100.20:81 

📚Домашнее задание/проектная работа разработано(-на) для курса ["Administrator Linux. Professional"](https://otus.ru/lessons/linux-professional/)
