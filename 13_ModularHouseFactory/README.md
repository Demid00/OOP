## Стройка
### 13.1.  Фабрика модульных домов - 1 балл:
#### 1.Используя паттерн “Строитель” организовать постройку домов (продукт 1) из различных составных частей.
-  Общие для всех домов этапы (построение стен, пола, крыши) вынести в общий абстрактный класс строителя.
-  Добавить конструктивных элементов в реализацию.
#### 2. Продуктом 2 будет документация на дом. Т.е. в документацию согласно включенным в дом элементам будут включаться страницы с описанием данного элемента.
#### 3. Продемонстрировать (минимум 2 - 3 примера) создание продукта 1 и продукта 2 конкретным строителем.

### Запуск

1. Создайте директорию для сборки (находясь в дирректории 13_ModularHouseFactory):
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
    ./construction
   ```
