**Отчёт о тестировании <Руководство использования KeyValidator>**

Краткое описание

<08.03.2021> - <08.03.2021> было проведено <санитраное тестирование(sanity testing)> приложения <Руководство использования KeyValidator>.

На тестирование затрачено: <0,2 часа>

В результате тестирования выявлены следующие дефекты:

    <https://github.com/ArtSV86/OpenJDK11-KeyValidator/issues/1>


Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* [KeyValidator.class](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/artifacts/KeyValidator.class)
* Тестовый сценарий<Руководство использования KeyValidator>


Описание тестового сценария <Руководство использования KeyValidator>:
* Шаг 1. Создайте пустой реппозиторий

* Шаг 2. Добавьте в него скаченный файл: 
[KeyValidator.class](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/artifacts/KeyValidator.class)
* Шаг 3. Введите в терминале команду
```
java KeyValidator <номер ключа>
```
где <номер ключа>

Валидные ключи:

    8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
    80b427f8-92cd-3aae-ba04-3927fbe17c6
    b295bc63-9f03-3b4b-af80-969b39f8c262
    387eedc6-12e9-3b32-9881-63b6b5e85317
    c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи:

    18252235-78e0-44a5-8720-556f0c7da17a
    e66075b6-ddad-445e-baf6-161b3289522b
    b6d53250-f07e-4352-a293-6102ddf7f1ca
    c2bc778a-1cb9-46c6-b435-0489649d2a42
    2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1


* Шаг 4. В результате работы вывод приложения будет выглядеть следующим образом:

```
Result for <номер ключа>: OK
```
или
```
Result for <номер ключа>: FAIL
```

В качестве тестовых данных использовались данные <[Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)>:


Данные ожидаемого результата при выполнении команд в терминале:

* Валидные ключи:
```
    8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
    80b427f8-92cd-3aae-ba04-3927fbe17c6
    b295bc63-9f03-3b4b-af80-969b39f8c262
    387eedc6-12e9-3b32-9881-63b6b5e85317
    c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180
```
* Невалидные ключи:
```
    18252235-78e0-44a5-8720-556f0c7da17a
    e66075b6-ddad-445e-baf6-161b3289522b
    b6d53250-f07e-4352-a293-6102ddf7f1ca
    c2bc778a-1cb9-46c6-b435-0489649d2a42
    2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1
```
Тестирование производилось в следующем окружении:

    <Windows 10, 64 bit>
    <версия Java "11.0.10">
