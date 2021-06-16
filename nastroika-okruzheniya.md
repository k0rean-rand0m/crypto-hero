---
description: Устанавливаем Node.js и Truffle Suite
---

# Настройка окружения

Есть несколько способов настроить окружение для разработки. У каждого свои плюсы и минусы, но в рамках этого гайда мы остановимся на самом интуитивном и простом способе начать разрабатывать свои смарт-контракты.

### Truffle Suite

**Truffle Suite** представляет из себя окружение для разработки, тестирования и деплоя смарт-контрактов. Для его работы понадобится **Node.js**. Это "движок", позволяющий JavaScript работать вне браузера.

#### Установка **Node.js**

Установить Node.js можно с официального сайта по следующей ссылке:[ **https://nodejs.org/ru/**](https://nodejs.org/ru/)  
****После установки в консоли должна стать доступна команда `node` запускающая js-консоль:

```text
node
```

Для выхода из консоли нужно дважды нажать Cmd+C

В комплекте с Node.js идет пакетный менеджер npm. Он понадобится для установки пакетов.

**Установка Truffle**

Итак, следующим шагом будет установка Truffle: [**https://www.trufflesuite.com/truffle**](https://www.trufflesuite.com/truffle)  
Для этого в консоли нужно запустить команду \(флаг -g означает, что truffle станет доступен как команда из любой директории\):

```
npm install truffle -g
```

{% hint style="warning" %}
Возможно, что во время установки возникнет ошибка

`npm ERR! The operation was rejected by your operating system.  
npm ERR! It is likely you do not have the permissions to access this file as the current user`

В таком случае команду следует перезапустить с sudo

```bash
sudo npm install truffle -g
```
{% endhint %}

**Установка Ganache** 

Ganache - локальный блокчейн, который пригодится для тестов в процессе работы. Можно обойтись и без него, используя команду `truffle develop` однако это будет менее удобно и не так наглядно.

Для установки Ganache достаточно следовать инструкциям  
[**https://www.trufflesuite.com/ganache**](https://www.trufflesuite.com/ganache)\*\*\*\*

