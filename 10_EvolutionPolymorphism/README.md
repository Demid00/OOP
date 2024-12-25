## evolution

### 10.1. Эволюция (полиморфизм):
#### 1. Создать последовательную иерархию наследования существ:
- A. generic creature - общий родитель
- B. ocean creature - наследник умеющий плавать
- C. amphibious - наследник умеющий плавать и ходить
- D. terrestrial creature - не умеет плавать, но умеет ходить
- F. bird - умеет ходить и летать
- E. waterfowl - водоплавающая птица. Умеет ходить, летать и плавать.
#### 2. Обязательно использовать абстрактный класс с чистой виртуальной функцией void eat().
#### 3. Переопределить (virtual) функцию поглощения пищи eat() в каждом классе (уникальное поведение).
#### 4. Создать массив generic_creature и массив указателей на generic_creature такие, чтобы объект каждого класса встречался не менее одного раза. Проиллюстрировать полиморфное (а также не полиморфное) поведение (показать существенные отличия, необходимые для реализации полиморфного поведения).


### Запуск

1. Создайте директорию для сборки (находясь в дирректории hw 10.1):
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
    ./evolution
   ```