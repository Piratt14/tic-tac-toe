This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

#Tic Tac Toe

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

----

Краткое описание:
- Для запуска надо скачать npm пакеты, для этого в консоли набрать npm install
- Для доступа к игре надо ввести верное имя пользоветеля и пароль, иначе будет выведено сообщение о неверных данных
- Если попытаться вручную перейти на нужный раздел приложения, без авторизации, то произойдет редирект на страницу входа
- Пользователь ходим "крестиком" и ходит первым, затем следует нажать кнопку "Computer turn" для того, что бы компьютер сделал случайный ход
- В любой момент времени можно переходить по истории ходов и менять ходы свои и компьютера(В рамках текущей партии)
- После победы одного из участников, или ничьей - надо нажать на кнопку "Next Match"
- Для выхода из игры(деавторизации) надо нажать на кнопку "Exit"
- В любой момент времени данные синхронизируются с сервером, поэтому можно продолжить незаконченную партию в любой момент после повторного входа.
Не важно как был осуществлен выход, по кнопке или закрыв страницу или браузер.
- Статистика матчей тоже сохраняется на сервере
- Под тремя кнопками "Computer Turn", "Next Match", "Exit" - показано кто ходит следующий, %username% или компьютер, так же там отображается в конце раунда кто победил или произошла ничья