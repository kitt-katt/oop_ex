# Ответы на тесты по ООП

## Тест 1

#### 1. Определение "Объект":
- [x] Экземпляр конкретного класса
- [ ] Возможность порождать один класс от другого с сохранением всех свойств и методов класса-предка
- [ ] Способность использовать классы-потомки в контексте, который был предназначен для класса-предка
- [ ] Объединение различных свойств и/или поведений внутри одного класса
- [ ] Набор значимых характеристик объекта
- [ ] Модель определённого типа, описывающая поведение и свойства

#### 2. Определение "Абстракция":
- [ ] Возможность порождать один класс от другого с сохранением всех свойств и методов класса-предка
- [x] Набор значимых характеристик объекта
- [ ] Объединение различных свойств и/или поведений внутри одного класса
- [ ] Способность использовать классы-потомки в контексте, который был предназначен для класса-предка
- [ ] Экземпляр конкретного класса
- [ ] Модель определённого типа, описывающая поведение и свойства

#### 3. Каким термином называют отсутствие наследования между производными типами в обобщениях?
- [x] Инвариант
- [ ] Контрвариативность
- [ ] Ковариантность

#### 4. Определение "Наследование":
- [ ] Способность использовать классы-потомки в контексте, который был предназначен для класса-предка
- [ ] Экземпляр конкретного класса
- [ ] Объединение различных свойств и/или поведений внутри одного класса
- [x] Возможность порождать один класс от другого с сохранением всех свойств и методов класса-предка
- [ ] Набор значимых характеристик объекта
- [ ] Модель определённого типа, описывающая поведение и свойства

#### 5. Как передаётся value-type и где хранится?
- [x] Передаётся по значению, хранится на стэке
- [ ] Передаётся по значению, хранится в куче
- [ ] Передаётся по ссылке, хранится в куче
- [ ] Передаётся по ссылке, хранится на стэке

#### 6. Как решить проблему ромбовидного наследования?
- [ ] Общением типов
- [x] Композицией
- [ ] Множественным наследованием
- [ ] Агрегацией

#### 7. Выберите все известные вам модификаторы доступа:
- [x] static
- [x] extern
- [x] private
- [x] internal
- [ ] base
- [x] virtual
- [x] unsafe
- [x] protected
- [x] abstract
- [x] sealed
- [x] explicit
- [x] public
- [x] readonly

#### 8. На какие группы принято делить паттерны?
- [ ] Фундаментальные
- [x] Пораждающие
- [x] Структурные
- [x] Поведенческие

#### 9. Определение "Инкапсуляция":
- [ ] Способность использовать классы-потомки в контексте, который был предназначен для класса-предка
- [ ] Экземпляр конкретного класса
- [ ] Набор значимых характеристик объекта
- [ ] Возможность порождать один класс от другого с сохранением всех свойств и методов класса-предка
- [x] Объединение различных свойств и/или поведений внутри одного класса
- [ ] Модель определённого типа, описывающая поведение и свойства

#### 10. Какие виды (типы) заместителей бывают?
- [x] Кеширование объектов («умная» ссылка)
- [x] Защита доступа (защищающий прокси)
- [x] Локальный запуск сервиса (удалённый прокси)
- [x] Ленивая инициализация (виртуальный прокси)
- [x] Логирование запросов (логирующий прокси)

#### 11. Определение "Класс":
- [ ] Способность использовать классы-потомки в контексте, который был предназначен для класса-предка
- [ ] Набор значимых характеристик объекта
- [ ] Экземпляр конкретного класса
- [ ] Объединение различных свойств и/или поведений внутри одного класса
- [x] Модель определённого типа, описывающая поведение и свойства
- [ ] Возможность порождать один класс от другого с сохранением всех свойств и методов класса-предка

#### 12. С каким принципом коррелирует Information Expert из GRASP?
- [x] SRP - Single Responsibility (Принцип единственной ответственности)
- [ ] OCP - Open-Closed (Принцип открытости-закрытости)
- [ ] ISP - Interface Segregation (Принцип разделения интерфейсов)
- [ ] DIP - Dependency Inversion (Принцип инверсии зависимостей)
- [ ] LSP - Liskov Substitution (Принцип подстановки Барбары Лисков)

#### 13. Как передаётся reference-type и где хранится?
- [ ] Передаётся по значению, хранится на стэке
- [x] Передаётся по ссылке, хранится в куче
- [ ] Передаётся по значению, хранится в куче
- [ ] Передаётся по ссылке, хранится на стэке

#### 14. Реализуйте метод SendMessage:
- [x] SendMessage<T>(T message) where T : Message
- [ ] SendMessage(out var message) where message : Message
- [ ] SendMessage(dynamic message as Message)
- [ ] SendMessage(Message message) where message is <Any>

#### 15. Какие два паттерна можно комбинировать для реализации отмены абстрактных операций?
- [ ] Мост
- [ ] Адаптер
- [x] Снимок
- [x] Команда
- [ ] Одиночка
- [ ] Прототип
- [ ] Строитель

#### 16. Как в C# реализуется параметрический полиморфизм?
- [ ] Через приведение типов
- [ ] С кайфом
- [ ] Через наследование
- [x] Через generic'и (через обобщённый тип)
- [ ] Через перегрузку методов

#### 17. Где происходит позднее (динамическое) связывание?
- [x] При использовании виртуальных методов или интерфейсов

#### 18. Определение "Полиморфизм":
- [ ] Объединение различных свойств и/или поведений внутри одного класса
- [x] Способность использовать классы-потомки в контексте, который был предназначен для класса-предка
- [ ] Модель определённого типа, описывающая поведение и свойства
- [ ] Экземпляр конкретного класса
- [ ] Набор значимых характеристик объекта
- [ ] Возможность порождать один класс от другого с сохранением всех свойств и методов класса-предка

#### 19. К какому принципу относится определение «Если q(x) — свойство объекта x типа T, то q(y) тоже верно для объекта y типа S, где S — подтип T»:
- [ ] DIP - Dependency Inversion (Принцип инверсии зависимостей)
- [x] LSP - Liskov Substitution (Принцип подстановки Барбары Лисков)
- [ ] SRP - Single Responsibility (Принцип единственной ответственности)
- [ ] ISP - Interface Segregation (Принцип разделения интерфейсов)
- [ ] OCP - Open-Closed (Принцип открытости-закрытости)

#### 20. Как реализуется Ad-Hoc полиморфизм в строго типизированных языках (например, в C#)?
- [ ] Через приведение типов
- [ ] Через generic'и (через обобщённый тип)
- [ ] Через наследование
- [ ] С кайфом
- [x] Через перегрузку методов


## Тест 2

#### 1. Какой это паттерн?
![Паттерн 1](./images/Снимок%20экрана_20250108_012039.png)
- Компоновщик (Composite)

#### 2. Какой это паттерн?
![Паттерн 2](./images/Снимок%20экрана_20250108_012049.png)
- Мост (Bridge)

#### 3. Какой это паттерн?
![Паттерн 3](./images/Снимок%20экрана_20250108_012101.png)
- Посетитель (Visitor)

#### 4. Какой это паттерн?
![Паттерн 4](./images/Снимок%20экрана_20250108_012108.png)
- Стратегия (Strategy)

#### 5. Какой это паттерн?
![Паттерн 5](./images/Снимок%20экрана_20250108_012116.png)
- Состояние (State)

#### 6. Какой это паттерн?
![Паттерн 6](./images/Снимок%20экрана_20250108_012124.png)
- Наблюдатель (Observer)

#### 7. Какой это паттерн?
![Паттерн 7](./images/Снимок%20экрана_20250108_012134.png)
- Снимок (Memento)

#### 8. Какой это паттерн?
![Паттерн 8](./images/Снимок%20экрана_20250108_012142.png)
- Посредник (Mediator)

#### 9. Какой это паттерн?
![Паттерн 9](./images/Снимок%20экрана_20250108_012149.png)
- Команда (Command)

#### 10. Какой это паттерн?
![Паттерн 10](./images/Снимок%20экрана_20250108_011903.png)
- Цепочка обязанностей (Chain of Responsibility)

#### 11. Какой это паттерн?
![Паттерн 11](./images/Снимок%20экрана_20250108_012156.png)
- Заместитель (Proxy))

#### 12. Какой это паттерн?
![Паттерн 12](./images/Снимок%20экрана_20250108_012204.png)
- Приспособленец (Flyweight)


## Тест 3

#### 1. Что значит "Архитектура"?
- [ ] Набор готовых решений на все случаи жизни
- [x] Совокупность решений об организации программной системы
- [ ] Это подходы по оптимизации скорости работы приложения и команды
- [ ] Это способ движения по карьерной лестнице

#### 2. Какие проблемы решает Архитектура?
- [x] Ускоряет доставку новой функциональности
- [x] Позволяет наращивать темп разработки
- [x] Уменьшает сложность разработки
- [x] Упрощает интеграцию разных компонент системы

#### 3. Может ли хорошая архитектура полностью исключить возможность написания "плохого" кода?
- [ ] Да
- [x] Нет

#### 4. Какие принципы помогают строить хорошую Архитектуру?
- [x] DRY
- [x] KISS
- [x] SOLID
- [x] GRASP
- [x] Закон Деметры

#### 5. Какой правильный порядок действий при построении архитектуры?
- [ ] архитектура – требования – логика – структура – код
- [ ] требования – логика – структура – архитектура – код
- [x] требования – архитектура – логика – структура – код
- [ ] архитектура – логика – требования – структура – код

#### 6. Входит ли формирование требований к инфраструктуре проекта в Архитектуру проекта?
- [x] Да
- [ ] Нет

#### 7. На каком уровне архитектуры используется архитектурный шаблон MVC?
- [x] На уровне приложения
- [ ] На уровне всего предприятия

#### 8. Одно из основных архитектурных правил гласит:
- [ ] Высокое зацепление (coupling), низкая связность (cohesion)
- [x] Низкое зацепление (coupling), высокая связность (cohesion)
- [ ] Высокое зацепление (coupling), высокая связность (cohesion)
- [ ] Низкое зацепление (coupling), низкая связность (cohesion)

#### 9. Какие типовые решения выделяет Мартин Фаулер для организации бизнес-логики корпоративных систем?
- [x] Transaction Script
- [x] Table Module
- [x] Domain Model
- [x] Service Layer

#### 10. Какой подход минимально отклоняется от основных концепций объектно-ориентированной разработки?
- [ ] Anemic Domain Model
- [x] Rich Domain Model
- [ ] Record Set
- [ ] Layer Supertype


## Тест 4

### Вопросы с вариантами ответов по C# и программированию

#### 1. Какой модификатор доступа предоставляет доступ только в пределах сборки?
- [ ] protected
- [ ] public
- [x] internal
- [ ] private

#### 2. Какие из примеров нарушают принцип Dependency Inversion в SOLID?
- [ ] Методы принимают абстракции вместо конкретных классов
- [ ] Класс зависит от интерфейса, а не от конкретной реализации
- [x] Класс использует конкретную реализацию вместо интерфейса

#### 3. Чем отличается интерфейс от абстрактного класса в C#? (выберите правильные суждения)
- [x] Абстрактные классы могут содержать поля и конструкторы, а интерфейсы нет
- [x] Абстрактные классы могут содержать реализацию методов, а интерфейсы нет
- [x] Интерфейсы поддерживают механизм множественного наследования, а абстрактные классы нет

#### 4. Что такое интерфейсы-маркеры?
- [x] Интерфейсы без методов, служащие для указания поведения или статуса объекта
- [ ] Интерфейсы, которые содержат только методы, но не свойства

#### 5. Что такое mapper?
- [ ] Метод для работы с базой данных
- [ ] Конструктор класса
- [x] Класс или библиотека для преобразования данных из одной модели в другую

#### 6. Что означает DTO (Data Transfer Object)?
- [ ] Класс для управления слоями
- [ ] Способ сериализации объектов
- [ ] Методы работы с базой данных
- [x] Объект для хранения данных и передачи их между слоями

#### 7. Что такое LINQ?
- [x] Язык запросов для работы с данными в C#
- [ ] Фреймворк для работы с СУБД
- [ ] Библиотека предназначенная для работы с файлами

#### 8. Для чего используется ключевое слово async?
- [ ] Для работы с LINQ-запросами
- [x] Для указания, что метод содержит асинхронные операции
- [ ] Для обработки ошибок в многопоточном коде

#### 9. Что означает ключевое слово await?
- [ ] Используется для создания нового потока
- [x] Указывает на вызов асинхронного метода, выполнение которого нужно дождаться
- [ ] Указывает на завершение метода

#### 10. На какие группы принято делить паттерны?
- [ ] Фундаментальные
- [x] Структурные
- [x] Поведенческие
- [x] Порождающие

#### 11. Какие бывают виды Domain Model?
- [ ] Static и dynamic
- [x] Rich и anemic
- [ ] Value и reference

#### 12. Зачем нужно разделение на слои?
- [x] Для упрощения сопровождения и модульности кода
- [ ] Для оптимизации работы памяти
- [ ] Для повышения производительности
- [ ] Для создания сложных алгоритмов


