<h1 align="center">VK-Listener</h1>

<h3>Как использовать</h3>
<h3>1. Установите chromedriver.exe Вашей версии Google Chrome<h3>
<h3>2. Перетащите chromedriver.exe в C:\Users\User\AppData\Local\Google\Chrome
<h3>3. Если нет папки, то создай её<h3>

<h1 align="center"Пример кода Vk-Listener"<h1>

```python
import vk-listener

listener.init('hide')

listener.authorization('Логин', 'Пароль')

if(listener.check()):
	print('Авторизация прошла успешно!')
else:
	print('Ошибка авторизации!')

listener.loop('Ссылка на Ваш альбом', 15)
```
