<h1 align="center">VK-Listener</h1>

<h3>Как использовать </h3>
<h3>1. Установите chromedriver.exe Вашей версии Google Chrome<h3>


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
