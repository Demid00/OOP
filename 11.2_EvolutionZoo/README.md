## Эволюция
### 11.2. Эволюция (Зоопарк) - 1 балл:
#### 1. За основу иерархии продуктов взять последовательную иерархию существ из задания 10.1 (все существа,имеют функцию eat()). Добавить каждому типу существ не менее двух наследников-представителей класса. Например, наследниками Amphibious могут быть Crocodile и Alligator, наследниками Bird - Pigeon и Parrot и т.п.
#### 2. Используя фабричный метод создать зоопарк существ указанной иерархии.
#### 3. Класс создатель - Создатель (Creator), имеет фабричный метод для создания особи существа, т.е. для Crocodile, Alligator, Pigeon, Parrot и т.п.
#### 4. Создать и накормить стадо/стаю (не менее 3-х экземпляров) каждого представителя класса существ уникальной пищей (подходящей этим особям, например, аллигатору - руки, а крокодилу - ноги … )
#### 5. Нарисовать диаграмму наследования [5 задание](#task5)

## task5
иерархии классов, использованные в данном заадании хранятся в данном репозитории с соответсвующими названиями


### Запуск

1. Создайте директорию для сборки (находясь в дирректории 11.2_EvolutionZoo):
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
   
