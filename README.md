# Отчёт о тестировании Карта

## Краткое описание

19.05.2021 - 19.05.2021 было проведено функциональное тестирование приложения Карта.

На тестирование затрачено: 30 минут

В результате тестирования выявлены следующие дефекты:
* [При вводе валидного номера банковской карты приложение идентифицирует его как невалидный](https://github.com/FingRinger/Zadacha1-Credit-Card-Number-Validator/issues/1#issuecomment-844820566)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Баг-репорт
* Отчет о тестировании


В качестве тестовых данных использовались данные www.getcreditcardnumbers.com:
* VISA 4024007142979862 - Result is OK 
* Mastercard 5145536500177736 - Result is OK
* Discover 6011840501468865 - Result is OK
* American Express 379901080455092 - Result is FAIL

Тестирование производилось в следующем окружении:
* ОС: Windows 10, x64
* версия Java:
  openjdk version "11.0.11" 2021-04-20
  OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9)
  OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9, mixed mode)
