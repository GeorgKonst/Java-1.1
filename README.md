# Отчёт о тестировании KeyValidator

## Краткое описание

16.12.2020 - 16.12.2020 было проведено тестирование установки, тестирование совместимости, функциональное тестирование согласно требованиям приложения KeyValidator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Присутствуют не корректные валидные ключи в руководстве использования #1](https://github.com/GeorgKonst/Java-1.1/issues/1)
* [Присутствует не корректный не валидный ключ в руководстве использования #2](https://github.com/GeorgKonst/Java-1.1/issues/2)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Инструкция по установке OpenJDK11
* Руководство использования KeyValidator

В качестве тестовых данных использовались данные из руководства использования:

* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 - OK
* 80b427f8-92cd-3aae-ba04-3927fbe17c6 - OK
* b295bc63-9f03-3b4b-af80-969b39f8c262 - OK
* 387eedc6-12e9-3b32-9881-63b6b5e85317 - OK
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 - OK
* 18252235-78e0-44a5-8720-556f0c7da17a - FAIL
* e66075b6-ddad-445e-baf6-161b3289522b - FAIL
* b6d53250-f07e-4352-a293-6102ddf7f1ca - FAIL
* c2bc778a-1cb9-46c6-b435-0489649d2a42 - FAIL
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 - FAIL

Тестирование производилось в следующем окружении:
* Microsoft Windows [Version 10.0.19042.685] x64
* java version "11.0.9" 2020-10-20 LTS
