## HW_class_Time 7.1

### Задание
#### 7.1. Дружественные функции и класс:
1. Спроектировать и реализовать дружественный к классу Time класс SimpleWatch, который:
   1. может показывать время, содержащееся в private переменных объекта класса Time.
   2. может устанавливать (менять) значение времени в переданном ему объекте класса Time, также через прямой доступ к private членам класса Time.
2. Реализовать класс Watch, который содержит функции члены класса дружественные к классу Time, реализующие просмотр и установку времени (см. предыдущий пункт) в объекте класса Time, который передается им как параметр. 
3. Оба класса Watch должны реализовывать возможность изменять формат выводимого времени (12/24), путем установления значения внутренней переменной класса Watch.

1. Создайте директорию для сборки (находясь в дирректории 7.1_FriendFunctions):
   ```sh
   mkdir build
   cd build
   ```
2. Запустите CMake для конфигурации проекта :
   
   ```sh
   cmake ..
   ```
   

3. Соберите проект с помощью make:
   ```sh
   make
   ```
4. После успешной сборки проекта вы можете запустить код:
   ```sh
    ./class_time
   ```
