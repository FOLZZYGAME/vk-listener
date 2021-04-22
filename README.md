<h1 align="center">VK-Listener - модуль для накручивания прослушиваний на Ваш альбом ВКонтакте.</h1>

<br>

<h1 align="center"> Как использовать </h1>

<h3 align="center"> Установите chromedriver.exe Вашей версии Google Chrome (https://chromedriver.chromium.org/downloads)<h2>
<h3 align="center"> Перетащите chromedriver.exe в C:/Users/User/AppData/Local/Google/Chrome<h2>


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
