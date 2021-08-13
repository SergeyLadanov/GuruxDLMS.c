# DLMS_Example
Пример реализации DLMS сервера для компилятора GCC

Источник: https://github.com/Gurux/GuruxDLMS.c

Для проверки работы использовать [DLMS Director](http://www.gurux.fi/Download)

## Настройка DLMS Director

1. Добавить модель: 

    ![Добавить модель](Resources/add_device.png)

2. Настроить подключение:
    * Для уровня доступа High:

        ![Уровень high](Resources/High_settings.png)

    * Для уровня доступа Low:

        ![Уровень low](Resources/Low_settings.png)

    * Для уровня доступа None:

        ![Уровень low](Resources/None_settings.png)

3. Подключиться:

    ![Подключиться](Resources/Connect.png)

### Файлы готовых настроек

* [ExampleHigh.gxc (Для уровня доступа High)](/Resources/ExampleHigh.gxc)

* [ExampleLow.gxc (Для уровня доступа Low)](/Resources/ExampleLow.gxc)

* [ExampleNone.gxc (Для уровня доступа None)](/Resources/ExampleNone.gxc)