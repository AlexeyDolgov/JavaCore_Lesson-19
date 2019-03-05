# JavaCore_Lesson-19
I/O Streams, Serialization

* [Завдання](https://github.com/AlexeyDolgov/JavaCore_Lesson-19/tree/master/JavaCore_Lesson-19/src/ua/lviv/lgs/task19)<br>
Створити клас <i>Employee</i>. Описати даний клас наступними полями: id, ім’я, зарплатня. Дані поля повинні бути позначені модифікатором
private. Описати getters та setters.<br><br>
Створити клас <i>Methods</i>, де описати два методи serialize() та deserialize(). В даних методах повинно бути використано
FileInputStream/FileOutputStream, ObjectInputStream/ObjectOutputStream.<br><br>
Створити метод <i>Main</i>. Створити екземпляр класу Employee і провести серіалізацію та десеріалізацію. Результат десеріалізації
вивести на консоль.<br><br>
Помітити поле зарплатня модифікатором transient і провести серіалізацію і десеріалізацію. Результат вивести на екран.<br><br>
Створити колекцію об’єктів Employee. Провести серіалізацію та десеріалізацю колекції.<br><br>
