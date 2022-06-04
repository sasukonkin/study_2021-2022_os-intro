**РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ**

**Факультет физико-математических и естественных наук**

*Отчёт по лабораторной работе №13        
Дисциплина: Операционные системы*

Студент: Суконкин С.А.  
Группа: НКНбд-02-21  
№ ст. билета: 1032216457                                       

МОСКВА
2022 г.

---

**Цель:**
Приобрести простейшие навыки разработки, анализа, тестирования и откладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями. 

---

**Описание результатов выполнения задания:**

**№1.**
Создал в домашнем каталоге подкаталог ~/work/os/lab_prog (Рис.1).  
![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.1.png?raw=true)        
Рис.1  

**№2.**
Создал в новом каталоге 3 файла: calculate.h, calculate.c, main.c. В каждый файл вписал необходимую программу (Рис. 2.1  - 2.4).   
![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.2.1.png?raw=true)     
Рис.2.1  

![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.2.2.png?raw=true)  
Рис.2.2  

![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.2.3.png?raw=true)  
Рис.2.3  

![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.2.4.png?raw=true)  
Рис.2.4  

**№3.**
Выполнил компиляцию программы посредством gcc (Рис. 3).  
![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.3.png?raw=true)    
Рис.3  

**№5.**
Создал Makefile со следующим содержимым (Рис. 5).  
![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.5.png?raw=true)  
Рис.5  

**№6.**
С помощью gdb выполнил откладку программы calcul (Рис.6.1), запустил откладку внутри откладчика с помощью run (Рис.6.2), для постраничного просмотра исходного кода использовал команду list (Рис.6.3), для просмотра с 12 по 15 строку исходного кода использовал list с параметрами (Рис.6.4), для просмотра определённых строк неосновного файла использовал list с параметрами (Рис.6.5), установил точку останова в файле calculate.c на строке 21, после удалил эту точку (Рис.6.6), вывел информацию об имеющихся в проекте точках останова (Рис.6.7).      
![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.6.1.png?raw=true)    
Рис.6.1  

![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.6.2.png?raw=true)    
Рис.6.2  

![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.6.3.png?raw=true)  
Рис.6.3  

![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.6.4.png?raw=true)  
Рис.6.4  

![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.6.5.png?raw=true)  
Рис.6.5  

![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.6.6.png?raw=true)  
Рис.6.6  

![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.6.7.png?raw=true)  
Рис.6.7  

**№7.**
С помощью утилиты splint проанализировал коды файлов calculate.c и main.c (Рис.7.1 — 7.2).  
![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.7.1.png?raw=true)    
Рис.7.1   

![1](https://github.com/sasukonkin/Otchyoty/blob/main/New%20folder%20(13)/13.7.2.png?raw=true)    
Рис.7.2   

---

**Выводы, согласованные с заданием работы:**
Приобрёл простейшие навыки разработки, анализа, тестирования и откладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.
