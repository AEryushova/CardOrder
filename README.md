# Project Sample  [![Build status](https://ci.appveyor.com/api/projects/status/xfdyklrxclcj1kgf?svg=true)](https://ci.appveyor.com/project/AEryushova/cardorder)
# Запуск автотестов для WEB-сервиса "[Заказ дебетовой карты](http://localhost:9999/)"

## Необходимое окружение :
- Git
- Java 11
- ОС : **Windows 10 64-bit**
- IDE : **IntelliJ IDEA**
- Браузер : **Google Chrome**


## Запуск :
1. Клонирование репозитория _git@github.com:AEryushova/CardOrder.git_
2. Запуск SUT командой : _java -jar artifacts/app-order.jar_
3. Запуск тестов командой : _./gradlew clean test_
  

- Остановка SUT : _CTRL + C_

[![cEt.gif](https://i.postimg.cc/SQBZwbWV/cEt.gif)](https://postimg.cc/4n1b9M2h)
