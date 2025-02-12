Установка и запуск Cypress для тестирования.

Требования:
Операционная система: Linux (Debian-based: Ubuntu, Mint, Kali и т. д.)
Установленный браузер на основе Chromium (Chrome, Edge, Opera и др.)

Установка npm
Перед началом установки Cypress убедитесь, что у вас обновлена система и установлен npm:
Обновите список пакетов и установите обновления:
`sudo apt update && sudo apt upgrade`
sudo apt install npm

Установка Cypress
Перейдите в любую удобную директорию (например, в домашнюю папку или папку проекта):
cd ~/my_project

Установите Cypress как dev-зависимость:
sudo npm install cypress --save-dev

Распаковка архива Cypress
Архив cypress.tar.xz нужно распаковать в директорию, где установлен Cypress

Запуск Cypress
Перейдите в директорию с установленным Cypress:
cd home/cypress

Откройте Cypress:
npx cypress open

В появившемся интерфейсе выберите:
E2E testing

Выберите браузер (Chrome или другой на основе Chromium)

Запуск тестов
Откроется интерфейс тестов, папка Avito
Запустите тестовый файл main.cy.js
После этого Cypress запустит тесты в выбранном браузере.
