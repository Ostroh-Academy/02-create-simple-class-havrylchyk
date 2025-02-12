[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/jc7SvnCg)
# Клас та об'єкт
1.	Розробити алгоритми використання класів згідно варіантів завдань для самостійної роботи [варіанти знаходяться у файлі](https://github.com/Ostroh-Academy/simpleclass/blob/main/%D0%9F%D0%B0%D1%82%D0%B5%D1%80%D0%BD%D0%B8%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F02.pdf).
2.	Написати відповідну програму на мові С#. Програма повинна мати як мінімум 2 методи: введення даних та обчислення.
3.	Перевірити код на дотримання Code Convention C#:
 (https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions , https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/identifier-names )
4.	Перевірити на дотримання принципу інкапсуляції.
5.	Завантажити код програми на GitHub у репозиторій заданий викладачем.
6.	Нарисувати UML діаграму класів у зручному редакторі та долучити її в README файл репозиторію у вигляді рисунка.
7.	Зробити pull request.


![image](https://github.com/Ostroh-Academy/02-create-simple-class-havrylchyk/assets/92024271/d4739bc0-b1ac-4762-a115-56ded831f40d)


## Вміст

1. [Класи та об'єкти](#класи-та-обєкти)
2. [Специфікатори доступу](#специфікатори-доступу)
3. [Конструктори та деструктори](#конструктори-та-деструктори)

## Класи та об'єкти

Клас - це шаблон або опис структури для об'єктів, який визначає їх властивості та методи. Об'єкт - це конкретний екземпляр класу, створений за допомогою конструктора. Класи дозволяють організовувати код у логічні блоки та забезпечують механізм зміни та розширення програми.

## Специфікатори доступу

У мові програмування С#, специфікатори доступу (public, private, protected, internal) вказують на рівень доступу до членів класу:
- `public`: доступні для використання з будь-якого коду;
- `private`: доступні лише в межах самого класу;
- `protected`: доступні в межах самого класу та в похідних класах;
- `internal`: доступні лише в межах поточної збірки.

## Конструктори та деструктори

Конструктор: Використовується для ініціалізації об'єкта під час його створення. Це місце для виконання будь-яких дій, необхідних для початкового налаштування об'єкта.
Деструктор: Використовується для виконання певних дій при звільненні пам'яті об'єктом. У С# деструктори не так часто використовуються, оскільки є система збирання сміття.
